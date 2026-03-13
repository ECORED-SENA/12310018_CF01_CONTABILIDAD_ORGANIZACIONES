<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Marco normativo base para comprender la empresa en Colombia 
    
    p.mb-5 El marco normativo explica la regulación y responsabilidad de la empresa en Colombia. La Constitución garantiza la libertad económica, reconoce su función social y permite la intervención del Estado para proteger el interés general. Además, el Código de Comercio define la empresa como una actividad económica organizada y diferencia los conceptos de empresa, comerciante y establecimiento de comercio. 
    
    .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-5
          img(src="@/assets/curso/tema1/img1.png")
    p.mb-5 A continuación, se presentan las principales normas jurídicas que fundamentan y orientan el desarrollo del presente componente formativo, las cuales permiten comprender el marco legal aplicable al estudio de la empresa en Colombia.
    .row.mb-5.align-items-center.justify-content-center
      .col-md-8.col-lg-3.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/img2.png", data-aos="zoom-in")
      .col-lg-9
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg-color-9")
          div(titulo="Constitución Política")
            p.ms-0 Artículo / acto: Arts. 333-334.
            .row.mb-5.justify-content-center.align-items-center
              .col-lg-5.mb-0.mb-lg-0.order-lg-2
                figure
                  img(src="@/assets/curso/tema1/img3.png", data-aos="zoom-in")
              .col-lg-7.order-lg-1
                ul.lista-ul--color.ms-5
                    i.fas.fa-circle-check.bg-color.bg-color-8
                    | <b>¿Qué establece?</b> Libertad económica; función social de la empresa; intervención del Estado.
                    li.mb-6.d-flex       
                    i.fas.fa-circle-check.bg-color.bg-color-8
                    | <b>¿Cómo se usa?</b> Explica por qué existen obligaciones y controles empresariales.  
                  
          div(titulo="Código de Comercio (Decreto. 410/1971")
            p.ms-5 Artículo / acto: Art. 25
            .row.mb-5.justify-content-center.align-items-center
              .col-lg-5.mb-0.mb-lg-0.order-lg-2
                figure
                  img(src="@/assets/curso/tema1/img4.png", data-aos="zoom-in")
              .col-lg-7.order-lg-1
                ul.lista-ul--color.ms-5
                    i.fas.fa-circle-check.bg-color.bg-color-8
                    | <b>¿Qué establece?</b> Concepto legal de empresa como actividad económica organizada.
                    li.mb-6.d-flex       
                    i.fas.fa-circle-check.bg-color.bg-color-8
                    | <b>¿Cómo se usa?</b> Define empresa y diferencia empresa vs. lugar o nombre.  
          div(titulo="Código de Comercio (Decreto. 410/1971)")
            p.ms-5 Artículo / acto: Art. 10
            .row.mb-5.justify-content-center.align-items-center
              .col-lg-5.mb-0.mb-lg-0.order-lg-2
                figure
                  img(src="@/assets/curso/tema1/img5.png", data-aos="zoom-in")
              .col-lg-7.order-lg-1
                ul.lista-ul--color.ms-5
                    i.fas.fa-circle-check.bg-color.bg-color-8
                    | <b>¿Qué establece?</b> Concepto de comerciante.
                    li.mb-6.d-flex       
                    i.fas.fa-circle-check.bg-color.bg-color-8
                    | <b>¿Cómo se usa?</b> Ubica quién ejerce profesionalmente actividades mercantiles. 
          div(titulo="Código de Comercio (Decreto. 410/1971)")
            p.ms-5 •	Artículo / acto: Art. 515
            .row.mb-5.justify-content-center.align-items-center
              .col-lg-5.mb-0.mb-lg-0.order-lg-2
                figure
                  img(src="@/assets/curso/tema1/img6.png", data-aos="zoom-in")
              .col-lg-7.order-lg-1
                ul.lista-ul--color.ms-5
                    i.fas.fa-circle-check.bg-color.bg-color-8
                    | <b>¿Qué establece?</b> Definición de establecimiento de comercio
                    li.mb-6.d-flex       
                    i.fas.fa-circle-check.bg-color.bg-color-8
                    | <b>¿Cómo se usa?</b> Aclara que el establecimiento no es sinónimo de empresa.
          div(titulo="Ley 590/2000 y Ley 905/2004")
            p.ms-5 Artículo / acto: MIPYMES
            .row.mb-5.justify-content-center.align-items-center
              .col-lg-5.mb-0.mb-lg-0.order-lg-2
                figure
                  img(src="@/assets/curso/tema1/img7.png", data-aos="zoom-in")
              .col-lg-7.order-lg-1
                ul.lista-ul--color.ms-5
                    i.fas.fa-circle-check.bg-color.bg-color-8
                    | <b>¿Qué establece?</b> Marco para promover MiPymes y su enfoque de clasificación
                    li.mb-6.d-flex       
                    i.fas.fa-circle-check.bg-color.bg-color-8
                    | <b>¿Cómo se usa?</b> Justifica la categoría micro/pequeña/mediana como referencia de política pública.



</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
