<template>
  <div class="headSection">
    <div class="bandeau">
      <div class="sectionOne">
        <div class="image-cercle">
          <img alt="Photo de profil" src="./../../public/PDP.png" />
        </div>
        <h1>AYACHE Naoufal</h1>
      </div>
    </div>
    <nav>
      <button @click="scrollToSectionTwo">A propos de moi</button>
      <button @click="scrollToSectionThree">Mes compétences</button>
      <button @click="scrollToSectionFour">Mes experiences</button>
      <button @click="scrollToSectionFive">Mes liens</button>
    </nav>
  </div>
</template>

<script>
export default {
  name: "SectionOne",
  methods: {
    scrollToSectionTwo() {
      this.$emit("scrollToSectionTwo");
    },
    scrollToSectionThree() {
      this.$emit("scrollToSectionThree");
    },
    scrollToSectionFour() {
      this.$emit("scrollToSectionFour");
    },
    scrollToSectionFive() {
      this.$emit("scrollToSectionFive");
    },
  },
};
</script>

<style>
.image-cercle {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  overflow: hidden;
}

.headSection {
  background-color: #000000;
  color: white;
}

nav {
  display: flex;
  justify-content: space-around;
}

.bandeau{
  background-color: #000000;
  border: 4px solid black;
}

.sectionOne {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  margin-bottom: 4px;
  margin-top: 4px;
}

.image-cercle img {
  width: 100%;
  height: auto;
}

button {
  opacity: 95%;
  appearance: none;
  border: none;
  background-color: #000000;
  box-sizing: border-box;
  color: #ffffff;
  cursor: pointer;
  display: inline-block;
  font-size: 16px;
  font-weight: 600;
  line-height: normal;
  margin: 0;
  min-height: 60px;
  min-width: 0;
  outline: none;
  padding: 16px 24px;
  text-align: center;
  text-decoration: none;
  transition: all 300ms cubic-bezier(0.23, 1, 0.32, 1);
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  width: 100%;
  will-change: transform;
}

button:disabled {
  pointer-events: none;
}

button:hover {
  box-shadow: rgba(0, 0, 0, 0.25) 0 8px 15px;
  transform: translateY(-2px);
}

button:active {
  box-shadow: none;
  transform: translateY(0);
}
</style>
