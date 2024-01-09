<script>



export default {

     data() {
          return {
               links: [
                    'CHARACTER',
                    'COMICS',
                    'MOVIES',
                    'TV',
                    'GAMES',
                    'COLLECTIBLES',
                    'VIDEOS',
                    'FANS',
                    'NEWS',
                    'SHOP',

               ]
          }
     }
}

</script>

<template lang="">
  <header>
     <div class="container">

          <div class="navbar">

               <div class="logo">
                    <a href="/">
                    <img src="../../public/img/dc-logo.png" >
               </a>
               </div>
               <div class="menu">
                    <ul>
                         <li v-for="link,index in links" :key="index" :class="index == 1 ? 'active' : '' ">
                         {{link}}
                         </li>
                    </ul>
               </div>
          </div>
     </div>
</header>
</template> 

<style lang="scss" scoped> @use '../styles/general.scss' as*;
 @use '../styles/partials/variables.scss' as*;

 .navbar {
      display: flex;
      justify-content: space-between;
      padding: 20px 0;

      .logo {
           width: 100px;
           vertical-align: middle;
      }

      ul {
           list-style-type: none;
           margin: 0;

           li{
               display: inline-block;
               margin: 9px;
               line-height: 70px;
               font-size: large;
           }
           .active{
               color: $colore_blu;
               border-bottom: 5px solid $colore_blu;
           }
      }
 }</style>