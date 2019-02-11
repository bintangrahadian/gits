<template>
  <div>
    <contentlogin></contentlogin>
    <nuxt/>
  </div>
</template>

<script>
  import Contentlogin from '../components/Contentlogin'

  export default {
    components: {
      Contentlogin
    }
  }
</script>

<style>
  body {
    background: rgb(0,143,237);
    background: linear-gradient(90deg, rgba(0,143,237,1) 21%, rgba(0,143,237,1) 21%, rgba(0,143,237,1) 28%, rgba(0,143,237,1) 32%, rgba(103,190,247,1) 67%);  
  }
</style>