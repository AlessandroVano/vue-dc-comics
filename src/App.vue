<template>
  <div id="app">
   <!-- HEADER -->
     <Header />
   
   <!-- MAIN -->
   <main>
    <Content />

    <Navigation />
   </main>

   <!-- FOOTER -->
   <footer>
     <ListContact />
     <Iscrizione />
   </footer>
       



  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Content from '@/components/Content.vue'
import Navigation from '@/components/Navigation.vue'
import ListContact from '@/components/ListContact.vue'
import Iscrizione from '@/components/Iscrizione.vue'


export default {
  name: 'App',
  components: {
       Header,
       Content,
       Navigation,
       ListContact,
       Iscrizione,
  },
}

</script>

<style lang="scss">
@import '@/style/globals';
@import '@/style/utilities';

  

  
  
</style>
