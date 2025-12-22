<template>
  <section id="about" class="relative py-24 px-6 overflow-hidden bg-white">
    <div class="absolute top-0 right-0 -translate-y-1/2 translate-x-1/4 w-96 h-96 bg-blue-50/50 rounded-full blur-3xl"></div>
    
    <div class="max-w-6xl mx-auto relative">
      <div class="text-center mb-20">
        <span class="inline-flex items-center gap-2 px-4 py-1.5 bg-slate-100 text-slate-700 rounded-full text-sm font-bold mb-4 tracking-wide uppercase">
          <span class="w-2 h-2 rounded-full bg-blue-600"></span>
          More than just code
        </span>
        <h2 class="text-4xl md:text-5xl lg:text-6xl font-black text-slate-900 mb-6 tracking-tight">
          Building with <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-600 to-indigo-600">purpose</span> and precision
        </h2>
        <p class="text-lg md:text-xl text-slate-500 max-w-2xl mx-auto leading-relaxed">
          I bridge the gap between complex technical architectures and tangible business results.
        </p>
      </div>

      <div class="grid lg:grid-cols-12 gap-16 items-start">
        <div class="lg:col-span-7 space-y-12">
          <div class="prose prose-slate lg:prose-lg">
            <h3 class="text-3xl font-bold text-slate-900 flex items-center gap-3">
              Hi, I'm David Cantor <span class="animate-bounce">👋</span>
            </h3>
            <p class="text-slate-600 text-lg leading-relaxed">
              I'm a <span class="text-slate-900 font-semibold border-b-2 border-blue-100">practical Full Stack Developer</span> 
              who believes that great software should solve real problems, not just look good. 
              My approach is centered on clean architecture, maintainable code, and tangible results.
            </p>
          </div>

          <div class="grid gap-6">
            <div class="group p-6 rounded-2xl bg-gradient-to-br from-slate-900 to-slate-800 text-white shadow-2xl transition-all hover:-translate-y-1">
              <div class="flex items-start gap-4">
                <div class="w-12 h-12 rounded-xl bg-blue-500/20 flex items-center justify-center text-2xl shadow-inner">
                  📊
                </div>
                <div>
                  <h4 class="text-xl font-bold mb-2 group-hover:text-blue-400 transition-colors">Business-Aware Development</h4>
                  <p class="text-slate-300 leading-relaxed">
                    I understand <span class="text-white font-medium">accounting, finance, and operational processes</span>. 
                    I build software that genuinely aligns with business needs, accelerating requirement understanding.
                  </p>
                </div>
              </div>
            </div>

            <div class="group p-6 rounded-2xl bg-white border border-slate-100 shadow-sm transition-all hover:border-blue-200 hover:shadow-md">
              <div class="flex items-start gap-4">
                <div class="w-12 h-12 rounded-xl bg-blue-50 flex items-center justify-center text-2xl group-hover:scale-110 transition-transform">
                  ⚙️
                </div>
                <div>
                  <h4 class="text-xl font-bold text-slate-900 mb-2">Technical Foundation</h4>
                  <p class="text-slate-500">
                    Specialized in <span class="text-blue-600 font-medium">Nuxt.js</span> and <span class="text-green-600 font-medium">Django/Laravel</span>. 
                    I prioritize performance, SEO, and robust backend logic.
                  </p>
                </div>
              </div>
            </div>
          </div>

          <div class="pt-6">
            <NuxtLink to="#contact" class="inline-flex items-center gap-2 text-blue-600 font-bold text-lg group">
              Let's discuss your next project
              <svg class="w-5 h-5 transition-transform group-hover:translate-x-2" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/></svg>
            </NuxtLink>
          </div>
        </div>

        <div class="lg:col-span-5 lg:sticky lg:top-24">
          <div class="relative group">
            <div class="absolute -inset-1 bg-gradient-to-r from-blue-600 to-indigo-600 rounded-3xl blur opacity-10 group-hover:opacity-20 transition duration-1000"></div>
            
            <div class="relative bg-white border border-slate-100 rounded-3xl p-8 shadow-2xl">
              <h3 class="text-xl font-bold text-slate-900 mb-8 pb-4 border-b border-slate-50">Technical Arsenal</h3>
              
              <div class="space-y-8">
                <div v-for="(group, index) in stack" :key="index">
                  <h4 class="text-xs font-bold uppercase tracking-widest text-slate-400 mb-4 flex items-center gap-2">
                    {{ group.title }}
                  </h4>
                  <div class="flex flex-wrap gap-2">
                    <span v-for="skill in group.skills" :key="skill" 
                      class="px-3 py-1.5 bg-slate-50 border border-slate-100 rounded-lg text-sm font-semibold text-slate-700 hover:border-blue-200 hover:bg-blue-50 transition-colors">
                      {{ skill }}
                    </span>
                  </div>
                </div>
              </div>

              <div class="mt-10 p-4 rounded-xl bg-slate-50 border border-dashed border-slate-200">
                <p class="text-xs text-slate-500 text-center italic">
                  "I choose tools based on project needs, not just trends."
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const stack = [
  {
    title: 'Backend & Databases',
    skills: ['Django', 'Laravel', 'PostgreSQL', 'REST APIs', 'Supabase']
  },
  {
    title: 'Frontend & UI',
    skills: ['Nuxt.js', 'Vue 3', 'Tailwind CSS', 'TypeScript', 'SSR/SEO']
  },
  {
    title: 'Deployment & Ops',
    skills: ['Git', 'Docker', 'Netlify', 'Vercel', 'Linux']
  }
]
</script>