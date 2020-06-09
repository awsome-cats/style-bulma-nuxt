<template>
  <div>
    <nav-bar />
    <div class="container main-body">
      <nuxt />
    </div>
    <Footer />
  </div>
</template>

<script>
import Footer from '@/components/Footer'
import NavBar from '@/components/NavBar'
export default {
  components: {
    Footer,
    NavBar
  }
}
</script>

<style>
.main-body {
  min-height: 720px;
}
</style>
