<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Herramientas y plataformas colaborativas
    
    #t_3_1.titulo-segundo
      h2 3.1 Concepto, usos y características





    Separador
    br
    br
    #t_3_2.titulo-segundo
      h2 3.2 El ciudadano digital del siglo XXI





    Separador
    br
    br

    #t_3_3.titulo-segundo
      h2 3.3 Herramientas digitales de uso gubernamental, personal y empresarial













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

<style lang="sass" scoped></style>
