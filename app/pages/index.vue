<template>
  <NavBar />

  <div class="min-h-screen bg-slate-50">

    <!-- HERO SECTION -->
    <section class="bg-gradient-to-r from-slate-900 to-indigo-900 text-white py-28">
      <div class="container mx-auto px-4 text-center">
        <img
          src="/images/kwambai.jpg"
          alt="Faith Jerono"
          class="mx-auto w-40 h-40 rounded-full mb-8"
        />

        <h1 class="text-5xl font-bold mb-4">
          Hi, I’m Jerono Faith.
        </h1>

        <p class="text-xl max-w-2xl mx-auto mb-10 text-slate-200">
          A web developer focused on building modern, responsive and scalable
          web applications using CSS, HTML, JavaScript, Vue 3, Nuxt.js, Tailwind CSS, Python and PHP.
        </p>

        <NuxtLink
          to="/projects"
          class="inline-block bg-white text-slate-900 px-8 py-3 rounded-lg font-semibold hover:bg-slate-200 transition"
        >
          View Projects
        </NuxtLink>
      </div>
    </section>

    <!-- ABOUT SECTION -->
    <section class="py-24 bg-white">
      <div class="container mx-auto px-4 text-center">
        <h2 class="text-3xl font-bold mb-10 text-slate-900">
          About Me
        </h2>

        <p class="max-w-4xl mx-auto text-slate-700 text-lg leading-relaxed">
          I am a dedicated web developer with a strong interest in creating
          clean, efficient, and user-focused digital solutions. I specialize
          in front-end development using HTML, CSS, JavaScript, and modern
          frameworks such as Nuxt.js and Vue 3.  
          <br /><br />
          On the backend, I work with PHP and Python to develop reliable,
          data-driven systems. I enjoy solving real-world problems through
          technology and continuously improving my skills by building
          practical, production-ready projects.
        </p>
      </div>
    </section>

    <!-- SKILLS SECTION -->
    <section class="py-24 bg-slate-100">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-16 text-slate-900">
          Languages & Technologies
        </h2>

        <div class="grid md:grid-cols-3 gap-10 max-w-6xl mx-auto text-center">

          <div class="bg-white p-8 rounded-xl shadow">
            <img src="/images/html.png" alt="HTML" class="mx-auto w-24 heart-img mb-6" />
            <h3 class="text-xl font-semibold mb-2">HTML</h3>
            <p class="text-slate-600">
              Provides the structural foundation of web applications and
              semantic content organization.
            </p>
          </div>

          <div class="bg-white p-8 rounded-xl shadow">
            <img src="/images/css.png" alt="CSS" class="mx-auto w-24 heart-img mb-6" />
            <h3 class="text-xl font-semibold mb-2">CSS</h3>
            <p class="text-slate-600">
              Used to design modern, responsive layouts with attention to
              usability and visual clarity.
            </p>
          </div>

          <div class="bg-white p-8 rounded-xl shadow">
            <img src="/images/js.png" alt="JavaScript" class="mx-auto w-24 heart-img mb-6" />
            <h3 class="text-xl font-semibold mb-2">JavaScript</h3>
            <p class="text-slate-600">
              Enables interactivity, dynamic content, and smooth user
              experiences across applications.
            </p>
          </div>

          <div class="bg-white p-8 rounded-xl shadow">
            <img src="/images/php.png" alt="PHP" class="mx-auto w-24 heart-img mb-6" />
            <h3 class="text-xl font-semibold mb-2">PHP</h3>
            <p class="text-slate-600">
              Handles server-side logic, form processing, and database
              interactions.
            </p>
          </div>

          <div class="bg-white p-8 rounded-xl shadow">
            <img src="/images/python.png" alt="Python" class="mx-auto w-24 heart-img mb-6" />
            <h3 class="text-xl font-semibold mb-2">Python</h3>
            <p class="text-slate-600">
              Used for backend development, automation, and clean application
              logic.
            </p>
          </div>

          <div class="bg-white p-8 rounded-xl shadow">
            <img src="/images/vue.png" alt="Vue & Nuxt" class="mx-auto w-24 heart-img mb-6" />
            <h3 class="text-xl font-semibold mb-2">Nuxt.js & Vue 3</h3>
            <p class="text-slate-600">
              Frameworks for building fast, scalable, and maintainable web
              applications.
            </p>
          </div>

        </div>
      </div>
    </section>

    <!-- PROJECTS SECTION -->
    <section class="py-24 bg-white">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-16 text-slate-900">
          Featured Projects
        </h2>

        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-10 max-w-6xl mx-auto">

          <div class="bg-slate-50 p-8 rounded-xl shadow hover:shadow-lg transition">            
            <h3 class="text-xl font-semibold mb-2">Travel Booking System</h3>
            <p class="text-slate-600">
              A responsive travel booking platform built using HTML, CSS,
              JavaScript, PHP, and MySQL with user-friendly booking flows.
            </p>
          </div>

          <div class="bg-slate-50 p-8 rounded-xl shadow hover:shadow-lg transition">
            <h3 class="text-xl font-semibold mb-2">SafeVoice Platform</h3>
            <p class="text-slate-600">
              An awareness platform focused on gender-based violence and
              femicide, providing educational content and resources.
            </p>
          </div>

          <div class="bg-slate-50 p-8 rounded-xl shadow hover:shadow-lg transition">           
            <h3 class="text-xl font-semibold mb-2">Charity Donation System</h3>
            <p class="text-slate-600">
              A web-based donation system that allows users to securely support
              charities and vulnerable communities.
            </p>
          </div>

        </div>
      </div>
    </section>

  </div>

  <svg xmlns="http://www.w3.org/2000/svg" width="0" height="0">
    <defs>
      <clipPath id="heart-shape" clipPathUnits="objectBoundingBox">
        <path d="M0.5 0.15 C0.35 -0.05, 0 0.1, 0.5 0.6 C1 0.1, 0.65 -0.05, 0.5 0.15 Z" />
      </clipPath>
    </defs>
  </svg>
</template>

<style scoped>
.heart-img {
  clip-path: url(#heart-shape);
}

svg {
  display: none;
}
</style>
