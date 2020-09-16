<template>
  <div class="header_block">
    <div class="logo">
      <img src="../static/img/logo.png" class="logo_img"/>
      <p class="logo_p">KIDS</p>
    </div>
    <div class="header_nav">
      <a class="header_nav_a">Главная</a>
      <a class="header_nav_a">О проекте</a>
      <a class="header_nav_a">Контакты</a>
      <button class="header_nav_btn">Заказать звонок</button>
      <a class="header_nav_a">+77477011414</a>
    </div>
    <div class="header_info">
      <p class="header_info_title">Детский садик "Kids"</p>
      <p class="header_info_p">Мы очень рады, что Вы заглянули к нам в гости и сделаем все, чтобы наше знакомство было обоюдно приятным.</p>
      <img src="../static/img/header_img.png" class="header_info_img"/>
    </div>
  </div>
</template>

<style>
/* .header_block {
  display: flex;
} */

.logo {
  position: absolute;
  width: 10%;
  margin: 0px 70px;
}

.Logo_img {
  width: 80px;
  height: 80px;
}

.logo_p {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 800;
  font-size: 24px;
  line-height: 29px;
  margin: 0;
  color:black;
}

.header_nav {
  width: 54%;
  height: 47px;
  margin-left: 490px;
  /* margin-top: 21px; */
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
/* left: 841px;
top: 21px; */
  background: linear-gradient(107.78deg, rgba(90, 114, 241, 0) -7.03%, #5A72F1 32.98%);
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
  width: 96%;
  height: 440px;
  margin: 80px 0 0 50px;
  transform: matrix(1, 0, 0, 1, 0, 0);
}

.header_info_title {
  position:absolute;
  font-family: Montserrat;
  font-weight: 900;
  font-size: 48px;
  line-height: 59px;
  color: #000000;
  margin: 15px 0 0 40px;
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
  margin: 105px 0 0 40px;
  text-align: left;
}

.header_info_img {
  margin-top: -40px;
}
</style>