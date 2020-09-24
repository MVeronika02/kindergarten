<template>
  <div class="request_container">
    <h1 class="request_title">Оставить заявку</h1>
    <form class="request_form">
      <input
        type="text"
        placeholder="Как зовут Вашего ребенка?"
        class="request_form_input"
      />
      <input
        type="text"
        placeholder="Сколько ему/ей лет?"
        class="request_form_input"
      />
      <input
        type="text"
        placeholder="Какой период пребывания Вам подходит"
        class="request_form_input"
      />
      <input
        type="tel"
        pattern="2[0-9]{3}-[0-9]{3}"
        placeholder="+7(---) --- -- --"
        class="request_form_input"
      />
      <input type="submit" value="Подать заявку" class="request_submit_btn" />
    </form>
    <div class="request_img_wrapper">
      <img src="../static/img/tiger.png" class="request_img" />
    </div>
  </div>
</template>

<style>
.request_container {
  grid-area: request;
  margin-top: 50px;
  margin-right: 190px;
  height: 480px;
  position: relative;
  display: flex;
  justify-content: space-between;
}
.request_title {
  font-family: Montserrat;
  font-weight: 800;
  font-size: 36px;
  line-height: 44px;
  color: #000000;
  width: 80%;
  height: 10%;
  margin-left: 240px;
}

.request_form {
  position: absolute;
  display: flex;
  flex-direction: column;
  width: 42%;
  margin-top: 60px;
  margin-left: 20%;
}

.request_form_input {
  position: relative;
  width: 97%;
  height: 20px;
  border-radius: 20px;
  margin-bottom: 15px;
  border: none;
  color: #000000;
  font-size: 18px;
  padding: 20px 0px 19px 11px;
}

.request_submit_btn {
  position: relative;
  width: 62%;
  height: 60px;
  background: #006dd1;
  border-radius: 20px;
  border: none;
  font-family: Montserrat;
  color: black;
  font-weight: 800;
  font-size: 22px;
  margin: 15px 0 0 80px;
}

.request_img_wrapper {
  position: relative;
  width: 72%;
  margin-left: 45px;
}

.request_img {
  max-width: 100%;
  max-height: 100%;
}
</style>