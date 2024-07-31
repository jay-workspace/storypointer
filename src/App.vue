<template>

  <head>
  </head>

  <body>
    <div class="login">
      <BaseLogin />
    </div>
  </body>
  <footer>
  </footer>
</template>

<script>
import BaseLogin from './components/login/BaseLogin.vue'

export default {
  name: 'App',
  components: {
    BaseLogin
  }
}
</script>

<style scoped>
body {
  background-color: #353d75;
}
</style>
