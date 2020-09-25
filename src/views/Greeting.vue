<template>
  <div class="greeting_wrapper">
    <div class="header_info_wrapper">
      <p class="header_info_title">Детский садик "Kids"</p>
      <p class="header_info_p">
        Мы очень рады, что Вы заглянули к нам в гости и сделаем все, чтобы наше
        знакомство было обоюдно приятным.
      </p>
    </div>
    <div class="container_header_info_img">
      <img src="../static/img/header_img.svg" class="header_info_img" />
    </div>
  </div>
</template>

<style>
.greeting_wrapper {
  grid-area: greeting;
  position: relative;
  display: inline;
}

.header_info_wrapper {
  margin: 37px 0 0 90px;
}

.header_info_title {
  position: relative;
  font-family: Montserrat;
  font-weight: 900;
  font-size: 48px;
  line-height: 59px;
  color: #000000;
  display: inline-block;
}

.header_info_p {
  position: absolute;
  font-family: Montserrat;
  font-weight: 900;
  font-size: 18px;
  line-height: 22px;
  color: #000000;
  width: 30%;
  height: 66px;
  margin-top: 33px;
  text-align: left;
}

.container_header_info_img {
  position: relative;
  margin-top: -100px;
  margin-left: 60px;
}
.header_info_img {
  max-width: 100%;
  max-height: 100%;
}

@media screen and (max-width: 991px) {
  .header_info_wrapper {
    margin: 10px 0 0 90px;
  }

  .header_info_title {
    font-size: 36px;
    line-height: 36px;
  }

  .header_info_p {
    width: 35%;
    height: 50px;
    font-size: 16px;
    line-height: 18px;
    margin-top: 15px;
  }

  .container_header_info_img {
    margin-top: -80px;
    margin-left: 60px;
  }
}

@media screen and (max-width: 767px) {
  .header_info_wrapper {
    margin: 25px 0 0 20px;
  }

  .header_info_title {
    font-size: 44px;
  }

  .header_info_p {
    font-size: 16px;
    line-height: 20px;
    width: 60%;
    margin-top: 25px;
  }

  .container_header_info_img {
    margin-top: -20px;
    margin-left: 10px;
  }
}

@media screen and (min-width: 360px) and (max-width: 500px) {
  .header_info_wrapper {
    margin: 10px 0 0 10px;
  }
  .header_info_title {
    font-size: 34px;
  }

  .header_info_p {
    width: 50%;
    margin-top: 15px;
    font-size: 16px;
    line-height: 16px;
  }
  .container_header_info_img {
    margin-top: 30px;
    margin-left: 10px;
  }

  .header_info_img {
    max-height: 80%;
  }
}

@media screen and (max-width: 325px){
  .header_info_wrapper {
    margin: 5px 0 0 5px;
  }
  .header_info_title {
    font-size: 30px;
  }

  .header_info_p {
    width: 50%;
    margin-top: 10px;
    font-size: 14px;
    line-height: 16px;
  }
  .container_header_info_img {
    margin-top: 30px;
    margin-left: 10px;
  }

  .header_info_img {
    max-height: 80%;
  }
}
</style>