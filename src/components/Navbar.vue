<template>
  <div id="container">
    <div class="bg-image">
      <div class="font-sans antialiased" id="app">
        <!-- Class Navbar -->
        <nav class="navbar flex items-center justify-between flex-wrap pl-6 pr-6 bg-transparent p-6 md:pl-24 md:pr-24">
          <!-- Brand and Logos -->
          <div class="flex items-center flex-no-shrink mr-6">
            <svg class="fill-current h-8 w-8 mr-2" width="54" height="54" viewBox="0 0 54 54" xmlns="http://www.w3.org/2000/svg"></svg>
            <img src="../assets/image/logorekberin.png" alt="brandlogo" width="48" />
            <h1 class="font-extrabold pl-3 brand-font">Rekberin</h1>
          </div>
          <!-- Hamburger Component -->
          <div class="block sm:hidden">
            <button @click="toggle" class="flex items-center px-3 py-2 border rounded text-teal-lighter border-teal-light hover:text-white hover:border-white">
              <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                <title>Menu</title>
                <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
              </svg>
            </button>
          </div>
          <!-- Hamburger Action -->
          <div :class="open ? 'block' : 'hidden'" class="w-full flex-grow sm:flex sm:items-center sm:w-auto">
            <!-- Navigation  Links-->
            <div class="text-sm sm:flex-grow sm:text-right">
              <a href="#responsive-header" class="no-underline block mt-4 sm:mx-6 sm:inline-block sm:mt-0 text-teal-lighter hover:text-green-800 mr-4"> Bantuan </a>
              <a href="#responsive-header" class="no-underline block mt-4 sm:mx-6 sm:inline-block sm:mt-0 text-teal-lighter hover:text-green-800 mr-4"> Tutorial </a>
              <a href="#responsive-header" class="no-underline block mt-4 sm:mx-6 sm:inline-block sm:mt-0 text-teal-lighter hover:text-green-800 mr-4"> Login </a>
            </div>
            <div>
              <!-- Download Button -->
              <a href="#" class="no-underline inline-block text-sm px-4 py-2 leading-none border rounded text-green-800 border-green-600 hover:border-transparent hover:bg-green-800 hover:text-white mt-4 sm:mt-0">Register</a>
            </div>
          </div>
        </nav>
      </div>
      <div id="container">
        <!-- Hero -->
        <div class="flex flex-col md:flex-row md:items-center py-10">
          <div class="w-full px-7 md:w-2/3 md:p-20 md:pt-12">
            <h1 class="heading leading-tight text-4xl md:leading-tight md:text-6xl font-bold">Transfer Beda Bank Bebas Biaya Admin</h1>
            <p class="wd:leading md:text-xl text-gray-500 md:mt-3 md:pr-18 font-semibold md:text-justify pt-5 text-justify">
              Pariatur et cupidatat sunt dolore veniam incididunt. Est officia exercitation aut utedde proident do adipisicing excepteur voluptate dolor. Lorem?
            </p>
            <button class="bg-green-600 hover:bg-green-800 text-white font-bold py-3 px-12 mt-5 rounded">Daftar</button>
          </div>
          <div class="w-full md:pt-18 pt-14 px-20 md:pr-8 md:w-1/2 flex justify-center">
            <img class="img" src="../assets/image/img-header.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      open: false,
    };
  },
  methods: {
    toggle() {
      this.open = !this.open;
    },
  },
};
</script>

<style>
.img {
  width: 100%;
}

.p-leading {
  line-height: 2rem;
}
</style>
