<template>
  <div style="padding-top: 50px;">
    <section>
      <div class="footer">
        <div class="container">

          <!-- Desktop -->
          <div class="footerDesktop d-none d-md-block">
            <div class="row" style="padding: 100px 0 0 0; ">
              <div class="col-sm-6">
                <div class="logoFoter">
                  <img src="~/assets/img/logoFooter.png" alt="" style="width: 254px; height: 73px;">
                </div>
                <div class="alamat">
                  <span>
                    Jl. Siliwangi No.32G, Area Sawah, Nogotirto, Kec. Gamping, Kabupaten Sleman, Daerah Istimewa
                    Yogyakarta
                    55592
                  </span>
                </div>
                <p
                  style="font-style: normal; font-weight: 500; font-size: 17px; line-height: 26px; color: #fff; margin-top: 20px;">
                  (0274) 380345</p>


                <div class="sosmedIcon d-flex flex-row">

                  <div class="fbIcon"
                    style="display: flex;align-items: center; justify-content: center; margin-right: 20px;">
                    <div>
                      <img src="~/assets/img/svg/sosmed/fb.svg" alt="">
                    </div>


                  </div>
                  <div class="waIcon"
                    style="display: flex;align-items: center; justify-content: center; margin-right: 20px;">
                    <div>
                      <img src="~/assets/img/svg/sosmed/wa.svg" alt="">
                    </div>


                  </div>
                  <div class="igIcon"
                    style="display: flex;align-items: center; justify-content: center; margin-right: 20px;">
                    <div>
                      <img src="~/assets/img/svg/sosmed/ig.svg" alt="">
                    </div>


                  </div>
                  <div class="igIcon"
                    style="display: flex;align-items: center; justify-content: center; margin-right: 20px;">
                    <div>
                      <img src="~/assets/img/svg/sosmed/twitter.svg" alt="">
                    </div>


                  </div>


                </div>



              </div>

              <div class="jelajahi col-sm-3">
                <ul class="d-flex flex-column">
                  <span>Jelajahi</span>
                  <NuxtLink to="/">
                    <li class="nav-item">Beranda</li>

                  </NuxtLink>
                  <li class="nav-item">Layanan</li>
                  <li class="nav-item">Paket</li>
                  <li class="nav-item">Daftar Sekarang</li>
                </ul>
              </div>
              <div class="bantuan col-sm-3">
                <ul class="d-flex flex-column">
                  <span>Dukungan</span>
                  <li class="nav-item">Cara Pembayaran</li>
                  <NuxtLink to="/syarat-ketentuan">
                    <li class="nav-item">Syarat dan Ketentuan</li>

                  </NuxtLink>
                  <NuxtLink to="/faq">
                    <li class="nav-item">FAQ</li>

                  </NuxtLink>

                </ul>
              </div>

            </div>


            <div class="row" style="padding: 0;">
              <div class="col-sm-12">
                <div class="copyright d-flex justify-content-between ">
                  <div>
                    <p>©2021 Fiberstream All Rights Reserved</p>
                  </div>

                  <div class="d-flex flex-row align-items-center">
                    <p>Terms</p>
                    <p style="margin-left: 50px;">Privacy</p>
                    <p style="margin-left: 50px;">Site Map</p>
                  </div>

                </div>
              </div>
            </div>

          </div>

          <!-- Mobile -->
          <div class="footerMobile d-block d-md-none">

            <div class="row">
              <div class="col-12">
                <div class="jelajahiMobile">
                  <ul style="padding: 0; ">
                    <span>Jelajahi</span>
                    <NuxtLink to="/">
                      <li class="nav-item">Beranda</li>

                    </NuxtLink>
                    <li class="nav-item">Layanan</li>
                    <li class="nav-item">Paket</li>
                    <li class="nav-item">Daftar Sekarang</li>
                  </ul>
                </div>
              </div>
            </div>
            <div>
              <div class="col-12">
                <div class="dukunganMobile">
                  <ul style="padding: 0; ">
                    <span>Dukungan</span>

                    <li class="nav-item">Cara Pembayaran</li>
                    <li class="nav-item">Syarat dan Ketentuan</li>
                    <li class="nav-item">FAQ</li>
                  </ul>
                </div>
              </div>

              <div class="logoFooterMobile">
                <img src="~/assets/img/logoFooter.png" alt="" style="width: 153px; height: 44px;">
              </div>

              <div class="alamatMobile">
                <span>
                  Jl. Siliwangi No.32G, Area Sawah, Nogotirto, Kec. Gamping, Kabupaten Sleman, Daerah Istimewa
                  Yogyakarta
                  55592
                </span>
              </div>

              <div class="contactMobile">
                <p>(0274) 380345</p>
              </div>


              <div class="sosmedIconMobile d-flex flex-row">

                <div class="fbIcon"
                  style="display: flex;align-items: center; justify-content: center; margin-right: 20px;">
                  <div>
                    <img src="~/assets/img/svg/sosmed/fb.svg" alt="">
                  </div>


                </div>
                <div class="waIcon"
                  style="display: flex;align-items: center; justify-content: center; margin-right: 20px;">
                  <div>
                    <img src="~/assets/img/svg/sosmed/wa.svg" alt="">
                  </div>


                </div>
                <div class="igIcon"
                  style="display: flex;align-items: center; justify-content: center; margin-right: 20px;">
                  <div>
                    <img src="~/assets/img/svg/sosmed/ig.svg" alt="">
                  </div>


                </div>
                <div class="igIcon"
                  style="display: flex;align-items: center; justify-content: center; margin-right: 20px;">
                  <div>
                    <img src="~/assets/img/svg/sosmed/twitter.svg" alt="">
                  </div>


                </div>


              </div>




            </div>


            <div class="copyrightMobile">
              <h2>© 2021 Fiberstream All Rights Reserved</h2>
            </div>

            <div class="col-sm-12" style="padding-top: 30px; ">
              <div class="d-flex justify-content-center">
                <div style="margin-right: 20px;">
                  <p style="font-style: normal; font-weight: 400; font-size: 14px; line-height: 21px;">Terms</p>
                </div>
                <div style="margin-right: 20px;">
                  <p style="font-style: normal; font-weight: 400; font-size: 14px; line-height: 21px;">Privacy</p>
                </div>
                <div style="margin-right: 20px;">
                  <p style="font-style: normal; font-weight: 400; font-size: 14px; line-height: 21px;">Site Map</p>
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
.footer {
  width: 100%;
  height: 519px;
  background: linear-gradient(72deg, rgb(218, 61, 161) 0%, rgba(93, 51, 213, 1) 100%);
  color: #fff;

}



