<template>
  <div id="app">
   <!-- HEADER -->
     <Header />
   
   <!-- MAIN -->
   <main>
    <Content />
   </main>

   <!-- FOOTER -->
   <footer></footer>
       



  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Content from '@/components/Content.vue'


export default {
  name: 'App',
  components: {
       Header,
       Content,
  },
}

</script>

<style lang="scss">
@import '@/style/globals';
@import '@/style/utilities';

  

  
  
</style>
