<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Herramientas y plataformas colaborativas
    
    .corner-box.color-b1.p-4.mb-5.m-custom
      .row.align-items-center
        .col-lg-3
          .wrap-overflow
            figure(data-aos="flip-left")
              img(src="@/assets/curso/t3-i1.png", alt="personaje animado")
        .col-lg-9
          p.text-xl La penetración de los medios digitales y el uso de los dispositivos móviles, ha hecho que hoy en día encuentres muchas herramientas para poder comunicarte y te relaciones con los demás, 
            span.text-normal la cultura digital te permite poder acceder a muchos recursos y así colaborar en espacios públicos y potenciar la inclusión y participación de un individuo como sociedad.
          .wrap-player
            audio(controls='')
              source(src='https://file-examples-com.github.io/uploads/2017/11/file_example_MP3_5MG.mp3' type='audio/mpeg')
              |  Your browser does not support the audio tag.
          //-- Aqui viene el player
    
    #t_3_1.titulo-segundo
      h2 3.1 Concepto, usos y características
    .row.mb-5
      .col-lg-2
        figure(data-aos="flip-left")
          img(src="@/assets/curso/t3-ic1.svg", alt="icono decorativo")
      .col-lg-10
        p Se puede inferir en la definición de las herramientas y plataformas colaborativas en línea, como un sistema en el cual se pueden acceder a muchos servicios, donde cada uno de los usuarios pueden interrelacionarse, comunicarse y trabajar en equipo, sin necesidad de estar en un mismo espacio, tiempo o lugar, todas las herramientas colaborativas brindan soluciones intrínsecas según las preferencias y perfiles de quienes las usan.
    .row.justify-content-center
      .col-lg-10(data-aos="fade-left")
        .bloque-texto-a.color-acento-botones.p-4.p-md-5.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4.mb-4.mb-lg-0
              figure(data-aos="flip-left")
                img.nW(src="@/assets/curso/t3-i2.svg", alt="imagen decorativa")
            .col-lg-8
              .bloque-texto-a__texto.p-4
                p La innovación en el mundo digital sobrepasa los límites de expansión en desarrollo de proyectos apoyados en el desarrollo tecnológico como modelo de consumo desde negocios hasta la educación, se han roto los paradigmas tradicionales de cómo te puedes relacionar o hacer tus actividades, se analizan las necesidades particulares en pro de mejorar experiencias de usuario en esferas sociales donde se busca una globalización de las cosas para beneficios comunes.
    
    .row.mb-5
      .col-lg-7
        p.mb-3(data-aos="fade-right")  Independientemente del uso que cada persona le pueda dar a las plataformas colaborativas, existe una sinergia en las interacciones desde lo social, económico, personal, profesional o personal, las cuales están diseñadas para minimizar los costos de operación y obtener muchos más beneficios, la puesta en marcha de estos nuevos modelos de compartir información toma valor en el cooperativismo por todos los actores que interactúan a través de una plataforma digital cambiando el paradigma sociocultural. Entre las más utilizadas están las siguientes plataformas colaborativas.
        p.mb-3(data-aos="fade-right")  Los espacios virtuales centralizan sus funcionalidades a la gestión de todo tipo de información que va ligada a los requerimientos, necesidades y funcionamiento de las personas u organizaciones, en el mundo globalizado y digital; los usos que se les da, varían de acuerdo a los intereses de las personas para ser participantes activos de una comunidad, su objetivo principal radica en facilitar y optimizar la comunicación entre las personas y organizaciones generando un nuevo componente social: <b>“Tu identidad digital y el Yo Virtual”</b>, entre  las de mayor auge son:
      .col-lg-5
        figure(data-aos="slide-left")
          img(src="@/assets/curso/t3-i3.jpg", alt="imagen decorativa")

    //-- ROW MODALS
    .row.mb-5.justify-content-center
      .col-5.col-lg-2
        .objBox
          a(@click="modal1 = true")
            figure(data-aos="flip-up")
              img.nW(src='@/assets/curso/t3-m1.svg', alt='icono decorativo')
          //--.indicador--click(v-if="mostrarIndicador")    
        ModalA(:abrir-modal.sync="modal1")
          .row.align-items-center
            .col-lg-2
              figure
                img.nW(src='@/assets/curso/t3-im1.svg', alt='icono decorativo')
            .col-lg-10
              .h4 Educación
              p La forma como se aprenden los contenidos y se apropian para su comprensión, han cambiado los preceptos sociales de la educación en el binomio profesor-estudiante, la colaboración en línea y la creación de este tipo de plataformas ha potencializado esta área abriendo posibilidades en el ámbito educativo que llevan a reevaluar los procesos enseñanza-aprendizaje.

      .col-5.col-lg-2
        .objBox
          a(@click="modal2 = true")
            figure(data-aos="flip-up")
              img.nW(src='@/assets/curso/t3-m2.svg', alt='icono decorativo')
          //--.indicador--click(v-if="mostrarIndicador")    
        ModalA(:abrir-modal.sync="modal2")
          .row.align-items-center
            .col-lg-2
              figure
                img.nW(src='@/assets/curso/t3-im2.svg', alt='icono decorativo')
            .col-lg-10
              .h4 Empresas
              p Generan espacios colaborativos entre sus proveedores y usuarios, facilitando el acceso a la nube, son muy fáciles de usar bajo el principio de integración y colaboración entre equipos de trabajo y solucionan problemas de manera más efectiva, permitiendo el seguimiento de los casos.

      .col-5.col-lg-2
        .objBox
          a(@click="modal3 = true")
            figure(data-aos="flip-up")
              img.nW(src='@/assets/curso/t3-m3.svg', alt='icono decorativo')
          //--.indicador--click(v-if="mostrarIndicador")    
        ModalA(:abrir-modal.sync="modal3")
          .row.align-items-center
            .col-lg-2
              figure
                img.nW(src='@/assets/curso/t3-im3.svg', alt='icono decorativo')
            .col-lg-10
              .h4 Personal
              p Se han logrado avances importantes en cómo se genera la comunicación con los demás, los perfiles digitales permiten compartir información en diferentes formatos, llegando a todo tipo de público y encontrar alrededor del mundo personas con intereses comunes, la relación e intercambio de información va desde lo personal hasta lo profesional.

      .col-5.col-lg-2
        .objBox
          a(@click="modal4 = true")
            figure(data-aos="flip-up")
              img.nW(src='@/assets/curso/t3-m4.svg', alt='icono decorativo')
          //--.indicador--click(v-if="mostrarIndicador")    
        ModalA(:abrir-modal.sync="modal4")
          .row.align-items-center
            .col-lg-2
              figure
                img.nW(src='@/assets/curso/t3-im4.svg', alt='icono decorativo')
            .col-lg-10
              .h4 Gestión de proyectos
              p Existen muchas plataformas para la gestión de proyectos, que permiten organizar el trabajo de forma ágil y flexible, buscan la efectividad y aumentar tu productividad como persona y como equipo de trabajo, incluyen características propias de seguimiento y cumplimiento automatizado que hace que las actividades realizadas sean mejor controladas, desde alertas, calendarios, hasta mensajes de correo electrónico o notificaciones en los dispositivos.

      .col-5.col-lg-2
        .objBox
          a(@click="modal5 = true")
            figure(data-aos="flip-up")
              img.nW(src='@/assets/curso/t3-m5.svg', alt='icono decorativo')
          //--.indicador--click(v-if="mostrarIndicador")    
        ModalA(:abrir-modal.sync="modal5")
          .row.align-items-center
            .col-lg-2
              figure
                img(src='@/assets/curso/t3-im5.svg', alt='icono decorativo')
            .col-lg-10
              .h4 Gobierno
              p Como estrategias y políticas las administraciones públicas hacen uso de las plataformas colaborativas, generando espacios de servicio al ciudadano y tener de primera mano las percepciones de las personas y como estas llegan a cada usuario, la mejor forma de comunicar leyes, proyectos o información relevante han sido los medios digitales, para poder construir país de forma equitativa, estos sistemas de base tienen módulos y aplicaciones para que los usuarios puedan acceder


    Separador
    br
    br
    #t_3_2.titulo-segundo
      h2 3.2 El ciudadano digital del siglo XXI
    .row.mb-5
      .col-lg-2
        figure(data-aos="flip-left")
          img(src="@/assets/curso/t3-ic2.svg", alt="icono decorativo")
      .col-lg-10
        p Los avances tecnológicos y la aparición de los escenarios digitales han hecho que el ciudadano digital del siglo XXI, debe tener un conglomerado de habilidades, actitudes y conocimientos, <b>para que los individuos de una sociedad puedan participar en una sociedad democrática, haciendo uso de las TIC, de forma responsable, ética, libre y participativa</b>, teniendo control sobre sus deberes y derechos digitales y llevarlas hasta sus entornos personales y sociales.
    .row.justify-content-center
      .col-lg-10(data-aos="fade-left")
        .bloque-texto-a.color-acento-botones.p-4.p-md-5.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4.mb-4.mb-lg-0
              figure(data-aos="flip-left")
                img.nW(src="@/assets/curso/t3-i4.svg", alt="imagen decorativa")
            .col-lg-8
              .bloque-texto-a__texto.p-4.shadow-box(data-aos="fade-right")
                p La ciudadanía digital invita a tener una mirada integradora que comprenda tanto su aprendizaje, buen uso, tu seguridad y amenazas a las cuales estás expuesto, asociados al mal uso o peligros del entorno digital, al igual que determinar de manera transparente las oportunidades ofrecen las nuevas tecnologías de información y comunicación TIC y de esta manera el ser social adquiera competencias ciudadanas para fortalecer la democracia.

    p.mb-5  El uso responsable de las herramientas tecnológicas es una premisa que debe de tener el ciudadano digital del siglo XXI para poder relacionarse con sus semejantes en un tejido social, la empatía es un eje fundamental para ello, ya que con estos medios y herramientas no se tiene el contacto físico como tal se puede estar incurriendo en delitos o ser víctima de ellos, para ello, a continuación, se encuentran las diferentes dimensiones que están inmersos en ser buen ciudadano digital.
    TabsA.color-primario.mb-5
      .tarjeta.color-primario.p-4(titulo="Salud y bienestar digital")
        .row
          .col-lg-2
            figure(data-aos="flip-left")
              img.nW(src="@/assets/curso/t3-t1.svg", alt="icono decorativo")
          .col-lg-10
            .h4 Salud y bienestar digital
            p Tener cuidado sobre la salud física y mental asociado al uso prolongado de dispositivos electrónicos, la adicción y la dependencia digital es común en el día a día, por ello, se debe tener cuidado que los entornos virtuales lo saquen de la realidad.

      .tarjeta.color-primario.p-4(titulo="Alfabetización digital")
        .row
          .col-lg-2
            figure.slideInLeft
              img.nW(src="@/assets/curso/t3-t2.svg", alt="icono decorativo")
          .col-lg-10
            .h4 Alfabetización digital
            p Conoce las nuevas herramientas tecnologías, para que se usen según las necesidades, desarrollando habilidades y competencias de su buen uso.

      .tarjeta.color-primario.p-4(titulo="Seguridad digital")
        .row
          .col-lg-2
            figure.slideInLeft
              img.nW(src="@/assets/curso/t3-t3.svg", alt="icono decorativo")
          .col-lg-10
            .h4 Seguridad digital
            p Toma las precauciones necesarias para que la integridad no se vea en riesgo, proteja la información sensible para que terceros hagan uso indebido de la información publicada.

      .tarjeta.color-primario.p-4(titulo="Acceso digital")
        .row
          .col-lg-2
            figure.slideInLeft
              img.nW(src="@/assets/curso/t3-t4.svg", alt="icono decorativo")
          .col-lg-10
            .h4 Acceso digital
            p Observa, comparte e interactúa de forma responsable, un ciudadano digital debe tener competencias que integran el comportamiento que se tiene con los demás.

      .tarjeta.color-primario.p-4(titulo="Comunicación digital")
        .row
          .col-lg-2
            figure.slideInLeft
              img.nW(src="@/assets/curso/t3-t5.svg", alt="icono decorativo")
          .col-lg-10
            .h4 Comunicación digital
            p Observa, comparte e interactúa de forma responsable, un ciudadano digital debe tener competencias que integran el comportamiento que se tiene con los demás.

      .tarjeta.color-primario.p-4(titulo="Comercio digital")
        .row
          .col-lg-2
            figure.slideInLeft
              img.nW(src="@/assets/curso/t3-t6.svg", alt="icono decorativo")
          .col-lg-10
            .h4 Comercio digital
            p Aprende a enfocarte en lo que verdaderamente se necesita comprar online, si eres vendedor es importante enfocarse en las herramientas como oportunidades no en oportunismo.

      .tarjeta.color-primario.p-4(titulo="Leyes y responsabilidad digital")
        .row
          .col-lg-2
            figure.slideInLeft
              img.nW(src="@/assets/curso/t3-t7.svg", alt="icono decorativo")
          .col-lg-10
            .h4 Leyes y responsabilidad digital
            p Comportarse según las normas y el uso ético de la información, el acceso a la información es ilimitado y público, úsalo de manera responsable con habilidades éticas y de autocuidado. 





    Separador
    br
    br

    #t_3_3.titulo-segundo
      h2 3.3 Herramientas digitales de uso gubernamental, personal y empresarial
    .row.mb-5
      .col-lg-2
        figure(data-aos="flip-left")
          img(src="@/assets/curso/t3-ic3.svg", alt="icono decorativo")
      .col-lg-10
        p Las herramientas digitales cobijan todos los sectores ya sean públicas, personales o privadas, su uso responsable es particular dependiendo el campo de acción en las que se las use, estas incursionan de forma ágil y práctica para lograr mejor transparencia y buscan mejorar una convivencia digital efectiva. A continuación, se podrán conocer las herramientas desde el uso gubernamental, personal y empresarial.

    TabsC.color-primario.mb-5
      .py-3.py-md-4(titulo="Herramientas gubernamentales")
        .row.justify-content-center
          .col-md-10.mb-4.mb-md-0
            h4 Herramientas gubernamentales
            p.mb-4 Las estrategias de un gobierno digital o e-Gobierno radica en mejorar las comunicaciones estado - población - instituciones haciendo uso de las nuevas  tecnologías de información y comunicación y sacarles el mejor provecho en la generación de democracia, para agilizar trámites o promover la transparencia, entre las herramientas del gobierno digital te podrás encontrar con:
            .row.justify-content-center
              .col-lg-12
                figure
                  img(src='@/assets/curso/t3-info1.svg', alt='imagen decorativa')

      .py-3.py-md-4(titulo="Herramientas personales")
        .row.justify-content-center
          .col-md-10.mb-4.mb-md-0
            h4 Herramientas personales
            p.mb-4 Dentro de las herramientas digitales de uso personal, el campo de acción es bastante amplio, ya que buscan ayudar a compartir información y pueda llegar a todo tipo de personas, entre las mas comunes están:
            .row.justify-content-center
              .col-lg-12
                figure.slideInLeft
                  img(src='@/assets/curso/t3-info2.svg', alt='imagen decorativa')

      .py-3.py-md-4(titulo="Herramientas empresariales")
        .row.justify-content-center
          .col-md-10.mb-4.mb-md-0
            h4 Herramientas empresariales
            p.mb-4 La empresa no es ajena a los grandes avances tecnológicos, hoy en día existen gran cantidad de herramientas que ayudan a posicionar en el mercado las empresas y mejorar su productividad, entre los cuales se puede mencionar:
            .row.justify-content-center
              .col-lg-12
                figure.slideInLeft
                  img(src='@/assets/curso/t3-info3.svg', alt='imagen decorativa')











</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    mostrarIndicador: true,
    modal1: false,
    modal2: false,
    modal3: false,
    modal4: false,
    modal5: false,
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
