<template>
  <div>
    <section class="order">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="titleOrder">
              <h2>Pasang Fiberstream Sekarang</h2>
            </div>
          </div>
        </div>

        <div class="row" style="padding-top: 60px;">
          <div class="col-md-6">
            <div class="displayImg">
              <div class="petaOrder">
                <img src="~/assets/img/peta.png" alt="peta">
              </div>
            </div>
          </div>

          <div class="col-md-6 d-none d-md-block">

            <div class="d-flex justify-content-center">
              <div class="col">
                <div class="form-group">
                  <input type="text" class="form-control" placeholder="Nama Lengkap" />
                </div>
              </div>
              <div class="col">
                <div class="d-flex justify-content-end">


                  <div class="form-group">
                    <input type="email" class="form-control" placeholder="Email" />
                  </div>
                </div>
              </div>
            </div>

            <div class="d-flex justify-content-center" style="margin-top:30px">
              <div class="col">
                <select class="form-select" aria-label="Default select example">
                  <option selected>Paket</option>
                  <option value="1">One</option>
                  <option value="2">Two</option>
                  <option value="3">Three</option>
                </select>
              </div>
              <div class="col">
                <div class="d-flex justify-content-end">


                  <div class="form-group">
                    <input type="text" class="form-control" placeholder="No.Hp" />
                  </div>
                </div>
              </div>
            </div>
            <div class="d-flex justify-content-center" style="margin-top:30px">
              <div class="col">
                <select class="form-select" aria-label="Default select example">
                  <option selected>Provinsi</option>
                  <option value="1">One</option>
                  <option value="2">Two</option>
                  <option value="3">Three</option>
                </select>
              </div>
              <div class="col">
                <div class="d-flex justify-content-end">


                  <select class="form-select" aria-label="Default select example">
                    <option selected>Kota</option>
                    <option value="1">One</option>
                    <option value="2">Two</option>
                    <option value="3">Three</option>
                  </select>
                </div>
              </div>
            </div>
            <div class="d-flex justify-content-center" style="margin-top:30px">
              <div class="col">
                <select class="form-select" aria-label="Default select example">
                  <option selected>Kecamatan</option>
                  <option value="1">One</option>
                  <option value="2">Two</option>
                  <option value="3">Three</option>
                </select>
              </div>
              <div class="col">
                <div class="d-flex justify-content-end">


                  <div class="form-group">
                    <input type="text" class="form-control" placeholder="Alamat Lengkap" />
                  </div>
                </div>
              </div>
            </div>
            <div class="d-flex justify-content-center" style="margin-top:30px">
              <div class="col">
                <div class="form-group">
                  <input type="text" class="form-control" placeholder="Longitude" />
                </div>
              </div>
              <div class="col">
                <div class="d-flex justify-content-end">


                  <div class="form-group">
                    <input type="text" class="form-control" placeholder="Latitude" />
                  </div>
                </div>
              </div>
            </div>


            <div class="col-12 text-center" style="padding: 55px 0 150px 0; ">

              <div>
                <button class="btnKirim">Kirim</button>
              </div>

            </div>

          </div>

          <div class="col-sm-12 d-block d-md-none">
            <div class="row" style="padding-top: 30px;">
              <form>
                <div class="col-sm-12 " style="width: 100%;">

                  <div class="d-flex justify-content-center">
                    <div class="form-group">
                      <input type="text" class="form-control" placeholder="Nama Lengkap" />
                    </div>
                  </div>

                </div>
                <div class="col-sm-12 " style="width: 100%; margin-top: 15px;">

                  <div class="d-flex justify-content-center">
                    <div class="form-group">
                      <input type="email" class="form-control" placeholder="Email" />
                    </div>
                  </div>

                </div>
                <div class="col-sm-12 " style="width: 100%; margin-top: 15px;">

                  <div class="d-flex justify-content-center">
                    <div class="form-group">
                      <input type="text" class="form-control" placeholder="Nomor Telepon" />
                    </div>
                  </div>

                </div>
                <div class="col-sm-12 " style="width: 100%; margin-top: 15px;">

                  <div class="d-flex justify-content-center">
                    <div class="form-group">
                      <input type="text" class="form-control" placeholder="Provinsi" />
                    </div>
                  </div>

                </div>
                <div class="col-sm-12 " style="width: 100%; margin-top: 15px;">

                  <div class="d-flex justify-content-center">
                    <div class="form-group">
                      <input type="text" class="form-control" placeholder="Kota" />
                    </div>
                  </div>

                </div>
                <div class="col-sm-12 " style="width: 100%; margin-top: 15px;">

                  <div class="d-flex justify-content-center">
                    <div class="form-group">
                      <input type="text" class="form-control" placeholder="Kecamatan" />
                    </div>
                  </div>

                </div>
                <div class="col-sm-12 " style="width: 100%; margin-top: 15px;">

                  <div class="d-flex justify-content-center">
                    <div class="form-group">
                      <input type="text" class="form-control" placeholder="Alamat Lengkap" />
                    </div>
                  </div>

                </div>
                <div class="col-sm-12 " style="width: 100%; margin-top: 15px;">

                  <div class="d-flex justify-content-center">
                    <div class="form-group">
                      <input type="text" class="form-control" placeholder="Paket" />
                    </div>
                  </div>

                </div>
                <div class="col-sm-12 " style="width: 100%; margin-top: 15px;">

                  <div class="d-flex justify-content-center">
                    <div class="form-group">
                      <input type="text" class="form-control" placeholder="Longitude" />
                    </div>
                  </div>

                </div>
                <div class="col-sm-12 " style="width: 100%; margin-top: 15px;">

                  <div class="d-flex justify-content-center">
                    <div class="form-group">
                      <input type="text" class="form-control" placeholder="Latitude" />
                    </div>
                  </div>

                </div>


              </form>
            </div>

            <div class="row">
              <div class="col-sm-12">
                <div class="d-flex justify-content-center">
                  <div class="recaptcha">
                    <img src="~/assets/img/recaptcha.png" alt="">
                  </div>
                </div>
              </div>
            </div>

            <div class="row" style="padding-top: 30px;">
              <div class="col-sm-12">
                <div class="d-flex justify-content-center align-items-center">
                  <div>
                    <button class="btnKirimMobile">Kirim</button>
                  </div>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Desktop -->
        <div class="promotion d-none d-md-block">
          <div class="row">

            <div class="col-md-8 col-12">
              <div class="fiberLogo">
                <img src="~/assets/img/logo.png" alt="">

                <div class="titlePromo">
                  <h3>
                    Pasang Internet Unlimited Tanpa
                    Kuota Fiberstream. Unduh Fiberstream
                    Sekarang!
                  </h3>

                </div>

              </div>
              <div class="row" style="padding: 60px 0 0 70px;">
                <div class="col-4">
                  <div>
                    <img src="~/assets/img/svg/GooglePlay.svg" alt="">
                  </div>
                </div>
                <div class="col-4">
                  <div>
                    <img src="~/assets/img/svg/AppStore.svg" alt="">
                  </div>
                </div>

              </div>
            </div>
            <div class="col-sm-4" style="padding:40px 0 53px 0;  ">
              <div>
                <img style="width: 275.77px; height: 490px; float: right; margin-right: 40px;"
                  src="~/assets/img/mobile.png" alt="">
              </div>
            </div>

          </div>



        </div>

        <!-- Mobile -->
        <div class="promotionMobile d-block d-md-none">
          <div class="row">
            <div class="col-sm-12">
              <div class="d-flex justify-content-center">
                <div class="fiberLogoMobile">
                  <img src="~/assets/img/logo.png" alt="">

                </div>

              </div>
              <div class="d-flex justify-content-center">
                <div class="fiberMobile">
                  <img src="~/assets/img/mobile.png" alt="">
                </div>

              </div>

              <div class="fiberTitleMobile">
                <h3>
                  Pasang Internet Unlimited Tanpa
                  Kuota Fiberstream. Unduh Fiberstream
                  Sekarang!
                </h3>

              </div>

              <div class="row">

                <div class="col-6" >
                  <img src="~/assets/img/svg/GooglePlay.svg" alt="" style="width: 132px;height: 38px; float: right;">
                </div>
                <div class="col-6">
                  <img src="~/assets/img/svg/AppStore.svg" alt="" style="width: 132px;height: 38px;">
                </div>


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
.order {
  padding-top: 100px;

}

