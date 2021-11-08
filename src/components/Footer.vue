<template>
  <!-- FAQ -->

  <!-- Daftar -->
  <div class="footer bg-green-500 text-center">
    <h1 class="heading text-white font-extrabold text-6xl pt-48">Mulai Bisnis Anda Sekarang</h1>
    <h2 class="small-heading text-gray-200 text-3xl pt-1">Daftar sekarang juga</h2>
    <button class="bg-white hover:bg-gray-100 text-green-500 font-semibold py-3 px-10 mt-8 border border-gray-400 rounded shadow">Daftar</button>
  </div>
  <!-- Contact -->
  <div class="footer-list w-1/2 mx-auto pt-16">
    <ul class="flex justify-between">
      <li>
        <a href="#">Bantuan</a>
      </li>
      <li>
        <a href="#">Tutorial</a>
      </li>
      <li>
        <a href="#">Daftar</a>
      </li>
      <li>
        <a href="#">Syarat & Ketentuan</a>
      </li>
      <li>
        <a href="#">Kebijakan Privasi</a>
      </li>
    </ul>
    <div class="container social mx-auto py-12">
      <div class="image flex justify-around mx-3.5">
        <a href="">
          <img src="../assets/image/IG.png" alt="" />
        </a>
        <a href="">
          <img src="../assets/image/Twitter.png" alt="" />
        </a>
        <a href="">
          <img src="../assets/image/WA.png" alt="" />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.footer {
  height: 517px;
  border-radius: 20px;
}

.image a img {
  height: 40px;
}

.social {
  width: 50%;
}
</style>
