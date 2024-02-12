<template>
  <SectionOne
    @scrollToSectionTwo="scrollToSectionTwo"
    @scrollToSectionThree="scrollToSectionThree"
    @scrollToSectionFour="scrollToSectionFour"
    @scrollToSectionFive="scrollToSectionFive"
  />
  <div class="sections">
    <section id="sectionTwo">
      <SectionTwo ref="sectionTwo" />
    </section>

    <section id="sectionThree">
      <SectionThree ref="sectionThree" />
    </section>

    <section id="sectionFour">
      <SectionFour ref="sectionFour" />
    </section>

    <section id="sectionFive">
      <SectionFive ref="sectionFive" />
    </section>
  </div>
</template>

<script>
import SectionOne from "./components/SectionOne.vue";
import SectionTwo from "./components/SectionTwo.vue";
import SectionThree from "./components/SectionThree.vue";
import SectionFour from "./components/SectionFour.vue";
import SectionFive from "./components/SectionFive.vue";

export default {
  name: "App",
  components: {
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour,
    SectionFive,
  },
  methods: {
    scrollToSectionTwo() {
      const sectionTwo = document.getElementById("sectionTwo");
      sectionTwo.scrollIntoView({ behavior: "smooth" });
    },
    scrollToSectionThree() {
      const sectionThree = document.getElementById("sectionThree");
      sectionThree.scrollIntoView({ behavior: "smooth" });
    },
    scrollToSectionFour() {
      const sectionFour = document.getElementById("sectionFour");
      sectionFour.scrollIntoView({ behavior: "smooth" });
    },
    scrollToSectionFive() {
      const sectionFive = document.getElementById("sectionFive");
      sectionFive.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>

<style>
#app {
  width: 100%;
  height: 100%;
}

.sections{
  margin-left: 3%;
  margin-right: 3%;
}

h1,
h2,
h3 {
  font-family: "Open Sans", sans-serif;
}

body,
html {
  width: 100%;
  height: 100%;
  margin: 0%;
  font-weight: bolder;
  margin: 0;
  background-color: #75A9F3;
  font-family: "Roboto", sans-serif;
}
</style>
