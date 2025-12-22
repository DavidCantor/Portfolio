<template>
  <nav 
    :class="[
      'fixed top-0 w-full z-[100] transition-all duration-500 px-6 py-4',
      isScrolled || isMenuOpen ? 'bg-white border-b border-slate-100 py-3' : 'bg-transparent'
    ]"
  >
    <div class="max-w-7xl mx-auto flex justify-between items-center relative z-[110]">
      <NuxtLink to="/" class="group flex items-center gap-2" @click="closeMenu">
        <div class="w-10 h-10 bg-slate-900 text-white rounded-xl flex items-center justify-center font-black">
          D
        </div>
        <span class="font-black text-slate-900 tracking-tighter text-xl">David Cantor</span>
      </NuxtLink>

      <div class="hidden md:flex items-center gap-8">
        <NuxtLink v-for="item in navItems" :key="item.path" :to="item.path"
          class="text-sm font-bold text-slate-500 hover:text-blue-600 transition-colors uppercase tracking-widest">
          {{ item.name }}
        </NuxtLink>
        <NuxtLink to="#contact" class="px-6 py-2.5 bg-slate-900 text-white text-sm font-bold rounded-xl hover:bg-blue-600 transition-all">
          Let's talk
        </NuxtLink>
      </div>

      <button @click="toggleMenu" class="md:hidden flex flex-col justify-center items-center gap-1.5 w-10 h-10">
        <span :class="['w-6 h-0.5 bg-slate-900 transition-all', isMenuOpen ? 'rotate-45 translate-y-2' : '']"></span>
        <span :class="['w-6 h-0.5 bg-slate-900 transition-all', isMenuOpen ? 'opacity-0' : '']"></span>
        <span :class="['w-6 h-0.5 bg-slate-900 transition-all', isMenuOpen ? '-rotate-45 -translate-y-2' : '']"></span>
      </button>
    </div>

    <Transition
      enter-active-class="transition duration-300 ease-out"
      enter-from-class="opacity-0"
      enter-to-class="opacity-100"
      leave-active-class="transition duration-200 ease-in"
      leave-from-class="opacity-100"
      leave-to-class="opacity-0"
    >
      <div v-if="isMenuOpen" class="fixed inset-0 bg-white z-[90] md:hidden flex flex-col justify-center items-center">
        <div class="flex flex-col space-y-8 text-center">
          <NuxtLink 
            v-for="item in navItems" 
            :key="item.path" 
            :to="item.path"
            @click="closeMenu"
            class="text-5xl font-black text-slate-900 tracking-tighter active:text-blue-600"
          >
            {{ item.name }}
          </NuxtLink>
          <NuxtLink 
            to="#contact" 
            @click="closeMenu"
            class="text-2xl font-bold text-blue-600"
          >
            Contact
          </NuxtLink>
        </div>
      </div>
    </Transition>
  </nav>
</template>

<script setup>
const isScrolled = ref(false)
const isMenuOpen = ref(false)

const navItems = [
  { name: 'About', path: '#about' },
  { name: 'Projects', path: '#projects' },
  { name: 'Services', path: '#services' },
]

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value
  // Bloqueamos el scroll del body cuando el menú está abierto
  if (isMenuOpen.value) {
    document.body.style.overflow = 'hidden'
  } else {
    document.body.style.overflow = 'auto'
  }
}

const closeMenu = () => {
  isMenuOpen.value = false
  document.body.style.overflow = 'auto'
}

onMounted(() => {
  window.addEventListener('scroll', () => {
    isScrolled.value = window.scrollY > 20
  })
})
</script>