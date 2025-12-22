<template>
  <footer class="bg-white border-t border-slate-100 pt-20 pb-10 px-6">
    <div class="max-w-7xl mx-auto">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-12 mb-16">
        
        <div class="md:col-span-2 space-y-6">
          <NuxtLink to="/" class="flex items-center gap-2">
            <div class="w-8 h-8 bg-slate-900 text-white rounded-lg flex items-center justify-center font-black">
              D
            </div>
            <span class="font-black text-slate-900 tracking-tighter text-xl">David Cantor</span>
          </NuxtLink>
          <p class="text-slate-500 max-w-sm leading-relaxed">
            Building digital solutions with a focus on clean code, business logic, and exceptional user experience. Based in Colombia, working worldwide.
          </p>
          <div class="flex gap-4">
            <a href="https://github.com/DavidCantor" target="_blank" class="p-2 bg-slate-50 rounded-lg text-slate-600 hover:bg-blue-600 hover:text-white transition-all">
              <span class="sr-only">GitHub</span>
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 21.795 24 17.298 24 12c0-6.627-5.373-12-12-12z"/></svg>
            </a>
            </div>
        </div>

        <div>
          <h4 class="font-bold text-slate-900 mb-6 uppercase text-xs tracking-widest">Navigation</h4>
          <ul class="space-y-4">
            <li><NuxtLink to="#about" class="text-slate-500 hover:text-blue-600 transition-colors text-sm">About Me</NuxtLink></li>
            <li><NuxtLink to="#projects" class="text-slate-500 hover:text-blue-600 transition-colors text-sm">Projects</NuxtLink></li>
            <li><NuxtLink to="#services" class="text-slate-500 hover:text-blue-600 transition-colors text-sm">Services</NuxtLink></li>
          </ul>
        </div>

        <div>
          <h4 class="font-bold text-slate-900 mb-6 uppercase text-xs tracking-widest">Contact</h4>
          <ul class="space-y-4">
            <li class="text-sm text-slate-500">
              <span class="block font-bold text-slate-900">Email:</span>
              <a href="mailto:dsantiagocanvar@gmail.com" class="hover:text-blue-600 transition-colors">dsantiagocanvar@gmail.com</a>
            </li>
            <li class="text-sm text-slate-500">
              <span class="block font-bold text-slate-900">Location:</span>
              Mosquera, Cundinamarca, CO
            </li>
          </ul>
        </div>
      </div>

      <div class="pt-8 border-t border-slate-50 flex flex-col md:flex-row justify-between items-center gap-4">
        <p class="text-slate-400 text-xs font-medium">
          © {{ new Date().getFullYear() }} David Cantor. All rights reserved.
        </p>
        <div class="flex items-center gap-2 text-slate-400 text-xs">
          <span>Built with</span>
          <span class="px-2 py-1 bg-slate-50 rounded font-bold text-slate-600">Nuxt 4</span>
          <span>&</span>
          <span class="px-2 py-1 bg-slate-50 rounded font-bold text-slate-600">Tailwind</span>
        </div>
      </div>
    </div>
  </footer>
</template>