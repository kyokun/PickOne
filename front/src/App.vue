<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    Font test
    <hello></hello>
    <button>Login with facebook</button>
  </div>
</template>

<script>
import Hello from './components/Hello'

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>

<style lang="scss">
@import 'sass/master';
</style>
