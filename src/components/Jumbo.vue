<script>



export default {

     data() {
          return {

          }
     }
}

</script>

<template lang="">
          
          <div class="jumbo">
               <button>CORRENT SERIES</button>
          </div>
        
</template> 

<style lang="scss" scoped> 
 @use '../styles/general.scss' as*;
 @use '../styles/partials/variables.scss' as*;

 .jumbo{
         background-image: url('../../public/img/jumbotron.jpg');
         background-size: cover;
         background-repeat: no-repeat;
         height: 500px;
         position: relative;
         margin-bottom: 40px;

         button{
          color: white;
          padding: 20px;
          background-color: $colore_blu;
          position: absolute;
          left: 200px;
          bottom:-30px
         }
      }
 
</style>