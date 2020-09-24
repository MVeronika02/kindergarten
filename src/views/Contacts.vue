<template>
  <div class="contacts_container">
    <div id="map" class="map_block"></div>
    <div id="contacts" class="contacts">
      <h1 class="contacts_title">Контактные данные</h1>
      <div class="block_adress_and_email">
        <img src="../static/img/geo.svg" class="addres_img" />
        <p class="contacts_text">Казахстан, г.Алматы, ул.Гоголя 99</p>
        <img src="../static/img/telephone.svg" class="tel_img" />
        <p class="contacts_text">
          Телефон: +77477011414
          <br />Email: example@gmail.com
        </p>
      </div>
      <div class="img_social_network">
        <img src="../static/img/whatsapp.svg" class="wp_img" />
        <img src="../static/img/instagram.svg" class="contacts_img" />
        <img src="../static/img/telegram.svg" class="contacts_img" />
        <img src="../static/img/facebook.svg" class="contacts_img" />
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "Contacts",
  data() {
    return {};
  },
};
</script>

<style>
.contacts_container {
  grid-area: contacts;
  margin: 50px 75px 50px 90px;
  position: relative;
  display: flex;
  justify-content: space-between;
}

.map_block {
  width: 600px;
  height: 365px;
}

.contacts {
  position: relative;
  margin-left: 30px;
  width: 40%;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.contacts_title {
  position: relative;
  width: 450px;
  height: 30px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 36px;
  line-height: 44px;
  text-align: justify;
  color: #000000;
}

.block_adress_and_email {
  position: relative;
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.addres_img {
  height: 64px;
}

.tel_img {
  height: 64px;
}

.contacts_text {
  width: 80%;
  height: 40px;
  font-family: Montserrat;
  font-weight: 500;
  font-size: 18px;
  line-height: 22px;
  text-align: justify;
  color: #000000;
  margin-top: 12px;
}

.img_social_network {
  position: relative;
  display: flex;
  justify-content: space-between;
}

.contacts_img {
  margin-left: 30px;
  height: 40px;
}

.wp_img {
  height: 40px;
}


</style>

