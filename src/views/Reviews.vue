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
  margin-left: 160px;
}

.review_info_box {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.review {
  position: relative;
  width: 37%;
  height: 450px;
  background: #27cb37;
  box-shadow: 0px 4px 16px 7px rgba(0, 0, 0, 0.25);
  border-radius: 31px;
  margin-top: 140px;
  margin-left: 5%;
}

.review_info_box > :last-child {
  background: #cb2776;
}

.review_img {
  position: absolute;
  margin: -20% 0 0 -15%;
  max-width: 58%;
  max-height: 58%;
}

.review_name {
  position: absolute;
  width: 70%;
  height: 70px;
  margin-top: 10px;
  margin-left: 30%;
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
  margin-left: 7%;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 18px;
  line-height: 22px;
  text-align: justify;
  color: #000000;
}

@media screen and (max-width: 991px) {
  .reviews_title {
    margin-left: 20%;
  }

  .review {
    width: 40%;
    height: 500px;
    margin-left: 8%;
  }

  .review_name {
    font-size: 20px;
    line-height: 22px;
    width: 60%;
  }

  .review_text {
    font-size: 18px;
    margin-top: 25%;
    height: 250px;
  }

  .review_img {
    margin: -20% 0 0 -15%;
  }
}

@media screen and (max-width: 850px) {
  .review {
    width: 80%;
    height: 370px;
  }
}

@media screen and (max-width: 767px) {
  .reviews_title {
    margin-left: 20%;
  }


  .review {
    margin-left: 40px;
  }

  .review_img {
    margin: -15% 0 0 -8%;
    max-width: 50%;
    max-height: 50%;
  }

  .review_name {
    margin-left: 25%;
  }

  .review_text {
    margin-top: 110px;
    font-size: 18px;
  line-height: 22px;
  }
}

@media screen and (min-width: 360px) and (max-width: 600px) {
  .reviews_container {
    margin: 40px 0 0 0;
  }
  .reviews_title {
    margin-left: 8%;
    font-size: 26px;
    line-height: 28px;
  }

  .review {
    margin: 20% 0 0 10%;
  }

  .review_img {
    margin: -17% 0 0 -8%;
    max-width: 50%;
    max-height: 50%;
  }

  .review_name {
    margin-left: 38%;
    font-size: 18px;
    line-height: 20px;
  }

  .review_text {
    margin-top: 34%;
    font-size: 16px;
    line-height: 18px;
  }
}
</style>

