<template>
  <section id="contact" class="relative py-32 px-6 overflow-hidden">
    <div class="absolute inset-0 bg-slate-900 -z-10">
      <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#e5e7eb_1px,transparent_1px)] [background-size:16px_16px]"></div>
      <div class="absolute bottom-0 left-0 right-0 h-32 bg-gradient-to-t from-slate-950 to-transparent"></div>
    </div>

    <div class="max-w-4xl mx-auto">
      <div class="bg-white rounded-[2.5rem] p-8 md:p-16 shadow-2xl border border-slate-100 text-center relative overflow-hidden">
        <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-blue-50 text-blue-700 text-xs font-black uppercase tracking-widest mb-8">
          Ready to start
        </div>

        <h2 class="text-4xl md:text-5xl font-black text-slate-900 mb-6 tracking-tight">
          Let’s build something <span class="text-blue-600 font-serif italic">extraordinary</span>
        </h2>

        <p class="text-lg text-slate-500 mb-12 max-w-xl mx-auto leading-relaxed">
          If you have a project in mind or need help improving an existing product, my inbox is always open.
        </p>

        <div class="flex flex-col sm:flex-row justify-center items-center gap-4">
          <a 
            href="mailto:dsantiagocanvar@gmail.com" 
            class="group w-full sm:w-auto flex items-center justify-center gap-3 px-8 py-4 bg-slate-900 text-white rounded-2xl font-bold transition-all hover:bg-blue-600 hover:-translate-y-1 active:scale-95 shadow-lg shadow-slate-200"
          >
            <svg class="w-5 h-5 opacity-70 group-hover:scale-110 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
            </svg>
            Email Me
          </a>

          <a 
            href="https://github.com/DavidCantor" 
            target="_blank" 
            class="group w-full sm:w-auto flex items-center justify-center gap-3 px-8 py-4 bg-white text-slate-900 border border-slate-200 rounded-2xl font-bold transition-all hover:border-slate-300 hover:bg-slate-50 active:scale-95 shadow-sm"
          >
            <svg class="w-5 h-5 opacity-70 group-hover:rotate-12 transition-transform" fill="currentColor" viewBox="0 0 24 24">
              <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 21.795 24 17.298 24 12c0-6.627-5.373-12-12-12z" />
            </svg>
            Follow on GitHub
          </a>
        </div>

        <div class="mt-16 pt-8 border-t border-slate-50 flex flex-col md:flex-row justify-between items-center gap-4 text-slate-400 text-sm">
          <p>© {{ new Date().getFullYear() }} David Cantor. Built with Nuxt 4.</p>
          <div class="flex gap-6">
            <span class="hover:text-slate-600 transition-colors cursor-default">Mosquera, Colombia</span>
            <a href="#about" class="hover:text-blue-600 transition-colors">Back to top ↑</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>