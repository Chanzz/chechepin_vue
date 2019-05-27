<template>
  <div class="hello">
    <vue-form :infos="infos"></vue-form>
    <div v-for="info in infos">
      {{info}}
    </div>
  </div>
</template>

<script>
  import VueForm from "./sub/vue-form";
  import axios from 'axios'
  //验证jquery引入成功没
  // $(function () {
  //   alert(123);
  // });
  export default {
    name: 'HelloWorld',
    components: {VueForm},
    data() {
      return {
        infos: null,
        test:'this is a test'
      }
    },
    mounted() {
      axios.get('http://localhost:8667/api/activity/activity/2/').then(
        response => (this.infos = response.data)
        // function(response){
        //   console.log(response);}
      )
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
