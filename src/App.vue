<template>
  <div id="app">
    <SignIn />
  </div>
</template>

<script>
import SignIn from './components/SignIn.vue'

export default {
  name: 'app',
  components: {
    SignIn
  }
}
</script>

<style lang="scss">
  body {
    margin: 0;
    padding: 0;
  }

  #app {
    font-family: Tahoma;
    font-size: 1.6rem;
    color: #222;
    background-color: #092525;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>
