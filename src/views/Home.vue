<template>
  <div class="home">
    <h1 id='title'>Spencer Haugh</h1>
    <!-- <img alt="Vue logo" src="../assets/WAPBars-01.png"> -->
    <HelloWorld msg="// Let's Get Radical"/>
    <Resume />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import Resume from '@/components/Resume.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Resume,
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
