<template>
  <section id="presentation" class="about">
    <img id="photo-portrait" src="@/assets/profile-picture.jpg" alt="Photo de Jarod Patingre"
    />
    <div class="about-text">
      <p>
        Je m’appelle Jarod Patingre et je suis actuellement en formation de
        développeur web et web mobile.
      </p>

      <p>
        Passionné à la fois par la cuisine et par l’univers du numérique, je
        m’intéresse particulièrement à l’informatique (hardware,
        développement, jeux vidéo) ainsi qu’à des domaines innovants comme la
        cryptomonnaie.
      </p>

      <p>
        J’ai déjà expérimenté plusieurs de ces secteurs par curiosité et
        passion, ce qui m’a poussé à m’investir pleinement dans le
        développement web après avoir arrêté le lycée à 16 ans.
      </p>

      <p>Au cours de ma formation, j’ai réalisé plusieurs projets concrets :</p>

      <ul>
        <li>Dynamiser un espace commentaire</li>
        <li>Rédiger un cahier des charges pour une entreprise fictive</li>
        <li>Créer mon CV en HTML et CSS</li>
      </ul>

      <p>
        Ces expériences m’ont permis de prendre goût à la conception de sites
        et de développer mes compétences techniques tout en renforçant ma
        motivation à progresser.
      </p>

      <p>
        Mon objectif à long terme est de me spécialiser en cybersécurité, afin
        de protéger les utilisateurs contre toutes formes d’arnaques en ligne.
      </p>

      <p>
        En parallèle, je souhaite approfondir mes connaissances en trading de
        cryptomonnaies, domaine qui me passionne.
      </p>

      <p>
        En dehors de mes études et projets numériques, je suis aussi amateur de
        lecture, notamment de manhwa et de manga, qui stimulent ma créativité.
      </p>

      <p>
        Je continue aujourd’hui à apprendre et à persévérer dans mes projets,
        déterminé à construire une carrière dans le numérique, entre
        développement web et cybersécurité.
      </p>
    </div>
  </section>
</template>

<style scoped>

#presentation {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 50px 20px;
  background: linear-gradient(135deg, #ff9a76, #ffc08c); 
  min-height: 100vh;
  box-sizing: border-box;
}

#photo-portrait {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 30px;
  box-shadow: 0 10px 20px rgba(0,0,0,0.2);
  border: 5px solid white;
}

.about-text {
  width: 50%;
  background: rgba(255, 255, 255, 0.9);
  padding: 40px;
  border-radius: 40px 10px 40px 10px; 
  box-shadow: 0 10px 30px rgba(0,0,0,0.15);
  column-count: 2; 
  column-gap: 30px;
  text-align: justify;
}

.about-text p, .about-text li {
  margin-bottom: 15px;
  line-height: 1.6;
  color: #333;
}

.about-text ul {
  padding-left: 20px;
}

</style>