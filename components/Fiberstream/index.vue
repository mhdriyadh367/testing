<template>
  <div style="width: 100%; background-color: #fff;">
    <section class="aboutFiberstream">
      <div class="container">
        <div class="row" style="padding-top: 80px; color: #303030;">
          <div class=" col-sm-12 col-md-6 d-flex flex-column justify-content-md-center align-items-start ">
            <div class="checkFibers">
              <p>Check what we can do for your Internet</p>
            </div>

            <div class="titleFibers">
              <h4>Fiberstream</h4>
            </div>

            <div class="excerptFibers">
              <p>Fiberstream adalah
                internet broadband terbaik untuk kebutuhan internet rumah yang menggunakan media
                Fiber Optic dengan jaminan kecepatan internet stabil dan kualitas layanan yang dapat diandalkan.</p>
            </div>

            <div class="descript">
              <p>You will gain all
                our knowledge onboard.</p>
              <p>Cek lebih langsung
                tentang kita</p>
            </div>


            <div>
              <button class="btnTentang">
                Tentang Fiberstream
              </button>


            </div>

          </div>

          <div class=" col-sm-12 col-md-6 d-flex  justify-content-md-end justify-content-sm-center align-items-center">
            <div class="bgKanan">
              <img src="~/assets/img/bg1.png" alt="">
            </div>
          </div>
        </div>







        <div class="row" style="padding-top: 60px; color: #303030;">
          <div class="col-sm-12 col-md-6  d-flex justify-content-start align-items-center">
            <div class="bgKiri">
              <img src="~/assets/img/bg2.png" alt="bgKiri">
            </div>
          </div>
          <div class="col-sm-12 col-md-6 d-flex flex-column justify-content-end align-items-start ">
            <div class="mengapaFibers">
              <p>Check what we can do for your Internet</p>
            </div>

            <div class="titleMengapa">
              <h4>Mengapa Fiberstream
              </h4>
            </div>

            <div class="excerptMengapa">
              <p>Keunggulan yang
                tidak dimiliki oleh produk lain adalah jaringan Fiberstream dirancang khusus dengan teknologi terkini
                untuk memprioritaskan traffic streaming. Dengan internet unlimited tanpa FUP, membuat Fiberstream cocok
                di
                segala aktifitas</p>
            </div>

            <div class="descript">
              <p>You will gain all
                our experience onboard.</p>
              <p>Cek harga paket
                layanan internet kita Fiberstream.
              </p>
            </div>



            <div>
              <button class="btnPaket">Cek Paket</button>
            </div>



          </div>

        </div>






      </div>

    </section>
  </div>
</template>

<style>
.descript {
  margin-top: 20px;
}

.descript p {
  font-style: normal;
  font-weight: 400;
  font-size: 17px;
  line-height: 26px;
}

.btnPaket {
  margin-top: 50px;
  width: 207px;
  height: 50px;
  background: linear-gradient(137.77deg, #B61AAE 0%, #590D82 258.61%);
  border-radius: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
  border: none;
  color: #fff;
}

.excerptMengapa {
  margin-top: 20px;
  width: 100%;
}

.excerptMengapa p {
  font-style: normal;
  font-weight: 400;
  font-size: 17px;
  line-height: 28px;
}

.titleMengapa {
  margin-top: 20px;
}

.titleMengapa h4 {
  font-style: normal;
  font-weight: 600;
  font-size: 34px;
  line-height: 51px;
}

.btnTentang {
  margin-top: 50px;
  width: 302px;
  height: 50px;
  background: linear-gradient(137.77deg, #B61AAE 0%, #590D82 258.61%);
  border-radius: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
  border: none;
  color: #fff;
  font-style: normal;
  font-weight: 600;
  font-size: 17px;
  line-height: 21px;
}

.checkFibers p {
  font-style: normal;
  font-weight: 600;
  font-size: 17px;
  line-height: 26px;
}

.mengapaFibers p {
  font-style: normal;
  font-weight: 600;
  font-size: 17px;
  line-height: 26px;
}

.titleFibers {
  margin-top: 20px;
}

.titleFibers h4 {
  font-style: normal;
  font-weight: 600;
  font-size: 34px;
  line-height: 51px;
}

.bgKanan img,
.bgKiri img {
  width: auto;
  height: 500px;
}

.excerptFibers {
  margin-top: 20px;
  width: 90%;
}

.excerptFibers p {
  font-style: normal;
  font-weight: 400;
  font-size: 17px;
  line-height: 28px;
}

@media (min-width: 320px) and (max-width: 767px) {

  .aboutFiberstream {
    height: auto;
    padding: 0 20px 0 20px;
    position: relative;
  }

  .checkFibers p {
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 20px;
    width: 80%;
    color: #590D82;
    margin-top: 250px;
  }

  .bgKanan img {
    width: 320px;
    height: 320px;
    position: absolute;
    top: 0;
  }

  .bgKiri img {
    width: 320px;
    height: 320px;
  }

  .titleFibers h4 {
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    line-height: 28px;
    margin-top: -30px;
  }

  .excerptFibers {
    width: 100%;

  }

  .excerptFibers p {
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;

  }

  .btnTentang {
    width: 200px;
    height: 45px;
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 21px;
    margin-top: -5px
  }

  .btnPaket {
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 21px;
    width: 200px;
    height: 45px;
  }


  .mengapaFibers p {
    margin-top: 30px;
    width: 80%;
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 20px;
    color: #590D82;
  }

  .titleMengapa h4 {
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    line-height: 28px;
    margin-top: -25px;
  }

  .excerptMengapa p {
    font-style: normal;
    margin-top: -15px;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
  }

  .descript {
    margin-top: -5px;
  }
  .descript p {
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    
  }
}
</style>