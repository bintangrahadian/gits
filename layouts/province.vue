<template>
  <div>
    <navbar></navbar>
    <contentprovince></contentprovince>
    <nuxt/>
  </div>
</template>

<script>
  import Navbar from '../components/Navbar'
  import Contentprovince from '../components/Contentprovince'


  export default {
    components: {
      Navbar,
      Contentprovince
    }
  }
</script>

