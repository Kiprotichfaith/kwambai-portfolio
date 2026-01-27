<template>
<NavBar/>
  <div class="min-h-screen bg-gray-50">
    <section class="py-24 bg-purple-600 text-white text-center">
      <h1 class="text-5xl font-bold mb-4">Projects</h1>
      <p class="text-xl max-w-2xl mx-auto">
        A selection of projects I have developed using modern web technologies.
      </p>
    </section>

    <section class="py-20">
      <div class="container mx-auto px-4 grid md:grid-cols-2 lg:grid-cols-3 gap-8">

        <div class="bg-white p-6 rounded-lg shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2">Travel Booking Website</h3>
          <p class="text-gray-600 mb-4">
            A responsive travel booking platform built using HTML, CSS, JavaScript, and PHP, allowing users to browse destinations and make bookings.
          </p>
          <span class="text-purple-600 font-semibold">HTML • CSS • JavaScript • PHP</span>
        </div>

        <div class="bg-white p-6 rounded-lg shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2">Safe Voice Platform</h3>
          <p class="text-gray-600 mb-4">
            A web platform designed to create awareness on gender-based violence and femicide in Kenya, focusing on education and advocacy.
          </p>
          <span class="text-purple-600 font-semibold">HTML • CSS • JavaScript • Tailwind CSS</span>
        </div>

        <div class="bg-white p-6 rounded-lg shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2">Charity Donation System</h3>
          <p class="text-gray-600 mb-4">
            A charity management system that enables users to donate funds to support the needy and orphaned children through an online platform.
          </p>
          <span class="text-purple-600 font-semibold">PHP • Python • HTML • CSS</span>
        </div>

        <div class="bg-white p-6 rounded-lg shadow hover:shadow-lg transition">
          <h3 class="text-xl font-semibold mb-2">Personal Portfolio Website</h3>
          <p class="text-gray-600 mb-4">
            A modern personal portfolio built with Nuxt.js, Vue 3, and Tailwind CSS to showcase skills, projects, and experience.
          </p>
          <span class="text-purple-600 font-semibold">Nuxt.js • Vue 3 • Tailwind CSS</span>
        </div>

      </div>
    </section>
  </div>
</template>
