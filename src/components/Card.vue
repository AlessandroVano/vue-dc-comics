<template>
  <div>
      <img  :src="url" :alt="title">
         <h5> {{title}} </h5>
  </div>
</template>

<script>
export default {
name: 'Card',
props: {
   url: String,
   title: String,
}
}
</script>

<style scoped lang="scss">
img{
 width: 120px;
 height: 120px;
 object-fit: cover;
 object-position: top;
}
h5 {
    font-size: 10px;
    text-transform: uppercase;
    width: 140px;
    margin-top: 0.8rem ;
    margin-bottom: 2rem;
}
</style>