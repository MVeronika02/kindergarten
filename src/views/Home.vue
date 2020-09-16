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
  
  <footer id="pageFooter">Footer</footer>

</div>
</body>
</template>

<script>

import Header from '../views/Header.vue'
import Information from '../views/Information.vue'

export default {
  name: 'Home',
  data () {
    return {}
  },
  components: {
    Header,
    Information
  }
}
</script>

<style>

body {
  margin: 0px;
  padding: 0px;
}

/* .main_background {
  position:  absolute;
  height: 100%;
  width: 100%;
  background-size: cover;
  z-index: 0;
  background: url(../assets/img/mainBackground.jpg);
} */

.mainPage {
  width: 65%;
  display: grid;
  grid-template-areas:
    "header header header"
    "content content content"
    "footer footer footer";
  grid-template-rows: 590px auto 300px;
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

#pageFooter {
  grid-area: footer;
  background: #F0E051;
}

.info {
  grid-area: content;
  padding: 0;
}

@media all and (max-width: 575px) {
  .mainPage {
    width: 65%;
    display: grid;
    grid-template-areas:
      "header"
      "content"
      "footer";
    grid-template-rows: 90px auto 80px;
    grid-template-columns: 3fr;
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

#pageFooter {
  grid-area: footer;
  background: #F0E051;
}

.info {
  grid-area: content;
  padding: 0;
}
}

</style>

