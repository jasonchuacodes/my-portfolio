<template>
<div class="container mt-5">
  <Navbar />
  <CustomInput 
    :name="firstNameLabel" 
    v-model="fname" 
  />
  <br>
  <CustomInput 
    :name="lastNameLabel" 
    v-model="lname" 
  />

  <div>First Name: {{fname}}</div>
  <div>Last Name: {{lname}}</div>
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