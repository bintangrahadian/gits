<template>
  <div>
    <navbar></navbar>
    <contentupload></contentupload>
    <nuxt/>
  </div>
</template>

<script>
  import Navbar from '../components/Navbar'
  import Contentupload from '../components/Contentupload'

  export default {
    components: {
      Navbar,
      Contentupload
    }
  }
</script>