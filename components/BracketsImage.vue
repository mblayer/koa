<template>
  <section id="brackets">
    <img class="bracketsImage" src="~assets/brackets_Corregidas.png" alt="" />
  </section>
</template>
<script>
export default {
  transition: 'bounce',
}
</script>

<style>
#brackets {
  text-align: center;
}
.bracketsImage {
  animation: 1s appear;
  width: 90vw;
}
.tray-enter,
.tray-leave-to {
  opacity: 0;
}

.tray-leave,
.tray-enter-to {
  opacity: 1;
}

.tray-enter-active,
.tray-leave-active {
  transition: opacity 300ms;
}
</style>
