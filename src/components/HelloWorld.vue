<template>
  <div class="hello">
    <h1>// Software Engineer</h1>
    <h2>{{ msg }}</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

h1 {
  color: #f5af19;
  margin-bottom: 3%;
}
</style>
