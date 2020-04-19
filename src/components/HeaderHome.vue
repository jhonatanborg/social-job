<template>
  <div id="header-intro" class="col-sm-6 mx-auto ">
    <div class="mx-auto col-sm-10">
      <div class="text-center">
        <Icon />
      </div>
      <h3 class="text-center">
        Explore mais de 1.600+ projetos no exterior e encontre seu melhor
        programa de voluntariado
      </h3>
    </div>
    <div class="col-sm-6 mx-auto">
      <v-btn x-large block color="#22b173" dark>Como funciona ?</v-btn>
    </div>
  </div>
</template>

<script>
import Icon from "@/components/Icon.vue";

export default {
  components: {
    Icon,
  },
};
</script>

<style>
#header-intro {
  margin-top: 50px;
  margin-bottom: 50px;
}
</style>
