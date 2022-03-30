<template>
  <input type="text" 
    :value="modelValue"
    @input="$emit('update:modelValue', $event.target.value)"
    :placeholder="'Insert ' + this.name"  
  >
  <!-- <button @click="submit">Submit</button> -->
</template>
<script>
export default {
  props: ['modelValue', 'name'],
  data() {
    return {
    }
  },
  methods: {
    submit() {
      
    }
  }
}
</script>