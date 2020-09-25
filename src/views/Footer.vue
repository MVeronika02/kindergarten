<template>
  <div class="footer_bar">
    <div class="logo_footer">
      <img src="../static/img/logo.png" class="logo_img" />
      <p class="logo_p_footer">KIDS</p>
    </div>
    <div class="footer_nav">
      <a href="#main" class="footer_nav_a">Главная</a>
      <img src="../static/img/line.png" class="footer_line" />
      <a href="#about" class="footer_nav_a">О проекте</a>
      <img src="../static/img/line.png" class="footer_line" />
      <a href="#contacts" class="footer_nav_a">Контакты</a>
    </div>
  </div>
</template>

<script>
import $ from "jquery";

export default {
  name: "Footer",
  data() {},
};

$(document).ready(function () {
  $("#menu").on("click", "a", function (event) {
    //отменяем стандартную обработку нажатия по ссылке
    event.preventDefault();
    //забираем идентификатор бока с атрибута href
    var id = $(this).attr("href"),
      //узнаем высоту от начала страницы до блока на который ссылается якорь
      top = $(id).offset().top;
    //анимируем переход на расстояние - top за 1500 мс
    $("body,html").animate({ scrollTop: top }, 1500);
  });
});
</script>

<style>
.footer_bar {
  grid-area: footer;
  display: flex;
  justify-content: space-between;
  position: relative;
}

.logo_footer {
  width: 90px;
  height: 130px;
  margin: 20px 0 0 85px;
}

.footer_nav {
  display: flex;
  justify-content: space-between;
  width: 30%;
  margin: 60px 250px 0 0px;
}

.footer_nav_a {
  font-family: Montserrat;
  font-weight: 600;
  font-size: 16px;
  line-height: 20px;
  color: #000000;
}

.footer_line {
  height: 20px;
}

@media screen and (max-width: 767px) {
  .logo_footer {
    width: 70px;
    height: 100px;
    margin: 20px 10px 0 40px;
  }

  .footer_nav_a {
    font-size: 14px;
    line-height: 16px;
  }
}

@media screen and (min-width: 360px) and (max-width: 500px){
  .logo_footer {
    margin: 30px 15px 0 10px;
  }

  .logo_img {
    width: 95%;
    height: 65%;
  }

  .footer_nav {
    width: 80%;
    margin-right: 30px;
  }
}

@media screen and (max-width: 325px){
  .logo_footer {
    margin: 30px 15px 0 5px;
  }

  .logo_img {
    width: 95%;
    height: 65%;
  }

  .footer_nav {
    width: 80%;
    margin-right: 30px;
  }
}
</style>