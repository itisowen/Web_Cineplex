<template>
  <div>
    <div id="home">
      <!-- <img src="../assets/logo.png"> -->
      <MyCarousel class="mx-3" :movies="movies" :categories="categories"/>
      <br>
      <div class="container">
        <CardMovie class="x" :movies="movies" :categories="categories"/>
      </div>
    </div>
  </div>
</template>

<script>
import MyCarousel from "@/components/MyCarousel";
import CardMovie from "@/components/CardMovie";
export default {
  name: "Home",
  components: {
    MyCarousel,
    CardMovie
  },
  data() {
    return {
      movies: movies,
      categories: categories,
      seat: seats
    };
  }
};
</script>

<style>
.x {
  margin-top: 0;
}
#home {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>