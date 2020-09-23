<template>
  <div id="about" class="info_container">
    <div class="one_info_block">
      <img src="../static/img/cicle.svg" class="info_dial" />
      <img src="../static/img/student.svg" class="info_img" />
      <p class="info_text">3590<br/>Всего детей</p>
    </div>
    <div class="one_info_block">
      <img src="../static/img/cicle.svg" class="info_dial" />
      <img src="../static/img/room.svg" class="info_img" />
      <p class="info_text">789<br/>комнат</p>
    </div>
    <div class="one_info_block">
      <img src="../static/img/cicle.svg" class="info_dial" />
      <img src="../static/img/teacher.svg" class="info_img" />
      <p class="info_text">300<br/>Всего учителей</p>
    </div>
  </div>
</template>

<style>
.info_container {
  grid-area: info;
  position: relative;
  display: flex;
  justify-content: space-between;
  margin: 50px 90px 0px 90px; 
}

.one_info_block {
  position: relative;
}

.info_dial {
  position: relative;
  max-width: 100%;
  max-height: 100%;
}

 .info_img {
  position: absolute;
  margin: 45px 0px 0 -200px;
}

.info_text {
  position: absolute;
  margin: -55% 0 0 20%;
  width: 200px;
  font-size: 36px;
  line-height: 36px;
}
/*
.info_p_text {
  position: absolute;
  margin: 190px 0 0 74px;
  width: 180px;
  font-size: 28px;
  line-height: 34px;
}

.info_img_cicle2 {
  position: absolute;
  margin: 50px 0px 0 450px;
}

.info_p2 {
  position: absolute;
  margin: 150px 0px 0 455px;
  width: 90px;
  font-size: 36px;
  line-height: 44px;
}

.info_p_text2 {
  position: absolute;
  margin: 190px 0 0 415px;
  width: 180px;
  font-size: 28px;
  line-height: 34px;
}

.info_img_cicle3 {
  position: absolute;
  margin: 50px 0px 0 800px;
}

.info_p3 {
  position: absolute;
  margin: 150px 0px 0 800px;
  width: 90px;
  font-size: 36px;
  line-height: 44px;
}

.info_p_text3 {
  position: absolute;
  margin: 190px 0 0 760px;
  width: 180px;
  font-size: 28px;
  line-height: 30px;
} */
</style>