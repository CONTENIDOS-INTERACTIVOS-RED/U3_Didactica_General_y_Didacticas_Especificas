<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. La planificación didáctica'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema1/1.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        .bg-color-4.p-4.mb-5(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 La planificación didáctica constituye una práctica central en el trabajo docente y en la formación inicial de educadores. Lejos de ser un instrumento rígido, se concibe como una herramienta dinámica y reflexiva que orienta el proceso de enseñanza-aprendizaje. Implica decisiones que el docente toma antes, durante y después del desarrollo de sus clases, considerando los objetivos, los contenidos, las estrategias y las evaluaciones, siempre en función del contexto específico del aula.
        p(data-aos="fade-left") Diversos autores han aportado miradas complementarias sobre su significado, características, funciones y enfoque. A continuación, se presentan estos aportes de forma estructurada para facilitar su comprensión y comparación.
    
    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/3.png")
            .col-lg-7
              h5 Monetti y Molina (2021)
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 Consideran la planificación como una <b>hipótesis de trabajo</b>, abierta a revisión y mejora. 
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 La describen como un <b>género profesional</b> que combina oralidad y escritura.
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 Enfatizan su carácter <b>reflexivo y flexible</b>, adaptado a contextos complejos.
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 Proponen un enfoque discursivo que la vincula con la práctica real del docente.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/4.png")
            .col-lg-7
              h5 Lifeder (2025)
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 Define la planificación como un proceso de <b>toma de decisiones</b> concretas para implementar el programa educativo.  
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 Destaca su <b>adaptabilidad al contexto del aula</b>, considerando objetivos, contenidos y características del alumnado. 
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 Subraya la importancia de respetar las <b>normativas legales nacionales</b> que regulan su estructura.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/5.png")
            .col-lg-7
              h5 Escritos de Psicología (2025)
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 Presenta la planificación como una herramienta que organiza el proceso de enseñanza para alcanzar <b>objetivos específicos</b>.   
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 Delimita <b>estrategias, métodos y criterios de evaluación</b>, creando un entorno favorable para el aprendizaje. 
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 Facilita la <b>participación activa</b> del estudiantado y permite responder a distintos estilos de aprendizaje.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/6.png")
            .col-lg-7
              h5 Montagud Rubio (2020)
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 Sostiene que el docente debe planificar <b>antes de iniciar el curso</b>, definiendo objetivos, contenidos, estrategias y evaluación.  
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 Afirma que la planificación convierte los contenidos en <b>actividades significativas</b>, facilitando el aprendizaje.  
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  p.mb-0 Permite <b>prever el avance</b> del curso y hacer ajustes según las necesidades del grupo.
    
    h2.mb-5(data-aos="fade-left") Características 

    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/7.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        .bg-color-1.p-4.mb-5(data-aos="fade-left")
          p.mb-0 La planificación didáctica eficaz, no solo debe responder a los objetivos curriculares institucionales, sino también adaptarse a los contextos cambiantes y a las necesidades reales del grupo de estudiantes. Su construcción implica procesos de escritura reflexiva, colaboración docente, toma de decisiones estratégicas y flexibilidad. Diversos autores coinciden en que una planificación bien formulada permite organizar, coordinar y proyectar la enseñanza con coherencia y sentido pedagógico.
        p(data-aos="fade-left") A continuación, se presentan sus principales características según los enfoques de Montagud Rubio, Lifeder, y Monetti y Molina.
    
    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/8.png", alt="").mb-4.mb-lg-0
      .col-lg-8
    
        AcordionA(tipo="b")
          .div(titulo="Montagud Rubio (2020)")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 Las planeaciones deben estar escritas (en papel o digital) con objetivos y estrategias claras.  
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 Deben alinearse con el marco institucional y garantizar que los contenidos sean asimilables. 
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 El proceso debe incluir colaboración con docentes que hayan enseñado previamente la materia, lo cual enriquece la planificación.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 La planificación debe ser flexible y realista, considerando posibles ajustes en el temario o en los tiempos.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 La coordinación entre docentes reduce incertidumbres y favorece un ambiente cohesivo de enseñanza.
    
          .div(titulo="Lifeder (2025)")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 La planeación debe responder a la realidad actual del grupo, siendo adaptable y personalizada.  
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 Debe ser realista en cuanto a objetivos y estrategias, asegurando su viabilidad en el aula. 
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 Tiene como finalidad responder preguntas clave: ¿qué competencias deben adquirir los estudiantes?, ¿qué acciones facilitarán su aprendizaje?, ¿cómo se evaluará?
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 Las planificaciones deben contemplar mínimos estructurales que garanticen un proceso educativo efectivo.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 La flexibilidad es fundamental para realizar ajustes según surjan nuevas necesidades.
    
          .div(titulo="Monetti y Molina (2021)")
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 La planificación tiene por objetivo diseñar y programar la enseñanza, abordando el qué, cómo, por qué y para qué se enseña.  
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 Cumple funciones de comandar, informar y expresar (Ciapuscio, 2012), esenciales para organizar la acción pedagógica.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 Es un género profesional, destinado al propio docente y a sus colegas o la institución.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 Permite la reflexión personal del docente y la exploración del potencial epistémico de la escritura (Carlino, 2005).
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 La escritura se apoya en procedimientos discursivos (descripción, fundamentación) y se organiza en categorías textuales (Cols, 2004; Davini, 2008).
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-10
                p.mb-0 En un estudio sobre 93 planificaciones, el 88 % seguía una estructura prototípica, lo que revela cierta regularidad discursiva con márgenes de libertad.
    
    .bg-full-width.bg-color-3
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema1/9.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 La planificación didáctica no es una simple exigencia administrativa, sino una herramienta profesional compleja que articula conocimientos, contextos y prácticas. En su elaboración intervienen procesos colaborativos, funciones discursivas y decisiones pedagógicas que permiten estructurar, legitimar y comunicar la intención educativa de forma eficaz y situada.
        
        
    

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/67059?page=24 " target="_blank" rel="noopener noreferrer") Pitluk, L. (2012). La planificación didáctica en el Jardín de Infantes: las unidades didácticas, los proyectos y las secuencias didácticas: el juego trabajo. Homo Sapiens Ediciones. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.escritosdepsicologia.es/planificacion-didactica/" target="_blank" rel="noopener noreferrer") Escritos de Psicología. (2025). Claves para una planificación didáctica efectiva en educación.  


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=CFDwtj8rsKw " target="_blank" rel="noopener noreferrer") DescLAB. (2019). LAB Webinar - PIAR 02 - El PIAR es una herramienta de planeación pedagógica y didáctica [video]. YouTube. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
