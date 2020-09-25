<template>
  <div class="request_container">
    <div class="form_container">
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
    </div>
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
  margin-left: 20%;
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
  margin-left: 40px;
  margin-bottom: 63px;
}

.request_form {
  display: flex;
  flex-direction: column;
}

.request_form_input {
  position: relative;
  width: 425px;
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
  margin: 20px 0 0 6%;
}

.request_img {
  min-width: 200px;
  min-height: 80%;
  max-width: 120%;
  max-height: 120%;
}

@media screen and (max-width: 991px) {
  .request_container {
    margin-left: 20%;
  }
}

@media screen and (max-width: 850px) {
  .request_img_wrapper {
    display: none;
  }
}

@media screen and (min-width: 360px) and (max-width: 767px) {
  .request_container {
    margin: 0;
  }

  .form_container {
    width: 90%;
    margin-left: 8%;
  }

  .request_title {
    font-size: 26px;
    line-height: 28px;
    width: 80%;
    margin: 20px 0 20px 50px;
  }

  .request_form_input {
    width: 300px;
    height: 20px;
    font-size: 14px;
    padding: 20px 0px 19px 11px;
  }

  .request_submit_btn {
    margin-left: 50px;
  }
}
</style>
