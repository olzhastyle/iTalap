<template>
    <!-- Footer -->
<footer class="bg-dark text-center text-white">
  <!-- Grid container -->
  <div class="container p-4">

    <!-- Section: Text -->
    <section class="mb-4">
      <!-- <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt distinctio earum
        repellat quaerat voluptatibus placeat nam, commodi optio pariatur est quia magnam
        eum harum corrupti dicta, aliquam sequi voluptate quas.
      </p> -->
    </section>
    <!-- Section: Text -->

    <!-- Section: Links -->
    <section class="">
      <!--Grid row-->
      <div class="row">
        <!--Grid column-->
        <div class="col-lg-3">
          <h5 class="text-uppercase">Аудитория</h5>

          <ul class="list-unstyled mb-0">
            <li>
              <a href="#!" class="text-white">Home</a>
            </li>
            <li>
              <a href="#!" class="text-white">About</a>
            </li>
            <li>
              <a href="#!" class="text-white">Contacts</a>
            </li>
            <li>
              <a href="#!" class="text-white">Vacations</a>
            </li>
          </ul>
        </div>
         <div class="col-lg-3">
          <h5 class="text-uppercase">Байланыс</h5>
          <a href="https://www.instagram.com/olzhastyle/">
            <img class="instagramfooter" src="./assets/instagram.png" alt="#">
          </a>
          <a href="http://sendamessage.to/">
            <img class="whatsappfooter" src="./assets/whatsapp.png" alt="#">
          </a>
          <h6>Түркістан қ., Б. Саттарханов даңғылы 64</h6>
        </div>
        <!--Grid column-->

      </div>
      <!--Grid row-->
    </section>
    <!-- Section: Links -->
  </div>
  <!-- Grid container -->

  <!-- Copyright -->
  <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
    © 2021 Turkistan:
    <a class="text-white" href="/home">iTalap.kz</a>
  </div>
  <!-- Copyright -->
</footer>
<!-- Footer -->
</template>

<style scoped>
.row{
    width: 100%;
    margin: 0;
    text-align: center;
}
/* img{
  filter: invert(0);
  transform: scale(1);
  z-index: 0;
} */

.col-lg-3 {
    margin: auto;
    width: 100%;
}
.instagramfooter {
  width: 35px;
  filter: invert(1);

}
.whatsappfooter {
  width: 60px;
  filter: invert(1);
}
</style>