<template>
  <div>
    <navbar></navbar>
    <contentcomplete></contentcomplete>
    <nuxt/>
  </div>
</template>

<script>
  import Navbar from '../components/Navbar'
  import Contentcomplete from '../components/Contentcomplete'

  export default {
    components: {
      Navbar,
      Contentcomplete
    }
  }
</script>