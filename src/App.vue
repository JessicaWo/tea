<template>
  <div id="app">

    <router-view/>
    <footerNav></footerNav>
  </div>
</template>

<script>
  import footerNav from './components/footer-nav'

  export default {
    name: 'App',
    components: {
      footerNav
    }
  }
</script>

<style>

</style>
