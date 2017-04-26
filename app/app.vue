<template lang="html">
  <div class="app">
    <div class="hero">
        <div class="nav">
          <img src="./images/logo.png" alt="">
          <div class="nav__right">
            <a href="#" class="nav__item nav__item--hidden">Browse</a>
            <a href="#" class="nav__item nav__item--hidden">Discover</a>
            <a href="#" class="nav__item">Add Event</a>
            <a href="#" class="nav__item nav__item--main">Join Us</a>
          </div>
        </div>
          <div class="hero__content">
            <p class="hero__content-title">Discover the top live music events near you</p>
            <div class="form">
              <input class="form__input" type="text" placeholder="Enter your favorite artist or genre">
              <div class="form__group">
              <select class="form__select">
                <option value="location">Location</option>
                <option value="Nashville">Nashville, TN</option>
                <option value="Atlanta">Atlanta, GA</option>
                <option value="Birmingham">Birmingham, AL</option>
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
        <div class="featured">
          <div class="featured__options">
            <p class="featured__options-item"><span class="active">Most popular</span></p>
            <p class="featured__options-item">Coming up</p>
            <p class="featured__options-item">Near you</p>
          </div>
          <div class="grid">
            <div class="grid__item">
              <img src="./images/event1.jpg" class="grid__item-image" alt="">
                  <p class="grid__item-title">Country</p>
                  <p class="grid__item-subtitle">Kenny Chesney w/ Grace Potter</p>
                <div class="grid__half">
                  <div class="grid__half-group">
                    <p class="grid__item-title">Location</p>
                    <p class="grid__item-subtitle">Nashville, TN</p>
                  </div>
                  <div class="grid__half-group">
                    <p class="grid__item-title">Price</p>
                    <p class="grid__item-subtitle">$30-260</p>
                  </div>
                </div>
            </div>
            <div class="grid__item">
              <img src="./images/event2.jpg" class="grid__item-image" alt="">
                  <p class="grid__item-title">Jazz</p>
                  <p class="grid__item-subtitle">Gerald Albright Band</p>
                <div class="grid__half">
                  <div class="grid__half-group">
                    <p class="grid__item-title">Location</p>
                    <p class="grid__item-subtitle">Atlanta, GA</p>
                  </div>
                  <div class="grid__half-group">
                    <p class="grid__item-title">Price</p>
                    <p class="grid__item-subtitle">$15-90</p>
                  </div>
                </div>
            </div>
            <div class="grid__item">
              <img src="./images/event3.jpg" class="grid__item-image" alt="">
                  <p class="grid__item-title">Electronic</p>
                  <p class="grid__item-subtitle">The Rock Church</p>
                <div class="grid__half">
                  <div class="grid__half-group">
                    <p class="grid__item-title">Location</p>
                    <p class="grid__item-subtitle">Birmingham, AL</p>
                  </div>
                  <div class="grid__half-group">
                    <p class="grid__item-title">Price</p>
                    <p class="grid__item-subtitle">$20-40</p>
                  </div>
                </div>
              </div>
            </div>
          <button class="featured__button">Discover more</button>
          </div>
      </div>

      <footer class="footer">
        <div class="footer__content">
          <div class="footer__group">
            <a href="#" class="footer__group-item">&#x24B8; 2017 Lewis</a>
            <a href="#" class="footer__group-item">Privacy Policy</a>
            <a href="#" class="footer__group-item">Terms Of Use</a>
          </div>
          <div class="footer__group">
            <a href="https://www.facebook.com/LewisCommunications" class="footer__group-item"><i class="fa fa-facebook" aria-hidden="true"></i></a>
            <a href="https://twitter.com/lewisideas" class="footer__group-item"><i class="fa fa-twitter" aria-hidden="true"></i></a>
            <a href="#" class="footer__group-item"><i class="fa fa-google-plus" aria-hidden="true"></i></a>
          </div>
        </div>
      </footer>
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
