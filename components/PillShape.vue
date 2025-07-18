<template>
  <div 
    class="decorative-pill" 
    :style="{
      position: 'absolute',
      borderRadius: '9999px',
      zIndex: 10,
      ...positionStyles
    }"
  ></div>
</template>

<script>
export default {
  props: {
    position: String,
    width: String,
    height: String,
    color: String
  },
  computed: {
    positionStyles() {
      const styles = {};
      this.position.split(';').forEach(rule => {
        const [key, value] = rule.split(':');
        if (key && value) styles[key.trim()] = value.trim();
      });
      
      // Set default dimensions
      styles.width = this.width || '200px';
      styles.height = this.height || '60px';
      styles.backgroundColor = this.color || 'rgba(76, 175, 79, 0.47)';
      
      return styles;
    }
  }
}
</script>