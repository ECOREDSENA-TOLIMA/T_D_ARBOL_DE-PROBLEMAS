<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Árbol de problemas
      
    Separador
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Planeación de actividades

    
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-12.col-md-5.mb-2
        img(src='@/assets/curso/temas/img-1.png', alt='')
      .col-12.col-md-7
        .cajon.color-primario.p-4.mb-3
          p.mb-0 Un árbol de problema consiste en desarrollar ideas creativas para identificar las posibles causas del conflicto, generando de forma organizada un modelo que explique las razones y consecuencias del problema. (Martínez, R., & Fernández, A. 2008). 
        p.mb-0 El árbol de problemas constituye una metodología participativa dentro del ámbito del pensamiento visual, destinada a fomentar la generación de ideas creativas para la identificación y organización de problemas. Mediante su aplicación, se desarrolla un modelo visual que representa las relaciones causales asociadas al problema en cuestión, este enfoque implica la identificación y análisis exhaustivo de las causas y efectos vinculados al problema, proporcionando una visión integral de la situación definida.

    p.mb-3(data-aos="fade-down") La representación gráfica de este proceso se materializa a través de un árbol, cuyos elementos principales son el tronco (que representa el problema central), las raíces (que simbolizan las causas), y la copa (que refleja los efectos). Al estructurar la información de esta manera, se facilita la comprensión de los problemas, allanando el camino para la formulación de propuestas de valor innovadoras. A continuación, se describen los elementos que componen el árbol de problemas.
    p.mb-5(data-aos="fade-down") Es necesario visualizar y desarrollar esta metodología con la integralidad causa - problema - efecto, es decir, casa causa tiene uno o varios efectos o consecuencias que reflejan nuevas situaciones problémicas que requieren ser atendidas efectivamente. Esta integralidad aporta a la identificación de alternativas de solución pertinentes que al atender el problema central incidirán en la solución de sus efectos. Esto facilita la identificación general del problema y facilita identificar la alternativa de solución.

    Separador
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Elementos que componen el árbol de problemas 

    p.mb-5(data-aos="fade-down") El árbol de problemas tiene la siguiente estructura:
    
    .row.justify-content-center.mb-5(data-aos="fade-left")
      .col-12.col-lg-10
        figure 
          img(src='@/assets/curso/temas/img-2.svg', alt='La figura indica la relación entre un árbol y la formulación de un problema, en donde la raíz equivale a la causa, el tronco al problema, y el follaje al efecto.')

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-12
        .cajon.color-primario.p-4.mb-0
          p #[b • CAUSA:] esta fase implica identificar los aspectos negativos de una situación, identificando las causas del problema observado. 
          p #[b •	PROBLEMA:] se refiere a cualquier pregunta o asunto que implique duda, incertidumbre o dificultad, así como a una situación problémica propuesta o real que deba ser solucionada.
          p.mb-0 #[b •	EFECTOS:] representan los efectos y el impacto que trae consigo el problema para la interesados o afectados de manera directa o indirecta.

    Separador
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Pasos para elaborar un árbol de problemas

    .BGIMG01.mb-5.p-4(data-aos="fade-down")
      LineaTiempoB.color-secundario.mb-5(:datos="datosLineaTiempoB")

    Separador
    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.4 Herramientas digitales para la elaboración de un árbol de problemas

    p.mb-5(data-aos="fade-down") Las siguientes herramientas posibilitan la elaboración de la metodología del árbol de problemas, permitiendo plasmar el análisis realizado mediante la creación de un gráfico y la generación de una URL para compartirlo.

    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row(titulo="Canva")
        .col-md-6.mb-4.mb-md-0
          p.mb-4 Es posiblemente el programa online más potente del mercado en este momento para realizar esquemas. Es gratuita y versátil.  
          a.boton.color-acento-botones(href="https://www.canva.com/es_co/graficos/arbol-decisiones/" target="_blank")
            span Enlace web
            i.fas.fa-code
        .col-md-6
          figure
            img(src='@/assets/curso/temas/img-3.png', alt='')
      .row(titulo="Lucidchart")
        .col-md-6.mb-4.mb-md-0
          p Es una plataforma web, que permite crear, dibujar, revisar y compartir gráficos, esquemas y diagramas.  
          a.boton.color-acento-botones(href="https://www.lucidchart.com/pages/es/ejemplos/diagrama-de-arbol-online" target="_blank")
            span Enlace web
            i.fas.fa-code
        .col-md-6
          figure
            img(src='@/assets/curso/temas/img-4.png', alt='')
      .row(titulo="Visme")
        .col-md-6.mb-4.mb-md-0
          p Es una herramienta en línea que permite a todos los usuarios crear gráficos dinámicos para comunicar visualmente datos, conceptos e ideas.
          a.boton.color-acento-botones(href="https://www.visme.co/es/diagrama-de-arbol/" target="_blank")
            span Enlace web
            i.fas.fa-code
        .col-md-6
          figure
            img(src='@/assets/curso/temas/img-5.png', alt='')
      .row(titulo="Creately")
        .col-md-6.mb-4.mb-md-0
          p Herramienta online donde se pueden crear diagramas. 
          a.boton.color-acento-botones(href="https://creately.com/es/lp/creador-de-arboles-de-decisiones-en-linea/" target="_blank")
            span Enlace web
            i.fas.fa-code
        .col-md-6
          figure
            img(src='@/assets/curso/temas/img-6.png', alt='')
      .row(titulo="Word o PowerPoint")
        .col-md-6.mb-4.mb-md-0
          p Permiten crear diagramas, editar, compartir y trabajar de manera colaborativa.	
        .col-md-6
          figure
            img(src='@/assets/curso/temas/img-7.png', alt='')

    Separador
    #t_1_5.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.5 Ejemplo de un árbol de problemas

    .row.justify-content-center.mb-5(data-aos="fade-left")
      .col-12.col-lg-10
        figure 
          img(src='@/assets/curso/temas/img-8.svg', alt='Se presenta un ejemplo de árbol de problemas con el aumento de quejas y reclamos como problema central. Las causas identificadas incluyen un deficiente servicio postventa, mientras que los efectos abarcan la disminución de las compras realizadas por los clientes, entre otros aspectos.')
          figcaption Nota. Tomado y adaptado de Betancourt, D. F. Ejemplo práctico. (05 de julio de 2016).

    p.mb-5(data-aos="fade-down") En el diagrama las flechas deben estar ubicadas hacia arriba, lo que permite evidenciar la relación de causa - efecto - problema, como se muestra a continuación:
    
    .row.justify-content-center.mb-5(data-aos="fade-left")
      .col-12.col-lg-10
        figure 
          img(src='@/assets/curso/temas/img-9.svg', alt='Se expone un esquema de árbol de problemas que visualiza las causas mediante líneas ascendentes hacia el problema central, así como los efectos que se desprenden de este último.')
          figcaption Tomado de #[a(href="https://olgerchaparro.blogspot.com/2011/09/que-cosa-es-el-arbol-de-problemas-el.html" target="_blank" style="color:blue") https://olgerchaparro.blogspot.com/2011/09/que-cosa-es-el-arbol-de-problemas-el.html]


    

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
    datosLineaTiempoB: [
      {
        titulo: null,
        texto:
          'Se debe leer atentamente el enunciado proporcionado por el instructor.',
        icono: require('@/assets/curso/temas/time-1a.svg'),
      },
      {
        titulo: null,
        texto: 'Se debe identificar el problema central.',
        icono: require('@/assets/curso/temas/time-1b.svg'),
      },
      {
        titulo: null,
        texto: `Posteriormente, se deben responder las siguientes preguntas:
<p class="mt-2 mb-0"> • ¿Cuáles son las causas de este problema?</p>
<p class="mb-0"> • ¿Por qué existe el problema?</p>
<p class="mb-0"> • ¿Qué efectos tiene el problema?</p>
<p class="mb-0"> • ¿Qué otros problemas que se pueden identificar a raíz del problema central?</p>
<p class="mb-0"> • ¿Por qué es importante resolverlo?</p>
<p class="mb-0"> • ¿A quién está afectando?</p>
<p class="mb-0"> • ¿Quién es responsable del problema?</p>

        `,
        icono: require('@/assets/curso/temas/time-1c.svg'),
      },
      {
        titulo: null,
        texto:
          'Una vez que se haya identificado el problema y se hayan respondido las preguntas, se procede a diseñar el árbol en borrador para poder establecer el grado de profundidad.',
        icono: require('@/assets/curso/temas/time-1d.svg'),
      },
      {
        titulo: null,
        texto:
          'Es importante tener presente que cada causa genera un efecto y que, si la causa desaparece, el efecto también desaparecerá.',
        icono: require('@/assets/curso/temas/time-1e.svg'),
      },
      {
        titulo: null,
        texto:
          'Se recomienda organizar en jerarquía tanto las causas como los efectos, es decir, analizar su interrelación y cómo una conduce a la otra para esto se sugiere numerar cada una de las causas y sus efectos, ejemplo: causa1 tiene 5 efectos, los efectos deben estar numerados como efecto 1.1, efecto 1.2, efecto 1.3, efecto 1.4 y efecto 1.5.',
        icono: require('@/assets/curso/temas/time-1f.svg'),
      },
    ],
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
