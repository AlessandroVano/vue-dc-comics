<template>
  <section>
      <div class="container icon ">
        <a class="banner" href="/digital-comincs">
        <img src="../assets/buy-comics-digital-comics.png" alt="digital-comincs">
        <span>DIGITAL COMICS</span>
        </a>
          <a class="banner" href="/dc-merchandise">
        <img src="../assets/buy-comics-merchandise.png" alt="dc-merchandise">
        <span>DC MERCHANDISE</span>
        </a>
          <a class="banner" href="/subscription">
        <img src="../assets/buy-comics-subscriptions.png" alt="subscription">
        <span>SUBSCRIPTION</span>
        </a>
          <a class="banner" href="/comic-shop-location">
        <img src="../assets/buy-comics-shop-locator.png" alt="comic-shop-location">
        <span>COMIC SHOP LOCATION</span>
        </a>
          <a class="banner" href="/dc-power-visa">
        <img src="../assets/buy-dc-power-visa.svg" alt="dc-power-visa">
        <span>DC POWER VISA</span>
        </a>
 
      </div>
  </section>
</template>

<script>
export default {
name: 'Navigation'
}
</script>

<style scoped lang="scss">
section {
    background-color: rgb(68, 68, 247);
    padding: 2rem 0;
    
}
.icon {
    display: flex;
    justify-content: space-between;
    
}
.banner {
    display: flex;
}
img {
   width: 35px;
   object-fit: contain;
}
span {
    margin-top: 1.2rem;
    font-size: 12px;
    padding-left: 15px;
    color: white;
}
a {
    text-decoration: none;
}

</style>