.titleOrder h2 {
  text-align: center;
}

.petaOrder img {
  width: 480px;
  height: 350px;
}

.form-group,
.form-select {
  width: 97%;
}

.form-control,
.form-select {
  height: 45px;
}

.btnKirim {
  width: 166px;
  height: 50px;
  background: linear-gradient(137.77deg, #B61AAE 0%, #590D82 258.61%);
  border: none;
  border-radius: 250px;
  color: #fff;
}

.promotion {
  width: 100%;
  height: 583px;
  background-color: #303030;
  border-radius: 30px;
  background: linear-gradient(72deg, rgb(218, 61, 161) 0%, rgba(93, 51, 213, 1) 100%);
}

.fiberLogo {
  padding: 60px 0 0 70px;
}

.fiberLogo img {

  width: 241px;
  height: 60px;
}

.titlePromo {
  width: 567px;
  padding-top: 60px;
}

.titlePromo h3 {
  font-style: normal;
  font-weight: 700;
  font-size: 28px;
  line-height: 42px;
  color: #fff;
}



@media (min-width: 320px) and (max-width: 767px) {
  .order {
    height: auto;
    padding: 0 20px 0 20px;
    padding-top: 50px;
  }

  .titleOrder h2 {
    text-align: center;
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    line-height: 28px;

  }

  .form-control {
    width: 100%
  }

  .displayImg {
    display: flex;
    justify-content: center;
  }

  .petaOrder img {
    width: 320px;
    height: 235px;
  }

  .recaptcha {
    padding-top: 15px;
  }

  .recaptcha img {
    width: 240px;
    height: 65px;
  }

  .btnKirimMobile {
    width: 320px;
    height: 35px;
    background: linear-gradient(137.77deg, #B61AAE 0%, #590D82 258.61%);
    border-radius: 300px;
    text-align: center;
    color: #fff;
    border: none;
    margin-bottom: 100px;
  }

  .promotionMobile {
    height: 705px;
    background: linear-gradient(72deg, rgb(218, 61, 161) 0%, rgba(93, 51, 213, 1) 100%);
    border-radius: 10px;
  }

  .fiberLogoMobile {
    padding-top: 40px;
  }

  .fiberLogoMobile img {
    width: 225px;
    height: 56px;

  }

  .fiberMobile {
    padding-top: 30px;
  }

  .fiberMobile img {
    width: 169px;
    height: 300px;
  }

  .fiberTitleMobile {
    padding: 30px 50px 30px 50px;
  }

  .fiberTitleMobile h3 {
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    line-height: 30px;
    color: #fff;
    text-align: center;
  }

  .googlePlayMobile img {
    width: 132px;
    height: 38px;
  }

}
</style>