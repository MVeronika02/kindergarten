<template>
  <div class="header_block" id="main">
    <div class="logo">
      <img src="../static/img/logo.png" class="logo_img" />
      <p class="logo_p">KIDS</p>
    </div>
    <div class="header_nav">
      <a id="a_main" class="header_nav_a">Главная</a>
      <a href="#about" class="header_nav_a">О проекте</a>
      <a href="#contacts" class="header_nav_a">Контакты</a>
      <button class="header_nav_btn">Заказать звонок</button>
      <a class="header_nav_a">+77477011414</a>
    </div>
    <div class="header_info">
      <p class="header_info_title">Детский садик "Kids"</p>
      <p
        class="header_info_p"
      >Мы очень рады, что Вы заглянули к нам в гости и сделаем все, чтобы наше знакомство было обоюдно приятным.</p>
      <div class="container_header_info_img">
        <img src="../static/img/header_img.svg" class="header_info_img" />
      </div>
    </div>
  </div>
</template>

<style>
.header_block {
  display: flex;
  flex-wrap: wrap;
}

.logo {
  /* position: relative; */
  width: 80px;
  margin: 0px 0px 0 85px;
}

.logo_img {
  width: 80px;
  height: 80px;
  margin-left: 0px;
}

.logo_p {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 800;
  font-size: 24px;
  line-height: 29px;
  margin-top: -10px;
  margin-left: 10px;
  width: 62px;
  color: black;
}

.header_nav {
  width: 54%;
  height: 47px;
  margin-left: 354px;
  margin-top: 11px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.header_nav_a {
  color: black;
  font-family: Montserrat;
  font-weight: 600;
  font-size: 16px;
  line-height: 20px;
}

.header_nav_btn {
  width: 164px;
  height: 47px;
  background: linear-gradient(
    107.78deg,
    rgba(90, 114, 241, 0) -7.03%,
    #5a72f1 32.98%
  );
  border: 1px solid #000000;
  box-sizing: border-box;
  filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
  border-radius: 9px;
  font-family: Montserrat;
  font-weight: 600;
  font-size: 16px;
  line-height: 20px;
  color: #000000;
}

.header_info {
  width: 95%;
  height: 440px;
  margin: 0px 0 0 60px;
  transform: matrix(1, 0, 0, 1, 0, 0);
}

.header_info_title {
  position: absolute;
  font-family: Montserrat;
  font-weight: 900;
  font-size: 48px;
  line-height: 59px;
  color: #000000;
  margin: 37px 0 0 30px;
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
  margin: 129px 0 0 30px;
  text-align: left;
}

.container_header_info_img {
  position: relative;
  object-fit: cover;
  height: 440px;
  margin-top: 30px;
}
.header_info_img {
  margin-top: -40px;
  display: block;
  max-width: 100%;
  max-height: 100%;
}

@media only screen and (min-width: 768px) and (max-width: 1023px) {
  .logo {
    margin: 0px 10px;
  }

  .logo_img {
    width: 50px;
    height: 50px;
  }

  .logo_p {
    font-size: 18px;
    margin-top: -10px;
  }

  .header_nav {
    margin-left: 80px;
    width: 60%;
  }

  .header_nav_btn {
    width: 120px;
    height: 30px;
    font-size: 14px;
    line-height: 20px;
  }

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

@media all and (min-width: 360px) and (max-width: 767px) {
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
    /* position: relative; */
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

@media all and (min-width: 1024px) and (max-width: 1474px) {
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
}
</style>