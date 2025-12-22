<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
<style>
/* 1. Definimos las animaciones con CSS puro */
@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes zoomIn {
  from {
    opacity: 0;
    transform: scale(0.8);
  }
  to {
    opacity: 1;
    transform: scale(1);
  }
}

/* 2. Creamos clases de utilidad para usarlas en tus componentes */
.animate-fade-in-up {
  animation: fadeInUp 0.6s ease-out forwards;
}

.animate-zoom-in {
  animation: zoomIn 0.5s ease-out forwards;
}

/* 3. Agregamos delays manuales */
.delay-100 { animation-delay: 0.1s; }
.delay-200 { animation-delay: 0.2s; }
.delay-300 { animation-delay: 0.3s; }

/* Importante: Para que las animaciones no parpadeen al inicio */
.animate-fade-in-up, .animate-zoom-in {
  opacity: 0;
}
</style>