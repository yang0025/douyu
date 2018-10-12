<template>
    <div class="kind-page">
      <kind-nav></kind-nav>
      <kind-pic></kind-pic>
    </div>
</template>

<script>
  import KindNav from './KindNav'
  import KindPic from './KindPic'
    export default {
        data: function () {
            return {}
        },
      components:{
          KindPic,
          KindNav
      }
    }
</script>

<style scoped>

</style>


