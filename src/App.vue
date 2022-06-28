<template>
  <div>
    <input type="text" v-bind:value="text" @input="inputFn">
  </div>
</template>

<script>
export default {
  data () {
    return {
      text: ''
    }
  },
  methods: {
    inputFn(e){
      this.text = e.target.value
    }
  }
}
</script>

<style>

</style>