<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Las TIC en la comunicación y colaboración en línea
    .spacer
    .corner-box.color-b3.p-4.mb-5.m-custom
      .row.align-items-center
        .col-lg-3
          .wrap-overflow
            figure(data-aos="flip-left")
              img.nW(src="@/assets/curso/t1-4.png", alt="personaje animado")
        .col-lg-9
          p.text-xl ¿Conoces para que han sido creadas las TIC? 
            span.text-normal El tratamiento de la información en referencia a la comunicación y colaboración en línea hace repensar que las TIC fueron creadas para determinar las herramientas que permiten el acceso a todo tipo de datos en diferentes formas digitales. Estas se representan en:
          .wrap-player
            audio(controls='')
              source(src='https://file-examples-com.github.io/uploads/2017/11/file_example_MP3_5MG.mp3' type='audio/mpeg')
              |  Your browser does not support the audio tag.
    
    //-- below Row card list
    .row.mb-5.justify-content-center
      .col-lg-2
        figure(data-aos="flip-left")
          img.nW(src="@/assets/curso/t1-n1.svg", alt="personaje animado")

      .col-lg-2
        figure(data-aos="flip-left")
          img.nW(src="@/assets/curso/t1-n2.svg", alt="personaje animado")

      .col-lg-2
        figure(data-aos="flip-left")
          img.nW(src="@/assets/curso/t1-n3.svg", alt="personaje animado")

      .col-lg-2
        figure(data-aos="flip-left")
          img.nW(src="@/assets/curso/t1-n4.svg", alt="personaje animado")

      .col-lg-2
        figure(data-aos="flip-left")
          img.nW(src="@/assets/curso/t1-n5.svg", alt="personaje animado")

    p.mb-5  Y se presentan en los diferentes dispositivos, como:

    //-- below Row card 2 list
    .row.mb-5.justify-content-center
      .col-lg-2
        figure(data-aos="flip-up")
          img.nW(src="@/assets/curso/t1-n6.svg", alt="personaje animado")

      .col-lg-2
        figure(data-aos="flip-up")
          img.nW(src="@/assets/curso/t1-n7.svg", alt="personaje animado")

      .col-lg-2
        figure(data-aos="flip-up")
          img.nW(src="@/assets/curso/t1-n8.svg", alt="personaje animado")
    
    p.mb-5(data-aos="slide-left")  En los móviles encontramos los smartphone, que hacen parte de la cotidianidad de cada uno de nosotros, de forma inmersiva e interactiva.
    .row.justify-content-center
      .col-lg-10(data-aos="fade-left")
        .bloque-texto-a.color-acento-botones.p-3.p-md-5.mb-5.dir-ltr
          .row.m-0.align-items-center.justify-content-between
            .col-lg-8
              .bloque-texto-a__texto.p-4.shadow-box
                p La comunicación es estrecha a la transformación de la sociedad y con ella el descubrir nuevas formas y medios de hacerlo. Por ello, los medios digitales no son ajenos a su desarrollo y evolución y están implícitos para lograr una comunicación efectiva y pertinente, lo que genera una identificación con los semejantes y se haga parte de una sociedad, con características intrínsecas y de comportamiento logrando una identidad. <b>Es una forma de aprender quién eres: desde la empatía y hoy con los medios de comunicación digital se traduce en el “Yo virtual”.</b>
            .col-lg-4.mb-4.mb-lg-0
              figure(data-aos="flip-left")
                img.nW(src="@/assets/curso/t1-i1.svg", alt="imagen decorativa")


    p.mb-5(data-aos="slide-left")  La definición de las TIC puede tener diferentes connotaciones desde el punto de vista del autor, a manera de repaso se puede decir que son:
    .row.justify-content-center
      .col-lg-10(data-aos="fade-left")
        .bloque-texto-a.color-acento-botones.p-3.p-md-5.mb-5.dir-ltr
          .row.m-0.align-items-center.justify-content-between
            .col-lg-8
              .bloque-texto-a__texto.p-4.shadow-box
                p El conjunto de herramientas de innovación para poder gestionar la información, almacenarla, recuperarla y enviarla de una parte a otra, la cual es procesada y esta pueda ser entendida en diferentes canales de comunicación para lograr una renovación cultural.
            .col-lg-4.mb-4.mb-lg-0
              figure(data-aos="flip-left")
                img.nW(src="@/assets/curso/t1-i2.svg", alt="imagen decorativa")

    .row.mb-5
      .col-lg-2
        figure(data-aos="flip-left")
          img.nW(src="@/assets/curso/t1-ic1.svg", alt="imagen decorativa")
      .col-lg-10
        p Teniendo en cuenta la afirmación que la tecnología ha incluido nuevas formas de comunicación y se ha incluido en todos los entornos entre los seres humanos y por ende en la vida social de cada uno de nosotros, se debe tener en cuenta también que, la apropiación de las nuevas herramientas de comunicación y colaboración en línea no es un proceso endógeno, solo es una condición de necesidad causada, por ello se debe valorar los factores, ventajas y desventajas que posee para llevarlas a práctica desde lo social. Veamos a continuación un recurso que permitirá conocer más sobre este importante tema. 
    .row.mb-5.justify-content-center
      .col-lg-8
        ImagenInfografica.color-primario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/t1-info1.svg', alt='ejemplo del uso de la tecnología')
          .tarjeta.color-b3.p-3.shadow-box(x="12%" y="30%")
            p El intercambio permite establecer vínculos y relaciones para lograr un YO integral en la sociedad. 
          .tarjeta.color-b3.p-3.shadow-box(x="6%" y="62%")
            p Responsabilidad y ética social para compartir sentimiento, experiencias y anécdotas.
          .tarjeta.color-b3.p-3.shadow-box(x="12%" y="92%")
            p La forma de comunicarte y establecer estrechos lazos se da como un proceso natural al ser humano, por lo que, no es propio de la tecnología.         
          .tarjeta.color-b3.p-3.shadow-box(x="93%" y="40%")
            p El mundo digital crea los preceptos en todas las esferas sociales, millones de datos se comparten, divulgan.
          .tarjeta.color-b3.p-3.shadow-box(x="93%" y="80%")
            p La socialización tiende a delimitarse desde la interacción de un dispositivo. 

    .row.mb-5
      .col-lg-7
        p.mb-4(data-aos="slide-left")  Es perentorio saber que la incursión de las TIC, se encuentran ya inmersas en las actividades diarias y han generado gran impacto, tanto individual como colectivo en la sociedad actual, causando efectos positivos y negativos que más adelante se confrontarán al relacionarlo con la realidad, territorio e identidad como persona. 
        .cajon.color-acento-botones.p-4(data-aos="flip-up")
          p.mb-0  Es importante tener presente que existe una manipulación e influencia de los medios de comunicación masiva, en el discernimiento personal, afectando conductas y actitudes, alterando la conciencia social hacia los demás y como se ven desde otra perspectiva en diferentes tejidos sociales orientados a desarrollar una identidad que cohesiona las relaciones entre las personas, realizando constructos de comunicación diferentes a los habituales.   
      .col-lg-5
        figure(data-aos="flip-left")
          img.nW(src="@/assets/curso/t1-i3.svg", alt="imagen decorativa")


    .corner-box.color-b2.p-4.mb-5.m-custom
      .row.align-items-center
        .col-lg-3
          .wrap-overflow
            figure(data-aos="fade-up")
              img.nW(src="@/assets/curso/t2-i8.png", alt="personaje animado")
        .col-lg-9
          p.text-xl 
            span.text-normal La influencia de las TIC en tu vida y la sociedad depende de lo que realices con las nuevas tecnologías: 
            span ¿alejar a los que tienes cerca y acercar a los que tienes lejos?  
          .wrap-player
            audio(controls='')
              source(src='https://file-examples-com.github.io/uploads/2017/11/file_example_MP3_5MG.mp3' type='audio/mpeg')
              |  Your browser does not support the audio tag.


    #t_1_1.titulo-segundo
      h2  1.1  Características  y clasificación de las TIC
    p.mb-5  Las tecnologías de información y comunicación poseen diferentes características que, por ser dinámicas y ágiles, hacen que los procesos comunicacionales entre las personas se hagan más fáciles. Dentro de las más representativas se encuentran: 
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/iJOOfpo1SdM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .row.mb-5
      .col-lg-7
        p.mb-3  Los preceptos sociales de comunicación han logrado un cambio de paradigma, porque dadas las características y nuevas posibilidades que te presentan, las TIC han hecho que los seres humanos interactúen de forma diferente y más efectiva con una buena utilización de las mismas, se te amplían las oportunidades, los recursos y servicios de cómo hacerlo, rompiendo barreras de forma flexible que logra la inclusión en todos los sectores, es capaz de reconfigurar la estructura normal de la comunicación humana, convergiendo en la interacción de los individuos de una sociedad que se conoce como globalización.
        p.mb-3.text-bold  Existen diferentes argumentos para poder clasificar las TIC, porque por ser tan flexibles muchos autores hacen diferentes clasificaciones, dependiendo del uso o las herramientas de las cuales están compuestas.

      .col-lg-5
        figure(data-aos="fade-up")
          img.nW(src="@/assets/curso/t1-i4.jpg", alt="imagen decorativa")
    .spacer
    .corner-box.color-b1.p-4.mb-5.m-custom.flipped-corners
      .row.align-items-center.justify-content-center
        .col-lg-8
          p.text-xl ¿Sabías que es importante reconocer que las herramientas se han convertido en las aliadas para el desarrollo del mundo digital, porque giran en torno a tres medios fundamentales, la informática, la microelectrónica y las telecomunicaciones, de una forma interconectada?
          .wrap-player
            audio(controls='')
              source(src='https://file-examples-com.github.io/uploads/2017/11/file_example_MP3_5MG.mp3' type='audio/mpeg')
              |  Your browser does not support the audio tag.
        .col-lg-2
          .wrap-overflow
            figure(data-aos="flip-left")
              img(src="@/assets/curso/i1.png", alt="personaje animado")


    p.mb-5  A continuación, podrás conocer una de las clasificaciones de las TIC:
    .row.mb-5.justify-content-center
      .col-lg-8
        ImagenInfografica.color-primario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/t1-info2.svg', alt='ejemplo del uso de la tecnología')
          .tarjeta.color-b3.p-3.shadow-box(x="82%" y="27%")
            p Permiten estructurar nuevos medios para la generación del aprendizaje.
          .tarjeta.color-b3.p-3.shadow-box(x="90%" y="58%")
            p Permite el envío y recepción de información para facilitar compartir cualquier tipo de información.       
          .tarjeta.color-b3.p-3.shadow-box(x="82%" y="89%")
            p Permiten compartir información desde cualquier esfera social, son participativas, posibilitan el intercambio y la generación de nuevas formas de interacción.            

    p.mb-5  Las TIC son utilizadas para gestionar información de todo tipo y son consideradas las más efectivas a la hora de comunicar y colaborar con contenidos en línea.
    .row.justify-content-center
      .col-lg-10
        .bloque-texto-a.color-acento-botones.p-3.p-md-5.mb-5.dir-ltr(data-aos="flip-left")
          .row.m-0.align-items-center.justify-content-between
            .col-lg-8
              .bloque-texto-a__texto.p-4.shadow-box
                p El acceso a los datos se realice de manera equitativa en todas las esferas sociales (económicas, sociales, políticas, culturales, educativas y científicas), siendo que la información es pública logrando que el binomio espacio-tiempo, no sea un obstáculo, esto hace que la interacción y colaboración entre los individuos de una sociedad pueda hacer construcción colectiva de conocimiento.
            .col-lg-4.mb-4.mb-lg-0
              figure(data-aos="flip-left")
                img.nW(src="@/assets/curso/t1-i5.svg", alt="imagen decorativa")

    p.mb-5(data-aos="slide-left")  Para determinar una clasificación de las TIC, se debe tener en cuenta los medios y los enfoques en las cuales se están utilizando, hoy en día y en ese contexto, se puede decir que estas innovadoras herramientas se pueden determinar cómo se relacionan a continuación.

    .row.mb-5.justify-content-center
      .col-md-4.col-lg-4
        .nav-holder.align-items-center(data-aos="flip-up")
          img(src="@/assets/curso/t1-p1.svg", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 Tradicionales
              p.small Conocidas como MASS-Media, utilizan canales de difusión masiva tales como la televisión, la radio, los periódicos, y pretenden llegar a un receptor colectivo, ya que la información no es controlada; es de tipo global e indiscriminada dentro de un mundo digital social.

      .col-md-4.col-lg-4
        .nav-holder.align-items-center(data-aos="flip-up")
          img(src="@/assets/curso/t1-p2.svg", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 En red e informáticas
              p.small A través de la incursión de dispositivos electrónicos y digitales se incrementa la interactividad, ofreciendo gran cantidad de servicios, que buscan la colaboración e intercambio de información entre los usuarios. Los medios digitales son inmersivos y muy rápidos, por ello, se han desarrollado diferentes opciones como la inteligencia artificial, las redes neuronales, la realidad virtual y aumentada.

      .col-md-4.col-lg-4
        .nav-holder.align-items-center(data-aos="flip-up")
          img(src="@/assets/curso/t1-p3.svg", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 Interactivas
              p.small Las herramientas son mucho más versátiles, hoy en día es muy común encontrar tableros electrónicos en un ambiente de formación, donde la experiencia de usuario se hace cada vez más inclusiva.
      .clearfix
      .col-md-4.col-lg-4
        .nav-holder.align-items-center(data-aos="flip-up")
          img(src="@/assets/curso/t1-p4.svg", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 Transmisivas
              p.small Apoyan los procesos de comunicación en los seres humanos, llevando un mensaje al receptor, dependiendo de sus gustos y aficiones, cada vez las bibliotecas virtuales toman más fuerza, los podcasts, los videojuegos, la TV digital.

      .col-md-4.col-lg-4
        .nav-holder.align-items-center(data-aos="flip-up")
          img(src="@/assets/curso/t1-p5.svg", alt="Imagen decorativa")
          .text.p-lg-3.p-4
            .row.px-lg-3.mb-lg-2
              p.h3 Activas
              p.small Son utilizadas en la educación para potenciar los aprendizajes en diferentes canales y medios, además en los procesos de productividad en empresas, a través de herramientas multimediales de gran impacto y hasta los buscadores de información generan una experiencia personalizada según cada usuario digital.






    Separador
    br
    br
    #t_1_2.titulo-segundo
      h2 Ventajas y desventajas en el proceso comunicacional en línea

    p.mb-5 El uso de las TIC en los procesos comunicacionales en línea se debe de saber utilizar en pro del desarrollo integral de una sociedad, pero es importante saber que existen múltiples ventajas y a su vez desventajas que pueden poner en peligro la identidad e integridad tanto física como emocional, la comunicación como proceso endógeno del ser humano se debe potencializar para el crecimiento y desarrollo del ser. 
    br
    .corner-box.color-b3.p-4.mb-5.m-custom
      .row.align-items-center
        .col-lg-3
          .wrap-overflow
            figure(data-aos="flip-left")
              img.nW(src="@/assets/curso/t1-nn.png", alt="personaje animado")
        .col-lg-9
          p.text-xl ¿Sabías que las herramientas comunicacionales que brindan las TIC no son neutras, positivas o negativas; todo depende de cómo se use? 
            span.text-normal A continuación, te invito a conocer sus ventajas y desventajas:
          .wrap-player
            audio(controls='')
              source(src='https://file-examples-com.github.io/uploads/2017/11/file_example_MP3_5MG.mp3' type='audio/mpeg')
              |  Your browser does not support the audio tag.

    .titulo-quinto.color-secundario
      .h4 Ventajas y desventajas del <br>proceso comunicacional en línea

    .neg-margin-x.bg-curve-soft
      .row.mb-5.justify-content-center
        .col-lg-2.d-none.d-sm-block
          figure(data-aos="flip-left")
            img.nW(src="@/assets/curso/t1-b1.svg", alt="personaje animado")
        .col-lg-4
          figure(data-aos="flip-left")
            img.nW(src="@/assets/curso/t1-b1-1.svg", alt="personaje animado")
        .col-lg-4
          figure(data-aos="flip-right")
            img.nW(src="@/assets/curso/t1-b1-2.svg", alt="personaje animado")
        .col-lg-2.d-none.d-sm-block
          figure(data-aos="flip-left")
            img.nW(src="@/assets/curso/t1-b2.svg", alt="personaje animado")










  
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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

<style lang="sass" scoped>
.bg-curve-soft
  background: url('../assets/curso/bg-curve.svg')
  background-position: bottom
  background-repeat: none
  background-size: cover
</style>
