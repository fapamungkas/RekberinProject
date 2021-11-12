<template>
  <!-- About Us -->
  <div class="container">
    <header>
      <div style="">
        <img class="img-about w-full" src="../assets/image/img-rectangle.png" alt="" />
      </div>
      <div class="about bg-green-700">
        <h1 class="heading md:text-8xl text-4xl text-center pt-14 md:pt-24 text-white font-bold">About Us</h1>
        <p class="leading md:text-2xl md:px-20 pt-9 pb-24 px-10 text-center text-white font-semibold">
          Rekberin adalah fitur yang akan memudahkan anda untuk transaksi dengan aman dan tanpa khawatir dengan biaya admin jika mengirim uang beda bank. Tujuan kami adalah menjadi platform nomor satu di Facebook dalam transaksi jual beli
          dan memberikan kepercayaan.
        </p>
      </div>
      <!-- Fitur -->
      <div>
        <div class="row flex flex-col md:flex-row">
          <div class="col md:w-1/2">
            <h1 class="heading-satu md:text-8xl text-5xl md:text-gray-600 font-bold pt-14 md:pl-11 pl-28">Feature</h1>
            <h1 class="heading-dua font-bold md:text-5xl text-3xl text-black pt-12 pl-11">Rekberin menunjang dalam bisnis anda</h1>
            <p class="paragraf text-black md:text-3xl md:pt-11 pt-6 pl-11">Kami akan membantu anda dengan berbagai fitur yang kami berikan</p>
            <div class="list text-green-700 pt-7 pl-11 leading-7 font-bold">
              <div class="img flex md:text-2xl">
                <img class="img-space pr-2 md:h-9 h-6" src="../assets/image/Frame.png" alt="" />
                <p>Pelayanan 24 Jam</p>
              </div>
              <div class="img flex md:text-2xl">
                <img class="img-space pr-2 md:h-9 h-6" src="../assets/image/Frame.png" alt="" />
                <p>Laporan Secara Real-Time</p>
              </div>
              <div class="img flex md:text-2xl">
                <img class="img-space pr-2 md:h-9 h-6" src="../assets/image/Frame.png" alt="" />
                <p>Keamanan Dalam Transaksi</p>
              </div>
              <div class="img flex md:text-2xl">
                <img class="img-space pr-2 md:h-9 h-6" src="../assets/image/Frame.png" alt="" />
                <p>Kode Unik Berbeda</p>
              </div>
            </div>
          </div>
          <div class="col img-space md:space-img flex md:w-1/2 md:bg-green-700 pb-20 pt-20">
            <!-- <div class="layer md:max-w-sm bg-white h-7"></div> -->
            <img class="md:-ml-10 ml-10" src="../assets/image/grafix.png" alt="" />
          </div>
        </div>
      </div>
      <!-- Manfaat -->
      <div>
        <h1 class="heading text-center text-gray-800 text-5xl md:text-7xl font-bold md:pt-20">Manfaat</h1>
        <div class="row flex justify-center space-x-3 md:space-x-12 text-green-700 md:text-2xl font-semibold py-12">
          <div class="col benefit-item">
            <img class="mx-auto pb-3 md:h-24 h-20" src="../assets/image/Delivery.png" alt="" />
            <p class="text-sm md:text-xl">Transaksi Cepat</p>
          </div>
          <div class="col benefit-item md:h-24">
            <img class="mx-auto pb-3 md:h-24 h-20" src="../assets/image/Shopping.png" alt="" />
            <p class="text-sm md:text-xl">Mulai Berbelanja</p>
          </div>
          <div class="col benefit-item md:h-24">
            <img class="mx-auto pb-3 md:h-24 h-20" src="../assets/image/Money.png" alt="" />
            <p class="text-sm md:text-xl">Gratis Biaya Admin</p>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {};
</script>

<style>
.heading-satu {
  color: #4d4d4d;
}

/* .benefit-item img {
  height: 100px;
} */

/* .img img {
  height: 36px;
} */

.space-img img {
  position: absolute;
  z-index: 2;
  right: 0;
  width: 600px;
  margin-left: -180px;
  margin-top: 80px;
}

.layer {
  width: 170px;
  height: 100%;
}

.space-img .layer {
  height: 42rem;
  height: 20rem;
}

@media screen and (max-width: 768px) {
  .img-space img {
    width: 400px;
    padding-right: 35px;
  }
}
</style>
