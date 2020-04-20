<template>
  <div>
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
</template>

<script>
export default {
  name: "Menu",
  props: {
    menu: Array,
  },
};
</script>

<style></style>
