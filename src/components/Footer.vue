<template>
  <!-- FAQ -->
  <div class="FAQ md:flex">
    <div class="row md:w-1/2 md:pl-11 pl-6 md:pr-32 pr-6">
      <h1 class="md:text-6xl text-5xl md:text-left text-center font-bold md:pb-8 pb-5">FAQ</h1>
      <p class="md:text-3xl text-2xl font-normal pt-6">Apakah anda memiliki masalah dalam transaksi atau memiliki pertanyaan?</p>
    </div>
    <div class="row md:w-1/2 md:pb-32 pb-20 pt-10">
      <!--  Panel 1  -->
      <div class="md:w-auto md:pr-32 md:pl-0 pr-6 pl-6">
        <input type="checkbox" name="panel" id="panel-1" class="hidden" />
        <label for="panel-1" class="relative block text-black p-4 shadow border-b border-grey accordion">Apakah Rekberin aman?</label>
        <div class="accordion__content overflow-hidden bg-grey-lighter">
          <h2 class="accordion__header pt-4 pl-4"></h2>
          <p class="accordion__body p-4" id="panel1">Rekberin merupakan platform yang aman karena sudah terdaftar sebagai lembaga seperti ini.</p>
        </div>
      </div>
      <!--  Panel 2  -->
      <div class="md:w-auto md:pr-32 md:pl-0 pr-6 pl-6">
        <input type="checkbox" name="panel" id="panel-2" class="hidden" />
        <label for="panel-2" class="relative block text-black p-4 shadow border-b border-grey accordion">Bagaimana saya menghubungi call center?</label>
        <div class="accordion__content overflow-hidden bg-grey-lighter">
          <h2 class="accordion__header pt-4 pl-4"></h2>
          <p class="accordion__body p-4" id="panel1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores saepe expedita, quaerat dicta facere eligendi illo quam dolorem optio distinctio?</p>
        </div>
      </div>
      <!--  Panel 3  -->
      <div class="md:w-auto md:pr-32 md:pl-0 pr-6 pl-6">
        <input type="checkbox" name="panel" id="panel-3" class="hidden" />
        <label for="panel-3" class="relative block text-black p-4 shadow border-b border-grey accordion">Apakah Rekberin memiliki aplikasi?</label>
        <div class="accordion__content overflow-hidden bg-grey-lighter">
          <h2 class="accordion__header pt-4 pl-4"></h2>
          <p class="accordion__body p-4" id="panel1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores saepe expedita, quaerat dicta facere eligendi illo quam dolorem optio distinctio?</p>
        </div>
      </div>
      <!--  Panel 4  -->
      <div class="md:w-auto md:pr-32 md:pl-0 pr-6 pl-6">
        <input type="checkbox" name="panel" id="panel-4" class="hidden" />
        <label for="panel-4" class="relative block text-black p-4 shadow border-b border-grey accordion">Dimana letak kantor Rekberin?</label>
        <div class="accordion__content overflow-hidden bg-grey-lighter">
          <h2 class="accordion__header pt-4 pl-4"></h2>
          <p class="accordion__body p-4" id="panel1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores saepe expedita, quaerat dicta facere eligendi illo quam dolorem optio distinctio?</p>
        </div>
      </div>
      <!--  Panel 5  -->
      <div class="md:w-auto md:pr-32 md:pl-0 pr-6 pl-6">
        <input type="checkbox" name="panel" id="panel-5" class="hidden" />
        <label for="panel-5" class="relative block text-black p-4 shadow border-b border-grey accordion">Bagaimana saya bisa mendaftar?</label>
        <div class="accordion__content overflow-hidden bg-grey-lighter">
          <h2 class="accordion__header pt-4 pl-4"></h2>
          <p class="accordion__body p-4" id="panel1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores saepe expedita, quaerat dicta facere eligendi illo quam dolorem optio distinctio?</p>
        </div>
      </div>
      <!--  -->
    </div>
  </div>
  <!-- Daftar -->
  <div class="footer bg-green-700 text-center pb-24 md:pb-40">
    <h1 class="heading pt-20 text-yellow-400 font-extrabold md:text-6xl text-4xl md:pt-48">Mulai Bisnis Anda Sekarang</h1>
    <h2 class="small-heading text-gray-200 md:text-3xl text-xl md:pt-1 pt-4">Daftar sekarang juga</h2>
    <button class="bg-white hover:bg-gray-100 text-green-700 font-semibold py-3 px-10 mt-8 border border-gray-400 rounded shadow">Daftar</button>
  </div>
  <!-- Contact -->
  <div class="footer-list md:w-1/2 mx-auto pt-16">
    <ul class="md:flex md:justify-between text-center leading-7">
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
    <div class="container social mx-auto md:py-12 py-6">
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
  /* height: 517px; */
  border-radius: 20px;
}

.image a img {
  height: 40px;
}

.social {
  width: 50%;
}

label:after {
  content: "+";
  position: absolute;
  right: 1em;
  color: black;
}

input:checked + label:after {
  content: "-";
  line-height: 0.8em;
}

.accordion__content {
  max-height: 0em;
  transition: all 0.4s cubic-bezier(0.865, 0.14, 0.095, 0.87);
}
input[name="panel"]:checked ~ .accordion__content {
  /* Get this as close to what height you expect */
  max-height: 50em;
}
</style>
