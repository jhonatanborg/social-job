<template>
  <div class="home">
    <HeaderHome />
    <CardsCategory />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderHome from "@/components/HeaderHome.vue";
import CardsCategory from "@/components/CardsCategory.vue";

export default {
  name: "Home",
  components: {
    HeaderHome,
    CardsCategory,
  },
};
</script>
