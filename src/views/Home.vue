<template>
  <div class="home">
    <TopMessage />
    <Search />
    <div class="container mx-auto">
      <div class="wrapper">
        <div class="box1">unS</div>
        <div class="box2">
          <Cards />
          <Cards />
          <Cards />
          <Cards />
          <Cards />
          </div>
        <div class="box3">Trois</div>
      </div>
    </div>
    <!-- <div id="conteneur">
      <div id="bloc1">
        <Cards />
      </div>
      <div id="bloc2">
      </div>
    </div> -->
  </div>
</template>

<script>
import Cards from "../components/Cards.vue";
// @ is an alias to /src
import Search from "../components/Search";
import TopMessage from "../components/TopMessage";

export default {
  name: "Home",
  components: {
    Cards,
    Search,
    TopMessage,
  },
};
</script>

<style>
/* .containerHome {
    justify-content: start;
} */

/* #conteneur{
 width: 600px;
 margin: auto;
}
#bloc_1{
 width: 450px;
 position: relative;
 float: left;
}
#bloc_2{
 width: 120px;
 position: relative;
 float: left;
} */

/* . container {

} */

.wrapper {
  /* margin: 80px; */
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 100px 100px;
  grid-gap: 10px;
}

.box1 {
  background-color: blue;
  grid-column: 3 / 4;
  grid-row: 1;
}

.box2 {
  background-color: green;
  grid-column: 1 / 3;
  grid-row: 1 / 3;
}

.box3 {
  background-color: red;
  grid-row: 2;
  grid-column: 3;
}
</style>
