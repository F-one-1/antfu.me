<template>
  <svg viewBox="0 0 500 100" fill="none" xmlns="http://www.w3.org/2000/svg">
    <title>Xinrui Fan</title>
    <text
      class="path1" x="50%" y="50%" text-anchor="middle" dominant-baseline="middle" font-size="24"
      font-family="monospace" stroke="black" stroke-width="2" fill="none"
    > Xinrui Fan </text>
  </svg>
</template>

<style scoped>
@media (prefers-reduced-motion) {
  .path1 {
    animation: none !important;
    stroke-dasharray: unset !important;
  }
}

@media print {
  .path1 {
    animation: none !important;
    stroke-dasharray: unset !important;
  }
}

@keyframes grow {
  0% {
    stroke-dashoffset: 1px;
    stroke-dasharray: 0 800px;
    opacity: 0;
  }

  10% {
    opacity: 1;
  }

  40%,
  85% {
    stroke-dasharray: 800px 0;
  }

  95%,
  to {
    stroke-dasharray: 0 800px;
  }
}

.path1 {
  stroke-dashoffset: 1px;
  stroke-dasharray: 400px 0;
  transform-origin: center;
  stroke: #303030;
  animation-delay: 0s;
}

.dark .path1 {
  stroke: #fdfdfd;
}
</style>
