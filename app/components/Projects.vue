<template>
  <section id="projects" class="py-24 px-6 bg-slate-50/50">
    <div class="max-w-6xl mx-auto">
      <div class="flex flex-col md:flex-row md:items-end justify-between mb-16 gap-4">
        <div>
          <h2 class="text-4xl font-black text-slate-900 tracking-tight">
            Selected <span class="text-blue-600">Works</span>
          </h2>
          <p class="mt-4 text-slate-500 max-w-md">
            Real-world applications focused on solving specific business needs with modern tech stacks.
          </p>
        </div>
        <div class="h-px flex-grow bg-slate-200 mb-2 mx-8 hidden md:block"></div>
        <span class="text-sm font-bold uppercase tracking-widest text-slate-400">2024 — 2025</span>
      </div>

      <div class="grid md:grid-cols-2 gap-8">
        <div class="group relative bg-white border border-slate-200 rounded-3xl p-8 transition-all hover:shadow-2xl hover:shadow-blue-500/5 hover:-translate-y-1">
          <div class="flex justify-between items-start mb-6">
            <div class="p-3 bg-blue-50 rounded-2xl text-blue-600 group-hover:bg-blue-600 group-hover:text-white transition-colors">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9h18" />
              </svg>
            </div>
            <div class="flex gap-2">
              <span class="px-3 py-1 bg-slate-100 text-slate-600 text-xs font-bold rounded-full">Nuxt 4</span>
              <span class="px-3 py-1 bg-slate-100 text-slate-600 text-xs font-bold rounded-full">SSR</span>
            </div>
          </div>

          <h3 class="text-2xl font-bold text-slate-900 mb-3">Asconfi-JY</h3>
          <p class="text-slate-600 leading-relaxed mb-6">
            Professional website for an accounting and financial advisory office. 
            Focused on <span class="text-slate-900 font-medium">SEO optimization</span> and business conversion through educational content.
          </p>

          <ul class="space-y-3 mb-8">
            <li v-for="item in ['Server-Side Rendering (SSR)', 'SEO testing & optimization', 'Educational blog implementation']" :key="item" class="flex items-center text-sm text-slate-500">
              <svg class="w-4 h-4 mr-2 text-green-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"/></svg>
              {{ item }}
            </li>
          </ul>

          <a href="https://asconfijy.netlify.app/" target="_blank" class="inline-flex items-center justify-center w-full py-3 px-4 bg-slate-900 text-white font-bold rounded-xl transition-all hover:bg-blue-600">
            View Live Demo
            <svg class="w-4 h-4 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"/></svg>
          </a>
        </div>

        <div class="group relative bg-white border border-slate-200 rounded-3xl p-8 transition-all hover:shadow-2xl hover:shadow-indigo-500/5 hover:-translate-y-1">
          <div class="flex justify-between items-start mb-6">
            <div class="p-3 bg-indigo-50 rounded-2xl text-indigo-600 group-hover:bg-indigo-600 group-hover:text-white transition-colors">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" />
              </svg>
            </div>
            <div class="flex gap-2">
              <span class="px-3 py-1 bg-slate-100 text-slate-600 text-xs font-bold rounded-full">Django</span>
              <span class="px-3 py-1 bg-slate-100 text-slate-600 text-xs font-bold rounded-full">PostgreSQL</span>
            </div>
          </div>

          <h3 class="text-2xl font-bold text-slate-900 mb-3">CBAPASS</h3>
          <p class="text-slate-600 leading-relaxed mb-6">
            QR-based access control system. A robust backend solution for 
            <span class="text-slate-900 font-medium">real-time authentication</span> and automated access logging.
          </p>

          <ul class="space-y-3 mb-8">
            <li v-for="item in ['Dynamic QR generation', 'Admin dashboard & Analytics', 'RESTful API Architecture']" :key="item" class="flex items-center text-sm text-slate-500">
              <svg class="w-4 h-4 mr-2 text-green-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"/></svg>
              {{ item }}
            </li>
          </ul>

          <a href="https://github.com/DavidCantor/CbaPoint-Despliegue.git" target="_blank" class="inline-flex items-center justify-center w-full py-3 px-4 border-2 border-slate-900 text-slate-900 font-bold rounded-xl transition-all hover:bg-slate-900 hover:text-white">
            <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 21.795 24 17.298 24 12c0-6.627-5.373-12-12-12z"/></svg>
            Repository
          </a>
        </div>
      </div>
    </div>
  </section>
</template>