<template>
  <div>
    <div class="terms">
      <div class="term">
        <img src="../static/img/frame.svg" class="term_img"/>
        <p class="term_p">Занимательные и увлекательные задания каждый день</p>
      </div>
      <div class="term">
        <img src="../static/img/frame.svg" class="term_img"/>
        <p class="term_p">Индивидуальный подход к каждому нашему ученику</p>
      </div>
      <div class="term">
        <img src="../static/img/frame.svg" class="term_img"/>
        <p class="term_right_p">Дружный коллектив помогает в адаптации и развитии</p>
      </div>
    </div>

    <div>
      <h1 class="courses_title">Мы будем изучать ...</h1>
      <div class="courses">
        <div class="course">
          <img src="../static/img/eng.png" class="course_img" />
          <div class="courses_eng_p">
            <p class="course_title">Английский язык</p>
            <p class="course_age">
              От 3 до 5 лет
              <br />От 5 до 7 лет
            </p>
          </div>
        </div>
        <div class="course">
          <img src="../static/img/russs.png" class="courses_rus_img" />
          <div class="courses_rus_p">
            <p class="course_title">Русский язык</p>
            <p class="course_age">
              От 3 до 5 лет
              <br />От 5 до 7 лет
            </p>
          </div>
        </div>
        <div class="course">
          <img src="../static/img/kaz.png" class="course_img" />
          <div class="courses_kaz_p">
            <p class="course_title">Казахский язык</p>
            <p class="course_age">
              От 3 до 5 лет
              <br />От 5 до 7 лет
            </p>
          </div>
        </div>
        <div class="course">
          <img src="../static/img/logic.png" class="course_img" />
          <div class="courses_logic_p">
            <p class="course_title">Логические задачи</p>
            <p class="course_age">
              От 1,5 до 3 лет
              <br />От 3 до 5 лет
              <br />От 5 до 7 лет
            </p>
          </div>
        </div>
        <div class="course">
          <img src="../static/img/speech.png" class="course_img" />
          <div class="courses_speech_p">
            <p class="course_title">Развитие речи</p>
            <p class="course_age">
              От 1,5 до 3 лет
              <br />От 3 до 5 лет
              <br />От 5 до 7 лет
            </p>
          </div>
        </div>
        <div class="course">
          <img src="../static/img/figures.png" class="course_img" />
          <div class="courses_figures_p">
            <p class="course_title">Геометрические фигуры</p>
            <p class="course_age">
              От 1,5 до 3 лет
              <br />От 3 до 5 лет
              <br />От 5 до 7 лет
            </p>
          </div>
        </div>
        <div class="course">
          <img src="../static/img/write.png" class="course_img" />
          <div class="courses_write_p">
            <p class="course_title">Обучение прописи</p>
            <p class="course_age">
              От 1,5 до 3 лет
              <br />От 3 до 5 лет
              <br />От 5 до 7 лет
            </p>
          </div>
        </div>
        <div class="course">
          <img src="../static/img/read.png" class="course_img" />
          <div class="courses_read_p">
            <p class="course_title">Чтение</p>
            <p class="course_age">
              От 1,5 до 3 лет
              <br />От 3 до 5 лет
              <br />От 5 до 7 лет
            </p>
          </div>
        </div>
        <div class="course">
          <img src="../static/img/count.png" class="course_img" />
          <div class="courses_count_p">
            <p class="course_title">Количество и счет</p>
            <p class="course_age">
              От 1,5 до 3 лет
              <br />От 3 до 5 лет
              <br />От 5 до 7 лет
            </p>
          </div>
        </div>
      </div>
      <div class="div_bottom"></div>
    </div>

    <div id="about" class="info_block">
      <img src="../static/img/cicle.svg" class="info_img" />
      <img src="../static/img/student.svg" class="info_img_cicle" />
      <p class="info_p">3590</p>
      <br />
      <p class="info_p_text">Всего детей</p>
      <img src="../static/img/cicle.svg" class="info_img" />
      <img src="../static/img/room.svg" class="info_img_cicle2" />
      <p class="info_p2">789</p>
      <br />
      <p class="info_p_text2">комнат</p>
      <img src="../static/img/cicle.svg" class="info_img" />
      <img src="../static/img/teacher.svg" class="info_img_cicle3" />
      <p class="info_p3">300</p>
      <br />
      <p class="info_p_text3">Всего учителей</p>
    </div>

    <h1 class="request_title">Оставить заявку</h1>
    <div class="request_block">
      <form class="request_form">
        <input type="text" placeholder="Как зовут Вашего ребенка?" class="request_form_input" />
        <input type="text" placeholder="Сколько ему/ей лет?" class="request_form_input" />
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
      <img src="../static/img/tiger.png" class="request_img" />
    </div>
    <h1 class="reviews_title">Отзывы наших родителей</h1>
    <div class="reviews_block">
      <div class="left_review">
        <img src="../static/img/leftR.png" class="left_review_img" />
        <p class="left_review_name">
          Карлыгаш
          <br />дочь Адема, 3 года
        </p>
        <p
          class="left_review_text"
        >"Мы начали ходить сначала в неполную группу, но Адеме очень понравилось с первого дня и мы стали оставлять ее на весь день. Много детей, игры, интересные занятия! Ребенок стал лучше кушать, лучше говорить, интересоваться различными фигурами, мастерить из них что-то. Очень занимательно учат детей считать и знать буквы. Всё в игровой легкой форме и дети с удовольствием участвуют в процессе."</p>
      </div>
      <div class="right_review">
        <img src="../static/img/rightR.png" class="left_review_img" />
        <p class="left_review_name">
          Олеся
          <br />сын Егор, 5,5 лет
        </p>
        <p
          class="left_review_text"
        >“Уже полгода сын с удовольствием ходит в этот садик. За это время он многому научился. В бытовом плане - приучили к горшку и кушать самостоятельно, в плане развития - очень активно начал говорить, строить предложения, мастерить поделки. Мы очень довольны!”</p>
      </div>
    </div>
    <div class="contacts_block">
      <div id="map" class="map_block"></div>
      <div id="contacts" class="contacts">
        <h1 class="contacts_title">Контактные данные</h1>
        <img src="../static/img/geo.svg" class="addres_img"/>
        <p class="contacts_text">Казахстан, г.Алматы, ул.Гоголя 99</p>
        <img src="../static/img/telephone.svg" class="tel_img"/>
        <p class="contacts_text">
          Телефон: +77477011414
          <br />Email: example@gmail.com
        </p>
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
  name: "Information",
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
  font-size: 18px;
  line-height: 20px;
  margin: -180px 0 0 80px;
  width: 172px;
  height: 80px;
}

