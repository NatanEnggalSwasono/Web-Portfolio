<template>
  <div class="home">
    <HelloWorld/>
    <img alt="Vue logo" src="../assets/Tobi_Akatsuki.png">
  </div>
  <div class="project">
    <Projects/>
  </div>
</template>

<style>
  .home {
    display: flex;
    padding: 100px 80px 0 80px;
    box-shadow: inset rgba(52, 192, 127, 0.288) 0px -25px 20px -20px;
  }

  .home img {
    padding: 70px 30px 5px 30px;
    width: 0;
    flex: 1;
    background-image: radial-gradient(circle, #42b983 30%, #0f0f0f 70%);
    box-shadow: inset rgba(52, 192, 127, 0.288) 0px -25px 20px -20px;
  }
</style>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Projects from '@/components/Projects.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    Projects
  }
}
</script>
