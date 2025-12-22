<template>
  <section id="services" class="bg-slate-50 py-24 border-y border-slate-100">
    <div class="max-w-5xl mx-auto px-6">
      <div class="flex flex-col md:flex-row justify-between items-start md:items-end mb-12 gap-6">
        <div>
          <h2 class="text-3xl md:text-4xl font-black text-slate-900 tracking-tight">
            Freelance <span class="text-blue-600">Services</span>
          </h2>
          <p class="mt-4 text-slate-500 max-w-md italic">
            Tailored solutions for businesses that need reliability and technical excellence.
          </p>
        </div>
        <div class="inline-flex items-center px-4 py-2 bg-blue-50 text-blue-700 rounded-lg text-sm font-bold border border-blue-100">
          ✨ Currently accepting new projects
        </div>
      </div>

      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <div class="group p-8 rounded-2xl border border-slate-200 bg-white shadow-sm transition-all hover:border-blue-300 hover:shadow-md">
          <div class="text-2xl mb-4 opacity-80 group-hover:scale-110 transition-transform inline-block">🎯</div>
          <h3 class="font-bold text-slate-900 mb-2">Business Presence</h3>
          <p class="text-sm text-slate-500 leading-relaxed">
            Landing pages & small business websites built for high conversion.
          </p>
        </div>

        <div class="group p-8 rounded-2xl border border-slate-200 bg-white shadow-sm transition-all hover:border-blue-300 hover:shadow-md">
          <div class="text-2xl mb-4 opacity-80 group-hover:scale-110 transition-transform inline-block">🚀</div>
          <h3 class="font-bold text-slate-900 mb-2">High Performance</h3>
          <p class="text-sm text-slate-500 leading-relaxed">
            Nuxt (SSR) websites optimized for blazing speed and SEO rankings.
          </p>
        </div>

        <div class="group p-8 rounded-2xl border border-slate-200 bg-white shadow-sm transition-all hover:border-blue-300 hover:shadow-md">
          <div class="text-2xl mb-4 opacity-80 group-hover:scale-110 transition-transform inline-block">📊</div>
          <h3 class="font-bold text-slate-900 mb-2">Business Logic</h3>
          <p class="text-sm text-slate-500 leading-relaxed">
            Admin dashboards & CRUD applications to automate your operations.
          </p>
        </div>

        <div class="group p-8 rounded-2xl border border-slate-200 bg-white shadow-sm transition-all hover:border-blue-300 hover:shadow-md">
          <div class="text-2xl mb-4 opacity-80 group-hover:scale-110 transition-transform inline-block">🛠️</div>
          <h3 class="font-bold text-slate-900 mb-2">Backend Architecture</h3>
          <p class="text-sm text-slate-500 leading-relaxed">
            Robust and secure Backend APIs built with Django & PostgreSQL.
          </p>
        </div>

        <div class="group p-8 rounded-2xl border border-slate-200 bg-white shadow-sm transition-all hover:border-blue-300 hover:shadow-md lg:col-span-2">
          <div class="flex flex-col sm:flex-row sm:items-center gap-4">
            <div class="text-2xl opacity-80 group-hover:rotate-12 transition-transform inline-block">🎨</div>
            <div>
              <h3 class="font-bold text-slate-900 mb-1">Frontend Refinement</h3>
              <p class="text-sm text-slate-500 leading-relaxed">
                Improvements, UI fixes, and modernizing existing interfaces for better UX.
              </p>
            </div>
          </div>
        </div>
      </div>

      <div class="mt-12 flex flex-col sm:flex-row items-center justify-center gap-4 py-6 border-t border-slate-200">
        <p class="text-slate-500 text-sm font-medium">
          Interested in a custom solution?
        </p>
        <NuxtLink to="#contact" class="px-6 py-2 bg-slate-900 text-white text-sm font-bold rounded-full hover:bg-blue-600 transition-colors">
          Get a Quote
        </NuxtLink>
      </div>
    </div>
  </section>
</template>