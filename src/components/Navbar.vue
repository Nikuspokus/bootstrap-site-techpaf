<template>
  <b-navbar  class=" BG">
    <b-navbar-nav >
      <!-- <img src="../assets/logo-test-typo.png" style="max-width: 20%; max-heigth: 20%; min-width: 1%; min-heigth: 1%"> -->

      <b-nav-item href="/">Home</b-nav-item>
      <b-nav-item href="/about">About</b-nav-item>

      <!-- Navbar dropdowns -->
      <b-nav-item-dropdown text="Lang" right>
        <b-dropdown-item href="#">EN</b-dropdown-item>
        <b-dropdown-item href="#">ES</b-dropdown-item>
        <b-dropdown-item href="#">RU</b-dropdown-item>
        <b-dropdown-item href="#">FA</b-dropdown-item>
      </b-nav-item-dropdown>
      <spacer />
    </b-navbar-nav>

    <div style="margin-left: 10px" class="right">
      <Avatar />

      <!-- <b-form-input class="mr-sm-2" placeholder="Search"></b-form-input>
      <b-button variant="outline-success" class="my-2 my-sm-0" type="submit"
        >Search</b-button -->
      
    </div>
  </b-navbar>
</template>

<script>
import Avatar from "./Avatar.vue";

export default {
  name: "Navbar",
  components: {
    Avatar,
  },
};
</script>

<style>
.BG {
  background-color: #0D4278;
}
</style>