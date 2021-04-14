<template>
  <div class="navbar-main">
    <img class="oyuimage12" src="../assets/oyu.png" alt="" />
    <img class="oyuimage123" src="../assets/oyu.png" alt="" />
    <a class="navbar-brand" href="/"
      ><img
        class="logologo123"
        src="../assets/logo/white_transparent.png"
        alt=""
    /></a>
    <nav class="navbar navbar-expand-lg navbar-light">
      <div class="collapse navbar-collapse">
        <ul class="navbar-nav">
          <!-- <li class="nav-item">
            <nuxt-link
              exact
              no-prefetch
              active-class="active"
              class="nav-link"
              to="/"
            >
              Үйге
            </nuxt-link>
          </li> -->
          <li class="aboutSchool">
            <nuxt-link active-class="active" class="nav-link" to="/about">
              Мектеп туралы
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link active-class="active" class="nav-link" to="/about">
              Курстар
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link active-class="active" class="nav-link" to="/contacts">
              Байланыс
            </nuxt-link>
          </li>
        </ul>
        <a
          class="buttoninstagram"
          target="_blank"
          href="https://www.instagram.com/italap_turkestan/"
        >
          <img
            class="imageinstagram78963"
            src="../pages/components/assets/instagram.png"
            alt=""
          />
        </a>
        <a
          class="buttonwhatsapp"
          target="_blank"
          href="https://www.instagram.com/italap_turkestan/"
        >
          <img
            class="imagewhatsapp78963"
            src="../pages/components/assets/whatsapp.png"
            alt=""
          />
        </a>
      </div>
    </nav>
    <!-- <a class="kz" href="/">KZ</a>
    <a class="ru" href="/">RU</a> -->
  </div>
</template>

<style scoped>
.oyuimage12 {
  filter: opacity(0.3);
  position: absolute;
  left: 2%;
  width: 17%;
}
.oyuimage123 {
  filter: opacity(0.3);
  position: relative;
  float: right;
  right: 2%;
  width: 17%;
}

.imageinstagram78963 {
  filter: invert(1);
  width: 2.5rem;
  float: right;
  top: 14px;

  position: absolute;
}
.imagewhatsapp78963 {
  filter: invert(1);
  width: 4rem;
  float: right;
  top: 2px;
  margin-left: 50px;
  position: absolute;
}
.navbar {
  float: none;
  margin: auto;
  top: 50px;
  transform: translate(-50%, -50%);
  font-size: 24px;
  width: 0px;
}
/* .navbar-brand {
  float: none;
  position: absolute;
  top: 30px;
  left: 25%;
  transform: translate(-50%, -50%);
  font-size: 36px;
  color: white;
} */
.navbar-brand {
  position: absolute;
  left: 25%;
  top: -10%;
}

img {
  border: none;
  width: 160px;
}
.logologo123 {
  position: absolute;
  top: -20px;
  left: -150px;
}

.kz {
  float: none;
  position: absolute;
  top: 30px;
  right: 27%;
  transform: translate(-50%, -50%);
  font-size: 16px;
  color: rgb(0, 0, 0);
  cursor: pointer;
}

.ru {
  float: none;
  position: absolute;
  top: 30px;
  right: 25%;
  transform: translate(-50%, -50%);
  font-size: 16px;
  color: rgb(0, 0, 0);
  cursor: pointer;
}
.nav-link {
  text-decoration-color: white;
  color: white;
  cursor: pointer;
  width: 200px;
  margin: auto;
}

.nav-link:after {
  content: "";
  display: block;
  display: none;
  width: 100%;
  height: 3px;
  background-color: black;
  position: relative;
  top: 20px;
  left: 0px;
  z-index: 1;
}

.nav-link:hover {
  color: black;
}
.nav-link:hover:after {
  display: block;
  color: black;
}
.navbar-main {
  background-color: rgb(122, 122, 122);
  height: 100px;
  width: 100%;
}
.navbar-nav {
  left: -130px;
  position: relative;
  margin: auto;
}
</style>