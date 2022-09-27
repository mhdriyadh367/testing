<template>
  <div>
    <div
      style="background: linear-gradient(137.77deg, rgba(0, 0, 0, 0.6) 0%, rgba(89, 13, 130, 0.6) 258.61%); width: 100%; height: 100vh; position: absolute;">

    </div>
    <!-- navbar -->
    <nav class=" bg pt-3">
      <div class=" container d-flex justify-content-between align-items-center text-white">

        <div class="navbar-brand-logo">
          <NuxtLink to="/">
            <img src="~/assets/img/logo.png" alt="logo">

          </NuxtLink>
        </div>

        <div>
          <ul class="navbar-menu d-none d-sm-block">
            <li class="list-menu">
              <NuxtLink to="/">Beranda</NuxtLink>
            </li>
            <li class="list-menu">
              <NuxtLink to="/">Layanan</NuxtLink>
            </li>
            <li class="list-menu">
              <NuxtLink to="/">Paket</NuxtLink>
            </li>
            <li class="list-menu">
              <NuxtLink to="/">Daftar Streaming</NuxtLink>
            </li>
            <li class="list-menu">
              <NuxtLink to="/">Pendaftaran</NuxtLink>
            </li>
            <li class="list-menu">
              <NuxtLink to="/">Artikel</NuxtLink>
            </li>

          </ul>

        </div>
        <div class="menu-right d-none d-sm-block">

          <img src="~/assets/img/indonesia.png" style="width: 18px; height: 18px;" alt="">
          <span>ID</span>
          <img src="~/assets/img/gmedia.png" alt="">
        </div>

      </div>

      <!-- carousel -->
      <div style="padding-top: 100px;">
        <Carousel />
      </div>
      <!-- akhir carousel -->

    </nav>
    <!-- navbar -->

  </div>
</template>

<script>
import Carousel from '../Carousel/index.vue';
export default {
  components: { Carousel }
}
</script>

<style>
.navbar-menu {
  list-style: none;
  margin: 0;
  padding-left: 0;
}

.navbar-menu li {
  color: #fff;
  display: block;
  float: left;
  padding: 1rem;
  position: relative;


}

.navbar-menu a {
  color: #fff;
  text-decoration: none;
}

.bg {
  height: 100vh;

  background-image: url("~/assets/img/bg.png");
  background-size: cover;
  background-color: transparent;
}

.navbar-brand-logo img {
  width: 180px;
  height: 46px;
  position: relative;
}


.menu-right img {
  width: 130px;
  height: 25px;
  position: relative;
}

.menu-right span {
  position: relative;
  font-style: normal;
  font-weight: 400;
  font-size: 15px;
  color: #fff;
  padding-right: 20px;
}

.row {
  padding: 0 35px 0 35px;
}

.list-menu {

  font-size: 15px;
  font-weight: 400;
  line-height: 18px;
  letter-spacing: 0em;
}




.button button {
  width: 248px;
  height: 56px;
  background: linear-gradient(137.77deg, #B61AAE 0%, #590D82 258.61%);
  border-radius: 300px;
  border: none;
  color: white;
  font-style: normal;
  font-weight: 600;
  font-size: 17px;
  line-height: 26px;
  margin-top: 70px;
}

.title h1 {
  font-style: normal;
  font-weight: 600;
  font-size: 34px;
  line-height: 51px;
  margin-bottom: 30px;
  color: #ffffff;

}

.excerpt p {
  font-style: normal;
  font-weight: 400;
  font-size: 17px;
  line-height: 28px;
  color: #ffffff;

}


@media (min-width: 320px) and (max-width: 767px) {

  .row {
    display: flex;
    justify-content: center;
    padding: 0;
  }

  .title h1 {
    font-style: normal;
    font-weight: 600;
    font-size: 24px;
    line-height: 32px;
    text-align: center;
  }

  .excerpt p {
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    text-align: center;
  }

  .button {
    text-align: center;
    margin-top: -65px;
  }

  .button button {

    width: 200px;
    height: 56px;
  }

}
</style>