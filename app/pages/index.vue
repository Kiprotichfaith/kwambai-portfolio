<template>
<NavBar/>
  <div class="min-h-screen bg-gray-50">
    <section class="bg-indigo-300 text-white py-24">
      <h1 class="text-5xl font-bold mb-4">Hi, I'm Faith Jerono</h1>
      <p class="text-xl mb-8">I build modern, responsive web applications using Nuxt.js and Tailwind CSS.</p>
      <NuxtLink to="/projects" class="bg-white text-purple-600 px-6 py-3 rounded-lg font-semibold hover:bg-gray-200 transition">View Projects</NuxtLink>
    </section>

    <section class="py-20">
      <div class="container mx-auto px-4 text-center">
        <img src="/images/kwambai.jpg" alt="kwambai" class="mx-auto w-64 h-auto rounded-lg mb-8">
        <h2 class="text-3xl font-bold text-center mb-12">About Me</h2>
        <p class="max-w-3xl mx-auto text-gray-700 text-lg leading-relaxed">
          I am a passionate web developer from Kenya who enjoys bringing ideas to life through clean, functional, and visually appealing websites. I have a strong foundation in front-end technologies including HTML, CSS, and JavaScript, which I use to craft responsive and user-friendly interfaces. On the back end, I work with PHP and Python to build dynamic systems that power modern web applications. I am skilled in contemporary frameworks and tools such as Nuxt.js, Vue 3, and Tailwind CSS, and I enjoy blending creativity with technology to deliver meaningful digital experiences. Over time, I have developed several projects that reflect my dedication to learning, problem-solving, and building impactful web solutions.
        </p>
      </div>
    </section>

    <section class="py-20 bg-white">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12">Languages & Technologies</h2>

        <div class="grid md:grid-cols-2 gap-8 max-w-5xl mx-auto">
        <img src="/images/html.png" alt="html">
          <div class="bg-gray-50 p-6 rounded-lg shadow">
            <h3 class="text-xl font-semibold mb-2">HTML</h3>
            <p class="text-gray-600">
              Used to structure web pages and define the content layout, forming the foundation of all web applications.
            </p>
          </div>

          <div class="bg-gray-50 p-6 rounded-lg shadow">
          <img src="/images/css.png" alt="css">
            <h3 class="text-xl font-semibold mb-2">CSS</h3>
            <p class="text-gray-600">
              Used to style and design web pages, enabling responsive layouts, colors, fonts, and overall visual presentation.
            </p>
          </div>

          <div class="bg-gray-50 p-6 rounded-lg shadow">
          <img src="/images/js.png" alt="javascript">
            <h3 class="text-xl font-semibold mb-2">JavaScript</h3>
            <p class="text-gray-600">
              Adds interactivity and dynamic behavior to websites, improving user experience and functionality.
            </p>
          </div>

          <div class="bg-gray-50 p-6 rounded-lg shadow">
          <img src="/images/php.png" alt="php">
            <h3 class="text-xl font-semibold mb-2">PHP</h3>
            <p class="text-gray-600">
              Used for server-side development, handling form submissions, database operations, and backend logic.
            </p>
          </div>

          <div class="bg-gray-50 p-6 rounded-lg shadow">
          <img src="/images/python.png" alt="Python">
            <h3 class="text-xl font-semibold mb-2">Python</h3>
            <p class="text-gray-600">
              Used for backend development and data processing, allowing clean, efficient, and scalable application logic.
            </p>
          </div>

          <div class="bg-gray-50 p-6 rounded-lg shadow">
          <img src="/images/vue.png" alt="vue">
            <h3 class="text-xl font-semibold mb-2">Nuxt.js, Vue 3 & Tailwind CSS</h3>
            <p class="text-gray-600">
              Modern tools and frameworks used to build fast, scalable, and responsive web applications with clean UI design.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="py-20 bg-blue-100">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12">My Projects</h2>
        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-white p-6 rounded-lg shadow hover:shadow-lg transition">
            <h3 class="text-xl font-semibold mb-2">Project One</h3>
            <p class="text-gray-600">A responsive travel-booking website using HTML, css,javascript and php.</p>
          </div>
          <div class="bg-white p-6 rounded-lg shadow hover:shadow-lg transition">
            <h3 class="text-xl font-semibold mb-2">Project Two</h3>
            <p class="text-gray-600">A safe voice platform for creating awareness on GBV and femicide in kenya.</p>
          </div>
          <div class="bg-white p-6 rounded-lg shadow hover:shadow-lg transition">
            <h3 class="text-xl font-semibold mb-2">Project Three</h3>
            <p class="text-gray-600">A charity organization system that enables people to be able to donate funds for the needy and the orphans.</p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

