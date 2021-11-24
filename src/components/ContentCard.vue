<template>

 <section >
     <button class="btn2 mr"> <h4>Current Series</h4></button>
  <!--    <h1 class="container">-- Content goes here -- </h1> -->
  <div class="container">
     
     <ul class="boxes ">
         <li v-for="(card, index) in cards" :key="`card ${index}`">
      
         <!-- v-bind (:) x fargli interpretare js -->
         <Card :url="card.thumb" :title="card.series" />

         </li>
     </ul>

     <div class="text-center">
    <button class="btn"> <h4>load more</h4></button>
     </div>
  </div>
 </section>
</template>

<script>
import Card from '@/components/Card.vue';
import {Cards}   from '@/devData/prodItem.js';


export default {
 name: 'Contenuto',
 components: {
     Card,
 },

 data() {
     return {
        cards: Cards,
     };
 },
};
</script>

<style scoped lang='scss'>
section {
    padding: 2rem 0;
    background-color: black;
    color: white;
}

.boxes {
    display: flex;
    flex-wrap: wrap;
    list-style: none;
    margin-left: 140px;
    
    li {
        width: calc(100% / 6);
    }
}
.mr {
 position: absolute;
 margin-top: -48px;
 margin-left: 156px;
}



</style>