<template>
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
</template>

<script>
export default {
  name: "TopHome",
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
