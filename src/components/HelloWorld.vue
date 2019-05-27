<template>
  <div class="hello">
    <vue-form></vue-form>

  </div>
</template>

<script>
import VueForm from "./sub/vue-form";
//验证jquery引入成功没
// $(function () {
//   alert(123);
// });
export default {
  name: 'HelloWorld',
  components: {VueForm},
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  created(){
    console.log($);
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
