<template>
  <nav class="bg-white shadow-md sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">

      <h1 class="text-2xl font-bold text-rose-500">
        Luxe Salon
      </h1>

      <div class="space-x-6 hidden md:flex">
        <a href="#services" class="hover:text-rose-500">Services</a>
        <a href="#gallery" class="hover:text-rose-500">Gallery</a>
        <a href="#booking" class="hover:text-rose-500">Booking</a>
      </div>

      <button
        class="px-5 py-2 rounded-full text-white font-semibold
        bg-gradient-to-r from-rose-500 to-purple-500
        hover:scale-105 transition">
        Book Now
      </button>

    </div>
  </nav>
</template>

<script>
export default {
  name:"Navbar"
}
</script>