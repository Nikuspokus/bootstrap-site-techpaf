<template>
  <b-navbar>
    <div class="container">
      <div>
        <b-navbar-nav>
          <img
            src="../assets/logo-test-typo.png"
            style="max-width: 15%; max-heigth: 15%"
          />
          <!-- 
          <b-nav-item href="/">Home</b-nav-item>
          <b-nav-item href="/about">About</b-nav-item> -->

          <!-- <b-nav-item href="/js">JS</b-nav-item> -->
          <!-- Navbar dropdowns -->
          <b-nav-item-dropdown text="JS">
            <b-dropdown-item href="#">Trucs & Astuces</b-dropdown-item>
            <b-dropdown-item href="#">Angular</b-dropdown-item>
            <b-dropdown-item href="#">JQuery</b-dropdown-item>
            <b-dropdown-item href="#">NodeJS</b-dropdown-item>
            <b-dropdown-item href="#">VueJS</b-dropdown-item>
            <b-dropdown-item href="#">CR - Réunion</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item-dropdown text="PHP">
            <b-dropdown-item href="#">Trucs & Astuces</b-dropdown-item>
            <b-dropdown-item href="#">Angular</b-dropdown-item>
            <b-dropdown-item href="#">JQuery</b-dropdown-item>
            <b-dropdown-item href="#">NodeJS</b-dropdown-item>
            <b-dropdown-item href="#">VueJS</b-dropdown-item>
            <b-dropdown-item href="#">CR - Réunion</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item-dropdown text="JAVA">
            <b-dropdown-item href="#">Trucs & Astuces</b-dropdown-item>
            <b-dropdown-item href="#">Angular</b-dropdown-item>
            <b-dropdown-item href="#">JQuery</b-dropdown-item>
            <b-dropdown-item href="#">NodeJS</b-dropdown-item>
            <b-dropdown-item href="#">VueJS</b-dropdown-item>
            <b-dropdown-item href="#">CR - Réunion</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item-dropdown text=".NET">
            <b-dropdown-item href="#">Trucs & Astuces</b-dropdown-item>
            <b-dropdown-item href="#">Angular</b-dropdown-item>
            <b-dropdown-item href="#">JQuery</b-dropdown-item>
            <b-dropdown-item href="#">NodeJS</b-dropdown-item>
            <b-dropdown-item href="#">VueJS</b-dropdown-item>
            <b-dropdown-item href="#">CR - Réunion</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item-dropdown text="IA -ML">
            <b-dropdown-item href="#">Trucs & Astuces</b-dropdown-item>
            <b-dropdown-item href="#">Angular</b-dropdown-item>
            <b-dropdown-item href="#">JQuery</b-dropdown-item>
            <b-dropdown-item href="#">NodeJS</b-dropdown-item>
            <b-dropdown-item href="#">VueJS</b-dropdown-item>
            <b-dropdown-item href="#">CR - Réunion</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item-dropdown text="YPO">
            <b-dropdown-item href="#">Trucs & Astuces</b-dropdown-item>
            <b-dropdown-item href="#">Angular</b-dropdown-item>
            <b-dropdown-item href="#">JQuery</b-dropdown-item>
            <b-dropdown-item href="#">NodeJS</b-dropdown-item>
            <b-dropdown-item href="#">VueJS</b-dropdown-item>
            <b-dropdown-item href="#">CR - Réunion</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item-dropdown text="GREEN IT">
            <b-dropdown-item href="#">Trucs & Astuces</b-dropdown-item>
            <b-dropdown-item href="#">Angular</b-dropdown-item>
            <b-dropdown-item href="#">JQuery</b-dropdown-item>
            <b-dropdown-item href="#">NodeJS</b-dropdown-item>
            <b-dropdown-item href="#">VueJS</b-dropdown-item>
            <b-dropdown-item href="#">CR - Réunion</b-dropdown-item>
          </b-nav-item-dropdown>
          <spacer />
        </b-navbar-nav>
      </div>
      <div>
          <div class="searchBox">

            <input class="searchInput" type="text" name="" placeholder="Search">
            <button class="searchButton" href="#">
                <i class="material-icons">
                    search
                </i>
            </button>
        </div>
        <Avatar />

        <!-- <b-form-input class="mr-sm-2" placeholder="Search"></b-form-input>
      <b-button variant="outline-success" class="my-2 my-sm-0" type="submit"
        >Search</b-button -->
      </div>
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
  background-color: #0d4278;
}

.container {
  justify-content: space-between;
}

/* ///////////////////////////////////////////////////// */

.searchBox {
    position: absolute;
    top: 50%;
    left: 50%;
    transform:  translate(-50%,50%);
    background: #2f3640;
    height: 40px;
    border-radius: 40px;
    padding: 10px;

}

.searchBox:hover > .searchInput {
    width: 240px;
    padding: 0 6px;
}

.searchBox:hover > .searchButton {
  background: white;
  color : #2f3640;
}

.searchButton {
    color: white;
    float: right;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background: #2f3640;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: 0.4s;
}

.searchInput {
    border:none;
    background: none;
    outline:none;
    float:left;
    padding: 0;
    color: white;
    font-size: 16px;
    transition: 0.4s;
    line-height: 40px;
    width: 0px;

}

@media screen and (max-width: 620px) {
.searchBox:hover > .searchInput {
    width: 150px;
    padding: 0 6px;
}
}

</style>
