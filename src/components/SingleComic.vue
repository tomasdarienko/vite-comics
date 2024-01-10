<script>



export default {

     props: {
          fumetto: Object
     },
     data() {
          return {

          }
     }
}

</script>

<template lang="">
          
                <div class="carta">
                    <img :src="fumetto.thumb" />
                    <h4>{{fumetto.series}}</h4>
                </div>
        
</template> 

<style lang="scss" scoped> @use '../styles/general.scss' as*;
 @use '../styles/partials/variables.scss' as*;


 .carta {

      width: calc(100% / 6 - 20px);
      margin: 30px 10px;
      height: 200px;

      img {
           height: 200px;
           width: 200px;
           object-fit: cover;
      }
      h4{
          text-transform: uppercase;
      }
 }
</style>