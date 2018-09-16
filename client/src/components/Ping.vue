<template>
  <!-- <div class="hello">
    <h1>{{ msg }}</h1>
  </div> -->
  <div class="container">
    <h1>Ping!</h1>
    <button type="button" class="btn btn-primary">{{ msg }}</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
  color: #42b983;
}
</style>
