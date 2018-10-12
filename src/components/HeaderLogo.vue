<template>
   <div>
     <div class="nav-top">
       <img src="../assets/logo864f3e.png" alt="">
       <span class="open-App">打开App</span>
       <span class="chongzhi">充值</span>
       <span><i class="fa fa-search"></i></span>
     </div>
   </div>
</template>

<script>
  export default {
        data: function () {
            return {}
        }
    }
  // https://m.douyu.com/api/cate/recList?cid=&ct=
</script>

<style scoped>
  .nav-top{
    overflow: hidden;
  }
 .nav-top img{
   float: left;
   width: 76px;
   height: 34px;
   margin: 10px 0 0 10px;
 }
 .nav-top  .open-App{
     float: left;
     width: 74px;
     height: 28px;
     line-height: 28px;
     border-radius: 2px;
     font-size: 12px;
     margin: 15px 0 0 10px;
     border:1px solid #ff5d23;
     color: #ff5d23;
  }
 .nav-top .chongzhi{
   float: left;
   width: 49px;
   height: 28px;
   line-height: 28px;
   border-radius: 2px;
   color: #fff;
   background-color: #ff5d23;
   margin: 15px 0 0 10px;
   font-size: 14px;
 }
  .nav-top .fa{
    float: right;
    margin: 18px 10px 0 0;
    color:#444444;
  }

</style>


