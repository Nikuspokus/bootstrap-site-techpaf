<template>
  <div class="mx-auto containerSearch">
    <b-container class="m-5 mx-auto">
      <div class="d-flex align-items-center justif">
        <b-form-input class="mr-2" placeholder="Search" style="width: 600px"> </b-form-input>
        <b-button variant="success" class="ml-5" type="submit">Search</b-button>
      </div>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "Search",
};
</script>
<style>

.justif {
  justify-content: space-around;
}

.containerSearch {
  max-width: 750px;
}
</style>
