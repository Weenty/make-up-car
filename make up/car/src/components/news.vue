<template>
<div>
  <div class="news">
  Новости
  </div>
  <div class="container">
    <div class="left_block">
      <div class="img1">
        <v-img
        width="660px"
        height="500px"
          gradient="to top right, rgba(0, 0, 0, 0.496943),rgba(0, 0, 0, 0.496943)"
          src="../assets/news1.jpg"
        >
          <div class="text3">03.04.2020</div>
          <div class="text4">
            Номинант на оскар – фильм «Форд против Ферарри»
          </div>
          <div class="text5">Интересные подробности со съемок</div></v-img
        >
      </div>
    </div>

    <div class="right_block">
      <div class="img2">
        <div class="lr">
          <v-img
            height="230px"
            width="230px"
            gradient="to top right, rgba(0, 0, 0, 0.496943),rgba(0, 0, 0, 0.496943)"
            src="../assets/news2.jpg"
          >
          </v-img>
          <v-img
                    class="lr3"
            height="230px"
            width="230px"
            gradient="to top right, rgba(0, 0, 0, 0.496943),rgba(0, 0, 0, 0.496943)"
            src="../assets/news3.jpg"
          ></v-img>
        </div>
        <div class="lr1">
          <div class="text2">
            <b>Аварийная ситуация! Ночное ДТП в центре Нижнего Тагила </b> <br> <br>
            Разбираемся в инциденте вместе с инспектором ГИБДД А. А. Грибниковым
          </div>
                    <div class="text12">
            
            <b>Автовладельцы выступают против COVID-19 </b>
          </div>
        </div>
      </div>
    </div>
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
.news {
  font-family: TT Commons;
font-style: normal;
font-weight: 600;
font-size: 40px;
line-height: 46px;
margin-left: 7%;
/* identical to box height */

color: #686D79;
}
.text2 {
  margin-left: 1vw;
  width: 12vw;
}
.text12 {
  padding-top: 12vw;
  margin-left: 1vw;
}
.lr3 {
  margin-top: 3vw;
}
.text3 {
  margin-left: 1vw;
  font-family: TT Commons;
  font-style: normal;
  font-weight: normal;
  font-size: 20px;
  line-height: 40px;
  /* identical to box height, or 200% */

  color: #ffffff;
}
.text4 {
  padding-top: 40%;
  margin-left: 1vw;
  font-family: TT Commons;
  font-style: normal;
  font-weight: 600;
  font-size: 30px;
  line-height: 40px;
  /* or 133% */

  color: #ffffff;
}
.text5 {
  margin-left: 1vw;
  font-family: TT Commons;
  font-style: normal;
  font-weight: normal;
  font-size: 20px;
  line-height: 40px;
  /* identical to box height, or 200% */

  color: #ffffff;
}

.img1 {
  width: 100%;
  height: 110%;
}

.img2 {
  display: flex;
  margin-left: 1vw;
  width: 32%;
  height: 32%;
}

.container {
  display: flex;
  flex-direction: row;
}
.left_block {
  height: 1000px;
  display: block;
  width: 50%;
}
.right_block {
  height: 1000px;
  display: block;
  width: 50%;
}
</style>