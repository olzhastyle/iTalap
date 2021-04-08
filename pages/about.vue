<template>
<div>
      <div class="qwert1254">
          <h1>Аудитория:</h1>
          <div class="legowedo">
                <img src="../assets/robotic.jpg" alt="">
                <div class="legowedo1">
                    <h2>Lego Wedo</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo perspiciatis delectus eligendi? Dignissimos, vero maxime, aperiam corporis inventore incidunt amet aliquam facere maiores hic obcaecati accusamus error facilis nisi nulla!</p>
                </div>
          </div>
          <div class="scratch">
              <img src="../assets/scratch.jpg" alt="">
              <div class="scratch1">
                    <h2>Scratch</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo perspiciatis delectus eligendi? Dignissimos, vero maxime, aperiam corporis inventore incidunt amet aliquam facere maiores hic obcaecati accusamus error facilis nisi nulla!</p>
              </div>
          </div>
          <div class="mindstorm">
              <img src="../assets/mindstorm.jpg" alt="">
              <div class="mindstorm1">
                    <h2>Lego Mindstorm</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo perspiciatis delectus eligendi? Dignissimos, vero maxime, aperiam corporis inventore incidunt amet aliquam facere maiores hic obcaecati accusamus error facilis nisi nulla!</p>
              </div>
          </div>
          <div class="python">
                <img src="../assets/coding.jpg" alt="">
                <div class="python1">
                    <h2>Python</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo perspiciatis delectus eligendi? Dignissimos, vero maxime, aperiam corporis inventore incidunt amet aliquam facere maiores hic obcaecati accusamus error facilis nisi nulla!</p>
                </div>
          </div>
          <div class="arduino">
              <img src="../assets/arduino.png" alt="">
              <div class="arduino1">
                    <h2>Arduino</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo perspiciatis delectus eligendi? Dignissimos, vero maxime, aperiam corporis inventore incidunt amet aliquam facere maiores hic obcaecati accusamus error facilis nisi nulla!</p>
              </div>
          </div>
          <div class="webdev">
              <img src="../assets/webdev.png" alt="">
              <div class="webdev1">
                    <h2>Web development</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo perspiciatis delectus eligendi? Dignissimos, vero maxime, aperiam corporis inventore incidunt amet aliquam facere maiores hic obcaecati accusamus error facilis nisi nulla!</p>
              </div>
          </div>
          <div class="mobwebdev">
                <img src="../assets/mobappdev.jpg" alt="">
                <div class="mobwebdev1">
                    <h2>Mobile application development</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo perspiciatis delectus eligendi? Dignissimos, vero maxime, aperiam corporis inventore incidunt amet aliquam facere maiores hic obcaecati accusamus error facilis nisi nulla!</p>
                </div>
          </div>
          <div class="animation">
              <img src="../assets/3d.jpg" alt="">
              <div class="animation1">
                    <h2>3D анимация</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illo perspiciatis delectus eligendi? Dignissimos, vero maxime, aperiam corporis inventore incidunt amet aliquam facere maiores hic obcaecati accusamus error facilis nisi nulla!</p>
              </div>
          </div>
          <div class="robotech115599">
              <img src="../assets/robots.jpg" alt="">
              <div class="robotech1">
                    <h2>Робототехника</h2>
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

.qwert1254 {
  position: relative;
  margin-top: auto;
  padding-top: 35px;
  padding-bottom: 20px;
  text-align: center;
  margin: 0 auto;
}
.qwert1254 h1{
    margin: left;
    padding-top: 25px;
    margin-top: 3%;
    margin-bottom: 2%;
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

.qwert1254 img {
    border-radius: 25px;
    opacity: 1;
    display: block;
    width: 90%;
    max-width: 700px;
    height: 405px;
    margin: auto;
    transition: .5s ease;
    backface-visibility: hidden;
    border: 2px solid;
    margin-bottom: 50px;
}

/* ROBOTICS */
.legowedo {
  position: relative;
  float: left;
  height: 445px;
  width: 50%;
}
.legowedo1 {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.legowedo:hover img {
  opacity: 0.2;
}

.legowedo:hover .legowedo1 {
  opacity: 1;
}
.legowedo1 p{
    font-size: 24px;
    font-weight: 450;
}
/* CODING */
.scratch {
  position: relative;
  float: left;
  width: 50%;
  height: 445px;
}
.scratch1 {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.scratch:hover img {
  opacity: 0.2;
}

.scratch:hover .scratch1 {
  opacity: 1;
}
.scratch1 p{
    font-size: 24px;
    font-weight: 450;
}
/* MINDSTORM */
.mindstorm {
  position: relative;
  float: left;
  width: 50%;
  height: 445px;
}
.mindstorm1 {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.mindstorm:hover img {
  opacity: 0.2;
}

.mindstorm:hover .mindstorm1 {
  opacity: 1;
}
.mindstorm p{
    font-size: 24px;
    font-weight: 450;
}
/* PYTHON */

.python {
  position: relative;
  float: left;
  width: 50%;
  height: 445px;
}
.python1 {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.python:hover img {
  opacity: 0.2;
}

.python:hover .python1 {
  opacity: 1;
}
.python p{
    font-size: 24px;
    font-weight: 450;
}
.arduino {
  position: relative;
  float: left;
  width: 50%;
  height: 445px;
}
.arduino1 {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.arduino:hover img {
  opacity: 0.2;
}

.arduino:hover .arduino1 {
  opacity: 1;
}
.arduino p{
    font-size: 24px;
    font-weight: 450;
}
.webdev {
  position: relative;
  float: left;
  width: 50%;
  height: 445px;
}
.webdev1 {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.webdev:hover img {
  opacity: 0.2;
}

.webdev:hover .webdev1 {
  opacity: 1;
}
.webdev p{
    font-size: 24px;
    font-weight: 450;
}
.mobwebdev {
  position: relative;
  float: left;
  width: 50%;
  height: 445px;
}
.mobwebdev1 {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.mobwebdev:hover img {
  opacity: 0.2;
}

.mobwebdev:hover .mobwebdev1 {
  opacity: 1;
}
.mobwebdev p{
    font-size: 24px;
    font-weight: 450;
}
.animation {
  position: relative;
  float: left;
  width: 50%;
  height: 445px;
}
.animation1 {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.animation:hover img {
  opacity: 0.2;
}

.animation:hover .animation1 {
  opacity: 1;
}
.animation p{
    font-size: 24px;
    font-weight: 450;
}
/* 
 .robotech115599 {
  position: absolute;
  width: 50%;
  height: 445px;
  margin: auto;
  float: none;
}
.robotech1 {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.robotech115599:hover img {
  opacity: 0.2;
}

.robotech115599:hover .robotech1 {
  opacity: 1;
}
.robotech1 p{
    font-size: 24px;
    font-weight: 450;
} */

</style>
