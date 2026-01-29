<template>
  <NavBar />

  <div id="contact" class="min-h-screen bg-slate-50">

    <!-- HEADER -->
    <section class="py-28 bg-gradient-to-r from-slate-900 to-indigo-900 text-white text-center relative">
      <img
        src="/images/kwambai.jpg"
        alt="Faith Jerono"
        class="absolute left-8 top-1/2 transform -translate-y-1/2 w-40 h-40 rounded-full border-4 border-white shadow-lg"
      />
      <h1 class="text-5xl font-bold mb-4">Contact Me</h1>
      <p class="text-xl max-w-2xl mx-auto text-slate-200">
        Reach out for project inquiries, collaborations, or general questions.
      </p>
    </section>

    <!-- FORM -->
    <section class="py-24">
      <div class="container mx-auto px-4">
        <div class="max-w-xl mx-auto bg-white p-10 rounded-2xl shadow-lg">

          <form class="space-y-8">
            <div>
              <label class="block text-slate-700 font-semibold mb-2">
                Name
              </label>
              <input
                type="text"
                placeholder="Your full name"
                class="w-full border border-slate-300 rounded-lg px-4 py-3
                       focus:outline-none focus:ring-2 focus:ring-indigo-600"
              />
            </div>

            <div>
              <label class="block text-slate-700 font-semibold mb-2">
                Email
              </label>
              <input
                type="email"
                placeholder="you@example.com"
                class="w-full border border-slate-300 rounded-lg px-4 py-3
                       focus:outline-none focus:ring-2 focus:ring-indigo-600"
              />
            </div>

            <div>
              <label class="block text-slate-700 font-semibold mb-2">
                Message
              </label>
              <textarea
                rows="5"
                placeholder="Tell me about your project..."
                class="w-full border border-slate-300 rounded-lg px-4 py-3
                       focus:outline-none focus:ring-2 focus:ring-indigo-600"
              ></textarea>
            </div>

            <button
              type="submit"
              class="w-full bg-indigo-600 text-white py-3 rounded-lg
                     font-semibold hover:bg-indigo-700 transition"
            >
              Send Message
            </button>
          </form>

        </div>
      </div>
    </section>

    <!-- CONTACT CARD -->
    <section class="py-24 bg-gradient-to-r from-slate-900 to-indigo-900">
      <div class="container mx-auto px-4">
        <div class="max-w-md mx-auto bg-gradient-to-r from-purple-500 to-pink-500 text-white p-8 rounded-2xl shadow-lg">
          <h2 class="text-2xl font-bold mb-4 text-center">Get in Touch</h2>
          <p class="text-center mb-6">Feel free to reach out to me via the following platforms:</p>
          <ul class="space-y-4">
            <li class="flex items-center gap-4">
              <img src="/images/instagram.png" class="w-6 h-6" alt="Instagram" />
              <a href="https://instagram.com/thequietbloomofnova" target="_blank" class="text-indigo-200 hover:underline">@thequietbloomofnova</a>
            </li>
            <li class="flex items-center gap-4">
              <img src="/images/snapchat.png" class="w-6 h-6" alt="Snapchat" />
              <a href="https://snapchat.com/add/purple_kwambai" target="_blank" class="text-indigo-200 hover:underline">@purple_kwambai</a>
            </li>
            <li class="flex items-center gap-4">
              <img src="/images/whatsapp.png" class="w-6 h-6" alt="WhatsApp" />
              <a href="https://wa.me/254724086730" target="_blank" class="text-indigo-200 hover:underline">0724086730</a>
            </li>
            <li class="flex items-center gap-4">
              <img src="/images/phone.png" class="w-6 h-6" alt="Call" />
              <span class="text-slate-900">0704290031</span>
            </li>
          </ul>
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
