<template>
  <NavBar />

  <div id="contact" class="min-h-screen bg-slate-50">

    <!-- HEADER -->
    <section class="py-28 bg-gradient-to-r from-slate-900 to-indigo-900 text-white text-center">
      <img
        src="/images/contact.jpg"
        alt="Contact"
        class="mx-auto w-32 h-32 heart-img mb-6"
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
