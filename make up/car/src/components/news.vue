<template>
  <div>
    <div class="zag">Новости</div>
    <div class="block">
     <div class='img1'> <v-img src="../assets/news1.jpg" width="20vw"> </v-img> </div>
      <div class='block2'> <v-img src="../assets/news2.jpg"> </v-img>
      <v-img src="../assets/news3.jpg"> </v-img> </div>
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
.padding-right {
  padding-right: 2vw;
}
.block {
  display: flex;
}
.block2 {
  display: normal;
}
</style>