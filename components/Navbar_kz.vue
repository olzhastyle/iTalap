<template>
<div class="navbar-main">
    <a class="navbar-brand" href="/"><img src="../assets/logo1.png" alt=""></a>
    <nav class="navbar navbar-expand-lg navbar-light">

    <div class="collapse navbar-collapse">
        <ul class="navbar-nav">
        <li class="nav-item">
            <nuxt-link exact no-prefetch active-class="active" class="nav-link" to="/">
            Home
            </nuxt-link>
        </li>
        <li class="nav-item">
            <nuxt-link active-class="active" class="nav-link" to="/about">
            About
            </nuxt-link>
        </li>
        <li class="nav-item">
            <nuxt-link active-class="active" class="nav-link" to="/contacts">
            Contacts
            </nuxt-link>
        </li>
        </ul>
    </div>
    </nav>
    <a class="kz" href="/">KZ</a>
    <a class="ru" href="/">RU</a>
</div>
</template>

<style scoped>
.navbar {
  float: none;
  left: 44%;
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

img{
    border: none;
    width: 160px;

}
.kz{
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
.nav-link{
    text-decoration-color: white;
    color: white;
    cursor: pointer ;
    
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

.nav-link:hover{
    color: black;
}
.nav-link:hover:after{
    display: block;
    color: black;
}
.navbar-main {
    background-color: rgb(122, 122, 122);
    height: 100px;
}


</style>