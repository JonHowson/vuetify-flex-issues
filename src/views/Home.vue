<template>
  <div class="home">
    <div class="text-right">
      dsadsadsa
    </div>
    <div class="d-flex">
      <v-btn>Hello</v-btn>
      <v-btn>World</v-btn>
    </div>
    <div class="d-flex">
      <div style="background-color: blue;">blue</div>
      <div style="background-color: red;">red</div>
      <div style="background-color: yellow;">yellow</div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss" scoped>
/*
 body {
  @debug $utilities;
  @if ($utilities: true) {
    background: green;
  } @else {
    background: red;
  }
 }
 */
</style>