<template>
  <div class="position-relative">
      <Header />
      <div class="SectionImage">
          <img src="../assets/Image/Place Your Design Here (Double Click to Edit) (1).png" alt="FirstImage"/>
      </div>
      <div class="FullWebsite">
          <h3>Brunch</h3>
          <h2>FULL WEBSITE</h2>
          <button>READ MORE</button>
      </div>
  </div>
</template>
<script>
import Header from './Header.vue';
import '../assets/Css/FirstContainer.css'
export default {
  components: { Header },
  name: "FirstContainer",
};
</script>