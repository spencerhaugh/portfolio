<template>
  <div class="home">
    <h1 id='title' class="slide-in-top">Spencer Haugh</h1>
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
  @import url('https://fonts.googleapis.com/css2?family=Bungee+Shade&display=swap');
  img {
    width: 90%;
  }
  h1 {
    /* font-family: KCOraleSans, Helvetica, Arial; */
    font-family: 'Bungee Shade', cursive;
    font-size: 8rem;
  }
  h1.slide-in-top {
    -webkit-animation: slide-in-top 1s cubic-bezier(0.250, 0.460, 0.450, 0.940) 0.75s both;
    animation: slide-in-top 1s cubic-bezier(0.250, 0.460, 0.450, 0.940) 0.75s both;
  }
  @-webkit-keyframes slide-in-top {
  0% {
    -webkit-transform: translateY(-1000px);
    transform: translateY(-1000px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    opacity: 1;
  }
}
@keyframes slide-in-top {
  0% {
    -webkit-transform: translateY(-1000px);
    transform: translateY(-1000px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    opacity: 1;
  }
}

</style>
