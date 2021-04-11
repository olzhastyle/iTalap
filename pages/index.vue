<template>
  <div>
    <div class="qwert111">
      <!-- <Nuxt /> -->
      <Homepage />
      <!--  <Aboutus /> -->
      <!-- <Lessons /> -->
      <Lessonskz />
      <Aboutus />
    </div>
  </div>
</template>

<script>
import Homepage from "../pages/components/Homepage.vue";
import Aboutus from "../pages/components/Aboutus.vue";
import Lessons from "../pages/components/Lessons.vue";
import Lessonskz from "../pages/components/Lessonskz.vue";

export default {
  components: {
    Homepage,
    Aboutus,
    Lessonskz,
  },
};
</script>

<style>
.qwert111 {
  position: relative;
  margin-top: auto;
  padding-top: 35px;
  padding-bottom: 20px;
  text-align: center;
  margin: 0 auto;
}
</style>
