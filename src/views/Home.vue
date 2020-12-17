<template>
  <div class="home">
    <h1>Spencer Haugh</h1>
    <!-- <img alt="Vue logo" src="../assets/WAPBars-01.png"> -->
    <HelloWorld msg="// Let's Get Radical"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
};
</script>

<style scoped>
  img {
    /* background-size: cover; */
    width: 90%;
  }
  h1 {
    font-family: KCOraleSans, Helvetica, Arial;
    font-size: 10rem;
  }

</style>
