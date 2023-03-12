<template>
  <div>
    <Nav />
    <Header />
    <About />
    <Features />
    <Cards />
    <Stories />
    <Book />
    <Footer />
    <Popup />
  </div>
</template>

<script>
import Nav from "./components/Nav.vue";
import Header from "./components/Header.vue";
import About from "./components/About.vue";
import Features from "./components/Features.vue";
import Cards from "./components/Cards.vue";
import Stories from "./components/Stories.vue";
import Book from "./components/Book.vue";
import Footer from "./components/Footer.vue";
import Popup from "./components/Popup.vue";

export default {
  name: "App",
  components: {
    Nav,
    Header,
    About,
    Features,
    Cards,
    Stories,
    Book,
    Footer,
    Popup,
  },
};
</script>

<style lang="scss">
// @import "sass/abstracts/functions";
// @import "sass/abstracts/_mixins";
// @import "sass/abstracts/_variables";

// @import "sass/base/_base.scss";
// @import "sass/base/_animations.scss";
// @import "sass/base/_typography.scss";
// @import "sass/base/_utilities.scss";

// @import "sass/layout/_header.scss";
// @import "sass/layout/_grid.scss";
// @import "sass/layout/_footer.scss";
// @import "sass/layout/_navigation.scss";

// @import "sass/components/_button.scss";
// @import "sass/components/_composition.scss";
// @import "sass/components/_feature-box.scss";
// @import "sass/components/_card.scss";
// @import "sass/components/_story.scss";
// @import "sass/components/_bg-video.scss";
// @import "sass/components/_form.scss";
// @import "sass/components/_popup.scss";

// @import "sass/pages/_home.scss";
@import "sass/main.scss";
</style>
