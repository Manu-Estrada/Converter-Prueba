<script>
import Converter from "./components/Converter.vue";
import Navbar from "./components/Navbar.vue";

export default {
  name: "app",
  components: {
    Converter,
    Navbar,
  },
};
</script>

<template>
    <Navbar />
    <Converter />
    
</template>
<style scoped>
.fondo {
  background-image: url("./assets/euro-g6e55d6828_640.jpg");
  height: 100vh;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
</style>
