<template>
  <div class="hello">
    {{ msg }}
    
  </div>
</template>
<!--https://medium.com/notonlycss/the-difference-between-props-slots-and-scoped-slots-in-vue-js-a697b57099ee-->
<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  padding-top: 20px;
  font-size: 20px
}
</style>
