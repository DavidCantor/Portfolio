<template>
  <section id="services" class="relative py-32 overflow-hidden bg-slate-50">
    <div class="absolute top-0 left-1/2 -translate-x-1/2 w-full h-full -z-10">
      <div class="absolute top-0 left-1/4 w-96 h-96 bg-blue-100/50 rounded-full blur-[120px]"></div>
      <div class="absolute bottom-0 right-1/4 w-96 h-96 bg-indigo-100/50 rounded-full blur-[120px]"></div>
    </div>

    <div class="max-w-6xl mx-auto px-6">
      <div class="flex flex-col md:flex-row justify-between items-center md:items-end mb-20 gap-8">
        <div class="text-center md:text-left">
          <span class="text-blue-600 font-black text-xs uppercase tracking-[0.3em] mb-4 block">Solutions & Expertise</span>
          <h2 class="text-4xl md:text-5xl font-black text-slate-900 tracking-tight">
            Freelance <span class="bg-gradient-to-r from-blue-600 to-indigo-600 bg-clip-text text-transparent">Services</span>
          </h2>
          <p class="mt-4 text-slate-500 max-w-md leading-relaxed">
            I help brands stand out in the digital age with performance-driven development and cutting-edge design.
          </p>
        </div>
        
        <div class="relative group">
          <div class="absolute -inset-1 bg-gradient-to-r from-blue-600 to-indigo-600 rounded-xl blur opacity-25 group-hover:opacity-50 transition duration-1000"></div>
          <div class="relative inline-flex items-center px-6 py-3 bg-white text-slate-800 rounded-xl text-sm font-bold border border-slate-100 shadow-xl">
            <span class="relative flex h-3 w-3 mr-3">
              <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-green-400 opacity-75"></span>
              <span class="relative inline-flex rounded-full h-3 w-3 bg-green-500"></span>
            </span>
            Available for new projects
          </div>
        </div>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-6 gap-6">
        
        <div class="md:col-span-3 lg:col-span-2 group relative p-8 rounded-3xl border border-slate-200 bg-white/80 backdrop-blur-sm transition-all duration-500 hover:-translate-y-2 hover:shadow-2xl hover:shadow-blue-100">
          <div class="w-14 h-14 rounded-2xl bg-blue-50 flex items-center justify-center text-2xl mb-6 group-hover:bg-blue-600 group-hover:text-white transition-colors duration-500">
            🎯
          </div>
          <h3 class="text-xl font-bold text-slate-900 mb-3">Business Presence</h3>
          <p class="text-slate-500 leading-relaxed text-sm">
            Conversion-focused landing pages and corporate sites with a balance of aesthetics and strategy.
          </p>
          <div class="mt-6 flex gap-2">
            <span class="text-[10px] font-bold px-2 py-1 bg-slate-100 rounded text-slate-400 uppercase">Conversion</span>
            <span class="text-[10px] font-bold px-2 py-1 bg-slate-100 rounded text-slate-400 uppercase">SEO</span>
          </div>
        </div>

        <div class="md:col-span-3 lg:col-span-2 group relative p-8 rounded-3xl border border-blue-100 bg-gradient-to-br from-white to-blue-50/30 transition-all duration-500 hover:-translate-y-2 hover:shadow-2xl hover:shadow-blue-100">
          <div class="w-14 h-14 rounded-2xl bg-blue-600 flex items-center justify-center text-2xl mb-6 shadow-lg shadow-blue-200">
            🚀
          </div>
          <h3 class="text-xl font-bold text-slate-900 mb-3">High Performance</h3>
          <p class="text-slate-500 leading-relaxed text-sm">
            Fast-loading Nuxt (SSR) applications optimized for Core Web Vitals and top-tier Google rankings.
          </p>
          <div class="mt-6 flex gap-2">
            <span class="text-[10px] font-bold px-2 py-1 bg-blue-100 rounded text-blue-600 uppercase">Nuxt 3</span>
            <span class="text-[10px] font-bold px-2 py-1 bg-blue-100 rounded text-blue-600 uppercase">Vitals</span>
          </div>
        </div>

        <div class="md:col-span-6 lg:col-span-2 group relative p-8 rounded-3xl border border-slate-200 bg-white/80 transition-all duration-500 hover:-translate-y-2 hover:shadow-2xl hover:shadow-indigo-100">
          <div class="w-14 h-14 rounded-2xl bg-indigo-50 flex items-center justify-center text-2xl mb-6 group-hover:bg-indigo-600 group-hover:text-white transition-colors duration-500">
            📊
          </div>
          <h3 class="text-xl font-bold text-slate-900 mb-3">Business Logic</h3>
          <p class="text-slate-500 leading-relaxed text-sm">
            Custom admin panels and internal tools designed to streamline your business operations.
          </p>
        </div>

        <div class="md:col-span-3 group relative p-8 rounded-3xl border border-slate-200 bg-white/80 transition-all duration-500 hover:-translate-y-2 hover:shadow-2xl hover:shadow-slate-200">
          <div class="flex items-center gap-6">
            <div class="w-16 h-16 shrink-0 rounded-2xl bg-slate-900 flex items-center justify-center text-2xl group-hover:rotate-12 transition-transform duration-500">
              🛠️
            </div>
            <div>
              <h3 class="text-xl font-bold text-slate-900 mb-2">Backend Architecture</h3>
              <p class="text-slate-500 leading-relaxed text-sm">
                Scalable APIs and robust database schemas built with Python, Django, and PostgreSQL.
              </p>
            </div>
          </div>
        </div>

        <div class="md:col-span-3 group relative p-8 rounded-3xl border border-slate-200 bg-white transition-all duration-500 hover:-translate-y-2 hover:shadow-2xl hover:shadow-blue-100 overflow-hidden">
          <div class="absolute -right-4 -bottom-4 opacity-5 group-hover:scale-110 group-hover:rotate-12 transition-transform duration-700">
            <svg class="w-32 h-32" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path></svg>
          </div>
          <div class="flex items-center gap-6 relative z-10">
            <div class="w-16 h-16 shrink-0 rounded-2xl bg-blue-50 text-blue-600 flex items-center justify-center text-2xl">
              🎨
            </div>
            <div>
              <h3 class="text-xl font-bold text-slate-900 mb-2">Frontend Refinement</h3>
              <p class="text-slate-500 leading-relaxed text-sm">
                Polishing UX, fixing UI bugs, and modernizing legacy codebases for 2025 standards.
              </p>
            </div>
          </div>
        </div>

      </div>

      <div class="mt-20 relative p-1 rounded-[2rem] bg-gradient-to-r from-slate-200 via-blue-100 to-slate-200">
        <div class="bg-white rounded-[1.9rem] px-8 py-10 flex flex-col sm:flex-row items-center justify-between gap-6">
          <div class="text-center sm:text-left">
            <h4 class="text-xl font-bold text-slate-900">Need a specialized developer?</h4>
            <p class="text-slate-500 text-sm">Let's discuss how I can add value to your next big idea.</p>
          </div>
          <NuxtLink 
            to="#contact" 
            class="group relative inline-flex items-center justify-center px-8 py-4 font-bold text-white transition-all duration-200 bg-slate-900 font-pj rounded-2xl focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-900 hover:bg-blue-600"
          >
            Start a Project
            <svg class="w-5 h-5 ml-2 group-hover:translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
            </svg>
          </NuxtLink>
        </div>
      </div>
    </div>
  </section>
</template>