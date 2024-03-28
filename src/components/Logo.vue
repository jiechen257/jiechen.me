<template>
  <div class="typing">
    Glad to see u tho!
  </div>
</template>

<style scoped>
.typing {
  font:
    bold 200% Consolas,
    Monaco,
    monospace;
  font-size: 1rem;
  width: 20ch;
  white-space: nowrap;
  overflow: hidden;
  border-right: 0.05em solid;
  animation:
    typing 3s steps(15) infinite,
    caret 1s steps(1) infinite;
}

@keyframes typing {
  from {
    width: 0;
  }
}

@keyframes caret {
  50% {
    border-right-color: transparent;
  }
}

.dark .typing {
  stroke: #fdfdfd;
}
</style>
