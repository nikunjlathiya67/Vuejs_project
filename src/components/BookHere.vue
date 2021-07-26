<template>
  <div class="BookHereMain container">
    <div class="BookHereTitle">
      <h3>Book here</h3>
    </div>
    <form class="BookHereForm">
      <div class="row">
        <div class="col-md-4 col-sm-6 form-wrap">
          <label>How many people?</label>
          <b-form-select class="form-submit" v-model="selected" :options="options"></b-form-select>
        </div>
        <div class="col-md-4 col-sm-6 form-wrap">
          <label>When is your date?</label>
          <b-form-datepicker class="form-submit"
            v-model="value"
            :min="min"
            :max="max"
            locale="en"
          ></b-form-datepicker>
        </div>
        <div class="col-md-4 col-sm-6 form-wrap">
          <label>Time</label>
          <b-form-timepicker class="form-submit" v-model="value" locale="en"></b-form-timepicker>
        </div>
        <div class="col-md-4 col-sm-6 form-wrap">
          <label>Name</label>
          <b-form-input class="form-submit" type="text" placeholder="Enter name"></b-form-input>
        </div>
        <div class="col-md-4 col-sm-6 form-wrap">
          <label>Email</label>
          <b-form-input class="form-submit"
          type="email"
          placeholder="Your email address"
        ></b-form-input>
        </div>
        <div class="col-md-4 col-sm-6 form-wrap">
          <label>Phone</label>
          <b-form-input class="form-submit" type="number" placeholder="Your Phone"></b-form-input>
        </div>
      </div>
      <div class="d-flex justify-content-center">
        <div class="col-4 form-wrap">
          <b-button class="form-submit" type="submit" variant="outline-light">Submit</b-button>
        </div>
      </div>
    </form>
  </div>
</template>
<script>
import "../assets/Css/BookHere.css";
export default {
  name: "BookHere",
  data() {
    return {
      selected: null,
      options: [
        { value: null, text: "Please select an option" },
        { value: "a", text: "1 People" },
        { value: "b", text: "2 People" },
        { value: "c", text: "2 to 5 People" },
        { value: "d", text: "6 to 10 People" },
        { value: "e", text: "11 to 20 People" },
        { value: "f", text: "21 or more" },
      ],
    };
  },
};
</script>