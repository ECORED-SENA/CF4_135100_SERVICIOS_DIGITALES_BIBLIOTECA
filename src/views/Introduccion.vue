<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .tarjeta.color-primario.p-5.mb-5.cont_intro(style="background-color:transparent;")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-2
          img(src="@/assets/curso/intro2.png" data-aos="fade-right")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              p.mb-0(data-aos="fade-up" style="color:#12263F;") Tenga una cordial bienvenida al estudio del componente formativo #[strong(style="color:#FD9827;") “Verificación del servicio bibliotecario e informes”.] #[br] Para comenzar, visualice el video que se muestra enseguida. #[strong(style="color:#FD9827;") ¡Éxitos!]

    figure.mt-5(style="position:relative")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/brGzAdPO7sg" title="Servicios digitales de bibliotecas" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
 

    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass">
.cont_intro
  background: url(../assets/curso/intro1.png)
  background-size: cover
  background-repeat: no-repeat
</style>
