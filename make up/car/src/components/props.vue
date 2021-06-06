<template>
<conatiner>
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
        title: 'Подбор и замена масла'
      },
      {
        img: 2,
        title: 'Консультация по замене автозапчастей'
      },
      {
        img: 3,
        title: 'Осмотр автомобилей и рекомендации по ремонту'
      },
    ]
  })
};
</script>

<style scoped>

</style>
    