<template>
  <section class="relative">

    <!-- Bg gradient -->
    <div class="absolute top-0 left-0 right-0 bg-gradient-to-b from-gray-800 to-gray-900 opacity-60 h-[10rem] pointer-events-none -z-10" aria-hidden="true"></div>

    <!-- Bg illustration -->
    <div class="absolute top-0 left-1/2 -z-10 ml-[390px]" aria-hidden="true">
      <img src="../images/features-illustration.svg" class="max-w-none" width="608" height="305" alt="Illustration">
    </div>

    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="py-12 md:py-20">

        <!-- Section header -->
        <div class="max-w-3xl mx-auto text-center pb-12 md:pb-20">
          <h2 class="h2 font-uncut-sans mb-4">Controla toda tu producción</h2>
          <div class="max-w-2xl mx-auto">
            <p class="text-xl text-gray-400">Conecta <b>múltiples máquinas</b> al sistema y centraliza el control de fabricación de manera remota.</p>
          </div>
        </div>

        <!-- Section content -->
        <div class="max-w-xl mx-auto md:max-w-none flex flex-col md:flex-row md:items-center md:space-x-8 lg:space-x-16 xl:space-x-18 space-y-8 space-y-reverse md:space-y-0">

          <!-- Content -->
          <div class="md:w-7/12 lg:w-1/2 order-1 md:order-none" data-aos="zoom-out" data-aos-delay="200">
            <div class="text-center md:text-left">
              <h3 class="h3 font-uncut-sans text-4xl mb-4">Utilidades</h3>
              <p class="text-xl text-gray-400 mb-6">Software adaptable a tus necesidades, conectamos todos tus equipos.</p>
              <ul class="inline-flex flex-col text-lg text-gray-400 space-y-3 mb-10">
                <li class="flex items-center">
                  <svg class="w-3 h-3 fill-current text-emerald-500 mr-3 shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                    <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                  </svg>
                  <span>Informes Legales para Auditorías</span>
                </li>
                <li class="flex items-center">
                  <svg class="w-3 h-3 fill-current text-emerald-500 mr-3 shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                    <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                  </svg>
                  <span>Control de Peso Promedio en Continuo</span>
                </li>
                <li class="flex items-center">
                  <svg class="w-3 h-3 fill-current text-emerald-500 mr-3 shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                    <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                  </svg>
                  <span>Alertas de rendimiento</span>
                </li>
                <li class="flex items-center">
                  <svg class="w-3 h-3 fill-current text-emerald-500 mr-3 shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                    <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                  </svg>
                  <span>Adquisición de Datos</span>
                </li>
                <li class="flex items-center">
                  <svg class="w-3 h-3 fill-current text-emerald-500 mr-3 shrink-0" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg">
                    <path d="M10.28 2.28L3.989 8.575 1.695 6.28A1 1 0 00.28 7.695l3 3a1 1 0 001.414 0l7-7A1 1 0 0010.28 2.28z" />
                  </svg>
                  <span>Resúmenes y Conclusiones</span>
                </li>
              </ul>
            </div>
          </div>

          <!-- Image -->
          <div class="md:w-5/12 lg:w-1/2" data-aos="zoom-out">
            <img class="mx-auto md:max-w-none" src="../images/production-2.jpg" width="640" height="581" alt="Features" style="filter: opacity(80%);"/>
          </div>

        </div>

      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Features02',
}
</script>