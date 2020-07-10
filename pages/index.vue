<template>
  <div class="container">
    <Header></Header>
    <BracketsImage></BracketsImage>
    <Civs></Civs>
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
import BracketsImage from '~/components/BracketsImage.vue'
import Civs from '~/components/Civs.vue'

export default {
  components: {
    Header,
    BracketsImage,
    Civs,
  },
}
</script>

<style></style>
