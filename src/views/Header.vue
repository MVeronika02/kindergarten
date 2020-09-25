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
    <div class="menu_header_nav">
      <div class="header_btn_and_number">
        <button class="menu_header_nav_btn">Заказать звонок</button>
        <a class="menu_header_nav_a">+77477011414</a>
      </div>

      <div class="menu_container">
        <ul id="menu" class="menu">
          <li><a id="a_main" class="menu_header_nav_a">Главная</a></li>
          <li><a href="#about" class="menu_header_nav_a">О проекте</a></li>
          <li><a href="#contacts" class="menu_header_nav_a">Контакты</a></li>
        </ul>
      </div>

      <div class="container" id="load" @click="myFunction()">
        <div class="bar1"></div>
        <div class="bar2"></div>
        <div class="bar3"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {},
  methods: {
    myFunction() {
      var preloader = document.getElementById("load");
      if (!preloader.classList.contains("change")) {
        preloader.classList.add("change");
        document.getElementById("menu").style.display = "block";
      } else {
        preloader.classList.remove("change");
        document.getElementById("menu").style.display = "none";
      }
    },
  },
};
</script>


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

.header_nav > a {
  padding-top: 15px;
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

.menu_header_nav {
  display: none;
}

.container {
  display: none;
}

.menu {
  display: none;
}

@media screen and (max-width: 991px) {
  .logo {
    margin-left: 20px;
  }
}

@media screen and (max-width: 767px) {
  .header_nav {
    display: none;
  }
  #menu {
    display: none;
    background-color: #ecc516;
    opacity: 0.65;
    width: 20vw;
    margin-left: 30px;
  }

  ul > li > a {
    font-size: 14px;
    line-height: 18px;
    margin-bottom: 5px;
    margin-left: 10px;
    color: black;
  }

  .menu_header_nav {
    display: inline;
    position: relative;
    width: 30%;
    margin: 20px 50px 0 0px;
  }

  .container {
    position: absolute;
    display: inline-block;
    cursor: pointer;
    margin: 0 10 0 160px;
  }

  .bar1,
  .bar2,
  .bar3 {
    width: 35px;
    height: 5px;
    background-color: #333;
    margin: 6px 0;
    transition: 0.4s;
  }

  .change .bar1 {
    -webkit-transform: rotate(-45deg) translate(-9px, 6px);
    transform: rotate(-45deg) translate(-9px, 6px);
  }

  .change .bar2 {
    opacity: 0;
  }

  .change .bar3 {
    -webkit-transform: rotate(45deg) translate(-8px, -8px);
    transform: rotate(45deg) translate(-8px, -8px);
  }
}

@media screen and (min-width: 360px) and (max-width: 500px) {
  .logo {
    width: 60px;
    margin-left: 10px;
    margin-top: 10px;
  }

  .logo_p {
    margin-top: -10px;
    margin-left: 0;
    font-size: 20px;
  }

  .menu_header_nav {
    display: flex;
    z-index: 99999999;
    justify-content: space-between;
    position: relative;
    width: 100%;
    margin: 10px 5px 0 15px;
  }

  .menu_container {
    z-index: 99999999;
    position: absolute;
    margin-left: 45%;
  }

  .header_btn_and_number {
    width: 80%;
  }

  .container {
    position: relative;
    display: inline-block;
    cursor: pointer;
    margin-right: 10px;
  }

  #menu {
    display: none;
    z-index: 99999999;
    background-color: #ecc516;
    opacity: 0.95;
    width: 90%;
    margin-left: 20px;
  }

  ul > li > a {
    font-size: 10px;
    margin-left: 10px;
    color: black;
  }

  .menu_header_nav_btn {
    width: 55%;
    height: 25px;
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
    font-size: 14px;
    line-height: 16px;
    color: #000000;
    margin-top: 5px;
  }

  .menu_header_nav_a {
    font-size: 12px;
    margin-top: 10px;
    margin-left: 15px;
  }

  .bar1,
  .bar2,
  .bar3 {
    width: 35px;
    height: 5px;
    background-color: #333;
    margin: 6px 0;
    transition: 0.4s;
  }

  .change .bar1 {
    -webkit-transform: rotate(-45deg) translate(-9px, 6px);
    transform: rotate(-45deg) translate(-9px, 6px);
  }

  .change .bar2 {
    opacity: 0;
  }

  .change .bar3 {
    -webkit-transform: rotate(45deg) translate(-8px, -8px);
    transform: rotate(45deg) translate(-8px, -8px);
  }
}

@media screen and (max-width: 325px) {
  .logo {
    width: 60px;
    margin-left: 10px;
    margin-top: 10px;
  }

  .logo_p {
    margin-top: -10px;
    margin-left: 0;
    font-size: 18px;
  }

  .menu_header_nav {
    display: flex;
    justify-content: space-between;
    position: relative;
    width: 80%;
    margin: 10px 5px 0 0px;
  }

  .menu_header_nav_a {
    font-size: 12px;
    margin-top: 5px;
  }

  .menu_header_nav_btn {
    width: 52%;
    height: 20px;
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
    font-size: 10px;
    line-height: 12px;
    margin-top: 5px;
  }

  .header_btn_and_number {
    width: 80%;
    margin-left: 10px;
    display: flex;
    justify-content: space-between;
  }

  .menu_container {
    position: fixed;
    z-index: 99999999;
    margin-left: 90px;
  }

  #menu {
    display: none;
    background-color: #ecc516;
    opacity: 0.95;
    width: 25vw;
    /* margin-right: 10px; */
  }

  ul > li > a {
    font-size: 10px;
    margin-left: 10px;
    color: black;
  }

  .container {
    z-index: 99999999;
    position: relative;
    display: inline-block;
    cursor: pointer;
    margin: 0px 0 0 20px;
  }

  .bar1,
  .bar2,
  .bar3 {
    width: 35px;
    height: 5px;
    background-color: #333;
    margin: 6px 0;
    transition: 0.4s;
  }

  .change .bar1 {
    -webkit-transform: rotate(-45deg) translate(-9px, 6px);
    transform: rotate(-45deg) translate(-9px, 6px);
  }

  .change .bar2 {
    opacity: 0;
  }

  .change .bar3 {
    -webkit-transform: rotate(45deg) translate(-8px, -8px);
    transform: rotate(45deg) translate(-8px, -8px);
  }
}
</style>