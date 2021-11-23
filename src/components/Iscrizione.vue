<template>

  <section>
     <div class="container df">
      <button>
          <h1>SIGN-UP NOW!  </h1> 
      </button>
      <nav>
          <ul>
              <li>
                  <h2>FOLLOW US</h2>
              </li>
              <li>
                  <a href="/">
                  <img src="../assets/footer-facebook.png" alt="">
                  </a>
              </li>
              <li>
                  <a href="/">
                  <img src="../assets/footer-twitter.png" alt="">
                  </a>
              </li>
              <li>
                  <a href="/">
                  <img src="../assets/footer-youtube.png" alt="">
                  </a>
              </li>
              <li>
                  <a href="/">
                  <img src="../assets/footer-pinterest.png" alt="">
                  </a>
              </li>
              <li>
                  <a href="/">
                  <img src="../assets/footer-periscope.png" alt="">
                  </a>
              </li>
          </ul>
      </nav>
     </div>
  </section>

</template>

<script>
export default {
name: 'Iscrizione'
}
</script>

<style scoped lang="scss">
section {
    background-color:rgb(73, 73, 73);
     
      
}

.df {
    display: flex;
    justify-content: space-between;
}
button {
      margin: 1.2rem ;
      padding: 0.6rem ; 
      text-transform: uppercase;
      font-size: 0.7rem;
      border: 3px solid rgb(68, 68, 247);
       background-color: rgb(73, 73, 73); 
    cursor: pointer;
    color: white;
}


h2{
    margin-top: 0.9rem;
    padding-right: 0.5rem;
    font-size: 1.2rem;
    color:  rgb(68, 68, 247);
}
ul {
    display: flex;
    list-style: none;
    margin: 1.6rem 0 ;
}
a{
    display: inline-block;
    padding: 0.5rem;
    text-decoration: none;
    font-weight: 501;
    font-size: 12px;
}

</style>