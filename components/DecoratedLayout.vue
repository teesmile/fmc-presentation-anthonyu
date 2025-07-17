<template>
  <div class="relative w-full h-full bg-white text-gray-900 overflow-hidden">
    <!-- Top-right shape -->
    <div class="absolute top-0 right-0 w-40 h-40 bg-orange-300 rounded-bl-[100%] animate-bounce-slow z-0"></div>

    <!-- Bottom-left shape -->
    <div class="absolute bottom-0 left-0 w-40 h-40 bg-[#227C99] rounded-tr-[100%] animate-pulse-slow z-0"></div>

    <!-- Main content -->
    <div class="relative z-10 p-10">
      <slot />
    </div>
  </div>
</template>

<style scoped>
@keyframes bounce-slow {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(8px);
  }
}
@keyframes pulse-slow {
  0%, 100% {
    transform: scale(1);
    opacity: 0.9;
  }
  50% {
    transform: scale(1.05);
    opacity: 1;
  }
}
@keyframes fade {
  0%, 100% {
    opacity: 0.5;
  }
  50% {
    opacity: 1;
  }
}

.animate-bounce-slow {
  animation: bounce-slow 6s ease-in-out infinite;
}
.animate-pulse-slow {
  animation: pulse-slow 7s ease-in-out infinite;
}
.animate-fade {
  animation: fade 10s ease-in-out infinite;
}
</style>
