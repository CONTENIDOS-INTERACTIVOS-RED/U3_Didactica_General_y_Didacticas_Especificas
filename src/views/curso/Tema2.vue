<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Pilares de la didáctica'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-color-2.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0
          figure
            img(src='@/assets/curso/tema2/1.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") Según Camilloni (2007), la didáctica se apoya en pilares fundamentales que orientan el proceso de enseñanza-aprendizaje. Estos pilares buscan optimizar la transmisión del conocimiento y el desarrollo de habilidades, promoviendo una enseñanza centrada en el estudiante, el aprendizaje significativo y el desarrollo integral.
    
    h2.mb-5(data-aos="fade-left") Pilar 1. El estudiante como protagonista del aprendizaje

    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema2/2.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        p(data-aos="fade-left") Este pilar reconoce al estudiante como un ser activo en la construcción de su conocimiento. Se fomenta su participación, reflexión crítica y autonomía, adaptando la enseñanza a sus necesidades, intereses y estilos de aprendizaje (Centro Educativo ECA, 2024).
    
        .bg-color-4.p-4.mb-3(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema2/3.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 “El aprendizaje significativo surge cuando el estudiante puede relacionar conocimientos nuevos con sus esquemas previos” (Ausubel, 2002, citado por Torres, 2016).
        p.mb-5(data-aos="fade-left") Los estudiantes dejan de ser receptores pasivos para convertirse en generadores y aplicadores del conocimiento. Es crucial crear un ambiente de aprendizaje activo, basado en proyectos reales, resolución de problemas y enseñanza diferenciada.

        h2(data-aos="fade-left") Estilos de aprendizaje
        p.mb-5 Según García Allen (2016), los estilos de aprendizaje son preferencias individuales en la forma de adquirir, procesar y retener información. Reflejan diferencias cognitivas, emocionales y fisiológicas, y permiten adaptar la enseñanza a cada estudiante.
    
    h2(data-aos="fade-left") Clasificación de Alonso, Gallego y Honey (1995)
    p.mb-5 Esta tipología identifica cuatro estilos predominantes, útiles para comprender cómo los niños aprenden desde edades tempranas:

    .bg-full-width.bg-color-info.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema2/4.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="67%" y="33%" numero="+")
                h5 01. Activo
                p Disfrutan de nuevas experiencias. 
                p <b>Ejemplo.</b> Mezcla de colores en taller artístico, promoviendo exploración y trabajo colaborativo.
    
              .bg-color-white.box-shadow.p-3(x="96%" y="33%" numero="+")
                h5 02. Reflexivo
                p Observan y analizan antes de actuar. 
                p <b>Ejemplo.</b> Observan figuras de animales marinos y luego expresan sus ideas con calma.
    
              .bg-color-white.box-shadow.p-3(x="67%" y="77%" numero="+")
                h5 03. Teórico
                p Son analíticos y buscan lógica.  
                p <b>Ejemplo.</b> Clasifican estaciones del año mediante fichas ilustradas, construyendo teorías simples.
    
              .bg-color-white.box-shadow.p-3(x="96%" y="77%" numero="+")
                h5 04. Pragmático
                p Prefieren lo práctico y útil.  
                p <b>Ejemplo.</b> Plantar semillas y observar su crecimiento, para comprobar el impacto de sus acciones.
    
    .bg-full-width.bg-color-7.mb-5
      .p-4.p-md-5
        h2(data-aos="fade-left") Otros estilos de aprendizaje, según procesamiento sensorial
        p.mb-5 Además de la clasificación anterior, existen estilos basados en las vías sensoriales preferidas para el aprendizaje:

        div.row.justify-content-center.align-items-stretch
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/5.svg" alt="" style="width: 90px")
              h5.text-center Visual
              p.mb-0.text-center Prefieren imágenes, colores y mapas conceptuales. Se entusiasman con gráficos y dibujos.
        
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/6.svg" alt="" style="width: 90px")
              h5.text-center Auditivo
              p.mb-0.text-center Aprenden escuchando. Disfrutan cuentos, canciones y explicaciones orales.
        
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/7.svg" alt="" style="width: 90px")
              h5.text-center Kinestésico
              p.mb-0.text-center Necesitan moverse y tocar. Aprenden construyendo, explorando y manipulando objetos.
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/8.svg" alt="" style="width: 90px")
              h5.text-center Lector/Escritor
              p.mb-0.text-center Prefieren leer y escribir. Les gusta copiar letras, colorear y hojear libros.
    
    .bg-full-width.bg-color-3.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema2/9.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Identificar el estilo preferido potencia el aprendizaje y permite una enseñanza personalizada (García Allen, 2016).
    
    h2(data-aos="fade-left") Pilar 2. El contenido significativo y relevante
    p.mb-5 Según Ausubel (2002), el contenido debe tener un propósito claro, conectarse con los intereses y experiencias de los estudiantes, y aplicarse en situaciones reales. Este enfoque fortalece el aprendizaje profundo y útil. Las características y ejemplos del contenido significativo son: 

    .bg-full-width.bg-color-5.mb-5
      .p-4.p-md-5

        TabsC.color-acento-contenido.mb-5
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Conexión con conocimientos previos" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
                h4 Conexión con conocimientos previos
                p Relacionar nuevos temas con experiencias pasadas (visita a un parque → enseñanza de ecosistemas).
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema2/10.png', alt='')
        
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Relevancia contextual" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
                h4 Relevancia contextual
                p Adaptar contenidos al entorno cultural, social y económico del alumno.
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema2/11.png', alt='')
        
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Aplicabilidad práctica" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
                h4 Aplicabilidad práctica
                p Utilizar escenarios reales: enseñar matemáticas con compras o distribución de recursos.
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema2/12.png', alt='', style="width: 100%;")
        
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Intereses del estudiante" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
                h4 Intereses del estudiante
                p Incluir temas atractivos como deportes, naturaleza, tecnología.
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema2/13.png', alt='', style="width: 100%;")
        
        p.mb-4 Las ventajas del <b>contenido significativo</b>, son: 
        
        div.row.justify-content-center.align-items-stretch
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/14.svg" alt="" style="width: 90px")
              h5.text-center Primero
              p.mb-0.text-center Aumenta la motivación y participación.
        
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/15.svg" alt="" style="width: 90px")
              h5.text-center Segundo
              p.mb-0.text-center Mejora la retención y comprensión.
        
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/16.svg" alt="" style="width: 90px")
              h5.text-center Tercero
              p.mb-0.text-center Desarrolla habilidades para la vida como la toma de decisiones y resolución de problemas.
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/17.svg" alt="" style="width: 90px")
              h5.text-center Cuarto
              p.mb-0.text-center Fomenta el vínculo emocional con el conocimiento.
        
    p.mb-4 Las estrategias sugeridas para su implementación son: 

    .bg-full-width.bg-color-9.mb-5
      .p-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").mb-3.mb-lg-0
                ul.lista-ul--color
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-10
                    p.mb-0 Desarrollar proyectos colaborativos basados en problemas reales.
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-10
                    p.mb-0 Integrar herramientas digitales que respondan a los intereses actuales del grupo.
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-10
                    p.mb-0 Promover debates que conecten la teoría con experiencias cotidianas.
              .col-lg-4(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema2/18.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    h2(data-aos="fade-left") Pilar 3. El docente como mediador y facilitador
    p.mb-5 Para Camilloni (2007), el docente deja de ser solo transmisor de información y se convierte en guía del proceso de enseñanza-aprendizaje. Su rol implica generar experiencias educativas activas, inclusivas y contextualizadas.

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/19.png")
            .col-lg-7
              h5 Promotor del aprendizaje activo
              p Diseña actividades que requieren reflexión, resolución de problemas y trabajo colaborativo.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/20.png")
            .col-lg-7
              h5 Generador de confianza
              p Crea un ambiente donde los estudiantes puedan expresarse libremente y aprender del error.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/21.png")
            .col-lg-7
              h5 Adaptador de estrategias didácticas
              p Emplea metodologías variadas, como proyectos, TICs y dinámicas colaborativas.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/22.png")
            .col-lg-7
              h5 Modelo de pensamiento crítico y reflexivo
              p Estimula el análisis y la conexión del conocimiento con la realidad.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema2/23.png")
            .col-lg-7
              h5 Facilitador de la colaboración
              p Promueve el trabajo grupal y el respeto por las ideas ajenas.
    
    .row.mb-5.align-items-center
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema2/24.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        .bg-color-2.p-5(data-aos="fade-left")
          h5 Ejemplo de aplicación del rol docente
          p.mb-0 En una clase de ciencias, el docente propone un proyecto sobre el impacto del cambio climático en la comunidad. Los estudiantes investigan, discuten y proponen soluciones. El docente guía el proceso, facilita recursos y promueve la conexión entre la teoría científica y el contexto local.

    h2.mb-5(data-aos="fade-left") Pilar 4: Metodologías activas para la participación del estudiante
          
    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema2/25.svg", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        p Este enfoque didáctico sitúa al estudiante como protagonista activo del proceso de enseñanza-aprendizaje, promoviendo la construcción del conocimiento a través de la interacción, la reflexión y la aplicación práctica. Las metodologías activas, como el aprendizaje basado en problemas (ABP), el aprendizaje cooperativo, el estudio de casos y la simulación, integran habilidades cognitivas, sociales y prácticas (Camilloni, 2007). Las principales metodologías activas son: 
              
    .bg-full-width.bg-color-5.mb-5
      .p-4.p-md-5

        TabsC.color-acento-contenido.mb-5
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Aprendizaje basado en problemas (ABP)" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
                h4 Aprendizaje basado en problemas (ABP)
                p Parte de un problema real o ficticio, para que los estudiantes investiguen, analicen y propongan soluciones. 
                p <b>Ejemplo.</b> “¿Cómo reducir la contaminación en nuestra comunidad?”. Los alumnos investigan causas y diseñan un plan de acción (Matini, 2024).
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema2/26.png', alt='')
        
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Aprendizaje cooperativo" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
                h4 Aprendizaje cooperativo
                p Se fundamenta en el trabajo en equipo con roles asignados. Promueve la comunicación, empatía y resolución de conflictos. 
                p <b>Ejemplo.</b> En historia, los estudiantes debaten desde distintas perspectivas sobre una independencia nacional (Matini, 2024).
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema2/27.png', alt='')
        
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Estudio de casos" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
                h4 Estudio de casos
                p Presenta situaciones reales o hipotéticas que deben ser analizadas críticamente. 
                p <b>Ejemplo.</b> En ética, los alumnos analizan dilemas sobre privacidad en redes sociales y proponen soluciones (Camilloni, 2007).
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema2/28.png', alt='', style="width: 100%;")
        
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Simulación" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
                h4 Simulación
                p Recrea situaciones reales en entornos controlados, conectando teoría y práctica. 
                p <b>Ejemplo.</b> En economía, los estudiantes participan en una simulación de mercado como vendedores y consumidores (Camilloni, 2007).
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema2/29.png', alt='', style="width: 100%;")
        
        p.mb-4 Las <b>ventajas</b> de estas metodologías son: : 
        
        div.row.justify-content-center.align-items-stretch
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/30.svg" alt="" style="width: 90px")
              h5.text-center Primero
              p.mb-0.text-center Fomentan el pensamiento crítico y creativo.
        
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/31.svg" alt="" style="width: 90px")
              h5.text-center Segundo
              p.mb-0.text-center Mejoran la resolución de problemas reales en equipo.
        
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/32.svg" alt="" style="width: 90px")
              h5.text-center Tercero
              p.mb-0.text-center Promueven la autonomía y el compromiso.
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/33.svg" alt="" style="width: 90px")
              h5.text-center Cuarto
              p.mb-0.text-center Generan una experiencia educativa significativa y contextualizada.
        
    
    .row.mb-5.align-items-center
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema2/34.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        .bg-color-1.p-5(data-aos="fade-left").h-100
          h5 Implicaciones para el rol docente
          p.mb-0 El éxito de estas metodologías, exige un docente mediador, que oriente sin imponer, facilite recursos, promueva la exploración y ajuste estrategias didácticas, según las necesidades del grupo (Camilloni, 2007).
    
    h2(data-aos="fade-left") Pilar 5. La evaluación formativa y continua
    p.mb-0 En el contexto educativo actual, la evaluación se concibe no solo como una medición de resultados, sino como una herramienta pedagógica que acompaña el aprendizaje. La evaluación formativa y continua, surge como un pilar fundamental que transforma la manera en que se valora el proceso educativo, priorizando el seguimiento permanente, la retroalimentación oportuna y la adaptación constante de las estrategias docentes para favorecer el desarrollo integral del estudiante.



    .bg-full-width.bg-color-5.mb-4
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-6.order-2.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/tema2/podcast.svg", data-aos="zoom-in")
          .col-lg-6.order-1
            p(data-aos="fade-left").mb-4 Para conocer esta temática, lo invitamos a escuchar el siguiente pódcast.

    
            TarjetaAudio.color-acento-botones.bg-color-white.mb-3(
              texto="La evaluación formativa y continua"
              tiempo
              :audio="require('../../assets/curso/podcast/podcast1.mp3')"
            )


    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/35.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        .bg-color-4.p-4.mb-5(data-aos="fade-left")
          h5 Ejemplo práctico
          p.mb-0 En una clase de ciencias, se implementa un portafolio donde los estudiantes registran sus experimentos, reflexiones y aprendizajes. Este se revisa periódicamente, con retroalimentación del docente para mejorar habilidades de análisis y presentación.
        p(data-aos="fade-left") En conjunto, los <b>cinco pilares de la didáctica</b> abordados, el estudiante como protagonista, el contenido significativo, el rol mediador del docente, las metodologías activas y la evaluación formativa, constituyen una guía integral para enriquecer el proceso de enseñanza-aprendizaje. Esta visión potencia una educación transformadora que no solo transmite conocimiento, sino que desarrolla en los estudiantes la capacidad de aplicarlo críticamente, con creatividad y en colaboración con otros.
    
    .bg-full-width.bg-color-2.mb-lg-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.order-2
            h2.mb-4(data-aos="flip-up") Estructura de planeación: metodología, modelo, objetivo, teoría de la propuesta pedagógica
            p.mb-4(data-aos="fade-right") Se invita a leer el documento <b>Estructura de planeación: metodología, modelo, objetivo, teoría de la propuesta pedagógica</b>, donde se aborda el diseño y desarrollo de la planeación didáctica, especialmente enfocada en la educación infantil.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Estructura de planeación: metodología, modelo, objetivo, teoría de la propuesta pedagógica.
    
          .col-lg-5.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/36.png', alt='')



    .bg-full-width.border-top.actividad.bg-color-actividad
        .p-4.p-md-5
          #Actividad                
            <Actividad :cuestionario="cuestionario"/>


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/129726?page=12" target="_blank" rel="noopener noreferrer") Sáez López, J. M. (2018). Estilos de aprendizaje y métodos de enseñanza. UNED - Universidad Nacional de Educación a Distancia. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://view.genially.com/608ac5d029b4970d884f34d8/presentation-pilares-de-la-didactica-de-nivel-inicial " target="_blank" rel="noopener noreferrer") Alejandra. (2021). Pilares de la Didáctica de Nivel inicial. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=rpR1QCwMWh8" target="_blank" rel="noopener noreferrer") Digital Family Canal. (2023). Beneficios de implementar las metodologías activas en el aula [video]. YouTube. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema2',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Herramientas colaborativas para la construcción de paz',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              '¿Qué representa la planificación didáctica en el proceso educativo?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'La improvisación de estrategias de enseñanza.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'La estructura de los pilares teóricos sin aplicación práctica.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'La organización sistemática de objetivos, contenidos y actividades para el aprendizaje.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto:
                  'Una lista de actividades aleatorias para llenar el tiempo en clase.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              '¿Cuál es el objetivo principal de la planificación didáctica?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Incluir teorías sin relación con el acto educativo.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Facilitar la construcción de escenarios pedagógicos modernos.',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto:
                  'Eliminar la importancia de los pilares de la didáctica.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto:
                  'Evitar la evaluación del proceso de enseñanza-aprendizaje.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              '¿Qué etapas constituyen la estructura de planeación básica?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Inicio, desarrollo y cierre.',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Planeación, ejecución y evaluación.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Evaluación y retroalimentación únicamente.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Identificación, improvisación y conclusión.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              'Según los pilares de la didáctica, ¿cuál es una función clave del acto didáctico?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Ignorar las diferencias en los tipos de aprendizaje.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Promover la interacción entre enseñanza y aprendizaje.',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Reducir el papel del docente en el aula.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Excluir el uso de metodologías adaptables.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              '¿Qué caracteriza un escenario didáctico acorde con las tendencias pedagógicas actuales?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'El uso exclusivo de herramientas tradicionales.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'La aplicación de principios teóricos sin actividades prácticas.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'La integración de metodologías y planificación adaptables.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'La ausencia de evaluación en el proceso educativo.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
