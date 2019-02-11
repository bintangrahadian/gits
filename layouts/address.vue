<template>
  <div>
    <navbar></navbar>
    <contentaddress></contentaddress>
    <nuxt/>
  </div>
</template>

<script>
  import Navbar from '../components/Navbar'
  import Contentaddress from '../components/Contentaddress'


  export default {
    components: {
      Navbar,
      Contentaddress
    }
  }
</script>

