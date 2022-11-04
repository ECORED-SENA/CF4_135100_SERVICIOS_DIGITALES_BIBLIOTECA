<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Servicios bibliotecarios

    .cont_2_1(style="position:relative;")
      .row
        .col-lg-3.mb-4.mb-lg-0
          p(data-aos="fade-up") El propósito de las bibliotecas es facilitar el libre acceso de información a la comunidad para fomentar el desarrollo sostenible, a través de la consulta y otros servicios que posibilitan al usuario mejorar sus capacidades de conocimiento e investigación.
        .col-lg-3.mb-4.mb-lg-0
          figure
            img(src="@/assets/curso/tema2/2.png" data-aos="zoom-in-up")
        .col-lg-6
          h5(data-aos="fade-up") Los principales servicios prestados por bibliotecas suelen ser, entre algunos otros:
          .p-4.mt-5(style="border-radius:15px;background-color:#EBC9B1;position:relative")
            ul.fa-ul
              li.mb-2(data-aos="fade-up")
                i.fa.fa-li.fa-check(style="color:#FD9827;")
                | Préstamo de libros y equipos.
              li.mb-2(data-aos="fade-up")
                i.fa.fa-li.fa-check(style="color:#FD9827;")
                | Consulta física y virtual de contenido.
              li.mb-2(data-aos="fade-up")
                i.fa.fa-li.fa-check(style="color:#FD9827;")
                | Servicio de internet, herramientas ofimáticas, informáticas y digitales.
              li.mb-2(data-aos="fade-up")
                i.fa.fa-li.fa-check(style="color:#FD9827;")
                | Asesoría para consulta e investigaciones.
              li.mb-2(data-aos="fade-up")
                i.fa.fa-li.fa-check(style="color:#FD9827;")
                | Referenciación en línea o bibliografía en línea.
              li.mb-2(data-aos="fade-up")
                i.fa.fa-li.fa-check(style="color:#FD9827;")
                | Capacitación y formación presencial o en línea.
              li.mb-2(data-aos="fade-up")
                i.fa.fa-li.fa-check(style="color:#FD9827;")
                | Alfabetización informacional.
              li.mb-2(data-aos="fade-up")
                i.fa.fa-li.fa-check(style="color:#FD9827;")
                | Servicios de georreferenciación.
              li.mb-2(data-aos="fade-up")
                i.fa.fa-li.fa-check(style="color:#FD9827;")
                | Actividades culturales y de apoyo a la comunidad.

      .tarjeta.color-primario.p-4.mt-5.cont_sintesis.col-lg-10.m-auto(style="position:relative")
        .row.justify-content-around.align-items-center
          .col-3.col-sm-2.col-lg-1.text-center
            img(src="@/assets/curso/tema1/28.png" data-aos="fade-right" style="max-width:90px;display:inline;")
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0(style="position:relative")
                h5.text-white(data-aos="fade-up") ¡Tenga presente!
                .indicador--click(v-if="mostrarIndicadorTarjetaAudio")
                TarjetaAudio.color-secundario.mb-3(
                  texto=""
                  :audio="require('@/assets/componentes/audios/servicios_bibliotecarios.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false"
                )

      Separador.mt-5

      .titulo-segundo(style="position:relative")
        h2#t_2_1 2.1  Procesos y procedimientos

      p(data-aos="fade-up" style="position:relative") La gestión en la biblioteca lleva un orden, según especificaciones y exigencias de las actividades que se plasman en procesos y procedimientos. Los procesos tienen que ver con las actividades de gestión y los procedimientos hacen referencia a los métodos utilizados para la gestión de procesos en la biblioteca.

      .bloque-texto-g.color-acento-botones.p-4.p-sm-4.p-md-5.col-lg-10.m-auto.mt-5
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/tema2/3.png')})`}"
        )
        .bloque-texto-g__texto.p-5
          p.mb-0 En lo relativo a los procesos, entiéndase como el conjunto de actividades de gestión que tienen una secuencia lógica con unas entradas, transformación y salidas, con el propósito de elaborar o cambiar un producto y/o actividad en la biblioteca, que se ve reflejado en áreas o dependencias.

    h5.mt-5(data-aos="fade-up") A continuación, se presentan algunos aspectos clave relativos a los procesos en bibliotecas:

    .p-5.mt-5.cont_2_2(style="border-radius:25px;")
      .row
        .col-lg-6.mb-4.mb-lg-0(style="place-self:center;")
          SlyderA(tipo="b" style="background-color:#FFF7EF;border-radius:25px")
            .row.p-5
              h4 Procesos estratégicos
              p Son los que definen las responsabilidades, políticas y direccionamiento de la biblioteca.
              p.mt-4 #[strong Ejemplo:] procesos de planificación, mejora continua, desarrollo tecnológico, proyectos y relacionamiento.
            .row.p-5
              h4 Procesos misionales
              p Son los enfocados a prestar, de forma directa, el servicio a los usuarios.
              p.mt-4 #[strong Ejemplo:] procesos de atención al cliente, investigación docente, donaciones, formación y capacitación a usuarios.
            .row.p-5
              h4 Procesos de apoyo
              p Son los que brindan soporte a todos los procesos. 
              p.mt-4 #[strong Ejemplo:] caja o facturación, gestión humana, compras, mantenimiento, seguridad.
        .col-lg-6(style="place-self:center;")
          figure
            img(src="@/assets/curso/tema2/5.png" data-aos="fade-left")

    h5.mt-5(data-aos="fade-up") En lo relacionado con los procedimientos, hay que tener presentes los siguientes aspectos:

    .p-5.mt-5.cont_2_2(style="border-radius:25px;")
      .row
        .col-lg-6.mb-4.mb-lg-0(style="place-self:center;")
          figure
            img(src="@/assets/curso/tema2/6.png" data-aos="fade-right")
        .col-lg-6(style="place-self:center;")
          SlyderA(tipo="b" style="background-color:#FFF7EF;border-radius:25px")
            .row.p-5
              h4 Procedimientos estratégicos
              p Son los pasos que se aplican para crear políticas y direccionamiento de la biblioteca.
              p.mt-4 #[strong Ejemplo:] pasos para entrega y creación de proyectos en la biblioteca.
            .row.p-5
              h4 Procedimientos misionales
              p Es la forma de atención al usuario y las actividades que se deben desarrollar para satisfacer sus necesidades.
              p.mt-4 #[strong Ejemplo:] actividades para crear un plan de formación y capacitación a usuarios.
            .row.p-5
              h4 Procedimientos apoyo
              p Son las actividades que se realizan para dar soporte a todos los procesos. 
              p.mt-4 #[strong Ejemplo:] pasos para hacer requisición de personal nuevo para atención al usuario y actividades de contratación que den respuesta.

    p.mt-5(data-aos="fade-up") Ahora, se invita a analizar el esquema que se muestra y reconocer en él el ejemplo que se muestra sobre un proceso y procedimiento en la biblioteca.

    .titulo-sexto.color-primario.mt-5
      h5 Figura 1.
      span Ejemplo de proceso y procedimiento en biblioteca
    figure.col-lg-9.m-auto
      img(src="@/assets/curso/tema2/7.svg" data-aos="zoom-in-up")

    Separador.mt-5

    .titulo-segundo
      h2#t_2_2 2.2 Objetivos e indicadores de calidad

    p(data-aos="fade-up") Los procesos en las bibliotecas tienen unos objetivos determinados por su naturaleza como, por ejemplo, garantizar el servicio al usuario, cumplir con la misión y visión, brindar una cobertura a la comunidad y demás. Por ende, deben estar en continuo seguimiento medible para verificar el cumplimiento de estos.

    .row.col-lg-10.m-auto.mt-5
      .col-lg-9.p-0
        .p-4(style="background-color:#EBC9B1;height:100%;")
          p.mb-0(data-aos="fade-up") Estas actividades de medición se realizan a través de unos #[strong indicadores de calidad] en donde se establecen #[strong metas y mecanismos] de acción para garantizar el buen funcionamiento de los procesos dentro de la biblioteca y dar, como resultado, una gestión óptima de la entidad.
      .col-lg-3.p-0
        .p-4(style="background-color:#785549;height:100%;")
          figure.text-center
            img(src="@/assets/curso/tema2/8.png" data-aos="fade-left" style="max-width:140px;display:inline")

    .tarjeta.color-primario.p-4.mt-3.cont_sintesis.col-lg-10.m-auto(style="position:relative")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1.text-center
          img(src="@/assets/curso/tema2/9.png" data-aos="fade-right" style="max-width:100px;display:inline;")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h5.text-white(data-aos="fade-up") ¿Qué es un indicador de calidad?
              p.mt-3.text-white(data-aos="fade-up") Un indicador de calidad es una herramienta de medición cuantitativa que permite valorar, de forma cualitativa, el grado de cumplimiento de un objetivo o meta específica en la biblioteca.


    .col-lg-10.m-auto.mt-4.cont_2_3.p-5
      h5(data-aos="fade-up") En la biblioteca, se pueden encontrar varios indicadores, tales como:
      .row.col-lg-9.m-auto.mt-5
        .col-lg-7.mb-4.mb-lg-0
          ul.fa-ul
            li.mb-2(data-aos="fade-up")
              i.fa.fa-li.fa-check(style="color:#FD9827;")
              | Indicador de rendimiento operacional.
            li.mb-2(data-aos="fade-up")
              i.fa.fa-li.fa-check(style="color:#FD9827;")
              | Indicador de visitas.
            li.mb-2(data-aos="fade-up")
              i.fa.fa-li.fa-check(style="color:#FD9827;")
              | Indicador de servicio.
            li.mb-2(data-aos="fade-up")
              i.fa.fa-li.fa-check(style="color:#FD9827;")
              | Indicador de impacto de las actividades.
        .col-lg-5
          figure.text-center
            img(src="@/assets/curso/tema2/11.png" data-aos="fade-left" style="max-width:150px;display:inline")

    p.mt-5(data-aos="fade-up") En la tabla que se muestra a continuación, se expresa el indicador de préstamos de libros; se sugiere dar atención a los aspectos clave y llevar nota de lo más destacado en una libreta personal de apuntes:

    .titulo-sexto.color-primario.mt-5
      h5 Tabla 2.
      span  Ejemplo de indicador de calidad en un proceso de la biblioteca


    .tabla-a.color-acento-botones.mt-5.col-lg-10.m-auto
      table
        thead(style="border:0;")
          tr
            th.p-3(style="width:60%;background-color:#EBC9B1;border:0;" colspan="2") Indicador de calidad
            th.p-3(style="background-color:#EFEFEF;border:0;" colspan="2") Meta
        tbody
          tr
            td.p-3(style="border:0;border-bottom:1px #D6CAC2 solid;background-color:#FFF3EA;" colspan="2") #[strong Proceso:] préstamo de libros
            td.p-3(style="border:0;background-color:#F5F5F5;" rowspan="2" colspan="2") 95%
          tr
            td.p-3(style="border:0;border-bottom:1px #D6CAC2 solid;background-color:#FFF3EA;" colspan="2") #[strong Objetivo:] cumplir con la meta de préstamos de libros a los usuarios 
          tr
            td.p-3(style="border:0;border-bottom:1px #D6CAC2 solid;background-color:#FFF3EA;font-weight:bold;") Mes
            td.p-3(style="border:0;border-bottom:1px #D6CAC2 solid;background-color:#FFF3EA;font-weight:bold;") Préstamos
            td.p-3(style="border:0;background-color:#F5F5F5;font-weight:bold;") Disponibilidad
            td.p-3(style="border:0;background-color:#F5F5F5;font-weight:bold;") Cumplimiento
          tr
            td.p-3(style="border:0;border-bottom:1px #D6CAC2 solid;background-color:#FFF3EA;") Agosto
            td.p-3(style="border:0;border-bottom:1px #D6CAC2 solid;background-color:#FFF3EA;") 300
            td.p-3(style="border:0;background-color:#F5F5F5;") 800
            td.p-3(style="border:0;background-color:#F5F5F5;") 38%
          tr
            td.p-3(style="border:0;border-bottom:1px #D6CAC2 solid;background-color:#FFF3EA;font-weight:bold;") Análisis cualitativo
            td.p-3(style="border:0;border-bottom:1px #D6CAC2 solid;background-color:#FFF3EA;") Se presenta un incumplimiento al indicador debido a la poca afluencia a la biblioteca en el mes de agosto.
            td.p-3(style="border:0;background-color:#F5F5F5;" rowspan="2" colspan="2")
          tr
            td.p-3(style="border:0;border-bottom:1px #D6CAC2 solid;background-color:#FFF3EA;font-weight:bold;") Acciones de mejora
            td.p-3(style="border:0;border-bottom:1px #D6CAC2 solid;background-color:#FFF3EA;") Crear en el mes de septiembre actividades de promoción como planes lectores y culturales para que la afluencia aumente y así las solicitudes de libros.

    .tarjeta.color-primario.p-4.mt-5.cont_sintesis.col-lg-10.m-auto(style="position:relative")
        .row.justify-content-around.align-items-center
          .col-3.col-sm-2.col-lg-1.text-center
            img(src="@/assets/curso/tema1/28.png" data-aos="fade-right" style="max-width:90px;display:inline;")
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0
                h5.text-white(data-aos="fade-up") ¡Importante!
                p.mb-0.text-white(data-aos="fade-up") Los indicadores de calidad se crean según las necesidades de la biblioteca y deben corresponder a los objetivos de las misma.

    Separador.mt-5

    .titulo-segundo
      h2#t_2_3 2.3 Medios digitales

    .row
      .col-lg-7.mb-4.mb-lg-0(style="place-self:center")
        p(data-aos="fade-up") En la actualidad, las herramientas digitales se utilizan para solventar cualquier tipo de necesidad que requieren los clientes en las organizaciones, programas y proyectos. No es distinto en la gestión que se realiza en las bibliotecas, que han adoptado las herramientas para satisfacer las necesidades de sus usuarios y comunidades impactadas.
        .mt-4.row.m-0.pt-4.pb-4.pe-4.ps-0.ps-sm-4.ps-md-4.ps-lg-0(style="background-color:#EBC9B1;")
          .col-auto.d-none.d-lg-block.p-0(style="place-self:center")
            figure
              img(src="@/assets/curso/tema2/13.png" data-aos="fade-right")
          .col(style="place-self:center")
            p.mb-0(data-aos="fade-up") Entre los medios digitales y herramientas informáticas más usados en la actualidad, se pueden mencionar el internet, los diversos dispositivos electrónicos de todas las gamas, portales #[em web], portafolios en línea, aplicaciones, bibliotecas digitales, realidad virtual y muchos más…
      .col-lg-5(style="place-self:center")
        figure
          img(src="@/assets/curso/tema2/12.png" data-aos="fade-left")

    h5.mt-5(data-aos="fade-up") Pero, ¿qué se puede decir o saber de ellos?

    .col-lg-10.m-auto.mt-5
      SlyderF(columnas="col-lg-4")
        .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
          .row.justify-content-center.mb-3
            .col-8.m-auto.text-center
              img(src='@/assets/curso/tema2/14.png')
          h5.text-center.text-center.text-white Internet
          p.text-center.text-center.text-white Servicio por medio de conexión wifi para consulta de información, trabajos y demás necesidades.
        .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
          .row.justify-content-center.mb-3
            .col-8.m-auto.text-center
              img(src='@/assets/curso/tema2/15.png')
          h5.text-center.text-center.text-white Ordenadores y salas
          p.text-center.text-center.text-white Por medio de estas herramientas el usuario puede hacer consultas de la biblioteca virtual a través de las salas de sistemas o desde la comodidad de su casa.
        .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
          .row.justify-content-center.mb-3
            .col-8.m-auto.text-center
              img(src='@/assets/curso/tema2/16.png')
          h5.text-center.text-center.text-white Portales #[em web]
          p.text-center.text-center.text-white El usuario puede consultar información de la biblioteca y sus novedades.
        .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
          .row.justify-content-center.mb-3
            .col-8.m-auto.text-center
              img(src='@/assets/curso/tema2/17.png')
          h5.text-center.text-center.text-white Portafolios en línea y préstamos de equipos
          p.text-center.text-center.text-white Con los primeros, el usuario puede consultar los servicios de la biblioteca mientras que, con los segundos, puede consultar libros electrónicos.
        .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
          .row.justify-content-center.mb-3
            .col-8.m-auto.text-center
              img(src='@/assets/curso/tema2/18.png')
          h5.text-center.text-center.text-white Realidad virtual
          p.text-center.text-center.text-white Se utiliza para recrear el contenido de libros o información.
        .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
          .row.justify-content-center.mb-3
            .col-8.m-auto.text-center
              img(src='@/assets/curso/tema2/19.png')
          h5.text-center.text-center.text-white Formación en línea
          p.text-center.text-center.text-white Se genera por medio de las herramientas digitales o informáticas dando cobertura a personas que no pueden, o les es más fácil, acceder a capacitaciones presenciales.
        .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
          .row.justify-content-center.mb-3
            .col-8.m-auto.text-center
              img(src='@/assets/curso/tema2/20.png')
          h5.text-center.text-center.text-white Aplicaciones
          p.text-center.text-center.text-white Se usan para gestionar de forma personalizada transferencias de los servicios desde cualquier dispositivo móvil.
        .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
          .row.justify-content-center.mb-3
            .col-8.m-auto.text-center
              img(src='@/assets/curso/tema2/22.svg')
          h5.text-center.text-center.text-white Biblioteca digital
          p.text-center.text-center.text-white Se utiliza para prestar los servicios de la entidad en línea, ya sea consulta de libros, noticias, revistas, publicaciones, bases de información, capacitación, asesoría, actividades culturales como clubes de lectura y demás funciones que ofrezca la biblioteca.
        .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
          .row.justify-content-center.mb-3
            .col-8.m-auto.text-center
              img(src='@/assets/curso/tema2/23.svg')
          h5.text-center.text-center.text-white Canales digitales
          p.text-center.text-center.text-white Se utilizan como medio de comunicación con el usuario, ya sea por redes sociales o aplicativos.


    Separador.mt-5

    .titulo-segundo
      h2#t_2_4 2.4  Acciones correctivas en los servicios de biblioteca

    p(data-aos="fade-up") Las bibliotecas, en su gestión de mejora continua, crean procesos y procedimientos para mitigar las fallas que se presentan en la prestación del servicio al usuario. Se da por hecho, entonces, que las acciones correctivas son toda la gestión que se hace, de forma inmediata, para eliminar una situación o falla que se genera en la prestación del servicio al usuario brindando solución a los requerimientos expuestos.

    .cont_2_7.pb-5.mt-5.pt-5(style="position:relative")
      h5(data-aos="fade-up" style="position:relative") Algunos ejemplos de situaciones que se pueden presentar y, en su momento, requieren una acción correctiva son:
      .row.col-lg-10.m-auto(style="position:relative")
        .col-lg-6.mb-4.mb-lg-0(style="position:relative;place-self:center")
          ul.fa-ul.mt-5
            li.mb-2(data-aos="fade-up")
              i.fa.fa-li.fa-check(style="color:#FD9827;")
              | Falta de disponibilidad de libros o información.
            li.mb-2(data-aos="fade-up")
              i.fa.fa-li.fa-check(style="color:#FD9827;")
              | Fallas de conexión.
            li.mb-2(data-aos="fade-up")
              i.fa.fa-li.fa-check(style="color:#FD9827;")
              | Falta de información al usuario.
            li.mb-2(data-aos="fade-up")
              i.fa.fa-li.fa-check(style="color:#FD9827;")
              | Faltas en el servicio al cliente.
            li.mb-2(data-aos="fade-up")
              i.fa.fa-li.fa-check(style="color:#FD9827;")
              | Planes de fidelización. 
            li.mb-2(data-aos="fade-up")
              i.fa.fa-li.fa-check(style="color:#FD9827;")
              | Problemas de seguridad en la información.
            li.mb-2(data-aos="fade-up")
              i.fa.fa-li.fa-check(style="color:#FD9827;")
              | Condiciones de infraestructura.
        .col-lg-4(style="position:relative;place-self:center")
          figure.col-6.m-auto
            img(src="@/assets/curso/tema2/21.png" data-aos="fade-left")
        .tarjeta.color-primario.p-4.mt-5.cont_sintesis.m-auto(style="position:relative")
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1.text-center
              img(src="@/assets/curso/tema1/28.png" data-aos="fade-right" style="max-width:90px;display:inline;")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5.text-white(data-aos="fade-up") ¡Recuerde!
                  .indicador--click(v-if="mostrarIndicadorTarjetaAudio2")
                  TarjetaAudio.color-secundario.mb-3(
                    style="position:relative"
                    texto=""
                    :audio="require('@/assets/componentes/audios/acciones_correctivas_en_bibliotecas.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio2 = false"
                  )

      

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
    mostrarIndicadorTarjetaAudio2: true,
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
.cont_2_1:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 92%
  background: url(../assets/curso/tema2/1.png)
  background-size: cover
  background-repeat: no-repeat
  top: -50px
