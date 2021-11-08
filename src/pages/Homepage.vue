<template>
  <Navbar />
  <Header />
  <!-- Content 1 -->
  <div class="container">
    <div class="heading text-center text-black text-8xl py-5">
      <h1>How To Work ?</h1>
    </div>
    <div class="row flex">
      <div class="col-content w-1/2 pt-20">
        <img src="../assets/image/onlineshop.png" alt="" />
      </div>
      <div class="col w-1/2 pt-72">
        <h1 class="text-green-400 text-xl font-bold">#1 Hal yang dilakukan pertama kali</h1>
        <h1 class="text-black font-bold text-6xl pt-6">Pembeli Memilih Pesanan</h1>
        <h1 class="text-gray-600 text-4xl pt-6 p-leading">Pembeli memilih pesanan di Facebook kemudian mulai menghubungi admin grup</h1>
      </div>
    </div>
  </div>

  <!-- Content 2 -->
  <div class="heading">
    <div class="row flex">
      <div class="col w-1/2 pt-72 pl-11 pr-11">
        <h1 class="text-green-400 text-xl font-bold">#2 Hal yang dilakukan penjual</h1>
        <h1 class="text-black font-bold text-6xl pt-6">Memasukkan Detail Pesanan</h1>
        <h1 class="text-gray-600 text-4xl pt-6 p-leading">Setelah mendapatkan kabar dari admin grup, maka penjual membuat detail pesanan pembeli</h1>
      </div>
      <div class="col-content w-1/2 pt-20">
        <img src="../assets/image/invoice.png" alt="" />
      </div>
    </div>
  </div>

  <!-- Content 3  -->
  <div class="container">
    <div class="row flex">
      <div class="col-content w-1/2 pt-20 pl-11">
        <img src="../assets/image/card-order.png" alt="" />
      </div>
      <div class="col w-1/2 pt-72">
        <h1 class="text-green-400 text-xl font-bold">#3 Pembeli melanjutkan pesanan</h1>
        <h1 class="text-black font-bold text-6xl pt-6">Membayar Pesanan</h1>
        <h1 class="text-gray-600 text-3xl pt-6">Detail pesanan telah selesai dan dapat dilanjutkan ke proses pembayaran</h1>
      </div>
    </div>
  </div>

  <!-- Content 4 -->
  <div>
    <div class="row flex">
      <div class="col w-1/2 pt-72 pl-11">
        <h1 class="text-green-400 text-xl font-bold">#4 Paket dalam perjalanan</h1>
        <h1 class="text-black font-bold text-6xl pt-6">Penjual Mengirim Pesanan</h1>
        <h1 class="text-gray-600 text-3xl pt-6">Pembayaran terkonfirmasi dan pesananpun dikirimkan oleh penjual</h1>
      </div>
      <div class="col-content w-1/2 pt-20">
        <img src="../assets/image/paket.png" alt="" />
      </div>
    </div>
  </div>

  <!-- Content 5 -->
  <div>
    <div class="row flex">
      <div class="col-content w-1/2 pt-20 pl-11">
        <img src="../assets/image/friends.png" alt="" />
      </div>
      <div class="col w-1/2 pt-72 pl-11">
        <h1 class="text-green-400 text-xl font-bold">#5 Barangpun sampai</h1>
        <h1 class="text-black font-bold text-6xl pt-6">Pembeli Menerima Barang</h1>
        <h1 class="text-gray-600 text-3xl pt-6">Setelah pembeli mengkonfirmasi menerima barang uangpun dikirimkan kepada penjual</h1>
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

<style>
.col-content img {
  height: 750px;
}
</style>
