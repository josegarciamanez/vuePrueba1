<template>
  <div>
    <h1>{{ msg }}</h1>
    <h3>{{ msg2 }}</h3>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'Pruebas Vue.js // CodeSandbox // ZeitNow // Github',
      msg2: 'JoseGarciaMañez © 2018'
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
</style>
