<template>
  <div class="col-sm-12">
    <v-row>
      <div class="col-sm-2">
        <v-list dense>
          <v-list-item
            link
            color="#22b173"
            v-for="item in menu"
            :key="item.id"
            :to="item.router"
          >
            <b>{{ item.name }}</b>
          </v-list-item>
        </v-list>
      </div>
      <div class="col-sm-6" id="volunteer-list">
        <v-card class="py-5 elevation-0">
          <div class="mx-3 col-sm-12">
            <h3><b>Explore</b></h3>
          </div>
          <div class="px-4" id="top-home">
            <v-card flat class="d-flex">
              <div class="col-sm-4">
                <v-select
                  dense
                  color="#22b173"
                  outlined
                  v-model="e2"
                  :items="states"
                  prepend-inner-icon="mdi-map-marker"
                  menu-props="auto"
                  hide-details
                  label="Sinop"
                  single-line
                ></v-select>
              </div>
              <div class="col-sm-8">
                <v-text-field
                  dense
                  outlined
                  name="name"
                  label="Ex. Crianças, educação, dança e etc"
                  id="id"
                ></v-text-field>
              </div>
            </v-card>
          </div>
          <div
            id="filter"
            class="d-flex justify-space-between col-sm-12 mx-auto py-4 align-center"
          >
            <v-subheader>Recentes</v-subheader>
            <v-btn class="mx-3" outlined flat color="#22b173">
              Filtrar
              <v-icon>mdi-filter-variant</v-icon>
            </v-btn>
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
      <div class="col-sm-4" id="work">
        <v-card flat>
          <v-tabs grow dense color="#22b173" v-model="activeTab">
            <v-tab active-class="tabs__item--active ">Detalhes</v-tab>
            <v-tab active-class="tabs__item--active  ">Atividades</v-tab>
            <v-tab active-class="tabs__item--active ">
              Galeria
            </v-tab>
            <v-tabs-items class="card-login" v-model="activeTab">
              <v-tab-item>
                <div class="col-sm-12">
                  <v-list-item two-line>
                    <v-list-item-avatar tile size="70" color="grey darken-3">
                      <v-img
                        src="https://tvcultura.com.br/upload/tvcultura/acontece/20180919161525_animalbabies-01-006-1.jpg"
                      ></v-img>
                    </v-list-item-avatar>
                    <v-list-item-content>
                      <v-list-item-title class="mb-1">
                        <h5>Community Development Experience</h5>
                      </v-list-item-title>
                      <v-list-item-subtitle>
                        Unemat - Faculdade de Sinop
                      </v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                  <div id="description" class="col-sm-12">
                    <div>
                      <div class="item-subtitle">
                        <b>Sobre</b>
                      </div>
                      <span class="text-justify">
                        O desenvolvimento da comunidade envolve muitas
                        atividades e, geralmente, mais voltado para voluntários
                        que desejam realizar uma variedade de tarefas enquanto
                        se voluntariam no Rio de Janeiro.
                      </span>
                    </div>
                    <div class="requirements mt-5">
                      <div class="item-subtitle">
                        <b>Requisitos</b>
                      </div>
                      <div class=" col-sm-12">
                        <v-row>
                          <div class="mb-3 mr-3">
                            <v-chip>Solteiros</v-chip>
                          </div>
                          <div class="mb-3 mr-3">
                            <v-chip>Idade +18</v-chip>
                          </div>
                          <div class="mb-3 mr-3">
                            <v-chip>Familia</v-chip>
                          </div>
                          <div class="mb-3 mr-3">
                            <v-chip>Estudantes</v-chip>
                          </div>
                          <div class="mb-3 mr-3">
                            <v-chip>Estudantes</v-chip>
                          </div>
                          <div class="mb-3 mr-3">
                            <v-chip>Estudantes</v-chip>
                          </div>
                        </v-row>
                        <div>
                          <v-row class="mt-5">
                            <div class="mr-5 py-0">
                              <v-btn block large flat outlined color="#22b173">
                                <v-icon>mdi-bookmark-outline</v-icon>
                                Salvar</v-btn
                              >
                            </div>

                            <v-btn class="col-sm-7" large dark color="#22b173">
                              <div>
                                Quero ajudar
                              </div>
                            </v-btn>
                          </v-row>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </v-tab-item>
              <v-tab-item>
                <div class="col-sm-12">
                  <div class="col-sm-12">
                    <div id="activities">
                      <div class="item-subtitle">
                        <b>Atividades</b>
                      </div>
                      <div class="d-flex mb-3">
                        <v-icon class="mr-4" size="10"
                          >mdi-checkbox-blank-circle</v-icon
                        >
                        <div>
                          Ministrando aulas sobre conhecimentos básicos de
                          informática
                        </div>
                      </div>
                      <div class="d-flex mb-3">
                        <v-icon class="mr-4" size="10"
                          >mdi-checkbox-blank-circle</v-icon
                        >
                        <div>
                          Ajudando a proteger uma conexão com a Internet e a
                          configurar um laboratório de TI.
                        </div>
                      </div>
                      <div class="d-flex mb-3">
                        <v-icon class="mr-4" size="10"
                          >mdi-checkbox-blank-circle</v-icon
                        >
                        <div>
                          Ajudando em uma horta comunitária.
                        </div>
                      </div>
                      <div class="d-flex mb-3">
                        <v-icon class="mr-4" size="10"
                          >mdi-checkbox-blank-circle</v-icon
                        >
                        <div>
                          Ministrando aulas sobre conhecimentos básicos de
                          informática
                        </div>
                      </div>
                      <div class="d-flex mb-3">
                        <v-icon class="mr-4" size="10"
                          >mdi-checkbox-blank-circle</v-icon
                        >
                        <div>
                          Ajudando a proteger uma conexão com a Internet e a
                          configurar um laboratório de TI.
                        </div>
                      </div>
                    </div>
                    <div class="requirements mt-5">
                      <div class=" col-sm-12">
                        <div>
                          <v-row class="mt-5">
                            <div class="mr-5 py-0">
                              <v-btn block large flat outlined color="#22b173">
                                <v-icon>mdi-bookmark-outline</v-icon>
                                Salvar</v-btn
                              >
                            </div>

                            <v-btn class="col-sm-7" large dark color="#22b173">
                              <div>
                                Quero ajudar
                              </div>
                            </v-btn>
                          </v-row>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </v-tab-item>
              <v-tab-item>
                <v-row class="col-sm-12 mx-auto">
                  <v-col cols="12" md="6">
                    <v-img
                      src="https://s2.glbimg.com/pVuH0290uy9NmG09TYhwyYgErYk=/0x0:1920x1080/1600x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_e84042ef78cb4708aeebdf1c68c6cbd6/internal_photos/bs/2019/1/C/09f5TERA6T9Ixqy7FUng/unhaodas-artes.00-00-08-03.still002.jpg"
                    ></v-img>
                  </v-col>
                  <v-col cols="12" md="6">
                    <v-img
                      src="https://s2.glbimg.com/pVuH0290uy9NmG09TYhwyYgErYk=/0x0:1920x1080/1600x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_e84042ef78cb4708aeebdf1c68c6cbd6/internal_photos/bs/2019/1/C/09f5TERA6T9Ixqy7FUng/unhaodas-artes.00-00-08-03.still002.jpg"
                    ></v-img>
                  </v-col>
                  <v-col cols="12" md="6">
                    <v-img
                      src="https://s2.glbimg.com/pVuH0290uy9NmG09TYhwyYgErYk=/0x0:1920x1080/1600x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_e84042ef78cb4708aeebdf1c68c6cbd6/internal_photos/bs/2019/1/C/09f5TERA6T9Ixqy7FUng/unhaodas-artes.00-00-08-03.still002.jpg"
                    ></v-img>
                  </v-col>
                  <v-col cols="12" md="6">
                    <v-img
                      src="https://s2.glbimg.com/pVuH0290uy9NmG09TYhwyYgErYk=/0x0:1920x1080/1600x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_e84042ef78cb4708aeebdf1c68c6cbd6/internal_photos/bs/2019/1/C/09f5TERA6T9Ixqy7FUng/unhaodas-artes.00-00-08-03.still002.jpg"
                    ></v-img>
                  </v-col>
                  <v-col cols="12" md="6">
                    <v-img
                      src="https://s2.glbimg.com/pVuH0290uy9NmG09TYhwyYgErYk=/0x0:1920x1080/1600x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_e84042ef78cb4708aeebdf1c68c6cbd6/internal_photos/bs/2019/1/C/09f5TERA6T9Ixqy7FUng/unhaodas-artes.00-00-08-03.still002.jpg"
                    ></v-img>
                  </v-col>
                </v-row>
              </v-tab-item>
            </v-tabs-items>
          </v-tabs>
        </v-card>
      </div>
    </v-row>
  </div>
</template>

<script>
export default {
  data: () => ({
    activeTab: null,
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
        name: "Itens Salvos",
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

<style>
.v-tab {
  text-transform: none !important;
}
.item-subtitle {
  font-size: 14px;
}
</style>
