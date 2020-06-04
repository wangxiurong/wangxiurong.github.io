<template>
  <div class="hello">
    <el-button @click="show = !show">Click Me</el-button>
  
     <el-radio v-model="number" label="1">备选项</el-radio>
    <el-radio v-model="number" label="2">备选项</el-radio>
   
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      show: true,
      number:'1',
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
