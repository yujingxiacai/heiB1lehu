<template>
  <div id="app">
    <div id="nav">
      <Header></Header>
    </div>
  </div>
</template>

<script>

import 'bootstrap/dist/css/bootstrap.min.css';
import 'bootstrap/dist/js/bootstrap.min';
import '@/assets/css/style.css';
// import '@/assets/js/jquery.flexslider-min.js';
import Header from'@/components/Header.vue';
// $(function () {
//   alert('234')
// });
export default {
  components:{
    Header,
  },
  data:{
  
 },
}
</script>


<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
