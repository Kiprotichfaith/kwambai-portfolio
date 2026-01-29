<template>
  <NavBar />

  <div class="min-h-screen bg-slate-50">

    <!-- HEADER -->
    <section class="py-28 bg-gradient-to-r from-slate-900 to-indigo-900 text-white text-center">
      <img
        src="/images/kwambai.jpg"
        alt="Faith Jerono"
        class="mx-auto w-36 h-36 heart-img mb-6"
      />
      <h1 class="text-5xl font-bold mb-4">About Me</h1>
      <p class="text-xl max-w-2xl mx-auto text-slate-200">
        A closer look at my background, technical skills, and experience as a web developer.
      </p>
    </section>

    <!-- CONTENT -->
    <section class="py-24 bg-white">
      <div class="container mx-auto px-4 max-w-4xl">

        <!-- WHO I AM -->
        <div class="mb-16">
          <h2 class="text-3xl font-bold mb-6 text-slate-900">Who I Am</h2>
          <p class="text-slate-700 text-lg leading-relaxed">
            I am a focused and detail-oriented web developer with a strong
            interest in building efficient, scalable, and user-friendly web
            applications. I enjoy transforming ideas into functional digital
            solutions using modern frameworks and best development practices.
          </p>
        </div>

        <!-- SKILLS -->
        <div class="mb-16">
          <h2 class="text-3xl font-bold mb-8 text-slate-900">Technical Skills</h2>

          <div class="grid md:grid-cols-2 gap-8">
            <div class="flex items-start gap-4">
              <img src="/images/vue.png" class="w-16 heart-img" alt="Vue" />
              <p class="text-slate-700">
                Nuxt.js and Vue 3 for building fast, component-based, and scalable
                front-end applications.
              </p>
            </div>

            <div class="flex items-start gap-4">
              <img src="/images/tailwind.png" class="w-16 heart-img" alt="Tailwind" />
              <p class="text-slate-700">
                Tailwind CSS for clean, responsive, and maintainable UI design.
              </p>
            </div>

            <div class="flex items-start gap-4">
              <img src="/images/js.png" class="w-16 heart-img" alt="JavaScript" />
              <p class="text-slate-700">
                JavaScript, HTML5, and CSS3 for interactive and accessible web
                interfaces.
              </p>
            </div>

            <div class="flex items-start gap-4">
              <img src="/images/git.png" class="w-16 heart-img" alt="Git" />
              <p class="text-slate-700">
                Git version control for collaborative development and code
                management.
              </p>
            </div>
          </div>
        </div>

        <!-- EXPERIENCE -->
        <div>
          <h2 class="text-3xl font-bold mb-6 text-slate-900">Experience</h2>
          <p class="text-slate-700 text-lg leading-relaxed">
            I have hands-on experience working on real-world projects, including
            a travel booking system with online payment integration, awareness
            platforms addressing social issues, and modern portfolio websites.
            These projects strengthened my skills in project planning,
            development, testing, and deployment using current web technologies.
          </p>
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
