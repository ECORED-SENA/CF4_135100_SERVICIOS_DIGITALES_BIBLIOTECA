<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Evaluación del servicio

    .cont_3_1(style="position:relative;")
      .row
        .col-lg-7.mb-4.mb-lg-0(style="place-self:center;position:relative")
          p(data-aos="fade-up") La gestión de evaluar las actividades que realiza la biblioteca y el impacto que tiene el servicio en los usuarios, en el cumplimiento de los requerimientos, ayuda a la creación de estrategias de mejora en la prestación de la oferta a la comunidad.
          .p-4.row.mt-4.m-0(style="background-color:#EBC9B1;border-radius:10px;")
            .col-auto.d-none.d-lg-block(style="place-self:center")
              figure
                img(src="@/assets/curso/tema3/2.png" data-aos="fade-right")
            .col(style="place-self:center")
              p.mb-0(data-aos="fade-up") Con base en la evaluación y las realimentaciones surgidas en este proceso, se logrará tener evidencia de si se están ejecutando, o no, los objetivos relacionados con responder a las necesidades de la comunidad y usuarios impactados. 
        .col-lg-5(style="place-self:center;position:relative")
          figure
            img(src="@/assets/curso/tema3/1.png" data-aos="fade-left")

      Separador.mt-5

      .titulo-segundo(style="position:relative")
        h2#t_3_1 3.1 Propósito y técnicas de medición

      p(data-aos="fade-up" style="position:relative") El propósito de la evaluación del servicio es garantizar el cumplimiento de los requerimientos y necesidades de los usuarios, superando sus expectativas por medio de la retroalimentación del mismo cliente, ya que gracias a ello se pueden tomar las medidas y estrategias para tal fin.

      .row.mt-5
        .col-lg-5.mb-4.mb-lg-0(style="place-self:center;position:relative")
          figure
            img(src="@/assets/curso/tema3/3.png" data-aos="fade-left")
        .col-lg-7(style="place-self:center;position:relative")
          .row.m-0.pt-4.pb-4.pe-4.ps-0.ps-sm-4.ps-md-4.ps-lg-0(style="background-color:#EBC9B1;")
            .col-auto.d-none.d-lg-block.p-0(style="place-self:center")
              figure
                img(src="@/assets/curso/tema2/13.png" data-aos="fade-right")
            .col(style="place-self:center")
              p.mb-0(data-aos="fade-up") En relación con los propósitos y técnicas de medición en la biblioteca, se invita a visualizar con atención el siguiente video y procurar llevar registro de lo más destacado en la libreta personal de apuntes.

      figure.mt-5(style="position:relative")
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .tarjeta.color-primario.p-4.mt-5.cont_sintesis.m-auto.mt-5.col-lg-10.m-auto(style="position:relative")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1.text-center
          img(src="@/assets/curso/tema1/28.png" data-aos="fade-right" style="max-width:90px;display:inline;")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h5.text-white(data-aos="fade-up") ¡Atención!
              p.text-white.mt-3(data-aos="fade-up") Existen innumerables técnicas de medición en las bibliotecas; su aplicación se puede hacer de forma física o virtual. Lo importante es entender que su elección se hace según las necesidades que busca satisfacer la biblioteca.

    Separador.mt-5

    .titulo-segundo
      h2#t_3_2 3.2 Recolección de información

    p(data-aos="fade-up") En la gestión de la evaluación del servicio se deben aplicar #[strong(style="color:#FD9827;") herramientas de recolección de datos] que suministren la información necesaria, con la que se logre un análisis que permita generar #[strong(style="color:#FD9827;") estrategias y toma de decisiones], en el proceso de mejora continua de la biblioteca.


    .cont_3_2.mt-5.pb-5.pt-5(style="position:relative")
      h5(data-aos="fade-up" style="position:relative") En el siguiente esquema se exponen las principales herramientas de recolección de datos que se usan en la biblioteca.
      TabsB.color-secundario.mt-5.bg-white(style="position:relative")
        .py-4.py-md-5(titulo="Cuestionario" :icono="require('@/assets/curso/tema3/5.png')")
          .row.p-4
            .col-md-6.mb-4.mb-md-0(style="place-self:center")
              p #[strong Cuestionario:] es una herramienta que usan las bibliotecas para obtener datos cuantitativos desde calificar de 1 a 10 las instalaciones hasta medir el nivel de conocimiento que adquieren los usuarios.
            .col-md-4(style="place-self:center")
              figure.text-center
                img(src='@/assets/curso/tema3/10.png' style="max-width:180px;display:inline")
        .py-4.py-md-5(titulo="Entrevista" :icono="require('@/assets/curso/tema3/6.png')")
          .row.p-4
            .col-md-6.mb-4.mb-md-0(style="place-self:center")
              p #[strong Entrevista:] se hace mediante preguntas de carácter cualitativo que den respuesta a las necesidades de información de la biblioteca como su experiencia, servicio y demás.
            .col-md-4(style="place-self:center")
              figure.text-center
                img(src='@/assets/curso/tema3/11.png' style="max-width:180px;display:inline")
        .py-4.py-md-5(titulo="Observación" :icono="require('@/assets/curso/tema3/7.png')")
          .row.p-4
            .col-md-6.mb-4.mb-md-0(style="place-self:center")
              p #[strong Observación:] se basa desde mirar el entorno de la comunidad, sus hábitos, realidad, cultura, según la necesidad de información.
            .col-md-4(style="place-self:center")
              figure.text-center
                img(src='@/assets/curso/tema3/12.png' style="max-width:180px;display:inline")
        .py-4.py-md-5(titulo="Grupos focales:" :icono="require('@/assets/curso/tema3/8.png')")
          .row.p-4
            .col-md-6.mb-4.mb-md-0(style="place-self:center")
              p #[strong Grupos focales:] se utiliza con frecuencia dentro de la comunidad como juntas de acción comunal, educativas, religiosas y demás.
            .col-md-4(style="place-self:center")
              figure.text-center
                img(src='@/assets/curso/tema3/13.png' style="max-width:180px;display:inline")
        .py-4.py-md-5(titulo="Comunidad en línea" :icono="require('@/assets/curso/tema3/9.png')")
          .row.p-4
            .col-md-6.mb-4.mb-md-0(style="place-self:center")
              p #[strong Comunidad en línea:] se toman por medio de las redes sociales y comunidades en la red.
            .col-md-4(style="place-self:center")
              figure.text-center
                img(src='@/assets/curso/tema3/14.png' style="max-width:180px;display:inline")

    h5.mt-5(data-aos="fade-up") Ahora, se debe prestar especial atención a los siguientes aspectos relacionados con la recolección de información:

    .col-lg-10.m-auto.mt-5.row
      .col-lg-4.mb-4.mb-lg-0
        .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
          .row.justify-content-center.mb-3
            .col-8.m-auto.text-center
              img(src='@/assets/curso/tema3/15.png')
          h5.text-center.text-center.text-white Ser activos siempre
          p.text-center.text-center.text-white Realizarán actividades de recolección de información presencial o digital.
      .col-lg-4.mb-4.mb-lg-0
        .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
          .row.justify-content-center.mb-3
            .col-8.m-auto.text-center
              img(src='@/assets/curso/tema3/16.png')
          h5.text-center.text-center.text-white Fortalecer su identidad de servicio
          p.text-center.text-center.text-white Deberán guardar conciencia de su función y sentirse parte de la gestión de la calidad en la biblioteca.
      .col-lg-4.mb-4.mb-lg-0
        .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
          .row.justify-content-center.mb-3
            .col-8.m-auto.text-center
              img(src='@/assets/curso/tema3/17.png')
          h5.text-center.text-center.text-white Ser protagonistas
          p.text-center.text-center.text-white Se reconocerán como garantes de la mejora continua de la biblioteca.

    Separador.mt-5

    .titulo-segundo
      h2#t_3_3 3.3 Informes

    .row
      .col-lg-7.mb-4.mb-lg-0(style="place-self:center")
        p(data-aos="fade-up") Los informes en biblioteca son documentos que contienen información completa de las actividades ejecutadas o resultados obtenidos durante un periodo determinado y tienen como finalidad retroalimentar al lector o a la dirección de la entidad para generar planes de acción.
        .row.m-0.pt-4.pb-4.pe-4.ps-0.ps-sm-4.ps-md-4.ps-lg-0(style="background-color:#EBC9B1;")
          .col-auto.d-none.d-lg-block.p-0(style="place-self:center")
            figure
              img(src="@/assets/curso/tema2/13.png" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") Las bibliotecas cuentan con procesos estratégicos, misionales y de apoyo que hacen posible la gestión diaria de esta; dichos procesos, a su vez, cuentan con unos subprocesos que pueden ser de planeación, atención al cliente, compras, gestión humana y demás.
      .col-lg-5(style="place-self:center")
        figure
          img(src="@/assets/curso/tema3/18.png" data-aos="fade-left")
    
    .tarjeta.color-primario.p-4.mt-5.cont_sintesis.m-auto.mt-5.col-lg-10.m-auto(style="position:relative")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1.text-center
          img(src="@/assets/curso/tema1/28.png" data-aos="fade-right" style="max-width:90px;display:inline;")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h5.text-white(data-aos="fade-up") ¡Nota!
              p.text-white.mt-3(data-aos="fade-up") Los procesos o subprocesos en la gestión de las bibliotecas, o de cualquier entidad en su gestión, deben presentar o rendir informes sin importar su grado o nivel jerárquico, por consiguiente, es importante conocer los tipos de informes apropiados para cada caso y cómo elaborarlos.

    h5.mt-5(data-aos="fade-up") Se invita a ampliar sus conocimientos en lo relacionado con los informes y tipos de informes en la gestión de la biblioteca:

    .p-5.mt-5.cont_3_3(style="border-radius:25px;")
      .row
        .col-lg-6.mb-4.mb-lg-0(style="place-self:center;")
          SlyderA(tipo="b" style="background-color:#FFF7EF;border-radius:25px;")
            .row.p-5
              h4(style="color:#FD9827;") Por su naturaleza
              p.mt-4 Estos informes usan un lenguaje técnico o científico para responder a una investigación básica o especializada, divulgando la información a un sector especifico o general.
            .row.p-5
              h4(style="color:#FD9827;") Por su contenido
              ul.fa-ul.mt-4
                li.mb-2(data-aos="fade-up")
                  i.fa.fa-li.fa-check(style="color:#FFBA5B;") 
                  | #[strong Expositivo:] brinda información.
                li.mb-2(data-aos="fade-up")
                  i.fa.fa-li.fa-check(style="color:#FFBA5B;") 
                  | #[strong Interpretativo:] argumenta y analiza datos.
                li.mb-2(data-aos="fade-up")
                  i.fa.fa-li.fa-check(style="color:#FFBA5B;") 
                  | #[strong Demostrativo:] dictamina una situación específica.
                li.mb-2(data-aos="fade-up")
                  i.fa.fa-li.fa-check(style="color:#FFBA5B;") 
                  | #[strong Persuasivo:] convence al lector sobre un tema e influye en la toma de decisiones.
            .row.p-5
              h4(style="color:#FD9827;") Autónomos
              p.mt-4 Son los que se realizan por parte de los procesos o subprocesos, dando cuenta de su gestión diaria.
            .row.p-5
              h4(style="color:#FD9827;") Financieros
              p.mt-4 Son los que se generan para brindar la información económica de la biblioteca para la toma de decisiones.
            .row.p-5
              h4(style="color:#FD9827;") Administrativos
              p.mt-4 Son los que rinden cuentas del estado general de la biblioteca o el manejo actual de sus recursos: financieros, personal, infraestructura, tecnológico, teniendo en cuenta el marco legal.
            .row.p-5
              h4(style="color:#FD9827;") Sectoriales
              p.mt-4 Brindan información del estado de la comunidad, preferencias de los usuarios y actualidad general, sirven como insumo para generar estrategias de marketing, entre otras. 
        .col-lg-6(style="place-self:center;")
          figure
            img(src="@/assets/curso/tema3/19.png" data-aos="fade-right")

    h5.mt-5(data-aos="fade-up") Por otro lado, para el proceso de elaboración de informes se deben tener en cuenta aspectos propios como:

    .row.mt-5
      .col-lg-5.mb-4.mb-lg-0(style="place-self:center")
        figure
          img(src="@/assets/curso/tema3/20.png" data-aos="fade-right")
      .col-lg-7(style="place-self:center")
        TabsA.color-acento-contenido
          .tarjeta.color-primario.p-5(titulo="Título del <br> informe" style="background-color:#DDD4D1;border-radius:10px")
            .row
              p.mb-0(style="color:#12263F;") Elaborar un título que permita identificar el tema.
          .tarjeta.color-primario.p-5(titulo="Introducción" style="background-color:#DDD4D1;border-radius:10px")
            .row
              p.mb-0(style="color:#12263F;") Contextualizar, por medio de una breve introducción, el contenido del informe que permita al lector tener una clara idea sobre el tema.
          .tarjeta.color-primario.p-5(titulo="Objetivos" style="background-color:#DDD4D1;border-radius:10px")
            .row
              p.mb-0(style="color:#12263F;") Plasmar los objetivos que facilita el análisis del informe.
          .tarjeta.color-primario.p-5(titulo="Contenido" style="background-color:#DDD4D1;border-radius:10px")
            .row
              p.mb-0(style="color:#12263F;") Redactar el contenido en donde se describa la gestión del proceso, subproceso o área y relate la idea principal del documento.
          .tarjeta.color-primario.p-5(titulo="Resultados" style="background-color:#DDD4D1;border-radius:10px")
            .row
              p.mb-0(style="color:#12263F;") Escribir los resultados obtenidos que demuestran la eficiencia y efectividad de la gestión realizada.
          .tarjeta.color-primario.p-5(titulo="Conclusiones" style="background-color:#DDD4D1;border-radius:10px")
            .row
              p.mb-0(style="color:#12263F;") Por último, redactar una breve conclusión que evidencie los hallazgos principales, plasmados en el informe y que sean clave para la toma de decisiones.

    .cont_3_4.pb-5.mt-5.pt-5(style="position:relative")
      .row.p-4.m-0(style="background-color:#ECEFC8;position:relative")
        .col-auto.d-none.d-md-block(style="place-self:center")
          figure
            img(src="@/assets/curso/tema3/21.png" data-aos="fade-right")
        .col(style="place-self:center")
          p.mb-0(data-aos="fade-up") El seguimiento de los pasos para la elaboración del informe requiere tener en cuenta y, a la vez, aplicar un procedimiento que vincula planificación, alistamiento de herramientas, uso de terminología adecuada, incluir factores o puntos de comparación, apoyo gráfico e ilustrativo, entre otras.
      h5.mt-5(data-aos="fade-up" style="position:relative") A continuación, se explican en detalle, los aspectos de dicho procedimiento, previo al informe:
      ul.fa-ul.mt-5
        li.mb-2(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FFBA5B;") 
          | #[strong Planificación:] en esta fase establecer para quien es el informe, la finalidad, qué datos se utilizarán y cómo ayuda en la gestión del proceso.
        li.mb-2(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FFBA5B;") 
          | #[strong Herramientas:] identificar el medio o herramienta para la elaboración del informe.
        li.mb-2(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FFBA5B;") 
          | #[strong Termínologia:] acorde al lector, establecer qué tipo de lenguaje se utilizará, si técnico o científico con el fin de garantizar su comprensión.
        li.mb-2(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FFBA5B;") 
          | #[strong Empatía:] redactar el contenido de forma estratégica que permita que el lector se apropie del mismo y se sienta parte de él.
        li.mb-2(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FFBA5B;") 
          | #[strong Comparación:] crear factores o puntos de comparación que permitan entender la situación actual de lo que se quiere informar.
        li.mb-2(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FFBA5B;") 
          | #[strong Visualización:] apoyar la redacción e información con gráficas o imágenes que apoyen la comprensión y análisis.
        li.mb-2(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FFBA5B;") 
          | #[strong Revisión:] leer todo el documento e identificar que este claro entendible sin errores ortográficos ni normativos.




</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass">
.cont_3_1:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 80%
  background: url(../assets/curso/tema1/27.png)
  background-size: cover
  background-repeat: no-repeat
  top: -50px
.cont_sintesis
  background: url(../assets/curso/s1.png)
  background-size: cover
  background-repeat: no-repeat
.cont_3_2:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 110%
  background: url(../assets/curso/tema3/4.png)
  background-size: cover
  background-repeat: no-repeat
  top: 0
.tabs-b__tab
  border: 0
  border-right: 2px #E8E8E8 solid
.tabs-b.color-secundario .tabs-b__tab--active
  border: 0
.cont_tarjetas
  background: url(../assets/curso/tema1/17.png)
  background-size: 100% 100%
  background-repeat: no-repeat
  min-height: 400px
.cont_tarjetas img
  max-width: 100px
  display: inline
.cont_3_3
  background: url(../assets/curso/tema2/4.png)
  background-size: cover
  background-repeat: no-repeat
.cont_3_3 .slyder-a__tipo-b
  padding: 1rem
.cont_3_3 .slyder-a__bullets__item
  background-color: #FEDBB4
.cont_3_3 .slyder-a__bullets__item--active
  background-color: #FD9827 !important
.cont_3_3 .slyder-a__btn--sigt, .slyder-a__btn--atrs
  background-color: #C0C942
  opacity: 1
.tabs-a__tab
  background-color: #E8E8E8
.cont_3_4:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 100%
  background: url(../assets/curso/tema1/27.png)
  background-size: cover
  background-repeat: no-repeat
  bottom: 0
</style>
