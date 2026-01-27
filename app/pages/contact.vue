<template>
<NavBar/>
  <div id="contact" class="min-h-screen bg-gray-50">
    <section class="py-24 bg-purple-600 text-white text-center">
      <h1 class="text-5xl font-bold mb-4">Contact Me</h1>
      <p class="text-xl max-w-2xl mx-auto">Get in touch for project inquiries or collaboration.</p>
    </section>

    <section class="py-20">
      <div class="container mx-auto px-4 max-w-xl bg-white p-8 rounded-lg shadow">
        <form action="#" class="space-y-6">
          <div>
            <label class="block text-gray-700 font-semibold mb-2">Name</label>
            <input type="text" placeholder="Your Name" class="w-full border border-gray-300 rounded px-4 py-2 focus:outline-none focus:ring-2 focus:ring-purple-600"/>
          </div>

          <div>
            <label class="block text-gray-700 font-semibold mb-2">Email</label>
            <input type="email" placeholder="Your Email" class="w-full border border-gray-300 rounded px-4 py-2 focus:outline-none focus:ring-2 focus:ring-purple-600"/>
          </div>

          <div>
            <label class="block text-gray-700 font-semibold mb-2">Message</label>
            <textarea rows="5" placeholder="Your Message" class="w-full border border-gray-300 rounded px-4 py-2 focus:outline-none focus:ring-2 focus:ring-purple-600"></textarea>
          </div>

          <button type="submit" class="bg-purple-600 text-white px-6 py-3 rounded-lg font-semibold hover:bg-purple-700 transition">Send Message</button>
        </form>
      </div>
    </section>
  </div>
</template>
