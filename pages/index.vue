<template>
  <div class="bg">
    <div class="container">
      <div class="main">
        <div class="logo-container">
          <Logo />
        </div>
        <h1 class="title">
          SARL Thonon
        </h1>
        <p>
          Offrons la possibilité de consommer un produit régional, sain et
          pratique. Notre stratégie est de vous proposer un produit au coeur de
          la tendance venu directement de notre terroir. Un packaging innovant
          et différenciant Une marque à l’écoute des envies et des besoins des
          consommateurs Afin d’optimiser les ventes, l'achat coup de coeur et la
          fidélisation. Un dispositif régional qui s'inscrit dans la durée
          Variété: Celtiane Poids net 2.5 kg Sac kr
        </p>
        <h2 class="subtitle">Producteur de pommes de terre Celtiane</h2>
        <p>
          C’est avant tout, une histoire de famille, le savoir-faire de la terre
          transmis de génération en génération depuis plusieurs décennies.
          Aujourd’hui, comme hier, nous sommes unis par la même passion, celle
          de l’agriculture authentique et responsable, notre désir étant de vous
          proposer des produits de qualité issus de notre terroir en respectant
          les équilibres de la nature. Nos pommes de terre sont triées et
          emballées directement à la ferme afin de vous assurer une qualité et
          une fraicheur irréprochable pour vos clients. La variété de pommes de
          terre Celtiane a de multiples atouts. Il s'agit d'une pomme de terre
          de consommation à la chair ferme. Son tubercule régulier de forme
          allongée, de très bonne qualité, se conserve très bien. La peau est
          fine et jaune tandis que la chair est jaune pâle. De très bonne tenue
          à la cuisson, ses tubercules ne demandent aucun épluchage et sont
          parfaits pour les cuissons à l'eau ou à la vapeur. Avec son packaging
          novateur et respectueux de l’environnement, notre produit optimisera
          les ventes de votre rayon.
        </p>
        <div class="contact-container">
          <h2 class="subtitle">Contact</h2>
          <p>
            <strong>SARL THONON La Récole de Joseph</strong><br />
            Producteur de pommes de terre<br />
            contact@larecoltedejoseph.com<br />
            Tel : 06 37 61 17 18<br />
            181, Bis rue d’Ytres 62124 LECHELLE
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: rgba(250, 250, 250, 0.6);
  padding: 0 100px;
}

.main {
  margin-top: 50px;
  margin-bottom: 50px;
}

.bg {
  /* The image used */
  background-image: url('../assets/bg-kraft.jpg');

  /* Full height */
  height: 100%;

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.title {
  font-family: 'Big Shoulders Stencil Text', cursive;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #43311a;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #43311a;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

h1,
h2 {
  font-family: 'Big Shoulders Stencil Text', cursive;
  color: #43311a;
  margin: 40px 0px 10px;
}
h2 {
  font-size: 20px;
  line-height: 150%;
  margin: 40px 0px 10px;
}
p {
  font-size: 16px;
  font-weight: 400;
  text-align: left;
}

@media only screen and (max-width: 600px) {
  h1.title {
    font-size: 65px;
  }
}

.contact-container {
  padding: 40px;
}
</style>
