<template>
  <NavBar />

  <div class="min-h-screen bg-slate-50">

    <!-- HEADER -->
    <section class="py-28 bg-gradient-to-r from-slate-900 to-indigo-900 text-white text-center">
      <h1 class="text-5xl font-bold mb-4">Projects</h1>
      <p class="text-xl max-w-2xl mx-auto text-slate-200">
        A selection of projects developed using modern web technologies and
        best development practices.
      </p>
    </section>

    <!-- PROJECTS GRID -->
    <section class="py-24">
      <div class="container mx-auto px-4 grid md:grid-cols-2 lg:grid-cols-3 gap-10 max-w-6xl mx-auto">

        <!-- PROJECT 1 -->
        <div class="bg-white p-8 rounded-2xl shadow hover:shadow-lg transition">
          <img
            src="/images/project1.jpg"
            alt="Travel Booking System"
            class="w-full h-40 object-cover heart-img mb-6"
          />
          <h3 class="text-xl font-semibold mb-3 text-slate-900">
            Travel Booking System
          </h3>
          <p class="text-slate-600 mb-4">
            A responsive travel booking platform that allows users to browse
            destinations, make reservations, and manage bookings through a
            clean and intuitive interface.
          </p>
          <span class="text-indigo-600 font-semibold text-sm">
            HTML • CSS • JavaScript • PHP • MySQL
          </span>
        </div>

        <!-- PROJECT 2 -->
        <div class="bg-white p-8 rounded-2xl shadow hover:shadow-lg transition">
          <img
            src="/images/project2.jpg"
            alt="Safe Voice Platform"
            class="w-full h-40 object-cover heart-img mb-6"
          />
          <h3 class="text-xl font-semibold mb-3 text-slate-900">
            SafeVoice Platform
          </h3>
          <p class="text-slate-600 mb-4">
            An awareness platform focused on gender-based violence and femicide,
            providing educational resources and informative content through a
            structured and accessible web interface.
          </p>
          <span class="text-indigo-600 font-semibold text-sm">
            HTML • CSS • JavaScript • Tailwind CSS
          </span>
        </div>

        <!-- PROJECT 3 -->
        <div class="bg-white p-8 rounded-2xl shadow hover:shadow-lg transition">
          <img
            src="/images/project3.jpg"
            alt="Charity Donation System"
            class="w-full h-40 object-cover heart-img mb-6"
          />
          <h3 class="text-xl font-semibold mb-3 text-slate-900">
            Charity Donation System
          </h3>
          <p class="text-slate-600 mb-4">
            A web-based donation platform that enables users to securely support
            charitable causes, manage donations, and improve transparency.
          </p>
          <span class="text-indigo-600 font-semibold text-sm">
            PHP • Python • HTML • CSS • MySQL
          </span>
        </div>

        <!-- PROJECT 4 -->
        <div class="bg-white p-8 rounded-2xl shadow hover:shadow-lg transition">
          <img
            src="/images/project4.jpg"
            alt="Personal Portfolio"
            class="w-full h-40 object-cover heart-img mb-6"
          />
          <h3 class="text-xl font-semibold mb-3 text-slate-900">
            Personal Portfolio Website
          </h3>
          <p class="text-slate-600 mb-4">
            A modern personal portfolio built to showcase technical skills,
            projects, and professional background using a clean and responsive
            design.
          </p>
          <span class="text-indigo-600 font-semibold text-sm">
            Nuxt.js • Vue 3 • Tailwind CSS
          </span>
        </div>

      </div>
    </section>

  </div>
</template>

<style scoped>
.heart-img {
  clip-path: path(
    "M50 15
     C35 -5, 0 10, 50 60
     C100 10, 65 -5, 50 15 Z"
  );
}
</style>
