<template>
  <div class="HeaderMain">
    <div class="container">
      <b-navbar toggleable="lg">
        <b-navbar-brand href="#">ANT-CODE</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse">
          <img src="../assets/Image/Menu.svg" alt=""/>
        </b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item href="#">WELCOME</b-nav-item>
            <b-nav-item href="#">MENU</b-nav-item>
            <b-nav-item href="#">EVENTS</b-nav-item>
            <b-nav-item href="#">CONTACT</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>
<script>
import '../assets/Css/Header.css'
export default {
  name: "Header",
};
</script>