<template>
  <div class="courses_container">
    <h1 class="courses_title">Мы будем изучать ...</h1>
    <div class="courses">
      <div class="course">
        <img src="../static/img/eng.png" class="course_img" />
        <div class="course_eng">
          <p class="course_title">Английский язык</p>
          <p class="course_age">
            От 3 до 5 лет
            <br />От 5 до 7 лет
          </p>
        </div>
      </div>
      <div class="course">
        <img src="../static/img/russs.png" class="course_rus_img" />
        <div class="course_rus">
          <p class="course_title">Русский язык</p>
          <p class="course_age">
            От 3 до 5 лет
            <br />От 5 до 7 лет
          </p>
        </div>
      </div>
      <div class="course">
        <img src="../static/img/kaz.png" class="course_kaz_img" />
        <div class="course_kaz">
          <p class="course_title">Казахский язык</p>
          <p class="course_age">
            От 3 до 5 лет
            <br />От 5 до 7 лет
          </p>
        </div>
      </div>
      <div class="course">
        <img src="../static/img/logic.png" class="course_img" />
        <div class="course_logic">
          <p class="course_title">Логические задачи</p>
          <p class="course_age">
            От 1,5 до 3 лет
            <br />От 3 до 5 лет <br />От 5 до 7 лет
          </p>
        </div>
      </div>
      <div class="course">
        <img src="../static/img/speech.png" class="course_img" />
        <div class="course_speech">
          <p class="course_title">Развитие речи</p>
          <p class="course_age">
            От 1,5 до 3 лет
            <br />От 3 до 5 лет <br />От 5 до 7 лет
          </p>
        </div>
      </div>
      <div class="course">
        <img src="../static/img/figures.png" class="course_img" />
        <div class="course_figures">
          <p class="course_title">Геометрические фигуры</p>
          <p class="course_age">
            От 1,5 до 3 лет
            <br />От 3 до 5 лет <br />От 5 до 7 лет
          </p>
        </div>
      </div>
      <div class="course">
        <img src="../static/img/write.png" class="course_img" />
        <div class="course_write">
          <p class="course_title">Обучение прописи</p>
          <p class="course_age">
            От 3 до 5 лет
            <br />От 5 до 7 лет
          </p>
        </div>
      </div>
      <div class="course">
        <img src="../static/img/read.png" class="course_img" />
        <div class="course_read">
          <p class="course_title">Чтение</p>
          <p class="course_age">
            От 3 до 5 лет
            <br />От 5 до 7 лет
          </p>
        </div>
      </div>
      <div class="course">
        <img src="../static/img/count.png" class="course_img" />
        <div class="course_count">
          <p class="course_title">Количество и счет</p>
          <p class="course_age">
            От 3 до 5 лет
            <br />От 5 до 7 лет
          </p>
        </div>
      </div>
    </div>
    <div class="div_flowers"></div>
  </div>
</template>

<script>
export default {
  name: "Courses",
  data() {
    return {};
  },
};
</script>

<style>
p {
  font-family: Montserrat;
  font-weight: 800;
  text-align: center;
  color: #000000;
}

.courses_container {
  grid-area: courses;
  margin-top: 50px;
}

.courses_title {
  font-family: Montserrat;
  font-weight: 800;
  font-size: 36px;
  line-height: 44px;
  text-align: center;
  color: #000000;
}

.courses {
  position: relative;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin: 46px 90px 0 90px;
}

.course {
  position: relative;
  margin-bottom: 115px;
}

.course_img {
  width: 305px;
  height: 315px;
}

.course_eng {
  position: absolute;
  width: 254px;
  height: 92px;
  background: #c8274e;
  border-radius: 10px;
  margin: -50px 0 0 25px;
  font-size: 20px;
  line-height: 24px;
}

.course_rus_img {
  width: 305px;
  height: 300px;
  margin-top: 5px;
}

.course_rus {
  position: absolute;
  width: 254px;
  height: 92px;
  background: #27c84a;
  border-radius: 10px;
  margin: -40px 0 0 25px;
  font-size: 20px;
  line-height: 24px;
}

.course_kaz_img {
  width: 305px;
  height: 300px;
  margin-top: 5px;
}

.course_kaz {
  position: absolute;
  width: 254px;
  height: 92px;
  background: #277bc8;
  border-radius: 10px;
  margin: -40px 0 0 25px;
  font-size: 20px;
  line-height: 24px;
}

.course_logic {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #c527c8;
  border-radius: 10px;
  margin: -40px 0 0px 25px;
  font-size: 20px;
  line-height: 24px;
}

.course_speech {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #27bec8;
  border-radius: 10px;
  margin: -40px 0 0 25px;
  font-size: 20px;
  line-height: 24px;
}

.course_figures {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #c85727;
  border-radius: 10px;
  margin: -40px 0 0 25px;
  font-size: 20px;
  line-height: 24px;
}

.course_write {
  position: absolute;
  width: 254px;
  height: 92px;
  background: #8bc827;
  border-radius: 10px;
  margin: -40px 0 0 25px;
  font-size: 20px;
  line-height: 24px;
}

.course_read {
  position: absolute;
  width: 254px;
  height: 92px;
  background: #8711be;
  border-radius: 10px;
  margin: -40px 0 0 25px;
  font-size: 20px;
  line-height: 24px;
}

.course_count {
  position: absolute;
  width: 254px;
  height: 92px;
  background: #dfca0b;
  border-radius: 10px;
  margin: -40px 0 0 25px;
  font-size: 20px;
  line-height: 24px;
}

.div_flowers {
  grid-area: flowers;
  position: relative;
  background-image: url("../static/img/bottom.png");
  background-repeat: repeat-x;
  width: 97%;
  height: 150px;
  margin: -75px 20px 0 20px;
}

@media screen and (max-width: 991px) {
  .courses {
    justify-content: space-around;
  }

  @media screen {
    .course {
      margin-bottom: 90px;
    }

    .div_flowers {
      margin-top: -65px;
    }
  }
}
</style>

