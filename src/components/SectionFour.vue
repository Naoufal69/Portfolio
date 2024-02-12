<template>
  <h2>Mes experiences</h2>
  <div class="experiences">
    <div class="experience">
      <a
        href="https://clubs.lappartfitness.com/45-l-appart-fitness-givors-robinson"
        target="_blank"
      >
        <img src="../../public/Logo/appart.png" alt="L'appart" />
      </a>
      <div class="info">
        <h2>Administrateur de base de données</h2>
        <p>Décembre à Janvier 2014-2015</p>
      </div>
    </div>
    <div class="experience">
      <a href="https://atelierautocolor.fr/" target="_blank">
        <img src="../../public/Logo/AutocolorSarl.png" alt="AutocolorSarl"
      /></a>
      <div class="info">
        <h2>Infographiste</h2>
        <p>Décembre à Janvier 2015-2016</p>
      </div>
    </div>

    <div class="experience">
      <a href="https://www.cgi.com/france/fr-fr" target="_blank">
        <img src="../../public/Logo/CGI.png" alt="CGI"
      /></a>
      <div class="info">
        <h2>Développeur PHP Junior</h2>
        <p>Novembre 2022 - Jusqu'aujourd'hui</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionFour",
};
</script>

<style>
.experience {
  display: flex;
  align-items: center;
  margin: 20px 0;
}
.experience img {
  width: 300px;
  height: 118.39px;
  margin-right: 15px;
}
</style>
