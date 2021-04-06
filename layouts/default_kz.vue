<template>
<div>

  <div class="salem">
    <Navbar/>
  </div>
  
    <main>
      <div class="qwerty12">
        <!-- <Nuxt /> -->
      <nuxt />
      </div>
    </main>
    <Footer />
</div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
import Footer from '../pages/components/Footer.vue';

export default {
  components:{
    Navbar,
    Footer
  }
}
</script>

<style>
div{
  scroll-behavior: smooth;
}
.salem {
  text-align: center;
  position: fixed;
  width: 100%;
  float: none;
  z-index: 10;
}
.qwerty12 {
  position: relative;
  margin-top: auto;
  padding-top: 35px;
  padding-bottom: 20px;
}

</style>
