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
<div class="petr">
  Петров Петр Петрович
</div>
<div class="enter_email">
        Введите электронную почту

</div>

<div style="padding-top:10px" class="petr">
          blabla@gmai.com
 
   </div>
   <div class="enter_email">
        Введите телефон

</div>

<div style="padding-top:10px" class="petr">
          88005553535
 
   </div>

</div>


<div class="right_block">
<div class = "right_top">
<strong class="text_1">Данные автомобиля</strong>
<strong class="text_2">Заказы</strong>
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
color: #D8D8D8;
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