<template>
  <div class="home">
    <TopHome />
  </div>
</template>

<script>
// @ is an alias to /src
import TopHome from "@/components/TopHome.vue";

export default {
  name: "Home",
  components: {
    TopHome
  }
};
</script>
