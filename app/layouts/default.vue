<template>
  <div class="min-h-screen flex flex-col antialiased">
    <Navbar />

    <main class="flex-grow">
      <slot />
    </main>

    <Footer />
  </div>
</template>

<style>
/* Estilos globales de transición o scroll */
html {
  scroll-behavior: smooth;
}

body {
  @apply font-sans text-slate-900 bg-white;
}

/* Opcional: Transición suave entre páginas si decides añadir más */
.page-enter-active,
.page-leave-active {
  transition: opacity 0.3s;
}
.page-enter-from,
.page-leave-to {
  opacity: 0;
}
</style>