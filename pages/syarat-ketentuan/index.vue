<template>
  <div>
    <Navbar />

    <Content />

    <Footer />
  </div>
</template>

<script>
import Navbar from "../../components/Syarat/Jumbotron/index.vue";
import Content from "../../components/Syarat/Content/index.vue";
export default {
  components: { Navbar, Content }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  font-family: 'Poppins', sans-serif !important;
}
</style>