<template>
  <section class="relative min-h-screen flex items-center px-6 py-24 overflow-hidden bg-white">
    <div class="absolute inset-0 -z-10">
      <div class="absolute top-0 right-0 w-[50%] h-[50%] bg-blue-50/50 blur-[120px] rounded-full"></div>
      <div class="absolute bottom-0 left-0 w-[30%] h-[30%] bg-indigo-50/50 blur-[100px] rounded-full"></div>
    </div>

    <div class="max-w-7xl mx-auto grid lg:grid-cols-2 gap-12 items-center">
      
      <div class="text-left space-y-8 animate-fade-in-up order-2 lg:order-1">
        <div>
          <span class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-green-50 text-green-700 text-xs font-bold tracking-wider uppercase mb-6 ring-1 ring-green-600/20">
            <span class="flex h-2 w-2">
              <span class="animate-ping absolute inline-flex h-2 w-2 rounded-full bg-green-400 opacity-75"></span>
              <span class="relative inline-flex rounded-full h-2 w-2 bg-green-500"></span>
            </span>
            Available for new projects
          </span>
          
          <h1 class="text-6xl md:text-8xl font-black text-slate-900 tracking-tighter leading-[0.9]">
            David<br />
            <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-600 to-indigo-600">Cantor</span>
          </h1>
        </div>

        <h2 class="text-2xl md:text-3xl font-medium text-slate-700 max-w-xl delay-100">
          Junior <span class="font-bold text-slate-900 underline decoration-blue-500/30">Full Stack</span> Developer
        </h2>

        <p class="max-w-lg text-lg text-slate-500 leading-relaxed delay-200">
          I build clear, functional, and SEO-friendly web applications for small businesses and real-world needs. Specialized in <span class="text-slate-900 font-semibold">Nuxt (SSR)</span> & <span class="text-slate-900 font-semibold">Django</span>.
        </p>
        
        <div class="flex flex-col sm:flex-row gap-4 delay-300">
          <NuxtLink 
            to="#projects" 
            class="group px-8 py-4 bg-slate-900 text-white rounded-2xl font-bold transition-all hover:bg-blue-600 hover:shadow-2xl hover:shadow-blue-200 hover:-translate-y-1 active:scale-95 text-center"
          >
            View Projects
          </NuxtLink>

          <NuxtLink 
            to="#contact" 
            class="px-8 py-4 bg-white text-slate-900 border-2 border-slate-100 rounded-2xl font-bold transition-all hover:border-blue-200 hover:bg-slate-50 active:scale-95 text-center"
          >
            Contact Me
          </NuxtLink>
        </div>
      </div>

      <div class="relative order-1 lg:order-2 flex justify-center lg:justify-end animate-zoom-in">
        <div class="relative w-72 h-72 md:w-[450px] md:h-[450px]">
          <div class="absolute -top-4 -right-4 w-full h-full border-2 border-slate-100 rounded-[3rem] -z-10"></div>
          <div class="absolute -bottom-4 -left-4 w-full h-full bg-blue-600/5 rounded-[3rem] -z-10"></div>
          
          <div class="w-full h-full rounded-[3rem] overflow-hidden shadow-2xl border-8 border-white">
            <img 
              src="/images/your-profile-picture.jpg" 
              alt="David Cantor" 
              class="w-full h-full object-cover transition-transform duration-700 hover:scale-110"
            >
          </div>

          <div class="absolute -bottom-6 -right-6 bg-white p-4 rounded-2xl shadow-xl border border-slate-50 hidden md:block animate-bounce">
            <div class="flex items-center gap-3">
              <div class="w-10 h-10 bg-green-50 rounded-lg flex items-center justify-center text-xl">🚀</div>
              <div class="text-left">
                <p class="text-[10px] font-bold text-slate-400 uppercase">Specialty</p>
                <p class="text-sm font-bold text-slate-900">Nuxt 4 Developer</p>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>

    <div class="absolute bottom-10 left-6 hidden lg:flex flex-col items-center gap-2">
      <span class="[writing-mode:vertical-lr] text-[10px] font-bold uppercase tracking-widest text-slate-400">Scroll Down</span>
      <div class="w-px h-12 bg-gradient-to-b from-slate-300 to-transparent"></div>
    </div>
  </section>
</template>