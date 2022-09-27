<template>
  <div>
    <Navbar />

    

    <Layanan />

    <Fiberstream />

    <DaftarStreaming />

    <Paket />

    <OrderForm />

    <Footer />


  </div>
</template>

<script>
import Navbar from '../components/Navbar/index.vue';
import Layanan from '../components/Layanan/index.vue';
import Fiberstream from '../components/Fiberstream/index.vue';
import Paket from '../components/Paket/index.vue';
import OrderForm from '../components/OrderForm/index.vue';
import Footer from '../components/Footer/index.vue';

export default {
    name: "IndexPage",
    components: { Navbar, Layanan, Fiberstream, Paket, OrderForm, Footer }
}
</script>

<style>
  * {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif !important;
  }
</style>