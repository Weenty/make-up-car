<template>
  <div>
      <div class="news">
          Новости
      </div>
      <button class="button">
          <svg 
          width="165" 
          height="40" 
          viewBox="0 0 165 40" 
          fill="none" 
          xmlns="http://www.w3.org/2000/svg">
          <rect 
          width="165" 
          height="40" 
          fill="#712BE1"/>
          </svg>
      </button>
    <div>
      <svg
        class="news2"
        width="232"
        height="232"
        viewBox="0 0 232 232"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <rect 
        width="232" 
        height="232" 
        rx="1" 
        fill="black" 
        fill-opacity="0.5" />
      </svg>
      <div class="news2_data">
          14.03.2020
      </div>
      <div class="news2_text1">
          Аварийная ситуация!
          <br />
          Ночное ДТП в центре
          <br />
          Нижнего тагила
      </div>
      <div class="news2_text2">
          Разбираемся в инциденте вместе
          <br />
          с инспектором ГИБДД 
          <br />
          А. А. Грибниковым
      </div>
    </div>
    <div>
      <svg
        class="news3"
        width="232"
        height="232"
        viewBox="0 0 232 232"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <rect width="232" height="232" rx="1" fill="black" fill-opacity="0.5" />
      </svg>
      <div class="news3_data">
          01.05.2020
      </div>
      <div class="news3_text">
          Автовладельцы
          <br />
          выступают против
          <br />
          COVID-19
      </div>
    </div>
    <svg
      class="news1"
      width="660"
      height="502"
      viewBox="0 0 660 502"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
    >
      <rect width="660" height="502" fill="black" fill-opacity="0.496943" />
    </svg>
    <div class="news1_text1">
      Номинант на оскар -
      <br />
      фильм "Форд против Ферарр"
    </div>
    <div class="news1_data">03.04.2020</div>
    <div class="news1_text2">
      Интересные подробности
      <br />
      со съемок
    </div>
  </div>
</template>

<script>
export default {
  name: "news",

  data: () => ({}),
};
</script>

<style scoped>
.button{
    position: absolute;
    top: 2892px;
    left: 1300px;
}
.news {
    font-family: TT commons;
    color: #686D79;
  position: absolute;
  font-weight: 600;
  top: 2898px;
  left: 300px;
  font-size: 35px;
}
.news1 {
  position: absolute;
  top: 3018px;
  left: 300px;
  background-image: url(../assets/news1.jpg);
  background-size: 100%;
}

.news1_data {
    font-family: TT commons;
    color: #ffffff;
  position: absolute;
  top: 3056px;
  left: 350px;
  font-size: 18px;
}

.news1_text1 {
  position: absolute;
  font-family: TT Commons;
  color: #ffffff;
  font-size: 30px;
  top: 3334px;
  left: 350px;
  line-height: 45px;
}

.news1_text2 {
  position: absolute;
  font-family: TT Commons;
  color: #ffffff;
  font-size: 20px;
  top: 3438px;
  left: 350px;
  line-height: 25px;
}

.news2 {
  position: absolute;
  top: 3016px;
  left: 1020px;
  background-image: url(../assets/news2.jpg);
  background-size: 100%;
}

.news2_data {
    position: absolute;
  font-family: TT Commons;
  color: #D8D8D8;
  font-size: 18px;
  top: 3016px;
  left: 1282px;
}

.news2_text1 {
    position: absolute;
  font-family: TT Commons;
  color: #686D79;
  font-size: 20px;
  font-weight: 600;
  top: 3082px;
  left: 1282px;
}

.news2_text2 {
    position: absolute;
  font-family: TT Commons;
  color: #686D79;
  font-size: 15px;
  top: 3195px;
  left: 1282px;
}

.news3 {
  position: absolute;
  top: 3288px;
  left: 1020px;
  background-image: url(../assets/news3.jpg);
  background-size: 100%;
}

.news3_data {
    position: absolute;
  font-family: TT Commons;
  color: #D8D8D8;
  font-size: 18px;
  top: 3287px;
  left: 1282px;
}

.news3_text {
    position: absolute;
  font-family: TT Commons;
  color: #686D79;
  font-size: 20px;
  font-weight: 600;
  top: 3377px;
  left: 1282px;
}
</style>