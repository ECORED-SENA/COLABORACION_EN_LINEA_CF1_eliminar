<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5






    #t_1_1.titulo-segundo
      h2  1.1  Características  y clasificación de las TIC
    p.mb-5  Las tecnologías de información y comunicación poseen diferentes características que, por ser dinámicas y ágiles, hacen que los procesos comunicacionales entre las personas se hagan más fáciles. Dentro de las más representativas se encuentran: 
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/iJOOfpo1SdM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)



    #t_1_2.titulo-segundo
      h2  



    #t_1_3.titulo-segundo
      h2 






















    //- El componente "Muestras" tiene las aplicaciones de todos los componentes de la base
    //- se encuentra en src/components/Muestras.vue
    //- Una vez el componente "Muestras" no se necesite 
    //- Se debe borrar el "import Muestras from '../components/Muestras'" y en "components" en "<script"
    //- esto evitará que se compile en la carpeta final de distribución
    Muestras





  
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
