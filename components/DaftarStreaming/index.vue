<template>
  <div>
    <section class="daftarStreaming">
      <div>

        <div class="container text-center text-white">
          <div class="titleStreaming">
            <h1>
              Daftar aplikasi streaming</h1>

          </div>
        </div>

        <div style="margin-top: -100px;">
          <div id="carouselExampleIndicators" class="carousel slide d-none d-md-block" data-bs-ride="carousel">
            <div class="carousel-indicators">
              <button style="margin-top: -100px;" type="button" data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
              <button style="margin-top: -100px;" type="button" data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="1" aria-label="Slide 2"></button>
              <button style="margin-top: -100px;" type="button" data-bs-target="#carouselExampleIndicators"
                data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <div class="container d-flex justify-content-center px-5" style="margin-top: 188px;">
                  <img style="margin-right: 80px;" src="~/assets/img/svg/yt.svg" class="yt" alt="...">
                  <img style="margin-right: 80px;" src="~/assets/img/svg/yt.svg" class="" alt="...">
                  <img style="margin-right: 80px;" src="~/assets/img/svg/yt.svg" class="" alt="...">
                  <img style="margin-right: 80px;" src="~/assets/img/svg/yt.svg" class="" alt="...">
                  <img style="margin-right: 80px;" src="~/assets/img/svg/yt.svg" class="" alt="...">
                  <img src="~/assets/img/svg/yt.svg" class="" alt="...">
                </div>
              </div>
              <div class="carousel-item">
                <div class="container d-flex justify-content-center px-5" style="margin-top: 188px;">
                  <img style="margin-right: 80px;" src="~/assets/img/svg/pv.svg" class="" alt="...">
                  <img style="margin-right: 80px;" src="~/assets/img/svg/pv.svg" class="" alt="...">
                  <img style="margin-right: 80px;" src="~/assets/img/svg/pv.svg" class="" alt="...">
                  <img style="margin-right: 80px;" src="~/assets/img/svg/pv.svg" class="" alt="...">
                  <img style="margin-right: 80px;" src="~/assets/img/svg/pv.svg" class="" alt="...">
                  <img src="~/assets/img/svg/pv.svg" class="" alt="...">
                </div>
              </div>

              <!-- <div class="carousel-item">
        <img src="~/assets/img/svg/yt.svg" class="" alt="...">
        <img src="~/assets/img/svg/yt.svg" class="" alt="...">
        <img src="~/assets/img/svg/yt.svg" class="" alt="...">
      </div>
      <div class="carousel-item">
        <img src="~/assets/img/svg/yt.svg" class="" alt="...">
      </div> -->
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
              data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
              data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>


        </div>

        <div>
          <div id="carouselExampleDark" class="mobileCarousel carousel slide d-block d-md-none" data-bs-ride="carousel">
            <div class="carousel-indicators">
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active"
                aria-current="true" aria-label="Slide 1" style="width: 18px; height: 8px;border-radius: 30px;" ></button>
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1"
                aria-label="Slide 2" style="width: 18px; height: 8px;border-radius: 30px;"></button>
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2"
                aria-label="Slide 3" style="width: 18px; height: 8px;border-radius: 30px;"></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active" data-bs-interval="10000">
                <div class="container d-flex justify-content-center px-5" style="margin-top: 188px;">
                  <img src="~/assets/img/svg/yt.svg" class="d-block" alt="..." style="width: 180px; height: 37px;">
                </div>

              </div>
              <div class="carousel-item" data-bs-interval="10000">
                <div class="container d-flex justify-content-center px-5" style="margin-top: 188px;">
                  <img src="~/assets/img/svg/pv.svg" class="d-block" alt="..." style="width: 180px; height: 37px;">
                </div>

              </div>


            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark"
              data-bs-slide="prev">
              <span class=" visually-hidden carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark"
              data-bs-slide="next">
              <span class="visually-hidden carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
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
.daftarStreaming {
  margin-top: 100px;
  width: 100%;
  background: linear-gradient(90deg, rgba(204, 72, 156, 1) 0%, rgba(93, 51, 213, 1) 100%);
}

.titleStreaming {
  padding-top: 80px;

}

.titleStreaming h1 {
  font-style: normal;
  font-weight: 600;
  font-size: 38px;
  line-height: 57px;
}

.carousel {
  padding-top: 0;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* .carousel-item img{
  background-color: #303030;
  padding: 
} */

@media (min-width: 320px) and (max-width: 767px) {
  .titleStreaming h1 {
    font-style: normal;
    font-weight: 600;
    font-size: 20px;
    line-height: 28px;
    margin-top: -30px;
    margin-bottom: 25px;
  }

  .daftarStreaming {
    height: 400px;
    width: auto;
  }

  .carousel-control-prev-icon {
    overflow: hidden;
  }

  .mobileCarousel {
    margin-top: -120px;
    height: 370px;
  }

}
</style>