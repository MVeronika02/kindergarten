<template>
  <div id="main" class="nav_wrapper">
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
  </div>
</template>

<style>
.nav_wrapper {
  grid-area: header;
  position: relative;
  display: flex;
  justify-content: space-between;
}

.logo {
  width: 80px;
  margin: 0px 0px 0 85px;
}

.logo_img {
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
  margin-top: 11px;
  position: relative;
  display: flex;
  justify-content: space-between;
  padding-right: 20px;
  width: 550px;
}

.header_nav > a{
  padding-top: 15px
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

</style>