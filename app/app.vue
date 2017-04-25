<template lang="html">
  <div class="app">
    <div class="hero">
      <div class="container1">
        <div class="nav">
          <img src="./images/logo.png" alt="">
          <div class="nav__right">
            <a href="#" class="nav__item">Browse</a>
            <a href="#" class="nav__item">Discover</a>
            <a href="#" class="nav__item">Add Event</a>
            <a href="#" class="nav__item nav__item--main">Join Us</a>
          </div>
        </div>
      </div>
          <div class="hero__content">
            <p class="hero__content-title">Discover the top live music events near you</p>
            <div class="form">
              <input class="form__input" type="text" placeholder="Enter your favorite artist or genre">
              <div class="form__group">
              <select class="form__select">
                <option value="location">Location</option>
                <option value="tennessee">Tennessee</option>
              </select>
              <select class="form__select">
                <option value="budget">Budget</option>
                <option value="low">$0 - $50</option>
                <option value="medium">$50 - $100</option>
                <option value="high">$100+</option>
              </select>
              <button class="form__button">Find events</button>
              </div>
            </div>
          </div>
    </div>

    <div class="app__main">

    </div>
  </div>
</template>

<script>
import Vue from 'vue';
export default Vue.extend({
  data() {
    return {};
  },

  methods: {

  },
});
</script>
