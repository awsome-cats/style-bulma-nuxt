<template>
  <div>
    <nav-bar />
    <div class="main-body container">
      <search />
      <nuxt />
    </div>
    <Footer />
  </div>
</template>

<script>
import Footer from '@/components/Footer'
import NavBar from '@/components/NavBar'
import Search from '@/components/Search'
export default {
  components: {
    Footer,
    NavBar,
    Search
  }
}
</script>

<style>

</style>
