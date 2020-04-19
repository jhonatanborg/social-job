<template>
  <v-app id="card-category">
    <div class="mt-5 mx-auto">
      <h3 class="text-subtitle">
        Tópicos de tendências & destinos de valor para 2020
      </h3>
    </div>
    <v-layout class="mt-5 mx-auto col-sm-10 col-mx-10 ">
      <v-row class=" mx-auto">
        <v-col class="" v-for="item in categories" :key="item.id" sm="2">
          <v-card justify-center fill-height flat color="white" class="mx-auto">
            <v-card flat>
              <v-img class="pb-3" height="130px" width="130" :src="item.image">
              </v-img>
            </v-card>

            <div class="pt-2">
              <span class="subtitle-card">
                <b>{{ item.name }}</b>
              </span>
            </div>
          </v-card>
        </v-col>
      </v-row>
    </v-layout>
  </v-app>
</template>

<script>
export default {
  name: "CardsCategory",
  data: () => ({
    categories: [
      {
        id: 1,
        image:
          "https://tvcultura.com.br/upload/tvcultura/acontece/20180919161525_animalbabies-01-006-1.jpg",
        name: "Animais",
      },
      {
        id: 2,
        image:
          "https://media-cdn.tripadvisor.com/media/attractions-splice-spp-720x480/07/2b/97/17.jpg",
        name: "Floresta",
      },
      {
        id: 3,
        image:
          "http://contaumahistoria.com.br/wp-content/uploads/2015/04/3080_NotaEducacao.jpg",
        name: "Educação",
      },
      {
        id: 4,
        image:
          "http://www.engeplus.com.br/cache/noticia/0144/0144899/quase-um-terco-dos-positivados-ja-estao-curados-da-covid-19-em-criciuma.jpg?t=20200417105212",
        name: "Covid-19 ",
      },

      {
        id: 5,
        image:
          "https://www.agenciabrasilia.df.gov.br/wp-conteudo/uploads/2017/10/policia-militar-comunidade-esporte-renato-araujo-640x427.jpg",
        name: "Esporte",
      },
      {
        id: 6,
        image: "https://miro.medium.com/max/1400/1*ODWg9QtTeiYADJHnawxP5Q.png",
        name: "Arte&cultura",
      },
    ],
  }),
  methods: {
    listCategories() {
      this.categories = null;
    },
  },
};
</script>

<style>
#card-category {
  background-color: white;
  font-family: CircularStd !important;
}
.text-subtitle {
  color: #22b173;
}
</style>
