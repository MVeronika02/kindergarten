<template>
  <div id="about" class="info_container">
    <div class="one_info_block">
      <img src="../static/img/cicle.svg" class="info_dial" />
      <img src="../static/img/student.svg" class="info_img" />
      <p class="info_text">3590<br />Всего детей</p>
    </div>
    <div class="one_info_block">
      <img src="../static/img/cicle.svg" class="info_dial" />
      <img src="../static/img/room.svg" class="info_img" />
      <p class="info_text">789<br />комнат</p>
    </div>
    <div class="one_info_block">
      <img src="../static/img/cicle.svg" class="info_dial" />
      <img src="../static/img/teacher.svg" class="info_img" />
      <p class="info_text">300<br />Всего учителей</p>
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
  display: flex;
  justify-content: space-between;
}

.info_dial {
  position: relative;
  max-width: 100%;
  max-height: 100%;
}

.info_img {
  position: absolute;
  margin: 32% 0 0 50%;
  transform: translate(-50%, -50%);
}

.info_text {
  position: absolute;
  margin: 62% 0 0 50%;
  width: 200px;
  font-size: 36px;
  line-height: 32px;
  transform: translate(-50%, -50%);
}

@media screen and (max-width: 991px) {
  .info_text {
    margin-top: 65%;
    font-size: 30px;
    line-height: 28px;
  }

  .info_container {
    flex-wrap: wrap;
    justify-content: center;
  }

  .one_info_block {
    margin-left: 10px;
  }
}

@media screen and (max-width: 767px) {
  .info_container {
    margin-left: 0;
    margin-right: 0;
    justify-content: center;
  }

  .one_info_block {
    margin-bottom: 10px;
  }
}

@media screen and (min-width: 360px){
  .info_text {
    margin-top: 60%;
  }
}

</style>