<template>
  <div id="app">

  <body>
    
   <!-- HEADER -->
     <Header />
   
   <!-- MAIN -->
   <main>
     <Hero />
    <Content />

    <Navigation />
   </main>

   <!-- FOOTER -->
   <footer>
     <ListContact />
     <Iscrizione />
    
   </footer>
  </body>
       



  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Content from '@/components/Content.vue'
import Navigation from '@/components/Navigation.vue'
import ListContact from '@/components/ListContact.vue'
import Iscrizione from '@/components/Iscrizione.vue'
import Hero from '@/components/Hero.vue'



export default {
  name: 'App',
  components: {
       Header,
       Content,
       Navigation,
       ListContact,
       Iscrizione,
       Hero,
  },
}

</script>

<style lang="scss">
@import '@/style/globals';
@import '@/style/utilities';

  body {
    background-color: black;
  }

  
  
</style>
