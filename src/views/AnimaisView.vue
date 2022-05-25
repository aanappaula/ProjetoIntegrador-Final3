<script>
export default {
  data() {
    return {
      animais: [
        {
          id: 1,
          nome: "Frajola",
          descricao:
            "Amo pular, sou muito ciumenta com meus brinquedos e não deixo outros animais pegarem. Estou a procura de donos que estejam dispostos a dar muito amor!",
          imagem: new URL("../assets/cat.jpeg", import.meta.url).href,
        },
        {
          id: 2,
          nome: "Bola",
          descricao:
            "Pelo meu nome já se sabe que eu sou um cão que ama brincar com uma bola... Sou muito dócil e fofo, adoro correr e passear de coleira.",
          imagem: new URL("../assets/cat2.jpg", import.meta.url).href,
        },
        {
          id: 3,
          nome: "Amora",
          descricao:
            "Meu nome é Amora, e tenho apenas 1 mês de idade, sou muito dócil e amo brincar, correr, e sou um pouco bagunceira também, busco amor e carinho...",
          imagem: new URL("../assets/dog.jpg", import.meta.url).href,
        },
        {
          id: 3,
          nome: "Lili",
          descricao:
            "Sou um pouco brava, mas é pra proteger aqueles que amo, adoro brincar com outros cães, mas não gosto de gatos... Amo passear de coleira com dias de sol.",
          imagem: new URL("../assets/dog1.png", import.meta.url).href,
        },
        {
          id: 4,
          nome: "Felipe",
          descricao:
            "Amo pular, sou muito ciumento com meus brinquedos e não deixo outros animais pegarem. Estou a procura de donos que esteja dispostos a dar muito amor!",
          imagem: new URL("../assets/cat.jpeg", import.meta.url).href,
        },
        {
          id: 5,
          nome: "Luna",
          descricao:
            "Olá, sou a gatinha do meio, e sou a única dos meus irmãos que ainda precisa de um lar... Sou muito dorminhoca, e quase não dou trabalho.",
          imagem: new URL("../assets/cat2.jpg", import.meta.url).href,
        },
        {
          id: 6,
          nome: "Bolinha",
          descricao:
            "Pelo meu nome já se sabe que eu sou um cão que ama brincar com uma bola... Sou muito dócil e fofo, adoro correr e passear de coleira.",
          imagem: new URL("../assets/dog.jpg", import.meta.url).href,
        },
        {
          id: 7,
          nome: "Totó",
          descricao:
            "Amo pular, sou muito ciumento com meus brinquedos e não deixo outros animais pegarem. Estou a procura de donos que estejam dispostos a dar muito amor!",
          imagem: new URL("../assets/dog1.png", import.meta.url).href,
        },
        {
          id: 8,
          nome: "Jill",
          descricao:
            "Amo pular, sou muito ciumento com meus brinquedos e não deixo outros animais pegarem. Estou a procura de donos que estejam dispostos a dar muito amor!",
          imagem: new URL("../assets/cat.jpeg", import.meta.url).href,
        }
      ],
    };
  },
  methods: {
    adotarAnimal(animal) {
      alert("Vou adotar a " + animal.nome);
    },
  },
};
</script>
<template>
  <div class="margin">
    <div class="row row-cols-1 row-cols-md-3 g-4">
      <div class="col" v-for="animal of animais" :key="animal.id">
        <div class="card">
          <img
            id="oi"
            :src="animal.imagem"
            class="card-img-top img-cards"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">{{ animal.nome }}</h5>
            <p class="card-text">
              {{ animal.descricao }}
            </p>
            <button
              type="button"
              class="btn btn-secondary botao-meu"
              @click="adotarAnimal(animal)"
            >
              Ver mais
            </button>
          </div>
        </div>
      </div>


      
    </div>
  </div>
</template>

