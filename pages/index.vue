<template>
  <div class="container">
    <div class="logo-container">
      <logo />
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
  .container {
    margin: 0 auto;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    max-width: 1200px;
  } 

  .logo-container {
    max-width: 80%;
    display: block;
    margin: auto;
    width: 100%;
  }
</style>
