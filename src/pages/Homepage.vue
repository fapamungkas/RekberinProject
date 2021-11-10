<template>
  <Navbar />
  <Header />
  <!-- Content 1 -->
  <div class="container">
    <div class="heading text-center text-black md:text-8xl text-5xl font-bold pt-16">
      <h1>How To Work ?</h1>
    </div>
    <div class="row md:flex">
      <div class="col-content md:w-1/2 md:pt-20 pt-12">
        <img class="online-img" src="../assets/image/onlineshop.png" alt="" />
      </div>
      <div class="col md:w-1/2 md:pt-52 pt-16 pl-3">
        <h1 class="text-green-700 text-xl font-bold">#1 Hal yang dilakukan pertama kali</h1>
        <h1 class="text-black font-bold md:text-6xl text-3xl md:pt-6 pt-4">Pembeli Memilih Pesanan</h1>
        <h1 class="text-gray-600 md:text-4xl text-lg md:pt-6 pt-2 md:p-leading">Pembeli memilih pesanan di Facebook kemudian mulai menghubungi admin grup</h1>
      </div>
    </div>
  </div>

  <!-- Content 2 -->
  <div class="heading">
    <div class="row md:flex">
      <div class="col md:w-1/2 md:pt-52 pt-36 md:pl-11 pl-3 md:pr-11">
        <h1 class="text-green-700 text-xl font-bold">#2 Hal yang dilakukan penjual</h1>
        <h1 class="text-black font-bold md:text-6xl text-3xl md:pt-6 pt-4">Memasukkan Detail Pesanan</h1>
        <h1 class="text-gray-600 md:text-4xl text-lg md:pt-6 pt-2 md:p-leading">Setelah mendapatkan kabar dari admin grup, maka penjual membuat detail pesanan pembeli</h1>
      </div>
      <div class="col-content md:w-1/2 md:pt-20 pt-3">
        <img src="../assets/image/invoice.png" alt="" />
      </div>
    </div>
  </div>

  <!-- Content 3  -->
  <div class="container">
    <div class="row md:flex">
      <div class="col-content md:w-1/2 pt-20">
        <img src="../assets/image/card-order.png" alt="" />
      </div>
      <div class="col md:w-1/2 md:pt-72 pt-16 pl-3">
        <h1 class="text-green-700 text-xl font-bold">#3 Pembeli melanjutkan pesanan</h1>
        <h1 class="text-black font-bold md:text-6xl text-3xl md:pt-6 pt-4">Membayar Pesanan</h1>
        <h1 class="text-gray-600 md:text-4xl text-lg md:pt-6 pt-2 md:p-leading">Detail pesanan telah selesai dan dapat dilanjutkan ke proses pembayaran</h1>
      </div>
    </div>
  </div>

  <!-- Content 4 -->
  <div>
    <div class="row md:flex">
      <div class="col md:w-1/2 md:pt-52 pt-36 md:pl-11 pl-3 md:pr-11">
        <h1 class="text-green-700 text-xl font-bold">#4 Paket dalam perjalanan</h1>
        <h1 class="text-black font-bold md:text-6xl text-3xl md:pt-6 pt-4">Penjual Mengirim Pesanan</h1>
        <h1 class="text-gray-600 md:text-4xl text-lg md:pt-6 pt-2">Pembayaran terkonfirmasi dan pesananpun dikirimkan oleh penjual</h1>
      </div>
      <div class="col-content md:w-1/2 md:pt-20">
        <img src="../assets/image/paket.png" alt="" />
      </div>
    </div>
  </div>

  <!-- Content 5 -->
  <div>
    <div class="row md:flex">
      <div class="col-content md:w-1/2 pt-20">
        <img src="../assets/image/friends.png" alt="" />
      </div>
      <div class="col md:w-1/2 md:pt-72 md:pl-11 pl-3">
        <h1 class="text-green-700 text-xl font-bold">#5 Barangpun sampai</h1>
        <h1 class="text-black font-bold md:text-6xl text-3xl md:pt-6 pt-4">Pembeli Menerima Barang</h1>
        <h1 class="text-gray-600 md:text-4xl text-lg md:pt-6 pt-2 pb-20">Setelah pembeli mengkonfirmasi menerima barang uangpun dikirimkan kepada penjual</h1>
      </div>
    </div>
  </div>

  <Footer />
</template>

<script>
// Import Navbar Component
import Navbar from "../components/Navbar.vue";

// Import Header Component
import Header from "../components/Header.vue";

// Import Footer Component
import Footer from "../components/Footer.vue";

export default {
  components: {
    Navbar,
    Header,
    Footer,
  },
};
</script>

<style></style>
