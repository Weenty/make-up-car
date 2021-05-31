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
      src="../assets/2.jpg" 
      height="200px"
    ></v-img>

    <v-card-title>
      {{data.title}}
    </v-card-title>
    <v-card-subtitle>
      1,000 miles of wonder
    </v-card-subtitle>

    <v-card-actions>
      <v-btn
        color="orange lighten-2"
        text
      >
        Explore
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn
        icon
        @click="show = !show"
      >
        <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
      </v-btn>
    </v-card-actions>
    

    <v-expand-transition>
      <div v-show="show">
        <v-divider></v-divider>

        <v-card-text>
          I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
        </v-card-text>
      </div>
    </v-expand-transition>
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
        img: "https://via.placeholder.com/600/51aa97",
        title: 'Подбор и замена масла'
      },
      {
        img: "https://via.placeholder.com/600/24f354",
        title: 'Консультация по замене автозапчастей'
      },
      {
        img: "https://via.placeholder.com/600/24f354",
        title: 'Осмотр автомобилей и рекомендации по ремонту'
      },
    ]
  })
};
</script>

<style scoped> 
.fucking_block {
  position: normal;
  display: normal;
}
</style>
    