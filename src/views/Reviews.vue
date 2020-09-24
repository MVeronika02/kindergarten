<template>
  <div class="reviews_container">
    <h1 class="reviews_title">Отзывы наших родителей</h1>
    <div class="review_info_box">
      <div class="review">
        <img src="../static/img/leftR.png" class="review_img" />
        <p class="review_name">
          Карлыгаш
          <br />дочь Адема, 3 года
        </p>
        <p class="review_text">
          "Мы начали ходить сначала в неполную группу, но Адеме очень
          понравилось с первого дня и мы стали оставлять ее на весь день. Много
          детей, игры, интересные занятия! Ребенок стал лучше кушать, лучше
          говорить, интересоваться различными фигурами, мастерить из них что-то.
          Очень занимательно учат детей считать и знать буквы. Всё в игровой
          легкой форме и дети с удовольствием участвуют в процессе."
        </p>
      </div>
      <div class="review">
        <img src="../static/img/rightR.png" class="review_img" />
        <p class="review_name">
          Олеся
          <br />сын Егор, 5,5 лет
        </p>
        <p class="review_text">
          “Уже полгода сын с удовольствием ходит в этот садик. За это время он
          многому научился. В бытовом плане - приучили к горшку и кушать
          самостоятельно, в плане развития - очень активно начал говорить,
          строить предложения, мастерить поделки. Мы очень довольны!”
        </p>
      </div>
    </div>
  </div>
</template>

<style>
.reviews_container {
  grid-area: reviews;
  position: relative;
  margin: 65px 75px 0 100px;
}

.reviews_title {
  font-family: Montserrat;
  font-weight: 800;
  font-size: 36px;
  line-height: 44px;
  color: #000000;
  width: 900px;
  margin-left: 160px;
}

.review_info_box{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.review {
  position: relative;
  width: 37%;
  height: 440px;
  background: #27cb37;
  box-shadow: 0px 4px 16px 7px rgba(0, 0, 0, 0.25);
  border-radius: 31px;
  margin-top: 140px;
  margin-left: 77px;
}

.review_info_box > :last-child{
  background: #cb2776;
}

.review_img {
  position: absolute;
  margin: -100px 0 0 -60px;
  max-width: 58%;
  max-height: 58%;
}

.review_name {
  position: absolute;
  width: 70%;
  height: 70px;
  margin-top: 10px;
  margin-left: 130px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 24px;
  line-height: 29px;
  text-align: center;
  color: #000000;
}

.review_text {
  position: absolute;
  width: 85%;
  height: 330px;
  margin-top: 120px;
  margin-left: 30px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 18px;
  line-height: 22px;
  text-align: justify;
  color: #000000;
}

@media screen and (max-width: 991px) {
  .review_name {
    margin-left:80px;
  }

  .review_text {
    margin-top: 80px;
  }
}

</style>

