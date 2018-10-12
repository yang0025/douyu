<template>
    <div>
         <header-logo></header-logo>
         <header-nav></header-nav>
         <slide-show></slide-show>
         <main-page></main-page>

    </div>
</template>

<script>
  import HeaderLogo from '../components/HeaderLogo'
  import HeaderNav from '../components/HeaderNav'
  import MainPage from '../components/MainPage'
  import  SlideShow from '../components/SlideShow'
  // import KindPage from '../components/KindPage'
  export default {
        data: function () {
            return {}
        },
      components:{
        HeaderLogo,
        HeaderNav,
        MainPage,
        SlideShow,
        // KindPage
      },
  }
</script>

<style scoped>


</style>