.jelajahi span,
.bantuan span {
  font-style: normal;
  font-weight: 600;
  font-size: 15px;
  line-height: 120%;
  margin-bottom: 40px;
}

.jelajahi li,
.bantuan li {
  list-style: none;
  margin-bottom: 30px;
}

.bantuan a,
.jelajahi a {
  text-decoration: none;
  color: #fff;
}

.alamat {
  width: 410px;
  padding-top: 20px
}

.alamat span {
  font-style: normal;
  font-weight: 500;
  font-size: 17px;
  line-height: 28px;
  color: #fff;

}

.fbIcon,
.waIcon,
.igIcon,
.twitterIcon {
  width: 40px;
  height: 40px;
  border-radius: 100px;
  border: 1px solid #FFFFFF;
}

.sosmedIcon {
  padding-top: 50px;
  padding-bottom: 25px;
}

.copyright {
  font-style: normal;
  font-weight: 300;
  font-size: 13px;
  line-height: 20px;
  color: #fff;
}








@media (min-width: 320px) and (max-width: 767px) {
  .footer {
    height: auto;
    padding: 0 20px 0 20px;
  }

  .jelajahiMobile {
    padding-top: 50px;
    padding-bottom: 30px;
  }

  .jelajahiMobile a,
  .dukunganMobile a {
    text-decoration: none;
    color: #fff;

  }

  .jelajahiMobile ul span,
  .dukunganMobile ul span {
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 21px;

  }

  .jelajahiMobile ul li,
  .dukunganMobile ul li {
    list-style: none;
  }

  .nav-item {
    margin-top: 10px;
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 21px;
  }

  .logoFooterMobile {
    padding-top: 30px;
  }

  .alamatMobile {
    width: 90%;
    padding-top: 20px;
    padding-bottom: 10px;
  }

  .alamatMobile span {
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 28px;
  }

  .contactMobile p {
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 21px;
  }

  .sosmedIconMobile {
    padding-top: 20px;
  }

  .copyrightMobile{
    padding-top: 70px;
  }
  .copyrightMobile h2 {
    font-style: normal;
    font-weight: 500;
    font-size: 13px;
    line-height: 20px;
    text-align: center;
  }


}
</style>