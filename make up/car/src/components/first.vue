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
<hr> 
<strong class="text_3">VIN</strong>
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
.right_block_text {
  margin: 0vw;
  margin-top: 1vw;
}
.right_block{
  
font-family: TT Commons;
font-style: normal;
font-weight: normal;
font-size: 30px;
line-height: 34px;

color: #686D79;
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

}
</style>