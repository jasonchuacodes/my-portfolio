<template>
<div class="container mt-5">
  <Navbar />
  <p>Ahoy there mates!
    This will fail
  </p>
</div>
</template>

<script>
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
		Navbar
  }
}
</script>

<style>
</style>