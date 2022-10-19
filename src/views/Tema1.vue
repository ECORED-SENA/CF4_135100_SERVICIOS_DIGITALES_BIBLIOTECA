<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 #[em Marketing] en la red

    .row
      .col-auto.d-md-block.d-none(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema1/1.png" data-aos="fade-right")
      .col(style="place-self:center;")
        p.mb-0(data-aos="fade-up") Las acciones que desarrollan las organizaciones para la realización de la gestión de promoción, difusión y dar a conocer sus actividades por medio de ambientes virtuales, se llama #[em marketing] digital. Para ello, utilizan herramientas y aplicaciones que brinda la #[em web] 2.0 que dan facilidades para compartir los portafolios de productos y servicios, por medio de las tecnologías de la información y redes sociales.

    .tarjeta.color-primario.p-3.mt-4.col-md-10.m-auto(style="background-color:#FFF0DE;")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/tema1/2.png")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h5.mb-3(style="color:#785549;" data-aos="fade-up") ¡Importante! 
              p.mb-0(data-aos="fade-up" style="color:#12263F;") Así mismo, el #[em(style="color:#12263F;") marketing] digital permite recibir retroalimentación de los clientes o usuarios, ya que posibilita interactuar con ellos en cualquier momento, sin importar su localización.

    Separador.mt-5

    .titulo-segundo
      h2#t_1_1 1.1  Redes sociales

    p(data-aos="fade-up") Las páginas #[em web] o aplicativos que sirven como canal de comunicación e interacción entre personas de forma virtual se denominan, comúnmente, #[strong redes sociales].

    figure.mt-5.col-md-8.m-auto
      img(src="@/assets/curso/tema1/3.png" data-aos="zoom-in-up")

    .tarjeta.color-primario.p-3.mb-5.col-md-10.m-auto.cont_1_1.mt-5
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/tema1/4.png" data-aos="fade-right")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h5.text-white(data-aos="fade-up") ¿ Para qué sirven ?
              p.mb-0.text-white.mt-3(data-aos="fade-up") Las redes sociales son un instrumento en el #[em marketing] digital, que sirve para la promoción de las empresas, sus productos o servicios. Es por ello que se requiere conocerlas y estar familiarizados con ellas..

    p.mt-5(data-aos="fade-up") En la siguiente tabla, se exponen las redes sociales más comunes y frecuentemente utilizadas; se invita a conocer más sobre sus usos en el #[em marketing].

    .titulo-sexto.color-primario.mt-5
      h5 Figura 1.
      span  Redes sociales y su uso en #[em marketing] digital

    .tabla-a.color-acento-botones.mt-5.col-lg-10.m-auto
      table
        thead(style="border:0;")
          tr
            th.p-4.text-center(style="background-color:#EBC9B1;border:0;width:25%;") Red social
            th.p-4.text-center(style="background-color:#DCD4D2;border:0;") Características
            th.p-4.text-center(style="background-color:#EFEFEF;border:0;") Uso en #[em marketing]
        tbody
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") Facebook
            td.p-4(style="background-color:#F2EAE9;border:0" rowspan="6") Para el público en general, no se requiere un tema específico o intereses.
            td.p-4(style="background-color:#F5F5F5;border:0;border-bottom:1px #D6CAC2 solid;") Comunicación bidireccional con usuarios actuales y potenciales para identificar preferencias, tendencias y demás.
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") Twitter
            td.p-4(style="background-color:#F5F5F5;border:0;border-bottom:1px #D6CAC2 solid;") Promoción de productos y servicios, como también publicación de campañas.
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") Instagram
            td.p-4(style="background-color:#F5F5F5;border:0;border-bottom:1px #D6CAC2 solid;") Posición de marca generando más visitas. 
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") TikTok
            td.p-4(style="background-color:#F5F5F5;border:0;border-bottom:1px #D6CAC2 solid;") Llegar a usuarios nuevos, aunque no sean seguidores, haciendo conocer la marca, sus productos y servicios.
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") Snapchat
            td.p-4(style="background-color:#F5F5F5;border:0;border-bottom:1px #D6CAC2 solid;") Interacción con los usuarios. 
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") VKontakte
            td.p-4(style="background-color:#F5F5F5;border:0;border-bottom:1px #D6CAC2 solid;") Postear los productos y servicios de la organización en diferentes comunidades en línea.
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") LinkedIn
            td.p-4(style="background-color:#F2EAE9;border:0;border-top:1px #D6CAC2 solid;" rowspan="6") Para el público en general, se manejan temas intereses específicos.
            td.p-4(style="background-color:#F5F5F5;border:0;border-bottom:1px #D6CAC2 solid;" rowspan="2") Posibilitan encontrar un mercado segmentado y generar alianzas estratégicas entre organizaciones.
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") InfoJobs
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") 21Buttons
            td.p-4(style="background-color:#F5F5F5;border:0;border-bottom:1px #D6CAC2 solid;") Permite hacer compras en línea de artículos de moda, en especial ropa.
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") Spotify
            td.p-4(style="background-color:#F5F5F5;border:0;border-bottom:1px #D6CAC2 solid;") Utiliza la aplicación para promoción de productos y servicios a diferentes posibles clientes.
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") Pinterest
            td.p-4(style="background-color:#F5F5F5;border:0;border-bottom:1px #D6CAC2 solid;" rowspan="2") Para campañas de mercadeo se hace uso de estas herramientas por medio del diseño, orden, creación y edición del contenido propuesto. 
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") Flickr
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") WhatsApp
            td.p-4(style="background-color:#F2EAE9;border:0;border-top:1px #D6CAC2 solid;" rowspan="6") Para el público en general, se caracterizan por la gestión de mensajería instantánea lo que permite de forma sincrónica interactuar ya sea por mensajes de texto o video llamadas.
            td.p-4(style="background-color:#F5F5F5;border:0;border-bottom:1px #D6CAC2 solid;" rowspan="5") Se utilizan como canal de venta, promoción y apasionamiento de marca, posibilita interactuar en línea con el usuario facilitando la resolución de necesidades de clientes, atención de pedidos, aclaración de dudas y demás requerimientos de forma personalizada, se utiliza de forma sincrónica o asincrónica. #[br] #[br] Posibilitan la comunicación por medio de mensajes de texto, llamadas o videollamadas.
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") Messenger
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") Line
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") Telegram
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") WeChat
          tr
            td.h5.p-4(style="background-color:#FFF3EA;border:0;border-bottom:1px #D6CAC2 solid;") Discord
            td.p-4(style="background-color:#F5F5F5;border:0;border-bottom:1px #D6CAC2 solid;") Se maneja para la recolección de comentarios de los usuarios para evaluar la satisfacción del cliente y hacer gestión de posventa.

    .mt-5.cont_1_2.pt-5.pb-5.row(style="position:relative;")
      .col-lg-7.mb-4.mb-lg-0(style="place-self:center;position:relative")
        p(data-aos="fade-up") Cabe resaltar que los beneficios principales de las redes sociales para el #[strong #[em marketing]], son:
        ul.fa-ul.mt-5
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | La creación de imagen corporativa.
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | El refuerzo y posicionamiento de la marca.
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | La aplicación y fortalecimiento de canales de comunicación con usuarios.
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | La posibilidad de captar nuevos clientes.
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | La posibilidad de fidelizar clientes existentes.
          li(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | La promoción de productos y servicios, entre otros.
      .col-lg-3(style="place-self:center;position:relative")
        figure
          img(src="@/assets/curso/tema1/6.png" data-aos="fade-left")

    Separador.mt-5

    .titulo-segundo
      h2#t_1_2 1.2  Netiqueta

    .row
      .col-lg-6.mb-4.mb-lg-0(style="place-self:center")
        p(data-aos="fade-up") Así como de forma presencial existe la etiqueta, que rige el actuar entre las personas frente a ciertas situaciones en sociedad, existe la netiqueta la cual aporta unos lineamientos para las formas de comportamiento, cuando se hace uso de las herramientas virtuales.
        .p-5.cont_1_3
          p(data-aos="fade-up") Comprendiendo lo anterior, se define netiqueta como el conjunto de reglas y la normatividad que rigen el comportamiento cuando se interactúa a través de la red: aplicaciones, redes sociales, aplicativos, plataformas, espacios de virtualidad y demás herramientas informáticas y digitales. 
      .col-lg-6(style="place-self:center")
        figure
          img(src="@/assets/curso/tema1/8.png" data-aos="fade-left")

    h5.mt-5(data-aos="fade-up") Se debe tener en cuenta algunas particularidades de la netiqueta y procurar ser garante de su cumplimiento en sus procesos y experiencia personal y laboral:

    .cont_1_4.mt-5.pb-5(style="position:relative")
      .p-5.row.col-lg-10.m-auto(style="background-color:#FAFAFA;border-radius:20px;position:relative")
        .col-lg-5.mb-4.mb-lg-0.m-auto(style="place-self:center")
          figure.text-center
            img(src="@/assets/curso/tema1/10.png" data-aos="fade-right" style="max-width:500px;display:inline;")
        .col-lg-7.row(style="place-self:center")
          .col-lg-2.mb-4.m-auto.indicador__container
            figure.mb-3.text-center(@mouseover="indicadorHover = false")
              .indicador--hover(v-if="indicadorHover")
              img.pointer(src="@/assets/curso/tema1/11.png" data-aos="zoom-in-up" @mouseover="cont_image1 = true" @mouseleave="cont_image1 = false" style="max-width:120px;display:inline;")
            figure.mb-3.text-center(@mouseover="indicadorHover = false")
              .indicador--hover(v-if="indicadorHover")
              img.pointer(src="@/assets/curso/tema1/12.png" data-aos="zoom-in-up" @mouseover="cont_image2 = true" @mouseleave="cont_image2 = false" style="max-width:120px;display:inline;")
            figure.mb-3.text-center(@mouseover="indicadorHover = false")
              .indicador--hover(v-if="indicadorHover")
              img.pointer(src="@/assets/curso/tema1/13.png" data-aos="zoom-in-up" @mouseover="cont_image3 = true" @mouseleave="cont_image3 = false" style="max-width:120px;display:inline;")
            figure.mb-3.text-center(@mouseover="indicadorHover = false")
              .indicador--hover(v-if="indicadorHover")
              img.pointer(src="@/assets/curso/tema1/14.png" data-aos="zoom-in-up" @mouseover="cont_image4 = true" @mouseleave="cont_image4 = false" style="max-width:120px;display:inline;")
            figure.mb-3.text-center(@mouseover="indicadorHover = false")
              .indicador--hover(v-if="indicadorHover")
              img.pointer(src="@/assets/curso/tema1/15.png" data-aos="zoom-in-up" @mouseover="cont_image5 = true" @mouseleave="cont_image5 = false" style="max-width:120px;display:inline;")
          .col-lg-10(style="position:relative")
            .cont_image1.cont_image(v-show="cont_image1" style="position:relative;")
              .p-4.cont_arrow(style="background-color:#F3F9FF;border-radius:15px;border:1px #81C0FF solid;position:relative")
                h5 Facebook
                p.mt-3 Identificarse, no enviar mensajes ofensivos o engañosos, publicar contenido privado de otras personas, entre otras reglas.
            .cont_image2.cont_image(v-show="cont_image2" style="position:relative;top:10%;")
              .p-4.cont_arrow(style="background-color:#F3F9FF;border-radius:15px;border:1px #81C0FF solid;position:relative")
                h5 Correo electrónico
                p.mt-3 No adjuntar contenido malicioso que afecte la seguridad cibernética de los demás usuarios, no escribir en mayúscula, pues indica que la comunicación es con un tono de voz alto.
            .cont_image3.cont_image(v-show="cont_image3" style="position:relative;top:40%;")
              .p-4.cont_arrow(style="background-color:#F3F9FF;border-radius:15px;border:1px #81C0FF solid;position:relative")
                h5 Foros
                p.mt-3 El aporte que se realice debe ser acorde al tema expuesto, respetar la opinión del otro y seguir la secuencia del tema de discusión.
            .cont_image4.cont_image(v-show="cont_image4" style="position:relative;top:55%;")
              .p-4.cont_arrow(style="background-color:#F3F9FF;border-radius:15px;border:1px #81C0FF solid;position:relative")
                h5 Blogs
                p.mt-3 Los comentarios deben ser con respeto tanto al autor como a los demás participantes, ya que los que se consideren ofensivos pueden ser bloqueados y eliminados.
            .cont_image5.cont_image(v-show="cont_image5" style="position:relative;top:70%;")
              .p-4.cont_arrow(style="background-color:#F3F9FF;border-radius:15px;border:1px #81C0FF solid;position:relative")
                h5 Chat - WhatsApp y demás
                p.mt-3 No enviar mensajes virales y falsos, evitar el uso de escritura en mayúscula para garantizar asertividad en la comunicación, enviar mensajes en horarios funcionales, no enviar contenido que afecte la integridad de otras personas y no utilizar la red como herramienta de #[em bullying].

      h5.mt-5(data-aos="fade-up") Dentro del conjunto general de reglas de la #[strong(style="color:#FD9827;") Netiqueta], las más básicas e importantes, son:

      ul.fa-ul.mt-5
        li.mb-2(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FD9827;")
          | Escribir teniendo en cuenta al lector, contexto y el mensaje que se quiere transmitir, cuidando el respeto por todas las personas naturales y no naturales.
        li.mb-2(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FD9827;")
          | Cumplir las reglas propias, expuestas en la red específica o herramientas informáticas y digitales que se estén usando.
        li.mb-2(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FD9827;")
          | Aplicar una enunciación y escritura moderada en cantidad y forma; evitando el uso de modismos despectivos, abreviaturas no oficiales, fuentes poco legibles, mayúsculas sostenidas, entre otras.
        li.mb-2(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FD9827;")
          | Respetar permisos otorgados y espacio de los demás.
        li.mb-2(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FD9827;")
          | Aportar al conocimiento.
        li(data-aos="fade-up")
          i.fa.fa-li.fa-check(style="color:#FD9827;")
          | Promover el respeto por la intimidad y privacidad.

      .tarjeta.color-primario.p-4.mt-5.cont_sintesis.col-lg-10.m-auto(style="position:relative")
        .row.justify-content-around.align-items-center
          .col-3.col-sm-2.col-lg-1.text-center
            img(src="@/assets/curso/tema1/28.png" data-aos="fade-right" style="max-width:90px;display:inline;")
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0
                h5.text-white(data-aos="fade-up") ¡Nota importante!
                .indicador--click(v-if="mostrarIndicadorTarjetaAudio")
                TarjetaAudio.color-secundario.mb-3(
                  style="position:relative"
                  texto=""
                  :audio="require('@/assets/componentes/audios/netiqueta.mp3')"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false"
                )



    Separador.mt-5

    .titulo-segundo
      h2#t_1_3 1.3   #[em Marketing] bibliotecario

    p(data-aos="fade-up") En relación con lo dicho hasta este punto, la gestión que la biblioteca realiza, dirigida a identificar y retroalimentarse de las necesidades de datos de sus clientes para buscar estrategias y satisfacerlas, se llama #[strong(style="color:#FD9827;") #[em marketing] bibliotecario].

    h5.mt-5(data-aos="fade-up") Por medio del #[em marketing] bibliotecario, la biblioteca logra:

    .row.mt-5
      .col-lg-4.mb-4.mb-lg-0(style="place-self:center")
        figure
          img(src="@/assets/curso/tema1/16.png" data-aos="fade-right")
      .col-lg-8(style="place-self:center")
        SlyderF(columnas="col-lg-6")
          .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
            .row.justify-content-center.mb-3
              .col-8.m-auto.text-center
                img(src='@/assets/curso/tema1/18.png')
            h5.text-center.text-center.text-white Visibilidad
            p.text-center.text-center.text-white Ser visible ante el sector geográfico donde se encuentra y toda su población.
          .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
            .row.justify-content-center.mb-3
              .col-8.m-auto.text-center
                img(src='@/assets/curso/tema1/19.png')
            h5.text-center.text-center.text-white Accesibilidad
            p.text-center.text-center.text-white Permanecer accesible, con facilidades para el ingreso, los préstamos de material bibliográfico y agilidad en los mecanismos de uso de los servicios.
          .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
            .row.justify-content-center.mb-3
              .col-8.m-auto.text-center
                img(src='@/assets/curso/tema1/20.png')
            h5.text-center.text-center.text-white Información
            p.text-center.text-center.text-white Ofrecer y dar información de interés y utilidad.
          .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
            .row.justify-content-center.mb-3
              .col-8.m-auto.text-center
                img(src='@/assets/curso/tema1/21.png')
            h5.text-center.text-center.text-white Acercamiento y extensión
            p.text-center.text-center.text-white Acercarse a los usuarios y demás agentes de la comunidad e impactar nueva población.
          .tarjeta.color-acento-botones.pt-5.pb-5.ps-4.pe-4.cont_tarjetas
            .row.justify-content-center.mb-3
              .col-8.m-auto.text-center
                img(src='@/assets/curso/tema1/22.png')
            h5.text-center.text-center.text-white Transformación
            p.text-center.text-center.text-white Fomentar el pensamiento crítico y el conocimiento; promover cambios positivos.

    h5.mt-5(data-aos="fade-up") Por tanto, la gestión del #[em marketing] bibliotecario está basado en:

    .cont_1_5.p-5.mt-5.row(style="position:relative")
      .col-lg-5.mb-4.mb-lg-0(style="place-self:center;position:relative")
        figure
          img(src="@/assets/curso/tema1/24.png" data-aos="fade-right" style="position:relative;right:-37%;z-index:1;")
      .col-lg-7(style="place-self:center")
        .p-5.row(style="background-color:#FFECD6;border-radius:20px;position:relative")
          .col-lg-2
          .tabla-a.color-acento-botones.col-lg-10.indicador__container
            .indicador--hover(v-if="indicadorHover2")
            table(style="min-width:100%;")
              tbody(@mouseover="indicadorHover2 = false")
                tr
                  td.p-2.pointer.font_weight_bold_hover.cont_table1(style="width:40%;border:0;border-left:1px #E8BE8F solid;border-bottom:1px #E8BE8F solid;" @mouseover="cont_description_table1 = true" @mouseleave="cont_description_table1 = false") Continuidad
                  td(style="border:0;")
                    .p-3.cont_description_table1.bg-white(v-show="cont_description_table1" style="border-radius:20px;") La biblioteca planeará y ofrecerá servicios continuos, buscando la permanencia.
                tr
                  td.p-2.pointer.font_weight_bold_hover.cont_table2(style="border:0;border-left:1px #E8BE8F solid;border-bottom:1px #E8BE8F solid;" @mouseover="cont_description_table2 = true" @mouseleave="cont_description_table2 = false") Planeación
                  td(style="border:0;")
                    .p-3.cont_description_table2.bg-white(v-show="cont_description_table2" style="border-radius:20px;") Tener una planeación enfocada en identificar necesidades y cómo resolverlas.
                tr
                  td.p-2.pointer.font_weight_bold_hover.cont_table3(style="border:0;border-left:1px #E8BE8F solid;border-bottom:1px #E8BE8F solid;" @mouseover="cont_description_table3 = true" @mouseleave="cont_description_table3 = false") Aportes
                  td(style="border:0;")
                    .p-3.cont_description_table3.bg-white(v-show="cont_description_table3" style="border-radius:20px;") dentificar la ubicación de la biblioteca y qué puede ofrecerle a la comunidad.
                tr
                  td.p-2.pointer.font_weight_bold_hover.cont_table4(style="border:0;border-left:1px #E8BE8F solid;border-bottom:1px #E8BE8F solid;" @mouseover="cont_description_table4 = true" @mouseleave="cont_description_table4 = false") Acercamiento
                  td(style="border:0;")
                    .p-3.cont_description_table4.bg-white(v-show="cont_description_table4" style="border-radius:20px;") Conocer las tendencias, gustos, preferencias, cultura y demás para generar acercamiento e interés.
                tr
                  td.p-2.pointer.font_weight_bold_hover.cont_table5(style="border:0;border-left:1px #E8BE8F solid;border-bottom:1px #E8BE8F solid;" @mouseover="cont_description_table5 = true" @mouseleave="cont_description_table5 = false") Motivación
                  td(style="border:0;")
                    .p-3.cont_description_table5.bg-white(v-show="cont_description_table5" style="border-radius:20px;") Motivar y capacitar al personal que hace la ejecución de la planeación.
                tr
                  td.p-2.pointer.font_weight_bold_hover.cont_table6(style="border:0;border-left:1px #E8BE8F solid;border-bottom:1px #E8BE8F solid;" @mouseover="cont_description_table6 = true" @mouseleave="cont_description_table6 = false") Seguimiento
                  td(style="border:0;")
                    .p-3.cont_description_table6.bg-white(v-show="cont_description_table6" style="border-radius:20px;") Es vital hacer una evaluación de los costos versus los beneficios.
                tr
                  td.p-2.pointer.font_weight_bold_hover.cont_table7(style="border:0;border-left:1px #E8BE8F solid;border-bottom:1px #E8BE8F solid;" @mouseover="cont_description_table7 = true" @mouseleave="cont_description_table7 = false") Articulación
                  td(style="border:0;")
                    .p-3.cont_description_table7.bg-white(v-show="cont_description_table7" style="border-radius:20px;") Generar redes de apoyo entre las bibliotecas y entidades de formación.
                tr
                  td.p-2.pointer.font_weight_bold_hover.cont_table8(style="border:0;border-left:1px #E8BE8F solid;" @mouseover="cont_description_table8 = true" @mouseleave="cont_description_table8 = false") Control
                  td(style="border:0;")
                    .p-3.cont_description_table8.bg-white(v-show="cont_description_table8" style="border-radius:20px;") Evaluar el grado de satisfacción de los clientes internos y externos.

    Separador.mt-5

    .titulo-segundo
      h2#t_1_4 1.4 Interacción con el usuario

    .row.cont_1_7.pb-5(style="position:relative")
      .col-lg-7.mb-4.mb-lg-0(style="position:relative")
        p(data-aos="fade-up") Las personas que requieren datos para transformar la información en conocimiento buscan los recursos que las bibliotecas les aportan; por eso, es importante conocer cómo el #[em marketing] bibliotecario interactúa con los usuarios.
        .cont_1_6.mt-5.p-4
          p.mb-0.ps-5(data-aos="fade-up") #[strong Tal gestión radica en promocionar los canales de comunicación,] servicios y actividades propias de la biblioteca, para dar una cobertura completa a la comunidad.
      .col-lg-5.mb-4.mb-lg-0(style="position:relative")
        figure
          img(src="@/assets/curso/tema1/26.png" data-aos="fade-left")
      .col-lg-7(style="position:relative")
        h5.mt-5(data-aos="fade-up") Para una mayor comprensión del #[em marketing] y su interacción en las bibliotecas, se exponen algunos ejemplos, a saber:
        ul.fa-ul.mt-5
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | Publicaciones de los servicios bibliotecarios en las redes sociales.
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | Publicar la ubicación de la biblioteca en redes sociales.
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | Señalizar la ubicación de forma física en la comunidad como una ruta guía en lugares específicos.
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | Gestión de voz a voz y referenciados.
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | Planes de fidelización. 
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | Publicidad y promoción de la biblioteca ya sea física o por internet.
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | Servicio al cliente que supere expectativas.
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | Ambientes según necesidades.
          li.mb-2(data-aos="fade-up")
            i.fa.fa-li.fa-check(style="color:#FD9827;")
            | Material accesible.

      .tarjeta.color-primario.p-4.mt-5.cont_sintesis.col-lg-10.m-auto(style="position:relative")
        .row.justify-content-around.align-items-center
          .col-3.col-sm-2.col-lg-1.text-center
            img(src="@/assets/curso/tema1/28.png" data-aos="fade-right" style="max-width:90px;display:inline;")
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0
                h5.text-white(data-aos="fade-up") ¡Atención!
                p.mb-0.text-white(data-aos="fade-up") El #[em marketing] bibliotecario es una gestión de dedicación y compromiso; existen diferentes maneras de hacerlo, todo depende de la comunidad a la que se quiere llegar y los objetivos propuestos por la biblioteca y su equipo de colaboradores.



      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    indicadorHover: true,
    indicadorHover2: true,
    cont_image1: false,
    cont_image2: false,
    cont_image3: false,
    cont_image4: false,
    cont_image5: false,
    cont_description_table1: false,
    cont_description_table2: false,
    cont_description_table3: false,
    cont_description_table4: false,
    cont_description_table5: false,
    cont_description_table6: false,
    cont_description_table7: false,
    cont_description_table8: false,
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
.cont_1_1
  background: url(../assets/curso/tema1/5.png)
  background-size: cover
  background-repeat: no-repeat
.cont_1_2:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 100%
  top: 0
  background: rgb(253,152,39)
  background: linear-gradient(180deg, rgba(253,152,39,0.08) 28%, rgba(49,49,60,0.08) 100%)
.cont_1_3
  background: url(../assets/curso/tema1/7.png)
  background-size: cover
  background-repeat: no-repeat
.cont_1_4:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 70%
  background: url(../assets/curso/tema1/9.png)
  background-size: cover
  background-position: bottom
  background-repeat: no-repeat
  top: 30%
.pointer
  cursor: pointer
.cont_arrow:before
  content: ''
  position: absolute
  left: -16px
  border-left: 0px transparent solid
  border-right: 15px #9cbafb solid
  border-top: 12px #00000000 solid
  border-bottom: 12px transparent solid
  width: 0
  height: 0
  top: 30%
  z-index: 2
@media only screen and (max-width: 1200px)
  .cont_image
    top: 0px !important
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
.cont_1_5:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 100%
  background: url(../assets/curso/tema1/23.png)
  background-size: cover
  background-repeat: no-repeat
  top: 0
.font_weight_bold_hover:hover
  font-weight: bold
.cont_1_6
  background: url(../assets/curso/tema1/25.png)
  background-size: cover
  background-repeat: no-repeat
.cont_sintesis
  background: url(../assets/curso/s1.png)
  background-size: cover
  background-repeat: no-repeat
.cont_1_7:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 74%
  background: url(../assets/curso/tema1/27.png)
  background-size: cover
  background-repeat: no-repeat
  bottom: 0
</style>
