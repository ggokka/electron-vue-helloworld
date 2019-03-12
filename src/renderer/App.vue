<template>
  <div id="app">
    <landing-page></landing-page>
    <data-binding></data-binding>
  </div>
</template>

<script>
  import LandingPage from '@/components/LandingPage'
  import DataBinding from '@/components/DataBinding'

  export default {
    name: 'helloworld',
    components: {
      LandingPage , DataBinding
    }
  }
</script>

<style>
  /* CSS */
</style>
