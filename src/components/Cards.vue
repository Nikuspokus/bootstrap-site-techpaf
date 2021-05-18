<template>
  <b-container class="m-5 mx-auto">
    <div class="d-flex align-items-center">
      <b-card
        img-src="https://placekitten.com/300/300"
        img-alt="Card image"
        img-left
        class="mb-3 card-1 mx-auto"
        img-height="200px"
      >
        <b-card-text>
          Some quick example text to build on the card and make up the bulk of
          the card's content.
        </b-card-text>
      </b-card>
    </div>
  </b-container>
</template>

<script>
export default {
  name: "Cards",
};
</script>

<style>
.card-1 {
  box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
  transition: all 0.3s cubic-bezier(.25,.8,.25,1);
}

.card-1:hover {
  box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22);
}
</style>
