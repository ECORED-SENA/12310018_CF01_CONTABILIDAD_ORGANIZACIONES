<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Concepto de la empresa en Colombia y nociones asociadas 

  
      .col-lg-0.order-lg-1
        .bg-color-1.px-5.py-4
          p.mb-0 
    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 En Colombia, la empresa es una actividad económica organizada para producir bienes o prestar servicios, diferenciándose del local o la marca. Se entiende como la integración de recursos, personas y procesos orientados a generar valor bajo reglas y controles establecidos.
    
    p.mb-5 Con el fin de profundizar en el concepto de empresa en Colombia y sus nociones relacionadas, se presentarán las principales diferencias entre empresa, comerciante y establecimiento de comercio.
    

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

<style lang="sass"></style>
