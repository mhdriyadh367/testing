<template>
  <div>
    <section class="layanan">
      <div>
        <div class="container">
          <div class="row">
            <div class="col-sm-12">
              <h1 class="text-center" style="padding-top: 100px">Jelajahi Layanan Fiberstream</h1>

            </div>
          </div>

          <div class="row text-center" style="color: #303030; padding-top: 50px;">
            <div class="col-sm">
              <div class="d-flex justify-content-center " style="margin-bottom: 30px">
                <div class="align-items-center d-flex justify-content-center"
                  style="width: 100px; height: 100px; background: linear-gradient(75deg, rgba(204,72,156,1) 0%, rgba(93,51,213,1) 100%); border-radius: 50%;">
                  <img src="~/assets/img/svg/2.svg">
                </div>

              </div>
              <div class="titleLayanan">
                <h2>
                  Jaringan
                  Serat Optik Generasi Baru</h2>

              </div>
              <div class="excerptLayanan" style="margin-top: 20px;">
                <p>Tetap memberikan informasi dan teknologi jaringan terbaru dan paling canggih.</p>
              </div>

            </div>

            <div class="col-sm">
              <div class="fiberstream d-flex justify-content-center " style="margin-bottom: 30px">
                <div class="align-items-center d-flex justify-content-center"
                  style="width: 100px; height: 100px; background: linear-gradient(75deg, rgba(204,72,156,1) 0%, rgba(93,51,213,1) 100%); border-radius: 50%;">
                  <img src="~/assets/img/svg/3.svg">
                </div>

              </div>
              <div class="titleLayanan">
                <h2>Streaming Berkualitas Tinggi</h2>

              </div>
              <div class="excerptLayanan" style="margin-top: 20px;">
                <p>Inovasi teknologi dari Gmedia untuk menciptakan pengalaman streaming tanpa lemot dengan bandwidth up to 100 Mbps.</p>
              </div>

            </div>
            <div class="col-sm">
              <div class="fiberstream d-flex justify-content-center " style="margin-bottom: 30px">
                <div class="align-items-center d-flex justify-content-center"
                  style="width: 100px; height: 100px; background: linear-gradient(75deg, rgba(204,72,156,1) 0%, rgba(93,51,213,1) 100%); border-radius: 50%;">
                  <img src="~/assets/img/svg/4.svg">
                </div>

              </div>
              <div class="titleLayanan">
                <h2>Akses Kuota Konten Tidak Terbatas</h2>

              </div>
              <div class="excerptLayanan" style="margin-top: 20px;">
                <p >Nikmati streaming kekinian tanpa batasan kuota dan akses konten. Paling nyaman sambil rebahan, nonton entertainment Streaming Film</p>
              </div>

            </div>
            <div class="col-sm">
              <div class="fiberstream d-flex justify-content-center " style="margin-bottom: 30px">
                <div class="align-items-center d-flex justify-content-center"
                  style="width: 100px; height: 100px; background: linear-gradient(75deg, rgba(204,72,156,1) 0%, rgba(93,51,213,1) 100%); border-radius: 50%;">
                  <img src="~/assets/img/svg/5.svg">
                </div>

              </div>
              <div class="titleLayanan">
                <h2>Saluran Streaming TV IP</h2>

              </div>
              <div class="excerptLayanan" style="margin-top: 20px;">
                <p>Tayangan TV Lokal dan puluhan Premium Channel dengan kualitas gambar terbaik.</p>
              </div>

            </div>
            <div class="col-sm">
              <div class="fiberstream d-flex justify-content-center " style="margin-bottom: 30px">
                <div class="align-items-center d-flex justify-content-center"
                  style="width: 100px; height: 100px; background: linear-gradient(75deg, rgba(204,72,156,1) 0%, rgba(93,51,213,1) 100%); border-radius: 50%;">
                  <img src="~/assets/img/svg/6.svg">
                </div>

              </div>
              <div class="titleLayanan">
                <h2>Layanan 24 Jam</h2>

              </div>
              <div class="excerptLayanan" style="margin-top: 20px;">
                <p>We serve you 24/7. Tim Helpdesk selalu standby dalam monitoring kualitas internet dan menangani kesulitan pelanggan.</p>
              </div>

            </div>

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
.layanan {
  width: 100%;
  height: 647px;
  background-color: #f5f5f5;
}

.titleLayanan h2 {
  font-size: 17px;
  font-style: normal;
  font-weight: 600;
  font-size: 17px;
  line-height: 28px;
}

.excerptLayanan p {
  font-size: 13px;
  font-style: normal;
  font-weight: 400;
  
  line-height: 24px;
}



@media (min-width: 320px) and (max-width: 767px) {
  .layanan {
    height: auto;
    padding: 0 39px 0 39px;
  }

  .layanan h1 {
    font-style: normal;
    font-weight: 600;
    font-size: 19px;
    margin-top: -50px;
    line-height: 20px;
  }

  .titleLayanan h2 {
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    line-height: 28px;
  }

  .excerptLayanan p {
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
  }

  .fiberstream {
    margin-top: 70px;
  }
}
</style>