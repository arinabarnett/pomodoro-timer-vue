<template>
  <button class="play-button" @click="$emit('click')">
    <svg width="62" height="74" viewBox="0 0 72 84" fill="none" xmlns="http://www.w3.org/2000/svg">
      <g>
        <path d="M72 42L0 83.5692L0 0.430782L72 42Z" fill="#636363" />
      </g>
    </svg>
  </button>
</template>

<style scoped>
.play-button {
  display: none;
}
.active {
  display: inline-block;
}
button {
  border: none;
}
</style>

