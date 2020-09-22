<template>
  <div class="greeting_wrapper">
    <div class="header_info_wrapper">
      <p class="header_info_title">Детский садик "Kids"</p>
      <p
        class="header_info_p"
      >Мы очень рады, что Вы заглянули к нам в гости и сделаем все, чтобы наше знакомство было обоюдно приятным.</p>
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
/* 
@media screen and (max-width: 1023px) {

  .header_info {
    width: 80%;
    height: 280px;
    margin: 10px 0 0 20px;
    transform: matrix(1, 0, 0, 1, 0, 0);
  }

  .header_info_title {
    margin-top: 0px;
    font-size: 28px;
    line-height: 30px;
  }

  .header_info_p {
    margin: 40px 0 0 30px;
    width: 50%;
  }

  .container_header_info_img {
    position: relative;
    object-fit: cover;
    height: 280px;
    margin-top: 30px;
  }
  .header_info_img {
    margin-top: -40px;
    display: block;
    max-width: 100%;
    max-height: 100%;
  }
}

@media screen and (max-width: 767px) {
  .logo {
    height: 40px;
    width: 40px;
    margin: 0 0 0 10px;
  }

  .logo_img {
    width: 30px;
    height: 30px;
    margin: 0 0 0 0px;
  }

  .logo_p {
    font-size: 14px;
    margin: -10px 0 0 -10px;
  }

  .header_nav {
    margin: 0 0 0 50px;
    width: 70%;
    height: 30px;
    justify-content: space-between;
  }

  .header_nav_a {
    font-size: 8px;
    margin-right: 5px;
  }

  #a_main {
    display: none;
  }

  .header_nav_btn {
    width: 80px;
    height: 20px;
    font-size: 8px;
    line-height: 10px;
  }

  .header_info {
    width: 92%;
    height: 140px;
    margin: 10px 0 0 10px;
    transform: matrix(1, 0, 0, 1, 0, 0);
  }

  .header_info_title {
    margin: 5px;
    font-size: 20px;
    line-height: 14px;
  }

  .header_info_p {
    margin: 35px 0 0 5px;
    width: 50%;
    height: 50px;
    font-size: 10px;
    line-height: 10px;
  }

  .container_header_info_img {
    /* position: relative; 
    object-fit: cover;
    height: 135px;
    width: 100%;
    margin-top: 30px;
  }
  .header_info_img {
    margin-top: -20px;
    display: block;
    max-width: 100%;
    max-height: 100%;
  }
}

@media screen and (max-width: 1474px) {
  .logo {
    position: absolute;
    width: 70px;
    margin-left: 60px;
  }

  .logo_img {
    margin: 0px;
  }

  .logo_p {
    margin: -5px 0 0 5px;
  }

  .header_nav {
    width: 65%;
    margin-left: 320px;
  }

  .header_info {
    width: 100%;
    height: 360px;
    margin: 40px 0 0 50px;
    transform: matrix(1, 0, 0, 1, 0, 0);
  }

  .header_info_title {
    position: absolute;
    font-family: Montserrat;
    font-weight: 900;
    font-size: 48px;
    line-height: 59px;
    color: #000000;
    margin: 15px 0 0 20px;
  }

  .header_info_p {
    position: absolute;
    font-family: Montserrat;
    font-weight: 900;
    font-size: 18px;
    line-height: 22px;
    color: #000000;
    width: 40%;
    height: 66px;
    margin: 90px 0 0 20px;
    text-align: left;
  }

  .container_header_info_img {
    position: relative;
    object-fit: cover;
    height: 360px;
    margin: 0px;
  }
  .header_info_img {
    margin: 0px;
    display: block;
    max-width: 100%;
    max-height: 100%;
  }
} */
</style>