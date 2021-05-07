<template>
  <div class="home">
    <TopMessage />
    <Search />
  </div>
</template>

<script>
// @ is an alias to /src
import Search  from '../components/Search'
import TopMessage  from '../components/TopMessage'

export default {
  name: "Home",
  components: {
    Search,
    TopMessage
  },
};
</script>
