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
   <footer></footer>
       



  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Content from '@/components/Content.vue'
import Navigation from '@/components/Navigation.vue'


export default {
  name: 'App',
  components: {
       Header,
       Content,
       Navigation,
  },
}

</script>

<style lang="scss">
@import '@/style/globals';
@import '@/style/utilities';

  

  
  
</style>
