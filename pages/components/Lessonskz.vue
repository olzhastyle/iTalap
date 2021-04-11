<template>
  <div class="main">
    <section>
      <h1 class="title1258">Біздің курстарымыз:</h1>
      <div class="tabs">
        <input type="radio" name="tab-btn" id="tab-btn-1" value="" checked />
        <label for="tab-btn-1">Lego Wedo</label>
        <input type="radio" name="tab-btn" id="tab-btn-2" value="" />
        <label for="tab-btn-2">Scratch</label>
        <input type="radio" name="tab-btn" id="tab-btn-3" value="" />
        <label for="tab-btn-3">Mindstorm</label>
        <input type="radio" name="tab-btn" id="tab-btn-4" value="" checked />
        <label for="tab-btn-4">Python</label>
        <input type="radio" name="tab-btn" id="tab-btn-5" value="" />
        <label for="tab-btn-5">Web Development</label>
        <input type="radio" name="tab-btn" id="tab-btn-6" value="" />
        <label for="tab-btn-6">Arduino</label>
        <input type="radio" name="tab-btn" id="tab-btn-7" value="" checked />
        <label for="tab-btn-7">Mobile application development</label>
        <input type="radio" name="tab-btn" id="tab-btn-8" value="" />
        <label for="tab-btn-8">3D animation</label>
        <input type="radio" name="tab-btn" id="tab-btn-9" value="" />
        <label for="tab-btn-9">Робототехника</label>

        <div id="content-1">
          <img class="image123654" src="../../assets/robotic.jpg" alt="" />
          <p class="text46548"></p>
        </div>
        <div id="content-2">
          <img class="image123654" src="../../assets/scratch.jpg" alt="" />
          <p class="text46548">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Amet ad
            perferendis adipisci, sunt fugiat neque reiciendis assumenda, quam
            aspernatur at impedit ut iusto mollitia expedita unde corrupti
            exercitationem dolore eligendi!
          </p>
        </div>
        <div id="content-3">
          <img class="image123654" src="../../assets/mindstorm.jpg" alt="" />
          <p class="text46548">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Amet ad
            perferendis adipisci, sunt fugiat neque reiciendis assumenda, quam
            aspernatur at impedit ut iusto mollitia expedita unde corrupti
            exercitationem dolore eligendi!
          </p>
        </div>
        <div id="content-4">
          <img class="image123654" src="../../assets/coding.jpg" alt="" />
          <p class="text46548">Python</p>
        </div>
        <div id="content-5">
          <img class="image123654" src="../../assets/webdev.png" alt="" />
          <p class="text46548">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Amet ad
            perferendis adipisci, sunt fugiat neque reiciendis assumenda, quam
            aspernatur at impedit ut iusto mollitia expedita unde corrupti
            exercitationem dolore eligendi!
          </p>
        </div>
        <div id="content-6">
          <img class="image123654" src="../../assets/arduino.png" alt="" />
          <p class="text46548">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Amet ad
            perferendis adipisci, sunt fugiat neque reiciendis assumenda, quam
            aspernatur at impedit ut iusto mollitia expedita unde corrupti
            exercitationem dolore eligendi!
          </p>
        </div>
        <div id="content-7">
          <img class="image123654" src="../../assets/mobappdev.jpg" alt="" />
          <p class="text46548">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Amet ad
            perferendis adipisci, sunt fugiat neque reiciendis assumenda, quam
            aspernatur at impedit ut iusto mollitia expedita unde corrupti
            exercitationem dolore eligendi!
          </p>
        </div>
        <div id="content-8">
          <img class="image123654" src="../../assets/3d.jpg" alt="" />

          <p class="text46548">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Amet ad
            perferendis adipisci, sunt fugiat neque reiciendis assumenda, quam
            aspernatur at impedit ut iusto mollitia expedita unde corrupti
            exercitationem dolore eligendi!
          </p>
        </div>
        <div id="content-9">
          <img class="image123654" src="../../assets/robots.jpg" alt="" />

          <p class="text46548">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Amet ad
            perferendis adipisci, sunt fugiat neque reiciendis assumenda, quam
            aspernatur at impedit ut iusto mollitia expedita unde corrupti
            exercitationem dolore eligendi!
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.tabs {
  max-width: 1200px;
  margin-left: auto;
  margin-right: auto;
}

.tabs > input[type="radio"] {
  display: none;
}

.tabs > input[type="radio"]:checked + label {
  background-color: #bdbdbd;
}

.tabs > div {
  /* скрыть контент по умолчанию */
  display: none;
  border: 1px solid #eee;
  padding: 10px 15px;
  border-radius: 4px;
}

/* отобразить контент, связанный с вабранной радиокнопкой (input type="radio") */
#tab-btn-1:checked ~ #content-1,
#tab-btn-2:checked ~ #content-2,
#tab-btn-3:checked ~ #content-3,
#tab-btn-4:checked ~ #content-4,
#tab-btn-5:checked ~ #content-5,
#tab-btn-6:checked ~ #content-6,
#tab-btn-7:checked ~ #content-7,
#tab-btn-8:checked ~ #content-8,
#tab-btn-9:checked ~ #content-9 {
  display: block;
}

.tabs > label {
  display: inline-block;
  text-align: center;
  vertical-align: middle;
  user-select: none;
  background-color: #eee;
  border: 1px solid transparent;
  padding: 2px 8px;
  font-size: 24px;
  line-height: 1.5;
  border-radius: 4px;
  transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out,
    border-color 0.15s ease-in-out;
  margin-left: 6px;
  cursor: pointer;
  margin-bottom: 10px;
}

.tabs > label:first-of-type {
  margin-left: 0;
}

.title1258 {
  margin-top: 35px;
  font-family: "Courier New", Courier, monospace;
  margin-bottom: 30px;
}
.image123654 {
  width: 100%;
  border: 2px solid;
  border-radius: 25px;
}
.text46548 {
  font-size: 26px;
}
</style>