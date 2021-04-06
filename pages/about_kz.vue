<template>
<div>
      <div class="qwert">
          <h1>Our Lessons</h1>
          <div class="robotics">
                <img src="../assets/robotic.jpg" alt="">
                <div class="robotics1">
                    <h2>Robotics</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo perspiciatis delectus eligendi? Dignissimos, vero maxime, aperiam corporis inventore incidunt amet aliquam facere maiores hic obcaecati accusamus error facilis nisi nulla!</p>
                </div>
          </div>
          <div class="coding">
              <img src="../assets/coding.jpg" alt="">
              <div class="coding1">
                    <h2>Coding</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo perspiciatis delectus eligendi? Dignissimos, vero maxime, aperiam corporis inventore incidunt amet aliquam facere maiores hic obcaecati accusamus error facilis nisi nulla!</p>
              </div>
          </div>
          <div class="language">
              <img src="../assets/language.png" alt="">
              <div class="language1">
                    <h2>Language</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo perspiciatis delectus eligendi? Dignissimos, vero maxime, aperiam corporis inventore incidunt amet aliquam facere maiores hic obcaecati accusamus error facilis nisi nulla!</p>
              </div>
          </div>
        
      </div>
</div>
</template>

<script>



export default {
  components:{

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
.qwert h1{
    margin: left;
    padding-top: 25px;
}
/* h2 {
    padding-top: 30px;
}
p {
    font-size: 24px;
    width: 100%;
    max-width: 1200px;
    margin: auto;
} */

img {
    border-radius: 25px;
    opacity: 1;
    display: block;
    width: 100%;
    max-width: 1200px;
    height: auto;
    margin: auto;
    transition: .5s ease;
    backface-visibility: hidden;
    border: 2px solid;
    margin-bottom: 50px;
}

/* ROBOTICS */
.robotics {
  position: relative;
  width: 50%;
  margin: auto;
}
.robotics1 {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.robotics:hover img {
  opacity: 0.2;
}

.robotics:hover .robotics1 {
  opacity: 1;
}
.robotics1 p{
    font-size: 24px;
    font-weight: 450;
}
/* CODING */
.coding {
  position: relative;
  width: 50%;
  margin: auto;
}

.coding1 {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.coding:hover img {
  opacity: 0.2;
}

.coding:hover .coding1 {
  opacity: 1;
}
.coding1 p{
    font-size: 24px;
    font-weight: 450;
}
/* LANGUAGE */
.language {
  position: relative;
  width: 50%;
  margin: auto;
}

.language1 {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.language:hover img {
  opacity: 0.2;
}

.language:hover .language1 {
  opacity: 1;
}
.language1 p{
    font-size: 24px;
    font-weight: 450;
}

</style>
