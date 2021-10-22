<template>
  <div class="preloader">
    <div class="loader">
      <div class="ytp-spinner">
        <div class="ytp-spinner-container">
          <div class="ytp-spinner-rotator">
            <div class="ytp-spinner-left">
              <div class="ytp-spinner-circle"></div>
            </div>
            <div class="ytp-spinner-right">
              <div class="ytp-spinner-circle"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <Header />
  <Features />
  <About />
  <Services />
  <Portfolio />
  <Team />
  <Contact />
  <Footer/>
  <!--<a href="http://wa.me/5519993176589" target="_blank" class="back-to-top"><i class="lni lni-facebook-messenger"></i></a>-->
  <a href="http://wa.me/5519993176589" target="_blank" class="back-to-top"
    ><span id="back-to-top2" class="material-icons-outlined">
      whatsapp
  </span></a
  >
</template>

<script>
import Header from "./pages/Header.vue";
import Features from "./pages/Features.vue";
import About from "./pages/About.vue";
import Services from "./pages/Services.vue";
import Portfolio from "./pages/Portfolio.vue";
import Team from "./pages/Team.vue";
import Contact from "./pages/Contact.vue";
import Footer from "./pages/Footer.vue";

export default {
  components: {
    Header,
    Features,
    About,
    Services,
    Portfolio,
    Team,
    Contact,
    Footer,
  },
};
</script>