<template>
  <div class="footer_bar">
    <div class="logo_footer">
      <img src="../static/img/logo.png" class="logo_img" />
      <p class="logo_p">KIDS</p>
    </div>
    <div class="footer_nav">
      <a href="#main" class="footer_nav_a">Главная</a>
      <img src="../static/img/line.png" class="footer_line"/>
      <a href="#about" class="footer_nav_a">О проекте</a>
      <img src="../static/img/line.png" class="footer_line"/>
      <a href="#contacts" class="footer_nav_a">Контакты</a>
    </div>
  </div>
  
</template>

<script>
import $ from 'jquery'

export default {
  name: "Footer",
  data() {},
};

  $(document).ready(function(){
    $("#menu").on("click","a", function (event) {
      //отменяем стандартную обработку нажатия по ссылке
      event.preventDefault();
      //забираем идентификатор бока с атрибута href
      var id  = $(this).attr('href'),
      //узнаем высоту от начала страницы до блока на который ссылается якорь
      top = $(id).offset().top;
      //анимируем переход на расстояние - top за 1500 мс
      $('body,html').animate({scrollTop: top}, 1500);
    });
  });
</script>

<style>
.footer_bar {
  display: flex;
}

.logo_footer {
  width: 90px;
  height: 130px;
  margin: 20px 0 0 85px;
}

.footer_nav {
  display: flex;
  justify-content: space-around;
  width: 300px;
  margin: 60px 0 0 280px;
  
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

@media all and (min-width: 768px) and (max-width: 1024px)  {

.footer_bar {
  width: 100%;
  margin-left: 0px;
}

.logo_footer {
  width: 70px;
  height: 100px;
  margin: 5px 0 0 20px;
}

.footer_nav {
  margin: 30px 0 0 150px;
}
}

@media all and (min-width: 360px) and (max-width: 767px) {

.footer_bar {
  width: 72%;
  margin-left: 0px;
}

.logo_footer {
  width: 70px;
  height: 100px;
  margin: 10px 0 0 0px;
}

.footer_nav {
  margin: 30px 0 0 10px;
  width: 60%;
}

.footer_nav_a {
  font-size: 14px;
  line-height: 14px;
}

.footer_line {
  height: 14px;
}

}

@media all and (min-width: 1024px) and (max-width: 1474px) {

.footer_bar {
  display: flex;
}

.logo_footer {
  width: 90px;
  height: 130px;
  margin: 5px 0 0 15px;
}

.logo_img {
  width: 60px;
  height: 60px;
}

.logo_p {
  font-size: 20px;
}

.footer_nav {
  display: flex;
  justify-content: space-around;
  width: 300px;
  margin: 40px 0 0 280px;
  
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
}

</style>