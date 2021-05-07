<template>
  <div class="home">
    <TopMessage />
    <Search />
    <Cards />
  </div>
</template>

<script>
import Cards from '../components/Cards.vue';
// @ is an alias to /src
import Search  from '../components/Search'
import TopMessage  from '../components/TopMessage'

export default {
  name: "Home",
  components: {
    Cards,
    Search,
    TopMessage
  },
};
</script>
