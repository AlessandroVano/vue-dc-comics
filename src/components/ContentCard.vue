<template>
 <section >
  <!--    <h1 class="container">-- Content goes here -- </h1> -->
  <div class="container">
     <ul class="boxes ">
         <li v-for="(card, index) in cards" :key="`card ${index}`">
      
         <!-- v-bind (:) x fargli interpretare js -->
         <Card :url="card.thumb" :title="card.series" />

         </li>
     </ul>

  </div>
 </section>
</template>

<script>
import Card from '@/components/Card.vue';
import {Cards} from '@/devData/prodItem.js';

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

</style>