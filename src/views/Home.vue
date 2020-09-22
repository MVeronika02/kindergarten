<template>
<body>
<!-- <div class="main_background"></div> -->
<div class="mainPage">
  <div class="header">
    <Header/>
  </div>

  <div class="info">
    <Information />
  </div>
  
    <Footer class="pageFooter"/>

</div>
</body>
</template>

<script>

import Header from '../views/Header.vue'
import Information from '../views/Information.vue'
import Footer from '../views/Footer.vue'

export default {
  name: 'Home',
  data () {
    return {}
  },
  components: {
    Header,
    Information,
    Footer
  }
}
</script>

<style>

body {
  margin: 0px;
  padding: 0px;
}

.mainPage {
  width: 65%;
  display: grid;
  grid-template-areas:
    "header header header"
    "content content content"
    "footer footer footer";
  grid-template-rows: 590px auto 155px;
  grid-template-columns: 15% 1fr 15%;
  grid-gap: 10px;
  margin: 0 auto;
  padding: 0px;
  z-index: 5;
  position: relative;
  background: #F0E051;
}

.header {
  grid-area: header;
  padding: 10px 0;
}

.info {
  grid-area: content;
  padding: 0;
}

.pageFooter {
  grid-area: footer;
  background: #E7D747;
}


@media all and (min-width: 768px) and (max-width: 1023px)  {

.mainPage {
  width: 98%;
  display: grid;
  grid-template-areas:
    "header"
    "content"
    "footer";
  grid-template-rows: 400px auto 80px;
  grid-template-columns: none;
  /* grid-gap: 10px; */
  margin: 0 auto 0 50px;
  padding: 0px;
  z-index: 5;
  /* position: relative; */
  background: #F0E051;
}

.header {
  grid-area: header;
  padding: 10px 0;
}

.pageFooter {
  grid-area: footer;
  background:#E7D747;
}

.info {
  grid-area: content;
  padding: 0;
}

}

@media all and (min-width: 360px) and (max-width: 767px)  {

.mainPage {
  width: 100%;
  display: grid;
  grid-template-areas:
    "header"
    "content"
    "footer";
  grid-template-rows: 200px auto 80px;
  grid-template-columns: none;
  /* grid-gap: 10px; */
  margin: 0 auto 0 5px;
  padding: 0px;
  z-index: 5;
  /* position: relative; */
  background: #F0E051;
}
}

@media all and (min-width: 1024px) and (max-width: 1474px) {

.mainPage {
  width: 98%;
  display: grid;
  grid-template-areas:
    "header header header"
    "content content content"
    "footer footer footer";
  grid-template-rows: 500px auto 100px;
  grid-template-columns: 15% 1fr 15%;
  grid-gap: 10px;
  margin: 0 auto;
  padding: 0px;
  z-index: 5;
  position: relative;
  background: #F0E051;
}

}

</style>

