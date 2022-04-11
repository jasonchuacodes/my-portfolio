<template>
<div class="container mt-5">
  <Navbar />

</div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import CustomInput from './components/CustomInput.vue'


export default {
  name: 'App',
  props: ['fname', 'lname'],
  components: {
    Navbar,
    CustomInput
  },
  data() {
    return{
      firstNameLabel: 'First Name',
      lastNameLabel: 'Last Name',
    }
  }
}
</script>

<style>
</style>