<template>
<body>
  <div class="mainPage">
    <Header />
    <Greeting />
    <Advertising/>
    <Courses/>
    <Information />
    <Request/>
    <Reviews/>
    <Contacts/>
    <Footer class="pageFooter" />
  </div>
</body>
</template>

<script>
import Header from "../views/Header.vue";
import Footer from "../views/Footer.vue";
import Greeting from "../views/Greeting.vue";
import Advertising from "../views/Advertising.vue";
import Courses from "../views/Courses.vue";
import Information from "../views/Information.vue"
import Request from "../views/Request.vue"
import Reviews from "../views/Reviews.vue"
import Contacts from "../views/Contacts.vue"

export default {
  name: "Home",
  data() {
    return {};
  },
  components: {
    Header,
    Greeting,
    Advertising,
    Courses,
    Information,
    Request,
    Reviews,
    Contacts,
    Footer,
  },
};
</script>

<style>
body {
  margin: 0px;
  padding: 0px;
}

.mainPage {
  display: grid;
  grid-template-areas:
    "header header header"
    "greeting greeting greeting"
    "adver adver adver"
    "courses courses courses"
    "info info info"
    "request request request"
    "reviews reviews reviews"
    "contacts contacts contacts"
    "footer footer footer";
  grid-template-rows: auto auto auto auto auto auto auto auto 155px;
  grid-template-columns: 15% 1fr 15%;
  z-index: 5;
  position: relative;
  background: #f0e051;
  margin: 0px 50px 0px 50px;
}


@media screen and (max-width: 1200px) {
  .mainPage {
    margin: 0px 0px 0px 0px;
  }
}


</style>

