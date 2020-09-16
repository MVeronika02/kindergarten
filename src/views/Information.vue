<template>
  <div>
    <div class="terms">
      <div class="term">
        <img src="../static/img/frame1.png"/>
        <p class="term_p">Занимательные и увлекательные задания каждый день</p>
      </div>
      <div class="term">
        <img src="../static/img/frame1.png"/>
        <p class="term_p">Индивидуальный подход к каждому нашему ученику</p>
      </div>
      <div class="term">
        <img src="../static/img/frame1.png"/>
        <p class="term3_p">Дружный коллектив помогает в адаптации и развитии</p>
      </div>
    </div>

    <div>
      <h1 class="courses_title">Мы будем изучать ...</h1>
      <div class="courses">
        <div class="courses_eng">
          <img src="../static/img/eng.png" class="courses_eng_img"/>
          <div class="courses_eng_p">
            <p class="courses_eng_title">Английский язык</p>
            <p class="courses_eng_age">От 3 до 5 лет<br>От 5 до 7 лет</p>
          </div>
        </div>
        <div class="courses_eng">
          <img src="../static/img/russs.png" class="courses_rus_img"/>
          <div class="courses_rus_p">
            <p class="courses_eng_title">Русский язык</p>
            <p class="courses_eng_age">От 3 до 5 лет<br>От 5 до 7 лет</p>
          </div>
        </div>
        <div class="courses_eng">
          <img src="../static/img/kaz.png" class="courses_eng_img"/>
          <div class="courses_kaz_p">
            <p class="courses_eng_title">Казахский язык</p>
            <p class="courses_eng_age">От 3 до 5 лет<br>От 5 до 7 лет</p>
          </div>
        </div>
        <div class="courses_eng">
          <img src="../static/img/logic.png" class="courses_eng_img"/>
          <div class="courses_logic_p">
            <p class="courses_eng_title">Логические задачи</p>
            <p class="courses_eng_age">От 1,5 до 3 лет<br>От 3 до 5 лет<br>От 5 до 7 лет</p>
          </div>
        </div>
        <div class="courses_eng">
          <img src="../static/img/speech.png" class="courses_eng_img"/>
          <div class="courses_speech_p">
            <p class="courses_eng_title">Развитие речи</p>
            <p class="courses_eng_age">От 1,5 до 3 лет<br>От 3 до 5 лет<br>От 5 до 7 лет</p>
          </div>
        </div>
        <div class="courses_eng">
          <img src="../static/img/figures.png" class="courses_eng_img"/>
          <div class="courses_figures_p">
            <p class="courses_eng_title">Геометрические фигуры</p>
            <p class="courses_eng_age">От 1,5 до 3 лет<br>От 3 до 5 лет<br>От 5 до 7 лет</p>
          </div>
        </div>
        <div class="courses_eng">
          <img src="../static/img/write.png" class="courses_eng_img"/>
          <div class="courses_write_p">
            <p class="courses_eng_title">Обучение прописи</p>
            <p class="courses_eng_age">От 1,5 до 3 лет<br>От 3 до 5 лет<br>От 5 до 7 лет</p>
          </div>
        </div>
        <div class="courses_eng">
          <img src="../static/img/read.png" class="courses_eng_img"/>
          <div class="courses_read_p">
            <p class="courses_eng_title">Чтение</p>
            <p class="courses_eng_age">От 1,5 до 3 лет<br>От 3 до 5 лет<br>От 5 до 7 лет</p>
          </div>
        </div>
        <div class="courses_eng">
          <img src="../static/img/count.png" class="courses_eng_img"/>
          <div class="courses_count_p">
            <p class="courses_eng_title">Количество и счет</p>
            <p class="courses_eng_age">От 1,5 до 3 лет<br>От 3 до 5 лет<br>От 5 до 7 лет</p>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Information",
  data() {
    return {}
  }
}
</script>

<style>
.terms {
  width: 90%;
  display: flex;
  justify-content: space-between;
  margin-left: 50px;
  margin-bottom: 60px;
}

.term {
  width: 30%;
}

.term_p {
  position: absolute;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 18px;
  line-height: 20px;
  text-align: center;
  color: #000000;
  margin: -180px 0 0 80px;
  width: 172px;
  height: 80px;
}

.term3_p {
  width: 100px;
  position: absolute;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 18px;
  line-height: 20px;
  text-align: center;
  color: #000000;
  margin: -195px 0 0 115px;
  height: 80px;
}

.courses {
  display: flex;
  flex-wrap: wrap;
  width: 95%;
}

.courses_title {
  font-family: Montserrat;
  font-weight: 800;
  font-size: 36px;
  line-height: 44px;
  text-align: center;
  color: #000000;
}

.courses_eng {
  width: 33%;
  height: 410px;
  /* display:block; */
}

.courses_eng_img {
  width: 305px;
  height: 315px;
}

.courses_eng_p {
  position: absolute;
  width: 254px;
  height: 92px;
  background: #C8274E;
  border-radius: 10px;
  margin: -60px 0 0 60px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 20px;
  line-height: 24px;
  text-align: center;
  color: #000000;
}

.courses_eng_title {
  margin: 0;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 20px;
  line-height: 24px;
  text-align: center;
  color: #000000;
}

.courses_eng_age {
  margin-top: 10px;
}

.courses_rus_img {
  width: 305px;
  height: 315px;
  margin-top: 5px;
}

.courses_rus_p {
  position: absolute;
  width: 254px;
  height: 85px;
  background: #27C84A;
  border-radius: 10px;
  margin: -50px 0 0 60px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 20px;
  line-height: 24px;
  text-align: center;
  color: #000000;
}

.courses_kaz_p {
  position: absolute;
  width: 254px;
  height: 85px;
  background: #277BC8;
  border-radius: 10px;
  margin: -50px 0 0 60px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 20px;
  line-height: 24px;
  text-align: center;
  color: #000000;
}

.courses_logic_p {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #C527C8;
  border-radius: 10px;
  margin: -45px 0 0 60px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 20px;
  line-height: 24px;
  text-align: center;
  color: #000000;
}

.courses_speech_p {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #27BEC8;
  border-radius: 10px;
  margin: -45px 0 0 60px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 20px;
  line-height: 24px;
  text-align: center;
  color: #000000;
}

.courses_figures_p {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #C85727;
  border-radius: 10px;
  margin: -45px 0 0 60px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 20px;
  line-height: 24px;
  text-align: center;
  color: #000000;
}

.courses_write_p {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #8BC827;
  border-radius: 10px;
  margin: -45px 0 0 60px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 20px;
  line-height: 24px;
  text-align: center;
  color: #000000;
}

.courses_read_p {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #8711BE;
  border-radius: 10px;
  margin: -45px 0 0 60px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 20px;
  line-height: 24px;
  text-align: center;
  color: #000000;
}

.courses_count_p {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #DFCA0B;
  border-radius: 10px;
  margin: -45px 0 0 60px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 20px;
  line-height: 24px;
  text-align: center;
  color: #000000;
}

</style>

