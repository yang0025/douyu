<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    <router-view/>


  </div>
</template>

<script>
// import HeaderNav from './components/HeaderNav'



export default {
  name: 'App',
  data:function () {
      return {

      }
  },


}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /*margin-top: 60px;*/
}
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  ul{
    list-style: none;
  }
  a{
    text-decoration: none;
    color: #444444;
  }

.el-dialog{
  height: 70%;

}
.el-dialog__body{
  padding: 0;
}
.el-dialog__title{
  font-size: 15px;
  color: #444444;
}


</style>