.term_right_p {
  width: 100px;
  position: absolute;
  font-size: 18px;
  line-height: 20px;
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

.course {
  width: 33%;
  height: 410px;
}

.course_img {
  width: 305px;
  height: 315px;
}

.courses_eng_p {
  position: absolute;
  width: 254px;
  height: 92px;
  background: #c8274e;
  border-radius: 10px;
  margin: -60px 0 0 60px;
  font-size: 20px;
  line-height: 24px;
}

.course_title {
  margin: 0;
  font-size: 20px;
  line-height: 24px;
}

.course_age {
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
  background: #27c84a;
  border-radius: 10px;
  margin: -50px 0 0 60px;
  font-size: 20px;
  line-height: 24px;
}

.courses_kaz_p {
  position: absolute;
  width: 254px;
  height: 85px;
  background: #277bc8;
  border-radius: 10px;
  margin: -50px 0 0 60px;
  font-size: 20px;
  line-height: 24px;
}

.courses_logic_p {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #c527c8;
  border-radius: 10px;
  margin: -45px 0 0 60px;
  font-size: 20px;
  line-height: 24px;
}

.courses_speech_p {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #27bec8;
  border-radius: 10px;
  margin: -45px 0 0 60px;
  font-size: 20px;
  line-height: 24px;
}

.courses_figures_p {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #c85727;
  border-radius: 10px;
  margin: -45px 0 0 60px;
  font-size: 20px;
  line-height: 24px;
}

.courses_write_p {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #8bc827;
  border-radius: 10px;
  margin: -45px 0 0 60px;
  font-size: 20px;
  line-height: 24px;
}

.courses_read_p {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #8711be;
  border-radius: 10px;
  margin: -45px 0 0 60px;
  font-size: 20px;
  line-height: 24px;
}

.courses_count_p {
  position: absolute;
  width: 254px;
  height: 108px;
  background: #dfca0b;
  border-radius: 10px;
  margin: -45px 0 0 60px;
  font-size: 20px;
  line-height: 24px;
}

.div_bottom {
  position: absolute;
  background-repeat: repeat-x;
  background-image: url("../static/img/bottom.png");
  width: 97%;
  height: 150px;
  margin: -35px 0 0 20px;
}

.info_block {
  display: flex;
  height: 320px;
  margin: 180px 0 50px 0px;
}

.info_img {
  margin-right: 40px;
}

.info_img_cicle {
  position: absolute;
  margin: 50px 0px 0 110px;
}

.info_img_cicle2 {
  position: absolute;
  margin: 50px 0px 0 470px;
}

.info_p {
  position: absolute;
  margin: 150px 0 0 115px;
  width: 90px;
  font-size: 36px;
  line-height: 44px;
}

.info_p_text {
  position: absolute;
  margin: 200px 0 0 75px;
  width: 180px;
  font-size: 28px;
  line-height: 34px;
}

.info_p2 {
  position: absolute;
  margin: 150px 0px 0 475px;
  width: 90px;
  font-size: 36px;
  line-height: 44px;
}

.info_p_text2 {
  position: absolute;
  margin: 200px 0 0 435px;
  width: 180px;
  font-size: 28px;
  line-height: 34px;
}

.info_img_cicle3 {
  position: absolute;
  margin: 50px 0px 0 830px;
}

.info_p3 {
  position: absolute;
  margin: 150px 0px 0 830px;
  width: 90px;
  font-size: 36px;
  line-height: 44px;
}

.info_p_text3 {
  position: absolute;
  margin: 190px 0 0 790px;
  width: 180px;
  font-size: 28px;
  line-height: 34px;
}

.request_title {
  font-family: Montserrat;
  font-weight: 800;
  font-size: 36px;
  line-height: 44px;
  color: #000000;
  width: 330px;
  margin-left: 240px;
}

.request_block {
  display: flex;
  margin-left: 200px;
}

.request_form {
  display: flex;
  flex-direction: column;
  width: 430px;
}

.request_form_input {
  width: 425px;
  height: 40px;
  border-radius: 20px;
  margin-bottom: 15px;
  border: none;
  color: #000000;
  font-size: 18px;
  padding: 15px;
}

.request_submit_btn {
  width: 200px;
  height: 50px;
  background: #006dd1;
  border-radius: 20px;
  border: none;
  font-family: Montserrat;
  color: black;
  font-weight: 800;
  font-size: 22px;
  margin: 20px 0 0 120px;
}

.request_img {
  height: 430px;
  margin: -50px 0 0 80px;
}

.reviews_title {
  font-family: Montserrat;
  font-weight: 800;
  font-size: 36px;
  line-height: 44px;
  color: #000000;
  margin-top: 40px;
}
.reviews_block {
  width: 80%;
  display: flex;
  margin: 100px 0 0 150px;
}

.left_review {
  width: 375px;
  height: 440px;
  background: #27cb37;
  box-shadow: 0px 4px 16px 7px rgba(0, 0, 0, 0.25);
  border-radius: 31px;
}

.left_review_img {
  position: absolute;
  margin: -60px 0 0 -240px;
  width: 180px;
  height: 180px;
}

.left_review_name {
  width: 215px;
  height: 70px;
  margin-left: 120px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 24px;
  line-height: 29px;
  text-align: center;
  color: #000000;
}

.left_review_text {
  width: 317px;
  height: 330px;
  margin-top: 40px;
  margin-left: 30px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 18px;
  line-height: 22px;
  text-align: justify;
  color: #000000;
}

.right_review {
  width: 375px;
  height: 440px;
  background: #cb2776;
  box-shadow: 0px 4px 16px 7px rgba(0, 0, 0, 0.25);
  border-radius: 31px;
  margin-left: 150px;
}

.contacts_block {
  display: flex;
}

.map_block {
  width: 600px;
  height: 360px;
  margin: 50px 30px 0 90px;
}

.contacts {
  width: 450px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.contacts_title {
  width: 450px;
  height: 30px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 36px;
  line-height: 44px;
  text-align: justify;
  color: #000000;
  margin: 50px 0 0 20px;
}

.addres_img {
  height: 64px;
}

.tel_img {
  height: 64px;
}

.contacts_text {
  width: 350px;
  height: 30px;
  font-family: Montserrat;
  font-weight: 500;
  font-size: 18px;
  line-height: 22px;
  text-align: justify;
  color: #000000;
  margin-left: 20px;
}

.contacts_img {
  margin-left: 30px;
  height: 40px;
}

.wp_img {
  height: 40px;
}

@media all and (min-width: 768px) and (max-width: 1024px) {

.terms {
  width: 80%;
  display: flex;
  justify-content: center;
  margin: 20px 0 60px 50px;
}
  
.term {
  width: 20%;
  margin-right: 80px;
}

.term_img {
  width: 180px;
}

.term_p {
  font-size: 12px;
  line-height: 14px;
  margin: -120px 0 0 45px;
  width: 100px;
  height: 60px;
}
  
.term_right_p {
  font-size: 12px;
  line-height: 14px;
  margin: -130px 0 0 45px;
  height: 80px;
}

.courses {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  width: 90%;
  margin-top: -20px; 
}

.courses_title {
  margin: -50px 0 30px -50px;
  font-size: 20px;
}

.course {
  width: 35%;
  height: 230px;
  margin-right: 40px;
  margin-bottom: 20px;
}

.course_img {
  width: 260px;
  height: 200px;
}

.courses_rus_img {
  width: 260px;
  height: 200px;
}

.courses_eng_p {
  width: 200px;
  height: 70px;
  margin: -60px 0 0 30px;
}

.course_age {
  margin-top: -5px;
  font-size: 16px;

}

.courses_rus_p {
  width: 200px;
  height: 70px;
  margin: -60px 0 0 30px;
}

.courses_kaz_p {
  width: 200px;
  height: 70px;
  margin: -60px 0 0 30px;
}

.courses_logic_p {
  width: 200px;
  height: 90px;
  margin: -60px 0 0 30px;
}

.courses_speech_p {
  width: 200px;
  height: 90px;
  margin: -60px 0 0 30px;
}

.courses_figures_p {
  width: 230px;
  height: 85px;
  padding: 5px;
  margin: -65px 0 0 10px;
}

.courses_write_p {
  width: 230px;
  height: 90px;
  margin: -65px 0 0 15px;
}

.courses_read_p {
  width: 230px;
  height: 90px;
  margin: -65px 0 0 15px;
}

.courses_count_p {
  width: 230px;
  height: 90px;
  margin: -75px 0 0 15px;
}

.course_title {
  margin: 0;
  font-size: 20px;
  line-height: 24px;
}

.div_bottom {
  width: 98%;
  height: 100px;
  margin: -35px 0 0 10px;
}

.info_block {
  display: flex;
  height: 180px;
  margin: 90px 0 50px 30px;
}

.info_img {
  margin-right: 40px;
  width: 200px;
  height: 200px;
}

.info_img_cicle {
  margin: 30px 0px 0 70px;
  width: 60px;
  height: 60px;
}

.info_p {
  margin: 90px 0 0 65px;
  width: 70px;
  font-size: 28px;
  line-height: 30px;
}

.info_p_text {
  margin: 120px 0 0 25px;
  width: 150px;
  font-size: 22px;
  line-height: 25px;
}

.info_img_cicle2 {
  margin: 25px 0px 0 310px;
  width: 60px;
  height: 60px;
}

.info_p2 {
  margin: 90px 0px 0 305px;
  width: 70px;
  font-size: 28px;
  line-height: 30px;
}

.info_p_text2 {
  margin: 120px 0 0 280px;
  width: 130px;
  font-size: 22px;
  line-height: 25px;
}

.info_img_cicle3 {
  margin: 30px 0px 0 550px;
  width: 60px;
  height: 55px;
}

.info_p3 {
  margin: 85px 0px 0 545px;
  width: 70px;
  font-size: 28px;
  line-height: 30px;
}

.info_p_text3 {
  margin: 110px 0 0 515px;
  width: 130px;
  font-size: 22px;
  line-height: 25px;
}

.request_title {
  margin-left: 170px;
}

.request_block {
  margin-left: 20px;
}

.request_form {
  width: 400px;
}

.request_form_input {
  width: 350px;
  height: 30px;
}

.request_submit_btn {
  font-size: 22px;
  margin: 10px 0 0 80px;
}

.request_img {
  height: 380px;
  margin: -50px 0 0 0px;
}

.reviews_title {
  width: 500px;
  font-size: 34px;
  line-height: 34px;
  margin: 20px  0 0px 100px;
}
.reviews_block {
  width: 80%;
  display: flex;
  margin: 25px 0 0 20px;
}

.left_review {
  width: 290px;
  height: 250px;
  background: #27cb37;
  box-shadow: 0px 4px 16px 7px rgba(0, 0, 0, 0.25);
  border-radius: 31px;
  margin-left: 20px;
}

.left_review_img {
  position: absolute;
  margin: -20px 0 0 -160px;
  width: 100px;
  height: 100px;
}

.left_review_name {
  width: 150px;
  height: 25px;
  margin: 10px 0 0 100px;
  font-size: 16px;
  line-height: 14px;
}

.left_review_text {
  width: 250px;
  height: 240px;
  margin-top: 55px;
  margin-left: 20px;
  font-size: 12px;
  line-height: 14px;
  text-align: justify;
}

.right_review {
  width: 290px;
  height: 250px;
  background: #cb2776;
  box-shadow: 0px 4px 16px 7px rgba(0, 0, 0, 0.25);
  border-radius: 31px;
  margin-left: 60px;
}

.contacts_block {
  display: flex;
  width: 95%;
}

.map_block {
  width: 300px;
  height: 180px;
  margin: 50px 30px 0 20px;
}

.contacts {
  width: 380px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
}

.contacts_title {
  width: 3800px;
  height: 30px;
  font-size: 26px;
  margin: 30px 0 10px 20px;
}

.addres_img {
  height: 40px;
}

.tel_img {
  height: 40px;
}

.contacts_text {
  width: 320px;
  height: 20px;
  font-size: 16px;
  line-height: 18px;
  text-align: justify;
  color: #000000;
  margin-left: 20px;
}

.contacts_img {
  margin-left: 30px;
  height: 30px;
}

.wp_img {
  height: 30px;
}

}

@media all and (min-width: 360px) and (max-width: 767px) {

.terms {
  width: 60%;
  display: flex;
  justify-content: center;
  margin: -50px 0 40px 10px;
}

.term {
  width: 25%;
  margin-right: 30px;
}

.term_img {
  height: 130px;
}

.term_p {
  position: absolute;
  font-size: 10px;
  line-height: 10px;
  margin: -90px 0 0 30px;
  width: 70px;
  height: 80px;
}

.term_right_p {
  width: 70px;
  position: absolute;
  font-size: 10px;
  line-height: 10px;
  margin: -95px 0 0 35px;
  height: 80px;
}

.courses {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  width: 40%;
  margin-top: -20px; 
}

.courses_title {
  margin: -50px 0 20px -150px;
  font-size: 20px;
}

.course {
  width: 35%;
  height: 230px;
  margin-right: 50px;
  margin-bottom: 20px;
}

.course_img {
  width: 260px;
  height: 200px;
}

.courses_rus_img {
  width: 260px;
  height: 200px;
}

.courses_eng_p {
  width: 200px;
  height: 70px;
  margin: -60px 0 0 30px;
}

.course_age {
  margin-top: -5px;
  font-size: 16px;

}

.courses_rus_p {
  width: 200px;
  height: 70px;
  margin: -60px 0 0 30px;
}

.courses_kaz_p {
  width: 200px;
  height: 70px;
  margin: -60px 0 0 30px;
}

.courses_logic_p {
  width: 200px;
  height: 90px;
  margin: -60px 0 0 30px;
}

.courses_speech_p {
  width: 200px;
  height: 90px;
  margin: -60px 0 0 30px;
}

.courses_figures_p {
  width: 230px;
  height: 85px;
  padding: 5px;
  margin: -65px 0 0 10px;
}

.courses_write_p {
  width: 230px;
  height: 90px;
  margin: -65px 0 0 15px;
}

.courses_read_p {
  width: 230px;
  height: 90px;
  margin: -65px 0 0 15px;
}

.courses_count_p {
  width: 230px;
  height: 90px;
  margin: -75px 0 0 15px;
}

.course_title {
  margin: 0;
  font-size: 20px;
  line-height: 24px;
}

.div_bottom {
  width: 100%;
  height: 100px;
  margin: -35px 0 0 0px;
}

.info_block {
  width: 70%;
  display: flex;
  height: 120px;
  margin: 80px 0 10px 5px;
}

.info_img {
  margin-right: 10px;
  width: 110px;
  height: 110px;
}

.info_img_cicle {
  margin: 15px 0px 0 36px;
  width: 35px;
  height: 35px;
}

.info_p {
  margin: 35px 0 0 30px;
  width: 50px;
  font-size: 16px;
}

.info_p_text {
  margin: 55px 0 0 5px;
  width: 100px;
  font-size: 14px;
}

.info_img_cicle2 {
  margin: 15px 0px 0 155px;
  width: 35px;
  height: 35px;
}

.info_p2 {
  margin: 35px 0px 0 150px;
  width: 50px;
  font-size: 16px;
}

.info_p_text2 {
  margin: 55px 0 0 125px;
  width: 100px;
  font-size: 14px;
}

.info_img_cicle3 {
  margin: 14px 0px 0 280px;
  width: 35px;
  height: 30px;
}

.info_p3 {
  margin: 30px 0px 0 270px;
  width: 50px;
  font-size: 16px;
}

.info_p_text3 {
  margin: 60px 0 0 265px;
  width: 50px;
  height: 60px;
  font-size: 14px;
  line-height: 12px;
}

.request_title {
  margin-left: 10px;
  font-size: 28px;
  line-height: 12px;
}

.request_block {
  margin-left: 15px;
}

.request_form {
  width: 300px;
}

.request_form_input {
  width: 300px;
  height: 30px;
}

.request_submit_btn {
  font-size: 22px;
  margin: 5px 0 0 60px;
}

.request_img {
  display: none;
}

.reviews_title {
  width: 350px;
  font-size: 26px;
  line-height: 12px;
  margin: 20px  0 0px 0px;
}
.reviews_block {
  width: 90%;
  display: flex;
  flex-wrap: wrap;
  margin: 25px 0 0 5px;
}

.left_review {
  width: 340px;
  height: 220px;
  background: #27cb37;
  box-shadow: 0px 4px 16px 7px rgba(0, 0, 0, 0.25);
  border-radius: 31px;
  margin-top: 50px;
}

.left_review_img {
  position: absolute;
  margin: -40px 0 0 -170px;
  width: 100px;
  height: 100px;
}

.left_review_name {
  width: 150px;
  height: 25px;
  margin: 10px 0 0 150px;
  font-size: 16px;
  line-height: 14px;
}

.left_review_text {
  width: 300px;
  height: 200px;
  margin-top: 30px;
  margin-left: 15px;
  font-size: 12px;
  line-height: 14px;
  text-align: justify;
}

.right_review {
  width: 340px;
  height: 220px;
  background: #cb2776;
  box-shadow: 0px 4px 16px 7px rgba(0, 0, 0, 0.25);
  border-radius: 31px;
  margin: 50px 0 0 0px;
}

.contacts_block {
  display: flex;
  flex-wrap: wrap;
  width: 98%;
}

.map_block {
  width: 330px !important;
  height: 170px !important;
  margin: 30px 30px 0 10px;
}

.contacts {
  margin: 10px 0 0 20px;
  width: 350px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
}

.contacts_title {
  width: 380px;
  height: 30px;
  font-size: 26px;
  margin: 0px 0 10px 20px;
}

.addres_img {
  height: 30px;
}

.tel_img {
  height: 30px;
}

.contacts_text {
  width: 290px;
  height: 20px;
  font-size: 14px;
  line-height: 14px;
  text-align: justify;
  color: #000000;
  margin-left: 20px;
}

.contacts_img {
  margin: 10px 0 0 20px;
  height: 20px;
}

.wp_img {
  height: 20px;
  margin-top: 10px;
}

}

@media all and (min-width: 1024px) and (max-width: 1474px) {

.terms {
  margin: 20px 0 40px 60px;
}

.term {
  width: 30%;
}

.term_p {
  margin: -125px 0 0 40px;
}

.term_right_p {
  margin: -130px 0 0 40px;
}

.courses {
  justify-content: center;
  /* align-content: space-between; */
  width: 98%;
}

.course {
  margin-bottom: 40px;
}

.courses_eng_p {
  margin: -40px 0 0 70px;
}

.courses_rus_p {
  margin: -50px 0 0 70px;
}

.courses_kaz_p {
  margin: -50px 0 0 70px;
}

.courses_logic_p {
  margin: -45px 0 0 70px;
}

.courses_speech_p {
  margin: -45px 0 0 70px;
}

.courses_figures_p {
  margin: -45px 0 0 50px;
}

.courses_write_p {
  margin: -45px 0 0 55px;
}

.courses_read_p {
  margin: -45px 0 0 55px;
}

.courses_count_p {
  margin: -45px 0 0 55px;
}

.div_bottom {
  width: 98%;
  margin: -35px 0 0 10px;
}

.info_block {
  margin: 120px 0 10px 20px;
  height: 250px;
}

.info_img {
  margin-right: 30px;
  height: 250px;
  width: 300px;
}

.info_img_cicle {
  margin: 40px 0px 0 120px;
}

.info_p {
  margin: 110px 0 0 115px;
  font-size: 30px;
}

.info_p_text {
  margin: 150px 0 0 75px;
  font-size: 26px;
}

.info_img_cicle2 {
  margin: 30px 0px 0 450px;
}

.info_p2 {
  margin: 100px 0px 0 445px;
  font-size: 30px;
}

.info_p_text2 {
  margin: 140px 0 0 420px;
  font-size: 26px;
}

.info_img_cicle3 {
  margin: 30px 0px 0 780px;
  height: 90px;
}

.info_p3 {
  margin: 115px 0px 0 775px;
  font-size: 30px;
}

.info_p_text3 {
  margin: 150px 0 0 765px;
  font-size: 26px;
  width: 20px;
  line-height: 18px;
}

.request_title {
  margin-left: 150px;
  margin-top: 20px;
}

.request_block {
  display: flex;
  margin-left: 100px;
}

.reviews_title {
  margin: 60px 0 0 0px;
}
.reviews_block {
  width: 90%;
  display: flex;
  margin: 100px 0 0 60px;
}

.left_review {
  width: 375px;
  height: 440px;
  background: #27cb37;
  box-shadow: 0px 4px 16px 7px rgba(0, 0, 0, 0.25);
  border-radius: 31px;
}

.left_review_img {
  position: absolute;
  margin: -60px 0 0 -240px;
  width: 180px;
  height: 180px;
}

.left_review_name {
  width: 215px;
  height: 70px;
  margin-left: 120px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 24px;
  line-height: 29px;
  text-align: center;
  color: #000000;
}

.left_review_text {
  width: 317px;
  height: 330px;
  margin-top: 40px;
  margin-left: 30px;
  font-family: Montserrat;
  font-weight: 800;
  font-size: 18px;
  line-height: 22px;
  text-align: justify;
  color: #000000;
}

.right_review {
  width: 375px;
  height: 440px;
  background: #cb2776;
  box-shadow: 0px 4px 16px 7px rgba(0, 0, 0, 0.25);
  border-radius: 31px;
  margin-left: 150px;
}

.map_block {
  /* width: 600px;
  height: 360px; */
  margin: 50px 70px 0 100px;
}


}

</style>

