<template>
  <h2>A propos de moi</h2>
  <p>Bonjour, je m'appelle Naoufal et j'ai {{ calculeAge(this.date) }} ans.</p>
  <p>Je suis né et j'ai grandi à Lyon, une ville magnifique!</p>
  <p>Depuis tout petit, je suis passionné par le développement informatique.</p>
  <p>
    J'ai toujours été attiré par le monde de l'informatique, fasciné par la
    façon dont les lignes de code peuvent donner vie à des idées et des projets.
    J'aime développer mes compétences de développeur, explorer de nouvelles
    technologies et résoudre des problèmes complexes.
  </p>
  <p>
    Je suis devenu un développeur professionnel il y a 3 ans et j'adore ce que
    je fais!
  </p>
</template>

<script>
export default {
  name: "SectionTwo",
  data() {
    return {
      date: "2000-01-18",
    };
  },
  methods: {
    calculeAge(dateNaissance) {
      const today = new Date();
      const birthDate = new Date(dateNaissance);
      let age = today.getFullYear() - birthDate.getFullYear();
      const moisActuel = today.getMonth();
      const moisNaissance = birthDate.getMonth();

      if (
        moisActuel < moisNaissance ||
        (moisActuel === moisNaissance && today.getDate() < birthDate.getDate())
      ) {
        age--;
      }

      return age;
    },
  },
};
</script>
