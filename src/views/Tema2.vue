<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Recursos informáticos en la comunicación y colaboración en línea
    .row.mb-5.slideInUp
      .col-lg-2
        figure(data-aos="flip-left")
          img.nW(src="@/assets/curso/t2-ic1.svg", alt="imagen decorativa")
      .col-lg-10
        p Las personas cuando ingresan a la red no solo quieren consumir recursos y servicios, cuando estas se conectan, lo hacen principalmente para comunicarse y para poder subir contenidos y estar más presentes digitalmente. <b>De manera constante se está colaborando con los demás, esto hace que se generen habilidades y competencias de trabajo en equipo y aprendizaje continuo.</b>
    .row.justify-content-center
      .col-lg-10(data-aos="fade-left")
        .bloque-texto-a.color-acento-botones.p-3.p-md-5.mb-5.dir-ltr
          .row.m-0.align-items-center.justify-content-between
            .col-lg-8
              .bloque-texto-a__texto.p-4.shadow-box
                p Las herramientas y recursos que se proporcionan para la comunicación y colaboración en línea aprovechan diferentes formas y entornos desde los servicios de voz, video y teleconferencias en las actividades de colaboración. La capacidad de colaborar en línea mejora todos los procesos comunicacionales de los usuarios, se hace de forma rápida y sencilla, rompiendo barreras y fronteras, esto logra que tu efectividad e innovación sea mucho más productiva en cualquier campo de aplicación
            .col-lg-4.mb-4.mb-lg-0
              figure(data-aos="flip-left")
                img.nW(src="@/assets/curso/t2-i1.svg", alt="imagen decorativa")

    p.mb-5  La construcción de nuevos conocimientos y la colaboración en línea permiten el desenvolvimiento en entornos de comunicación fluidos, de forma autónoma y determinando la gestión de servicios como pieza clave en el mundo digital. Comunicarse y compartir recursos son habilidades que debes de dominar a través de las metodologías activas y los avances informáticos posibilitan dichas labores en todos los entornos digitales.
    br
    .corner-box.color-b2.p-4.mb-5.m-custom
      .row.align-items-center
        .col-lg-3
          .wrap-overflow
            figure(data-aos="flip-left")
              img(src="@/assets/curso/t2-i2.png", alt="personaje animado")
        .col-lg-9
          p.text-xl ¿Conoces las características claves para la comunicación y colaboración en línea? 
            span.text-normal Te invito a conocer sobre estos recursos:
          .wrap-player
            audio(controls='')
              source(src='https://file-examples-com.github.io/uploads/2017/11/file_example_MP3_5MG.mp3' type='audio/mpeg')
              |  Your browser does not support the audio tag.
    br
    TabsB.color-secundario.mb-5
      .py-4.py-md-5(titulo="Apropiación de las competencias digitales" :icono="require('@/assets/curso/t3-tab-ic1.svg')")
        .row.justify-content-center
          .col-md-6.mb-4.mb-md-0
            .h4 Apropiación de las competencias digitales
            p Para apropiar el conocimiento de manera efectiva, se debe ser parte activa en el desarrollo de competencias digitales, e igualmente tener una definición clara de la comunicación y colaboración digital. Las cuales se pueden traducir en las acciones o actividades que un individuo desarrolla en un entorno digital, que no es otra que la forma de poder expresarse, intercambiar, o interactuar con las demás personas en entornos virtuales, trasladando los entornos físicos y por ende, se requiere de un conglomerado de conocimientos y habilidades para poderte comunicar y compartir con los demás.
          .col-md-4
            figure.slideInRight
              img(src='@/assets/curso/t2-t1.svg', alt='imagen decorativa')
      .py-4.py-md-5(titulo="Comunicación digital" :icono="require('@/assets/curso/t3-tab-ic2.svg')")
        .row.justify-content-center
          .col-md-6.mb-4.mb-md-0
            .h4 Comunicación digital
            p La comunicación digital a más de ser de tipo personal, va mucho más allá frente a las posibilidades que estas brindan, los entornos digitales permiten una serie de ventajas que se encuentran ligadas a las oportunidades. El uso constante y creciente de herramientas colaborativas en línea supone nuevos retos de poder compartir, crear y divulgar información a través de las diferentes plataformas existentes, por ejemplo, Facebook, Twitter, YouTube entre otras.
          .col-md-4
            figure.slideInRight
              img(src='@/assets/curso/t2-t2.svg', alt='imagen decorativa')

      .py-4.py-md-5(titulo="La vida digital" :icono="require('@/assets/curso/t3-tab-ic3.svg')")
        .row.justify-content-center
          .col-md-6.mb-4.mb-md-0
            .h4 La vida digital
            p La realidad actual, es clara, cada vez se ve en aumento dichos entornos virtuales y digitales, lo que presume que la base de la sociedad está cambiando y acoplándose a las nuevas tendencias informáticas, ha volcado todas las actividades sociales y la forma de hacer las cosas y combinadas con la vida digital.
          .col-md-4
            figure.slideInRight
              img(src='@/assets/curso/t2-t3.svg', alt='imagen decorativa')

    .row.mb-5
      .col-lg-5
        figure(data-aos="flip-left")
          img(src='@/assets/curso/t2-i3.svg', alt='imagen decorativa')
      .col-lg-7
        p.text-bold.mb-3 Y los siguientes son los aspectos a tener en cuenta en los entornos digitales:
        ul.lista-ul
          li(data-aos="flip-up")
            i.fas.fa-check
            p.mb-0 Interactuar a través de medios digitales y saber aplicarlos desde diferentes contextos.
          li(data-aos="flip-up")
            i.fas.fa-check
            p.mb-0  Compartir todo tipo de información y contenidos digitales de manera colaborativa.
          li(data-aos="flip-up")
            i.fas.fa-check
            p.mb-0  Participar en comunidades virtuales, ya sean personales, públicas o privadas, para encontrar las herramientas y tecnologías más adecuadas.
          li(data-aos="flip-up")
            i.fas.fa-check
            p.mb-0  Usar herramientas y tecnologías digitales para la colaboración.
          li(data-aos="flip-up")
            i.fas.fa-check
            p.mb-0  Realizar producciones digitales con recursos que sean apropiados para un gran conjunto de personas.
          li(data-aos="flip-up")
            i.fas.fa-check
            p.mb-0  Tener un comportamiento en la red adecuado para tener una buena comunicación.
          li(data-aos="flip-up")
            i.fas.fa-check
            p.mb-0  Tener una identidad digital siendo parte de una comunidad en línea teniendo en cuenta la importancia de la protección en el mundo digital.




    #t_2_1.titulo-segundo
      h2 2.1 La comunicación síncrona y asíncrona
    .row.justify-content-center
      .col-lg-10(data-aos="fade-left")
        .bloque-texto-a.color-acento-botones.p-4.p-md-5.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4.mb-4.mb-lg-0
              .h4 ¿Sabías que las nuevas metodologías activas del siglo XXI, han requerido que los medios de comunicación se amplíen con los canales de interacción?
            .col-lg-8
              .bloque-texto-a__texto.p-4.shadow-box
                p Allí se necesita que los actores involucrados en estos procesos sean parte cooperante y colaborativa, exigiendo que te vuelvas el propio protagonista de lo que comunicas y desarrolles en estos medios digitales, por su inmediatez dichos procesos comunicativos favorecen sustancialmente la posibilidad de aumentar tus conocimientos. 
    
    //-- Aqui viene la caja redondeada

    .row.mb-5.slideInUp
      .col-lg-2
        figure(data-aos="flip-left")
          img.nW(src="@/assets/curso/t2-ic2.svg", alt="imagen decorativa")
      .col-lg-10(data-aos="flip-right")
        p En todo proceso de comunicación y participativo en medios digitales, la comunicación sincrónica y asincrónica toman un valor relevante, ya que las dos formas dan mejores posibilidades de cómo comunicarse con quien se desee y en el momento que se desee, ya sea por medio de mensajería, chats, foros entre otros; que conozcas las posibilidades de las herramientas de comunicación será vital para que puedas elegir las que más se ajuste a tus actividades y sea relevante a la hora de compartir y comunicar.
    .corner-box.color-b1.p-4.mb-5.m-custom
      .row.align-items-center
        .col-lg-3
          .wrap-overflow
            figure(data-aos="flip-left")
              img(src="@/assets/curso/t2-i5.png", alt="personaje animado")
        .col-lg-9
          p.text-xl ¿Conoces la diversidad de herramientas la diversidad de herramientas digitales? 
            span.text-normal Te invito a conocer su clasificación. 
          .wrap-player
            audio(controls='')
              source(src='https://file-examples-com.github.io/uploads/2017/11/file_example_MP3_5MG.mp3' type='audio/mpeg')
              |  Your browser does not support the audio tag.

    TabsC.color-acento-contenido.mb-5
      .py-3.py-md-4(titulo="Herramientas síncronas")
        .row.justify-content-center
          .col-md-12.mb-4.mb-md-0
            h4 Herramientas síncronas
            p.mb-4 Te permiten tener una comunicación en tiempo real, para ello los individuos involucrados deben de tener una conexión al mismo momento.
            .row.justify-content-center
              .col-lg-3
                .tarjeta.color-p1.text-center.p-4.h-100(data-aos="flip-up")
                  figure
                    img.nW.centered(src="@/assets/curso/t3-c1.svg", alt="icono decorativo")
                  h3  Chat
                  p Comunicación escrita a través de internet entre dos o más personas.
              .col-lg-3
                .tarjeta.color-p2.text-center.p-4.h-100(data-aos="flip-up")
                  figure
                    img.nW.centered(src="@/assets/curso/t3-c2.svg", alt="icono decorativo")
                  h3  Videoconferencia
                  p Comunicación mediante audio y video de forma simultánea.
              .col-lg-3
                .tarjeta.color-p1.text-center.p-4.h-100(data-aos="flip-up")
                  figure
                    img.nW.centered(src="@/assets/curso/t3-c3.svg", alt="icono decorativo")
                  h3  Pizarra digital
                  p Conversaciones con audio y video de forma simultanea para clases y reuniones.
              .col-lg-3
                .tarjeta.color-p2.text-center.p-4.h-100(data-aos="flip-up")
                  figure
                    img.nW.centered(src="@/assets/curso/t3-c4.svg", alt="icono decorativo")
                  h3  Mensajería instantánea
                  p Comunicación de mensajes escritos, audios y videos en tiempo real.

      .py-3.py-md-4(titulo="Herramientas asíncronas")
        .row.justify-content-center
          .col-md-12.mb-4.mb-md-0
            h4 Herramientas asíncronas
            p.mb-4 Te permiten tener una comunicación en tiempo real, para ello los individuos involucrados deben de tener una conexión al mismo momento.
            .row.justify-content-center
              .col-lg-3
                .tarjeta.color-p1.text-center.p-4.h-100(data-aos="flip-up")
                  figure
                    img.nW.centered(src="@/assets/curso/t3-c5.svg", alt="icono decorativo")
                  h3  Correo electrónico
                  p Permite enviar y recibir información de manera instantánea. <br>Lista de distribución: permite enviar mensajes a partir de categorías de usuario.
              .col-lg-3
                .tarjeta.color-p2.text-center.p-4.h-100(data-aos="flip-up")
                  figure
                    img.nW.centered(src="@/assets/curso/t3-c6.svg", alt="icono decorativo")
                  h3  Foros
                  p Aplicación que permite la discusión y opiniones en línea. 
              .col-lg-3
                .tarjeta.color-p1.text-center.p-4.h-100(data-aos="flip-up")
                  figure
                    img.nW.centered(src="@/assets/curso/t3-c7.svg", alt="icono decorativo")
                  h3  Wikis
                  p Son webs que permite la edición de contenido de manera colaborativa.
              .col-lg-3
                .tarjeta.color-p2.text-center.p-4.h-100(data-aos="flip-up")
                  figure
                    img.nW.centered(src="@/assets/curso/t3-c8.svg", alt="icono decorativo")
                  h3  Documentos compartidos
                  p Permite subir a la nube información para que se pueda acceder desde diferentes dispositivos.

    h3.titulo-tercero Acceso al mundo digital
    p.mb-5  Los accesos y herramientas al mundo digital generan brechas que han propiciado diversos cambios en la sociedad actual, han transformado la forma como se genera la comunicación con los demás, de relacionarse, frente a las compras o venta de productos, cómo se aprende y hasta su utilización en entornos laborales, incluyendo entre ellas, el ocio y el entretenimiento.
    

    Separador
    br
    br
    #t_2_2.titulo-segundo
      h2 2.2 Navegación y principios de seguridad




















</template>

<script>
export default {
  name: 'Tema2',
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

<style lang="sass" scoped></style>
