<template>
  <div class="TraditionalCarausalMain">
    <div class="DesignLeft">
      <img src="../assets/Image/Design2.png" alt="Design1" />
    </div>
    <div class="Carausal container">
      <b-carousel
        id="carousel-1"
        v-model="slide"
        :interval="4000"
        indicators
        img-width="1024"
        img-height="480"
        @sliding-start="onSlideStart"
        @sliding-end="onSlideEnd"
      >
        <!-- Text slides with image -->
        <b-carousel-slide
          caption="Traditional cuisine made easy"
          text="Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis "
        ></b-carousel-slide>
        <b-carousel-slide
          caption="Traditional cuisine made easy"
          text="Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis "
        ></b-carousel-slide>
        <b-carousel-slide
          caption="Traditional cuisine made easy"
          text="Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis "
        ></b-carousel-slide>
      </b-carousel>
      <div class="carausalLink">
        <b-link href="#Meals">Meals</b-link>
        <b-link href="#Spices">Spices</b-link>
        <b-link href="#Book">Book</b-link>
        <b-link href="#Gallery">Gallery</b-link>
      </div>
    </div>
    <div class="DesignRight">
      <img src="../assets/Image/Design1.png" alt="Design2" />
    </div>
  </div>
</template>
<script>
import "../assets/Css/TraditionalCarausal.css";
export default {
  name: "TraditionalCarausal",
  data() {
    return {
      slide: 0,
      sliding: null,
    };
  },
  methods: {
    onSlideStart() {
      this.sliding = true;
    },
    onSlideEnd() {
      this.sliding = false;
    },
  },
};
</script>