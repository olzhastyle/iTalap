<template>
<div>
      <div class="qwert">
        <!-- <Nuxt /> -->
      <Homepage_kz />
      <Aboutus_kz />
      <Lessons_kz />
      </div>
</div>
</template>

<script>
import Homepage from '../pages/components/Homepage.vue';
import Aboutus from '../pages/components/Aboutus.vue';
import Lessons from '../pages/components/Lessons.vue';
import Footer from '../pages/components/Footer.vue';


export default {
  components:{
    Homepage,
    Aboutus,
    Lessons,
    Footer
  }
}
</script>

<style>

.qwert {
  position: relative;
  margin-top: auto;
  padding-top: 35px;
  padding-bottom: 20px;
  text-align: center;
  margin: 0 auto;
}

</style>
