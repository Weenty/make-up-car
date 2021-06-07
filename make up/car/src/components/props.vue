<template>
<conatiner>
  <div class="tr">
    Вы можете нам доверять
  </div>
  <div class='fucking_block'>
  <v-row no-gutters>
     <v-col v-for="data in data" :key="data" cols="2" sm="4">
<v-card
    class="mx-auto"
    max-width="344"
    
  >
    <v-img
      :src='"@/assets/"+data.img+".jpg"'
      height="450px"
    ></v-img>
   

    <v-card-title>
      {{data.title}}
    </v-card-title>
    <div class="buy">
<v-card-title>
      {{data.buy}}
    </v-card-title>
    </div>
    <div class="knopka">
      <button class="bt">
        Добавить  
        
      </button>
<div class="pod">Подробнее
</div>
    </div>

      <v-spacer></v-spacer>
  </v-card>

     </v-col>
  </v-row>
  </div>
</conatiner>     
</template>
      

<script>
 export default {
  name: "HelloWorld",
  data: () => ({
    data: [
      {
        img: 1,
        title: 'Подбор и замена масла',
        buy:'2000 Р' 
      },
      {
        img: 2,
        title: 'Консультация по замене автозапчастей',
        buy:'1444 P'
      },
      {
        img: 3,
        title: 'Осмотр автомобилей и рекомендации по ремонту',
        buy:'4800 P'
      },
    ]
  })
};
</script>

<style scoped>
.buy{
  color: #be0d0d;
}
.bt {
  text-indent: 1px;
  text-align: center;
  width: 200px;
  height: 70px;
  background-color: #ffa45a;
  font-family: TT Commons;
  font-style: normal;
  font-weight: 600;
  font-size: 30px;
  line-height: 34px;
  color: #ffffff;}

  .knopka{
font-family: TT Commons;
font-style: normal;
font-weight: 600;
font-size: 20px;
line-height: 40px;
    display: flex;
  }
  .pod{
       margin-top:1vw;
       margin-left: 1vw;
  }
  .tr{
    font-family: TT Commons;
font-style: normal;
font-weight: 600;
font-size: 40px;
line-height: 46px;
margin-left: 5vw;
margin-bottom: 4vw;
  }
</style>
    