<template>
  <div class="terms">
    <div class="term">
      <img src="../static/img/frame.svg" class="term_img" />
      <p class="term_p">Занимательные и увлекательные задания каждый день</p>
    </div>
    <div class="term">
      <img src="../static/img/frame.svg" class="term_img" />
      <p class="term_p">Индивидуальный подход к каждому нашему ученику</p>
    </div>
    <div class="term">
      <img src="../static/img/frame.svg" class="term_img" />
      <p class="term_p">
        Дружный<br />коллектив<br />помогает в адаптации и развитии
      </p>
    </div>
  </div>
</template>

<style>
.terms {
  grid-area: adver;
  position: relative;
  display: flex;
  justify-content: space-between;
  height: 340px;
  margin-left: 60px;
  margin-right: 105px;
  margin-top: 50px;
}

.term {
  margin: 0px 0px 0px 10px;
  position: relative;
}

.term_p {
  position: absolute;
  font-size: 18px;
  line-height: 20px;
  width: 172px;
  height: 80px;
  top: 42%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.term_img {
  max-width: 100%;
  max-height: 100%;
}

@media screen and (max-width: 991px) {
  .terms {
    margin-left: 80px;
    margin-right: 95px;
  }
  .term_p {
    top: 42%;
  }
}
</style>