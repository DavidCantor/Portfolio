<template>
  <section id="projects" class="max-w-5xl mx-auto px-6 py-20">
    <h2 class="text-3xl font-semibold mb-10">Projects</h2>

    <!-- Asconfi-JY -->
    <div class="mb-12">
      <h3 class="text-2xl font-semibold">Asconfi-JY</h3>
      <p class="mt-2 text-gray-600">
        Professional website built with Nuxt (SSR) and Tailwind CSS for an accounting
        and financial advisory office. Focused on SEO, performance, and business conversion.
      </p>

      <ul class="mt-4 text-gray-500 list-disc list-inside">
        <li>Server-Side Rendering (SSR)</li>
        <li>SEO testing and optimization</li>
        <li>Educational blog</li>
        <li>Responsive, mobile-first design</li>
      </ul>

      <div class="mt-4 flex gap-4">
        <a
          href="https://asconfijy.netlify.app/"
          target="_blank"
          class="underline"
        >
          Live Demo
        </a>
      </div>
    </div>

    <!-- CBAPASS -->
    <div>
      <h3 class="text-2xl font-semibold">CBAPASS</h3>
      <p class="mt-2 text-gray-600">
        QR-based access control system built with Django REST Framework and PostgreSQL.
      </p>

      <ul class="mt-4 text-gray-500 list-disc list-inside">
        <li>User authentication</li>
        <li>Dynamic QR generation</li>
        <li>Admin dashboard</li>
        <li>Access logging</li>
      </ul>

      <div class="mt-4 flex gap-4">
        <a
          href="https://github.com/DavidCantor/CbaPoint-Despliegue.git"
          target="_blank"
          class="underline"
        >
          GitHub Repository
        </a>
      </div>
    </div>
  </section>
</template>
