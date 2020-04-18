<template>
  <div>
    <v-toolbar dark class="px-5 text-menu" color="blue">
      <v-btn icon class="hidden-xs-only">
        <v-icon color="#383ab1" size="40">mdi-rocket</v-icon>
      </v-btn>
      <v-toolbar-title>
        <span class="text-menu">Volant´s</span>
      </v-toolbar-title>

      <v-spacer></v-spacer>
      <v-btn dark color="white">Iniciar sessão</v-btn>
    </v-toolbar>
    <v-card height="150" color="blue" class="card-home pt-5 overflow-hidden">
      <div>
        <div class=" col-sm-12 mx-auto d-flex justify-center">
          <div class="col-sm-6">
            <v-text-field
              prepend-inner-icon="mdi-magnify"
              solo
              label="Pesquise por cidade ou estado
"
            ></v-text-field>
          </div>
          <div class="col-sm-2">
            <v-btn outlined large block color="white">Burcar</v-btn>
          </div>
        </div>
      </div>
    </v-card>
    <div class="col-sm-12 mx-auto">
      <!-- <v-row class="mx-auto"> -->
      <!-- <v-card class="col-sm-2 elevation-0">
          <v-list-item>
            <v-list-item-content>
              <v-list-item-title class="title-category">
                Categorias
              </v-list-item-title>
            </v-list-item-content>
          </v-list-item>

          <v-divider></v-divider>
          <v-list dense>
            <v-list-item link>
              <v-list-item-title>Home Office</v-list-item-title>
            </v-list-item>
            <v-list-item link>
              <v-list-item-title>Meio Periodo</v-list-item-title>
            </v-list-item>
            <v-list-item link>
              <v-list-item-title>Estágio</v-list-item-title>
            </v-list-item>
            <v-list-item link>
              <v-list-item-title>Freelance</v-list-item-title>
            </v-list-item>
          </v-list>
        </v-card> -->

      <v-card class="col-sm-10 elevation-0">
        <v-list-item
          color="blue"
          link
          class="line-job mx-5 d-flex justify-start align-center"
        >
          <div class="d-flex col-sm-6">
            <div class="mr-3">
              <v-img
                width="50px"
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
                width="50px"
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
                width="50px"
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
                width="50px"
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
                width="50px"
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
      <!-- </v-row> -->
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({}),
};
</script>

<style>
.text-menu {
  font-size: 16px !important;
  color: #2b2c2e;
}
.text-category {
  font-size: 14px;
}
.job-title {
  font-size: 16px;
}
.category-title {
  font-size: 14px;
}
</style>
