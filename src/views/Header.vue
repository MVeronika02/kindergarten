<template>
  <div class="header_block" id="main">
    <div class="logo">
      <img src="../static/img/logo.png" class="logo_img"/>
      <p class="logo_p">KIDS</p>
    </div>
    <div class="header_nav">
      <a id="a_main" class="header_nav_a">Главная</a>
      <a class="header_nav_a">О проекте</a>
      <a href="#contacts" class="header_nav_a">Контакты</a>
      <button class="header_nav_btn">Заказать звонок</button>
      <a class="header_nav_a">+77477011414</a>
    </div>
    <div class="header_info">
      <p class="header_info_title">Детский садик "Kids"</p>
      <p class="header_info_p">Мы очень рады, что Вы заглянули к нам в гости и сделаем все, чтобы наше знакомство было обоюдно приятным.</p>
      <img src="../static/img/header_img.svg" class="header_info_img"/>
    </div>
  </div>
</template>

<style>

.logo {
  position: absolute;
  width: 10%;
  margin: 0px 70px;
}

.logo_img {
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

@media all and (min-width: 768px) and (max-width: 1024px) {

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
  margin-left: 220px;
  width: 58%;
}

.header_nav_btn {
  width: 120px;
  height: 30px;
  font-size: 14px;
  line-height: 20px;
}

.header_info {
  width: 90%;
  height: 440px;
  margin: 60px 0 0 20px;
  transform: matrix(1, 0, 0, 1, 0, 0);
}

.header_info_title {
  margin-top: -20px;
  font-size: 28px;
  line-height: 30px;
}

.header_info_p {
  margin: 20px 0 0 40px;
  width: 50%;
}

.header_info_img {
  margin: -50px 0 0 -60px;
  width: 700px;
}

}

@media all and (min-width: 360px) and (max-width: 767px) {

.logo {
  margin: 0px 10px;
}

.logo_img {
  width: 30px;
  height: 30px;
}

.logo_p {
  font-size: 16px;
  margin-top: -10px;
}

.header_nav {
  margin-left: 150px;
  width: 40%;
}

.header_nav_a {
  font-size: 10px;
}

#a_main {
  display: none;
}

.header_nav_btn {
  width: 110px;
  height: 20px;
  font-size: 12px;
  line-height: 12px;
}

.header_info {
  width: 90%;
  height: 440px;
  margin: 60px 0 0 10px;
  transform: matrix(1, 0, 0, 1, 0, 0);
}

.header_info_title {
  margin-top: -20px;
  font-size: 28px;
  line-height: 30px;
}

.header_info_p {
  margin: 20px 0 0 40px;
  width: 40%;
}

.header_info_img {
  margin: -50px 0 0 -290px;
  width: 700px;
}

}



@media all and (min-width: 1224px) {
.logo {
  position: absolute;
  width: 10%;
  margin: 0px 70px;
}

.logo_img {
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
  margin-left: 430px;
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
  margin-top: 0px;
  width: 98%;
}
}


</style>