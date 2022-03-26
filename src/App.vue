<template>
<div class="container m-5">
  <Navbar />
</div>
<div class="container">
  <Navbar2 />
</div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Navbar2 from './components/Navbar2.vue'
export default {
  name: 'App',
  components: {
		Navbar,
    Navbar2
  }
}
</script>

<style>
</style>