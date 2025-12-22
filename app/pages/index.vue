<template>
  <main class="min-h-screen bg-gray-950 text-gray-100">
    <!-- HERO -->
    <section class="max-w-5xl mx-auto px-6 py-24">
      <h1 class="text-4xl md:text-5xl font-bold leading-tight">
        Junior Full Stack Developer
        <span class="block text-emerald-400 mt-2">
          Specialized in Nuxt (SSR)
        </span>
      </h1>

      <p class="mt-6 text-gray-400 max-w-2xl">
        I build clean, functional, and SEO-friendly web applications using
        Nuxt, Tailwind CSS, and Django. Focused on real-world projects and
        business-oriented solutions.
      </p>

      <div class="mt-8 flex gap-4">
        <a
          href="#projects"
          class="px-6 py-3 bg-emerald-500 text-gray-900 font-medium rounded-lg hover:bg-emerald-400 transition"
        >
          View Projects
        </a>

        <a
          href="mailto:dsantiagocanvar@gmail.com"
          class="px-6 py-3 border border-gray-700 rounded-lg hover:border-emerald-400 transition"
        >
          Contact
        </a>
      </div>
    </section>

    <!-- PROJECTS -->
    <section id="projects" class="max-w-5xl mx-auto px-6 py-20">
      <h2 class="text-3xl font-semibold mb-10">Featured Projects</h2>

      <div class="grid md:grid-cols-2 gap-8">
        <!-- Asconfi -->
        <div class="border border-gray-800 rounded-xl p-6 hover:border-emerald-400 transition">
          <h3 class="text-xl font-semibold">Asconfi-JY</h3>
          <p class="text-gray-400 mt-2">
            Accounting & financial advisory website built with Nuxt SSR,
            optimized for SEO, performance, and business conversion.
          </p>

          <p class="text-sm text-gray-500 mt-3">
            Nuxt 4 · SSR · Tailwind · Netlify
          </p>

          <a
            href="https://asconfijy.netlify.app/"
            target="_blank"
            class="inline-block mt-4 text-emerald-400 hover:underline"
          >
            Live site →
          </a>
        </div>

        <!-- CBAPASS -->
        <div class="border border-gray-800 rounded-xl p-6 hover:border-emerald-400 transition">
          <h3 class="text-xl font-semibold">CBAPASS</h3>
          <p class="text-gray-400 mt-2">
            QR-based access control system for organizations and events with
            authentication and admin dashboard.
          </p>

          <p class="text-sm text-gray-500 mt-3">
            Django · PostgreSQL · Vue / Nuxt
          </p>

          <a
            href="https://github.com/DavidCantor/CbaPoint-Despliegue"
            target="_blank"
            class="inline-block mt-4 text-emerald-400 hover:underline"
          >
            Repository →
          </a>
        </div>
      </div>
    </section>

    <!-- FOOTER -->
    <footer class="border-t border-gray-800 py-8 text-center text-gray-500">
      © {{ new Date().getFullYear() }} David — Junior Full Stack Developer
    </footer>
  </main>
</template>
