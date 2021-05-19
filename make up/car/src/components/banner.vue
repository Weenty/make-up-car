<template>
  <div>
    <div class='banner' style>
      <v-banner class='v-banner'
    single-line
  >
    <svg class='logo' width="38" height="50" viewBox="0 0 38 50" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M16.1203 0C14.4082 4.15512 12.6968 8.31024 10.9847 12.4661C13.4551 18.6158 15.9246 24.7649 18.395 30.9139C13.3962 30.9036 8.39809 30.8925 3.39926 30.8822C2.26643 33.6324 1.13284 36.3825 0 39.1334C7.13838 39.1349 14.2767 39.1364 21.4151 39.1379L26.1051 50H37.234C30.1961 33.3338 23.1582 16.6662 16.1203 0Z" fill="#FFA45A"/>
</svg>
<div class='text_banner1'>
    Новости Акции Каталог Оплата Доставка Контакты
</div>
  </v-banner>
  <div class='text_banner2'>
    Масла Жидкости Автохимия Шины Диски Электрооборудование Прочее 
</div>
           </div>
    </div>
</template>

<script>
  export default {
    name: 'banner',

    data: () => ({

    }),
  }
</script>

<style scoped>
.banner {
  background-image: url(../assets/car.jpg);
  background-size: cover;
  position: flex;
  width: 100%;
}
.logo {
  margin-left: 2%;
}
.text_banner1 {
  color: white;
  margin-left: 10vw;
  word-spacing:2vw;
  size:20px;
  font-weight:600;
}
.text_banner2 {
  color: white;
  margin-left: 10vw;
  word-spacing:2vw;
  size:20px;
    font-weight:400;
}
</style>