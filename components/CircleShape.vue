
<template>
  <div 
    class="decorative-shape" 
    :style="{
      position: 'absolute',
      borderRadius: '50%',
      zIndex: 10,
      ...positionStyles
    }"
  ></div>
</template>

<script>
export default {
  props: {
    position: String,
    size: String,
    color: String
  },
  computed: {
    positionStyles() {
      const styles = {};
      this.position.split(';').forEach(rule => {
        const [key, value] = rule.split(':');
        if (key && value) styles[key.trim()] = value.trim();
      });
      
      // Set default size if not provided
      if (!styles.width) styles.width = this.size || '100px';
      if (!styles.height) styles.height = this.size || '100px';
      if (!styles.backgroundColor) styles.backgroundColor = this.color || 'rgba(3, 80, 105, 0.47)';
      
      return styles;
    }
  }
}
</script>