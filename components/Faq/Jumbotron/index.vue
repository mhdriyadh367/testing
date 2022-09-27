<template>
  <div>

    <section class="syarat" style="padding-top: 21px" >
      <div class="container d-flex justify-content-between align-items-center text-white">
        <div class="navbar-brand-logo">
          <img src="~/assets/img/logo.png" alt="">
        </div>
        <ul class="navbar-menu">
          <NuxtLink to="/">
            <li class="list-menu">Beranda</li>

          </NuxtLink>
          <li class="list-menu">Layanan</li>
          <li class="list-menu">Paket</li>
          <li class="list-menu">Daftar Streaming</li>
          <li class="list-menu">Pendaftaran</li>
          <li class="list-menu">Artikel</li>
        </ul>
        <div class="menu-right">

          <img src="~/assets/img/gmedia.png" alt="">
        </div>



      </div>

      <div class="container">
        <div>
          <div class="syaratTitle text-center" style="margin-top: 120px;">
            <h1>Pertanyaan yang sering ditanyakan</h1>
            <p>Home > FAQ</p>
          </div>
        </div>
      </div>

    </section>

  </div>
</template>

<script>
export default {

}
</script>

<style>
.syarat {
  width: 100%;
  height: 414px;
  background: linear-gradient(137.77deg, #B61AAE 0%, #590D82 258.61%);
  color: #fff;
}

.syaratTitle h1 {
  font-style: normal;
  font-weight: 600;
  font-size: 34px;
  line-height: 51px;
}

.syaratTitle p {
  font-style: normal;
  font-weight: 300;
  font-size: 15px;
  line-height: 22px;
  margin-top: 40px;
}
.navbar-menu a {
  text-decoration: none;
}
</style>