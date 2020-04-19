<template>
  <div class="col-sm-12">
    <v-row>
      <div class="col-sm-2">
        <v-list link>
          <v-list-item v-for="item in menu" :key="item.id" :to="item.router">
            <b>{{ item.name }}</b>
          </v-list-item>
        </v-list>
      </div>
      <div class="col-sm-6" id="volunteer-list">
        <v-card class="py-5 elevation-0">
          <div class="px-4 mt-5" id="top-home">
            <v-text-field
              dense
              outlined
              name="name"
              label="Ex. Crianças, educação, dança e etc"
              id="id"
            ></v-text-field>
          </div>
          <div id="filter">
            <v-subheader>Recentes</v-subheader>
          </div>
          <v-list-item
            color="blue"
            link
            class="line-job mx-5 d-flex justify-start align-center"
          >
            <div class="d-flex col-sm-6">
              <div class="mr-3">
                <v-img
                  width="60px"
                  src="https://img.utdstc.com/icons/facebook-android.png:75"
                ></v-img>
              </div>
              <div class="mr-3">
                <span class="job-title">
                  <b> Auxiliar cozinha comunitária</b>
                </span>
                <br />
                <small>Facebook CO. - postado a 4 dias</small>
              </div>
            </div>

            <div class="col-sm-3">
              <span class="category-title">
                <b> Freelance</b>
              </span>
              <br />
              <small>Sinop, MT</small>
            </div>
            <div class="col-sm-2">
              <v-chip outlined pill color="red" dark>Cozinha</v-chip>
            </div>
            <div>
              <v-btn icon color="primary">
                <v-icon> mdi-bookmark-outline</v-icon>
              </v-btn>
            </div>
          </v-list-item>
          <div class="col-sm-12">
            <v-divider class="mx-5"></v-divider>
          </div>
          <v-list-item
            link
            class="line-job mx-5 d-flex justify-start align-center"
          >
            <div class="d-flex col-sm-6">
              <div class="mr-3">
                <v-img
                  width="60px"
                  src="http://casadocarvalho.net/wp-content/uploads/2018/06/canto-da-terra.png"
                ></v-img>
              </div>
              <div class="mr-3">
                <span class="job-title">
                  <b> Auxiliar cozinha comunitária</b>
                </span>
                <br />
                <small>Facebook CO. - postado a 4 dias</small>
              </div>
            </div>

            <div class="col-sm-3">
              <span class="category-title">
                <b> Freelance</b>
              </span>
              <br />
              <small>Sinop, MT</small>
            </div>
            <div class="col-sm-2">
              <v-chip outlined pill color="red" dark>Cozinha</v-chip>
            </div>
            <div>
              <v-btn icon color="primary">
                <v-icon> mdi-bookmark-outline</v-icon>
              </v-btn>
            </div>
          </v-list-item>
          <div class="col-sm-12">
            <v-divider class="mx-5"></v-divider>
          </div>
          <v-list-item
            link
            class="line-job mx-5 d-flex justify-start align-center"
          >
            <div class="d-flex col-sm-6">
              <div class="mr-3">
                <v-img
                  width="60px"
                  src="http://casadocarvalho.net/wp-content/uploads/2018/06/canto-da-terra.png"
                ></v-img>
              </div>
              <div class="mr-3">
                <span class="job-title">
                  <b> Auxiliar cozinha comunitária</b>
                </span>
                <br />
                <small>Facebook CO. - postado a 4 dias</small>
              </div>
            </div>

            <div class="col-sm-3">
              <span class="category-title">
                <b> Freelance</b>
              </span>
              <br />
              <small>Sinop, MT</small>
            </div>
            <div class="col-sm-2">
              <v-chip outlined pill color="red" dark>Cozinha</v-chip>
            </div>
            <div>
              <v-btn icon color="primary">
                <v-icon> mdi-bookmark-outline</v-icon>
              </v-btn>
            </div>
          </v-list-item>
          <div class="col-sm-12">
            <v-divider class="mx-5"></v-divider>
          </div>
          <v-list-item
            link
            class="line-job mx-5 d-flex justify-start align-center"
          >
            <div class="d-flex col-sm-6">
              <div class="mr-3">
                <v-img
                  width="60px"
                  src="http://casadocarvalho.net/wp-content/uploads/2018/06/canto-da-terra.png"
                ></v-img>
              </div>
              <div class="mr-3">
                <span class="job-title">
                  <b> Auxiliar cozinha comunitária</b>
                </span>
                <br />
                <small>Facebook CO. - postado a 4 dias</small>
              </div>
            </div>

            <div class="col-sm-3">
              <span class="category-title">
                <b> Freelance</b>
              </span>
              <br />
              <small>Sinop, MT</small>
            </div>
            <div class="col-sm-2">
              <v-chip outlined pill color="red" dark>Cozinha</v-chip>
            </div>
            <div>
              <v-btn icon color="primary">
                <v-icon> mdi-bookmark-outline</v-icon>
              </v-btn>
            </div>
          </v-list-item>
          <div class="col-sm-12">
            <v-divider class="mx-5"></v-divider>
          </div>
          <v-list-item
            link
            class="line-job mx-5 d-flex justify-start align-center"
          >
            <div class="d-flex col-sm-6">
              <div class="mr-3">
                <v-img
                  width="60px"
                  src="http://casadocarvalho.net/wp-content/uploads/2018/06/canto-da-terra.png"
                ></v-img>
              </div>
              <div class="mr-3">
                <span class="job-title">
                  <b> Auxiliar cozinha comunitária</b>
                </span>
                <br />
                <small>Facebook CO. - postado a 4 dias</small>
              </div>
            </div>

            <div class="col-sm-3">
              <span class="category-title">
                <b> Freelance</b>
              </span>
              <br />
              <small>Sinop, MT</small>
            </div>
            <div class="col-sm-2">
              <v-chip outlined pill color="red" dark>Cozinha</v-chip>
            </div>
            <div>
              <v-btn icon color="primary">
                <v-icon> mdi-bookmark-outline</v-icon>
              </v-btn>
            </div>
          </v-list-item>
          <div class="col-sm-12">
            <v-divider class="mx-5"></v-divider>
          </div>
        </v-card>
      </div>
      <div class="col-sm-4" id="work"></div>
    </v-row>
  </div>
</template>

<script>
export default {
  data: () => ({
    menu: [
      {
        id: 1,
        name: "Home",
        router: "/",
      },
      {
        id: 2,
        name: "Perfil",
        router: "/profile",
      },
      {
        id: 3,
        name: "Salvos",
        router: "/saveded",
      },
      {
        id: 4,
        name: "Como funciona?",
        router: "/about",
      },
    ],
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
};
</script>

<style></style>
