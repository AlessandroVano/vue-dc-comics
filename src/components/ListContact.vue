<template>
  <section >

    <!-- colonne -->

    <div class="container columns">
      <div class="link">
     <div>
       <h2>DE COMICS</h2>
       <nav>
         <ul>
           <li>
             <a href="/characters">Characters</a>
           </li>
            <li>
             <a href="/comics">Comics</a>
           </li>
            <li>
             <a href="/movies">Movies</a>
           </li>
            <li>
             <a href="/tv">TV</a>
           </li>
            <li>
             <a href="/games">Games</a>
           </li>
            <li>
             <a href="/videos">Videos</a>
           </li>
            <li>
             <a href="/news">News</a>
           </li>
         </ul>

         <h2> SHOP</h2>
         <ul>
             <li>
             <a href="/shop-dc">Shop Dc</a>
           </li>
            <li>
             <a href="/shop-dc-collectibles">Shop DC Collectibles</a>
           </li>
         </ul>
       </nav>
     </div>

     <div>
       <h2> DC</h2>
       <nav>
         <ul>
             <li>
             <a href="/term-of-of-use">Terms Of Use</a>
           </li>
            <li>
             <a href="/privacy-policy-(new)">Privacy policy (New)</a>
           </li>
            <li>
             <a href="/ad-choices">Ad Choices</a>
           </li>
            <li>
             <a href="/advertising">Advertising</a>
           </li>
            <li>
             <a href="/jobs">Jobs</a>
           </li>
            <li>
             <a href="/subscriptions">Subscriptions</a>
           </li>
            <li>
             <a href="/talent-workshop">Talent Workshops</a>
           </li>
              <li>
             <a href="/cpcs-certificates">CPCS Certificates</a>
           </li>
            <li>
             <a href="/ratings">Ratings</a>
           </li>
              <li>
             <a href="/shop-help">Shop Help</a>
           </li>
            <li>
             <a href="/contanct-us">Contact Us</a>
           </li>
         </ul>
       </nav>
     </div>

     <div> 
       <h2>SITES</h2>
       <nav>
         <ul>
            <li>
             <a href="/dc">DC</a>
           </li>
            <li>
             <a href="/mad-magazine">MAD Magazine</a>
           </li>
            <li>
             <a href="/dc-kids">DC Kids</a>
           </li>
            <li>
             <a href="/dc-universe">DC Universe</a>
           </li>
            <li>
             <a href="/dc-power-visa">DC Power Visa</a>
           </li>
         </ul>
       </nav>
     </div>

      </div>

   
     <!-- logo -->
   <!--   <div>
       <a href="">
         <img src="../assets/dc-logo-bg.png" alt="">
       </a>
     </div> -->
      </div>

  </section>
</template>

<script>
export default {
name: 'ListContact'
}
</script>

<style scoped lang="scss">
section {
  background-image: url(../assets/footer-bg.jpg);
}
/* img {
  width: 400px;
  
} */
.link {
  display: flex;
}
 .columns {
   display: flex;
   justify-content: space-between;
   
 }
 h2 {
   margin-top: 1rem;
   padding-left: 2rem ;
   margin-bottom: 0.8rem;
   color: white;
 }
 ul {
   list-style: none;
   padding-left: 2rem;
   margin-bottom: 3rem;
   
   a{
     font-size: 14px;
     display: inline-block;
     margin-bottom: 0.35rem ;
     text-decoration: none;
     color: rgb(173, 170, 170);
   }
 }
</style>