<template>
  <h2>Mes liens</h2>
  <div class="liens">
    <a
      href="https://www.linkedin.com/in/naoufal-ayache-6295a01ba/"
      target="_blank"
      ><img src="./../../public/Liens/linkedin.png"
    /></a>
    <a href="mailto:naoufalayache@gmail.com"><img src="./../../public/Liens/mail.png" alt="Mail"/></a>
  </div>
</template>

<script>
export default {
  name: "SectionFive",
};
</script>

<style>

.liens img{
    width: 100px;
    height: 100px;
}

.liens{
    display: flex;
    justify-content: space-around;
    margin-bottom: 30px;
}

</style>
