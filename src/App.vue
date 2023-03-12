<template>
  <div class="wrapper">

    <!-- html code -->

    <Header></Header>
    <Main></Main>
    <Footer></Footer>



  </div>
</template>



<script>
   
  //  Java code

import Footer from './components/Footer.vue';
import Header from './components/Header.vue';
import Main from './components/Main.vue';

  export default {
    components: { Main, Header, Footer }
}
</script>






<style>
/* css code */

    *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    a {
      text-decoration: none;
    }


    ul {
      list-style: none;
    }

</style>