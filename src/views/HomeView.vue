<template>
  <div class="home">
    <HelloWorld/>
    <img alt="Vue logo" src="../assets/logo.png">
  </div>
</template>

<style>
  .home {
    display: flex;
    padding: 180px 80px;
    gap: 20px;
  }

  img {
    flex: 1;
  }
</style>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
