<template>
  <div>
    <div id="carouselExampleControls" class="carousel slide d-none d-md-block" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">

          <div class="container">
            <div class="row">
              <div class="title  col-9">
                <h1>Nonton Film Action Sampai Gregetan #UdahPasti Lancar Gak Pakai Jeda <br> ditengah Adegan</h1>

              </div>
              <div class="excerpt col-9">

                <p>Fiberstream adalah internet broadband terbaik untuk kebutuhan internet rumah yang menggunakan
                  media Fiber Optic dengan jaminan kecepatan internet stabil dan kualitas layanan yang dapat
                  diandalkan.</p>


              </div>

              <div class="button">
                <button>Get me to offer</button>
              </div>

            </div>
          </div>
        </div>
        <div class="carousel-item">

          <div class="container">
            <div class="row">
              <div class="title  col-9 col-xs-12">
                <h1>Nonton Film Action Sampai Gregetan #UdahPasti Lancar Gak Pakai Jeda <br> ditengah Adegan</h1>

              </div>
              <div class="excerpt col-9 col-sx-12">

                <p>Fiberstream adalah internet broadband terbaik untuk kebutuhan internet rumah yang menggunakan
                  media Fiber Optic dengan jaminan kecepatan internet stabil dan kualitas layanan yang dapat
                  diandalkan.</p>


              </div>

              <div class="button">
                <button>Get me to offer</button>
              </div>

            </div>
          </div>
        </div>

      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls"
        data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls"
        data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

    <div id="carouselExampleControlsMobile" class="carousel slide d-block d-md-none" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleControlsMobile" data-bs-slide-to="0" class="active"
          aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleControlsMobile" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleControlsMobile" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">

          <div class="">
            <div class="row">
              <div class="title  col-9"  style="padding:0 !important">
                <h1>Nonton Film Action Sampai Gregetan #UdahPasti Lancar Gak Pakai Jeda <br> ditengah Adegan</h1>

              </div>
              <div class="excerpt col-9" style="padding:0 !important">

                <p>Fiberstream adalah internet broadband terbaik untuk kebutuhan internet rumah yang menggunakan
                  media Fiber Optic dengan jaminan kecepatan internet stabil dan kualitas layanan yang dapat
                  diandalkan.</p>


              </div>

              <div class="button">
                <button>Get me to offer</button>
              </div>

            </div>
          </div>
        </div>
        <div class="carousel-item">

          <div class="">
            <div class="row">
              <div class="title  col-9"  style="padding:0 !important">
                <h1>Nonton Film Action Sampai Gregetan #UdahPasti Lancar Gak Pakai Jeda <br> ditengah Adegan</h1>

              </div>
              <div class="excerpt col-9" style="padding:0 !important">

                <p>Fiberstream adalah internet broadband terbaik untuk kebutuhan internet rumah yang menggunakan
                  media Fiber Optic dengan jaminan kecepatan internet stabil dan kualitas layanan yang dapat
                  diandalkan.</p>


              </div>

              <div class="button">
                <button>Get me to offer</button>
              </div>

            </div>
          </div>
        </div>
        


      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControlsMobile"
        data-bs-slide="prev">
        <span class="visually-hidden carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControlsMobile"
        data-bs-slide="next">
        <span class="visually-hidden carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style>
.carousel {
  padding-top: 100px;
}

.carousel-item {
  height: 78vh;

}

.carousel-control-prev-icon {
  background-image: url("~/assets/img/svg/circle_chevron_left.svg");
  width: 40px;
  height: 40px;
  margin-top: -100px;
  filter: invert(100%) sepia(0%) saturate(0%) hue-rotate(0deg) brightness(103%) contrast(103%);
}

.carousel-control-next-icon {
  background-image: url("~/assets/img/svg/circle_chevron_right.svg");
  width: 40px;
  height: 40px;
  margin-top: -100px;
  filter: invert(100%) sepia(0%) saturate(0%) hue-rotate(93deg) brightness(103%) contrast(103%);
}


@media (min-width: 320px) and (max-width: 767px) {

  .carousel {
    margin-top: -50px
  }

  .carousel-control-prev-icon,
  .carousel-control-next-icon {
    margin: 0;

  }
  .button{
    padding-top: 60px;
  }


}
</style>