<template>
<div class = "container">
 <div class="left_block">
<div class="search">
          Поиск товара
</div>
<div class="vin">
          Запрос по VIN
</div>
<div class="enter_name">
         Введите имя
</div>


<input class='petr' placeholder="Петр петрович">


<div class="enter_email">
        Введите электронную почту

</div>

<input class='petr' placeholder="balblalba@mail.ru">
   <div class="enter_email">
        Введите телефон

</div>

<input class='petr' placeholder="88005553535">
<v-checkbox
      v-model="checkbox1"
      :label="`Только оригинал`"
    ></v-checkbox>
    <v-checkbox
      v-model="checkbox2"
      :label="`Наши рекомендации`"
    ></v-checkbox>
    <v-checkbox
      v-model="checkbox3"
      :label="`Минимальная цена`"
    ></v-checkbox>
</div>


<div class="right_block">
<div class = "right_top">
  <div class='right_block_text'>
<strong class="text_1">Данные автомобиля</strong> <strong class="text_2">Запчасти</strong>
<div>
  
<div class='padding1'/> <div class='purpe'> </div> <div class='purpe2'> </div> <div class='padding1'/><strong class="text_3">VIN</strong> <div class='padding1'/>
<div class='input1'>
<input class='petr1' placeholder="XXX-XXX-XXX"> <div class='padding'/>
<hr>
</div>
<div class='padding1'/><strong class="text_3">Марка и модель</strong> <div class='padding1'/>
<div class='input1'>
<input class='petr1' placeholder="Lada X-RAY"> <div class='padding'/>
<hr>
</div>
<div class='padding1'/><strong class="text_3">Год выпуска</strong> <div class='padding1'/>
<div class='input1'>
<input class='petr1' placeholder="2000"> <div class='padding'/>
<hr>
</div>
</div>
</div>
</div><div class='padding1'/>
<button class='bt'>Отправить <svg class='svg-margin' width="42" height="15" viewBox="0 0 42 15" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M40 8.65076V6.8281L0 6.8281L0 8.65076L40 8.65076Z" fill="white"/>
<path fill-rule="evenodd" clip-rule="evenodd" d="M38.9754 7.97614L33.2401 13.7114L34.5281 15.0004L41.5523 7.97614L34.5281 0.951912L33.2401 2.24085L38.9754 7.97614Z" fill="white"/>
</svg>
</button><div class='padding1'/>
<div class='text-bottom'> Заполняя форму и нажимая на кнопку вы соглашаетесь с <b>политикой конфиденциальности</b> и на сбор и обработку персональных данных</div> 

</div>
</div>
</template>

<script>
 export default {
    data () {
      return {
        checkbox1: true,
        checkbox2: false,
      }
    },
  }
</script>

<style scoped>
.text-bottom {
  max-width: 450px;
  text-align: justify;
  color: #686D79;
  font-family: TT Commons;
font-style: normal;
font-weight: normal;
font-size: 15px;
line-height: 25px;
}
.svg-margin {
  margin-left: 280px;
}
.bt {
  text-indent: 10px;
  text-align: left;
  width: 500px;
  height: 70px;
  background-color: #FFA45A; 
  font-family: TT Commons;
font-style: normal;
font-weight: 600;
font-size: 30px;
line-height: 34px;
color: #FFFFFF;
}
.purpe2 {
  background-color: #712BE1;
  width: 500px;
height: 1px;
}
.purpe {
  background-color: #712BE1;
  width: 251px;
height: 6px;
}
.right_top
{
  background: #F3F3F3;
}
.text_1 { 
font-family: TT Commons;
font-style: normal;
font-weight: normal;
font-size: 30px;
line-height: 34px;

color: #686D79;
}
.padding1 {
  padding-top: 3vw;
}
.padding {
  padding-top: 1.5vw;
}
.input1 {
  max-width: 500px;
}
.text_3 {
  margin-top: 4vw;
  font-family: TT Commons;
font-style: normal;
font-weight: normal;
font-size: 30px;
line-height: 34px;
color: #686D79;
}
.text_2 {
  margin-left: 4vw;
  font-family: TT Commons;
font-style: normal;
font-weight: normal;
font-size: 30px;
line-height: 34px;
color: #686D79;
}
.right_block_text {
  margin: 0vw;
  margin-top: 10vw;
  width: 34vw;
}
.search{
  display: normal;
  margin: 0vw;
  margin-top: 10vw;   
 font-family: TT Commons;
font-style: normal;
font-weight: 600;
font-size: 20px;
line-height: 23px;
color: #D8D8D8;

}
.vin{
 display: normal;
  margin: 0vw;
  margin-top: 1vw;    
font-family: TT Commons;
font-style: normal;
font-weight: 600;
font-size: 40px;
line-height: 46px;
color: #686D79;
}
.enter_name{
    display: normal;
  margin: 0vw;
  margin-top: 5vw;
  font-family: TT Commons;
font-style: normal;
font-weight: normal;
font-size: 30px;
line-height: 34px;
color: #686D79;
}
:active, :hover, :focus {
    outline: 0;
    outline-offset: 0;
}
input.petr::placeholder {
  color: #D8D8D8;
}
input.petr1::placeholder {
  color: #D8D8D8;
}

.petr{
  width: 500px;
  height: 70px;
  margin: -1.3em 0 0 0.2em;
     display: normal;
  margin: 0vw;
  margin-top: 1vw;
  margin-left: 0vw;
  margin-right: 0vw;
    font-family: TT Commons;
font-style: normal;
font-weight: normal;
font-size: 20px;
line-height: 23px;
border: 1px solid #979797;
box-sizing: border-box;
}
.petr1{
  margin: -1.3em 0 0 0.2em;
     display: normal;
  margin: 0vw;
  margin-top: 1vw;
  margin-left: 0vw;
  margin-right: 0vw;
    font-family: TT Commons;
font-style: normal;
font-weight: normal;
font-size: 20px;
line-height: 23px;
box-sizing: border-box;
}
.enter_email{
      display: normal;
  margin: 0vw;
  margin-top: 3vw;
  margin-left: 0vw;
  margin-right: 0vw;
    font-family: TT Commons;
font-style: normal;
font-weight: normal;
font-size: 30px;
line-height: 34px;
color: #686D79;
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
background: #F3F3F3;
}
</style>