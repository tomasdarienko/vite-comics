<script>



export default {
     data() {
          return {

          }
     }
}

</script>

<template lang="">
  
          <footer>
               <div class="top_footer">
                    <div class="container">
                         <div class="content_footer">
                              <div class="menu_col">
                                   <h2>DC COMICS</h2>
                                   <ul>
                                        <li>CHARACTER</li>
                                        <li>COMICS</li>
                                        <li>TV</li>
                                        <li>GAMES</li>
                                        <li>VIDEOS</li>
                                        <li>NEWS</li>
                                   </ul>
                                   <h2>SHOP</h2>
                                   <ul>
                                        <li>SHOP</li>
                                        <li>SHOP DC</li>
                                       
                                   </ul>
                              </div>
                              <div class="menu_col">
                                   <h2>DC </h2>
                                   <ul>
                                        <li>COMICS</li>
                                        <li>TV</li>
                                        <li>GAMES</li>
                                        <li>VIDEOS</li>
                                        <li>NEWS</li>
                                        <li>TV</li>
                                        <li>GAMES</li>
                                        <li>VIDEOS</li>
                                        <li>NEWS</li>
                                   </ul>
                                 
                                  
                              </div>
                              <div class="menu_col">
                                   <h2>SITES </h2>
                                   <ul>
                                        <li>COMICS</li>
                                        <li>TV</li>
                                        <li>GAMES</li>
                                        <li>VIDEOS</li>
                                        <li>NEWS</li>
                                        <li>TV</li>
                                        <li>GAMES</li>
                                        <li>VIDEOS</li>
                                        <li>NEWS</li>
                                   </ul>
                              </div>
                         </div>
                    </div>
               </div>

               <div class="bottom_footer">
                    <div class="container">
                         <div class="content_bt">

                        
                              <button >
                              SING UP NOW
                              </button>
                              <div class="right_bt_content">
                                   <h2>FOLLOW US</h2>

                                   <img src="../../public/img/footer-facebook.png" alt="">
                                   <img src="../../public/img/footer-twitter.png" alt="">
                                   <img src="../../public/img/footer-periscope.png" alt="">
                                   <img src="../../public/img/footer-youtube.png" alt="">
                              </div> 
                         </div>
                    </div>
               </div>
          </footer>
 
</template> 

<style lang="scss" scoped>
@use '../styles/partials/variables.scss' as*;

.top_footer {
     background-image: url('../../public/img/footer-bg.jpg');
     background-size: cover;

     .content_footer {
          background-image: url('../../public/img/dc-logo-bg.png');
          background-repeat: no-repeat;
          background-position: right;
          padding: 40px;
          display: flex;
          color: #a6a6a6;

     }

     h2 {
          margin: 20px 0;
          margin-right: 100px;
          color: white;
     }

     ul {
          list-style-type: none;

          li {
               margin-top: 10px;
          }
     }
}

.bottom_footer {
     background-color: black;


     button {
          background-color: black;
          border-color: $colore_blu;
          color: white;
          padding: 20px;
          font-size: 20px;
     }

     .content_bt {
          display: flex;
          justify-content: space-between;
          align-items: center;
          padding: 30px;
     }
     h2 {
          margin: 10px;
          color: $colore_blu;
     }
     .right_bt_content{
          display: flex;
          align-items: center;
          img{
               margin: 10px;
          }
     }
}
</style>