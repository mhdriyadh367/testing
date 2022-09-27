<template>
  <div>
    
    <Jumbotron />

    <Content/>

    <Footer />

  </div>
</template>

<script>
import Jumbotron from '../../components/Faq/Jumbotron/index.vue';
import Content from '../../components/Faq/Content/index.vue';



export default {
    components: { Jumbotron, Content }
}
</script>

<style>

</style>