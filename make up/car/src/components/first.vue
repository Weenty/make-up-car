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

</div>


<div class="right_block">
<div class = "right_top">
  <div class='right_block_text'>
<strong class="text_1">Данные автомобиля</strong> <strong class="text_2">Запчасти</strong>
<div>
<div class='padding1'/><strong class="text_3">VIN</strong> <div class='padding1'/>
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
</div>
</div>
</div>
</template>

<script>
export default {
  name: "first",

  data: () => ({}),
};
</script>

<style scoped>
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