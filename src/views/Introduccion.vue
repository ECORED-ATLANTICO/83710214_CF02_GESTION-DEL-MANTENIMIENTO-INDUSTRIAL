<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    p.my-3 El componente formativo ejecución de actividades y <em>software</em> para órdenes de trabajo, se enfoca en describir la implementación y ejecución de las actividades programadas de mantenimiento a través de un estricto control y seguimiento por parte del área de mantenimiento. Esta labor es engorrosa, sensible al error humano y requiere mucho tiempo en su etapa de implementación y puesta en marcha. Es por esto, que se recurre a herramientas computacionales que permitan planificar y organizar las acciones del mantenimiento. Bienvenido a este componente formativo:
    
    .video
      iframe(width="560" height="315" src="https://www.youtube.com/embed/t9w1Ruvco-s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    figcaption Nota: Sena (2024).


    
  
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
