<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">Rey de las Americas</h1>
      <h2 class="subtitle">13 de Julio</h2>
      <div class="links">
        <a
          href="https://www.youtube.com/channel/UCPi7qn4OydOUSfHQqU0XDQg"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          <font-awesome-icon class="icon" :icon="['fab', 'youtube']" />
          Youtube
        </a>
        <a
          href="https://www.instagram.com/nachoaoe/?hl=es-la"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          <font-awesome-icon class="icon" :icon="['fab', 'instagram']" />
          Instagram
        </a>
        <a
          href="https://discord.gg/G8hMthq"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          <font-awesome-icon class="icon" :icon="['fab', 'discord']" />
          Discord
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo,
  },
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: #001e32;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 900;
  font-size: 100px;
  color: #e5cf3e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 700;
  font-size: 50px;
  color: #e5cf3e;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