.cont_sintesis
  background: url(../assets/curso/s1.png)
  background-size: cover
  background-repeat: no-repeat
.cont_2_2
  background: url(../assets/curso/tema2/4.png)
  background-size: cover
  background-repeat: no-repeat
.slyder-a__tipo-b
  padding: 1rem
.slyder-a__bullets__item
  background-color: #A6A19B
.slyder-a__bullets__item--active
  background-color: #000 !important
.slyder-a__btn--sigt, .slyder-a__btn--atrs
  background-color: #C0C942
  opacity: 1
.cont_2_3
  background: url(../assets/curso/tema2/10.png)
  background-size: cover
  background-repeat: no-repeat
.cont_tarjetas
  background: url(../assets/curso/tema1/17.png)
  background-size: cover
  background-repeat: no-repeat
  min-height: 400px
.cont_tarjetas img
  max-width: 100px
  display: inline
.slyder-f__btn i
  background-color: #C0C942
  font-size: 19px
  padding: 0.8rem 1rem
  border-radius: 147px
.cont_2_7:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 100%
  background: url(../assets/curso/tema1/27.png)
  background-size: cover
  background-repeat: no-repeat
  bottom: 0
.indicador--hover, .indicador--click
  left: 93%
@media only screen and (max-width: 750px)
  .indicador--hover, .indicador--click
    left: 87%
</style>
