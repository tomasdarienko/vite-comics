<script>


import appheader from './components/appheader.vue';
import appmain from './components/appmain.vue';
import appfooter from './components/appfooter.vue';

export default {
components:{
  appheader,
  appmain,
  appfooter,
}
}

</script>

<template lang="">
  <div>
    <appheader />
    <appmain />
    <appfooter />
  </div> 
</template> 

<style lang="scss"> 
@use './styles/general.scss'
</style>