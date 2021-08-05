<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Tecnología en Desarrollo de productos electrónicos
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Tecnología en Desarrollo de productos electrónicos
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 224204
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 3984 Horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en meses: 
                p.banner-principal__datos__item__texto 27 Meses
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto Virtual

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/43qG8hrF6CU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Estimado aprendiz le damos la bienvenida al programa virtual Tecnología en desarrollo de productos electrónicos donde podrá acercarse a la formación integral que le ofrece el SENA, además de fortalecer sus conocimientos destrezas y habilidades, que permitirán desempeñarse mejor en su vida laboral.
      br
      br
      |El egresado del programa será competente para realizar el estudio, definición, concepción y desarrollo de tarjetas y productos electrónicos, con capacidad para desarrollar actividades como: gestionar el proceso de fabricación y puesta a punto de prototipos para productos electrónicos con la calidad y fiabilidad requeridas y con los costes acordados, interpretación de diagramas esquemáticos, elaboración de planos electrónicos, caracterización de componentes electrónicos, controlar la gestión de residuos eléctricos y electrónicos, elaborar y hacer seguimiento a los planes de mantenimiento, documentar técnicamente los proyectos de desarrollo de productos electrónicos y participar en la elaboración de protocolos de pruebas.
      br
      br
      |El programa virtual Tecnología en Desarrollo de Productos Electrónicos es un programa novedoso que está adaptado para satisfacer las necesidades del sector productivo del país, articulado con la industria 4.0 y las nuevas tecnologías. Por lo tanto, al finalizar su capacitación podrá trabajar en cualquier empresa del sector de la industria electrónica, permitiendo, con su aporte, contribuir al crecimiento tecnológico del país.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p La electrónica y en particular el diseño y desarrollo de tarjetas electrónicas se constituye como la base de la mayoría de los desarrollos tecnológicos en la Industria 4.0. Cualquier dispositivo que posea: una interfaz humano-máquina, módulos de comunicación, unidades de almacenamiento, módulos de control, sensores, acondicionadores de señales o que esté destinado a la transformación de la energía eléctrica, tendrá  por lo menos una tarjeta electrónica sobre la cual están integrados todos los elementos electrónicos. 		
      br
      br
      |La industria electrónica ha crecido exponencialmente tanto en el mercado global como local siendo los servicios de fabricación y ensamble de dispositivos electrónicos los que más aportan en el desarrollo, impulsado básicamente por el internet de las cosas y la transversalidad de la electrónica.  
      br
      br
      |El SENA, a través del programa de formación virtual 
      b Tecnología en desarrollo de productos electrónicos
      |, espera brindarle al sector productivo industrial, la posibilidad de incorporar personal con alta calidad laboral y profesional que contribuya al desarrollo económico, social y tecnológico de su entorno y del país, adaptado a las nuevas tendencias y sistemas de formación, impactando positivamente la productividad, la competitividad, la equidad y el desarrollo a nivel nacional.	
      br
      br
      |Este programa permitirá que sus egresados tengan la capacidad de participar en la consolidación de soluciones pertinentes, acertadas e innovadoras a problemas en las áreas de desarrollo y mantenimiento de productos electrónicos, según las necesidades del sector productivo y su entorno, integrando a su vez conceptos tecnológicos interdisciplinarios. También tendrán la facultad para poder participar de los cambios tecnológicos, mediante el desarrollo de prototipos y la investigación aplicada para satisfacer las necesidades del sector industrial y de la sociedad en general.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a desarrollar 

    .tabla-a.color-acento-botones.mb-5 
      table
        caption Leyenda de la tabla
        thead
          tr
            th(colspan=2).h4 Competencias técnicas o específicas
          tr.text-center
            th Norma sectorial de la competencia laboral (NSCL)
            th Código NSC
            
        tbody.bg-white
          tr
            td Diagnosticar circuitos electrónicos según manuales técnicos y normativa técnica.
            td.text-center 291901033
          tr
            td Diseñar tarjetas de circuito impreso según especificaciones y normativa técnica.
            td.text-center 291901011
          tr
            td Ensamblar tarjetas electrónicas según especificaciones y normativa técnica.
            td.text-center 291901060
          tr
            td Desensamblar residuos de aparatos eléctricos y electrónicos de acuerdo con normativa y procedimientos técnicos.
            td.text-center 291901056
          tr
            td Determinar especificaciones según requerimientos del producto electrónico.
            td.text-center 291901007
          tr
            td Generar prototipo según técnicas y especificaciones de producto.
            td.text-center 220101016
          tr
            td Probar el producto electrónico según protocolo de pruebas y normativa.
            td.text-center 291901013
          tr
            td Configurar el suministro de tarjetas electrónicas según requerimiento y capacidades de producción.
            td.text-center 291901028
          tr
            td Controlar la calidad de los procesos de acuerdo con requerimientos técnicos y normativa.
            td.text-center 220601045
          tr
            td Mantener equipos electro electrónicos según manuales técnicos y normativa.
            td.text-center 291901026
    .tabla-a.color-acento-botones.mb-5 
      table
        thead
          tr
            th(colspan=2).h4 Competencias claves
          tr.text-center
            th Competencia 
            th Código NSC
            
        tbody.bg-white
          tr
            td Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales. 
            td.text-center 240201528
          tr
            td Aplicación de conocimientos de las ciencias naturales de acuerdo con situaciones del contexto productivo y social.
            td.text-center 220201501
          tr
            td Utilizar herramientas informáticas de acuerdo con necesidades de manejo de información.
            td.text-center 220501046
          tr
            td Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
            td.text-center 240201524
          tr
            td Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el marco común europeo de referencia para las lenguas.
            td.text-center 240202501
    .tabla-a.color-acento-botones.mb-5 
      table
        thead
          tr
            th(colspan=2).h4 Competencias transversales
          tr.text-center
            th Competencia 
            th Código NSC
            
        tbody.bg-white
          tr
            td Resultado de Aprendizaje de la Inducción.
            td.text-center 240201530
          tr
            td Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
            td.text-center 230101507
          tr
            td Ejercer derechos fundamentales del trabajo en el marco de la constitución política y los convenios internacionales.
            td.text-center 210201501
          tr
            td Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
            td.text-center 240201526
          tr
            td Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente.
            td.text-center 220601501
          tr
            td Fomentar cultura emprendedora según habilidades y competencias personales.
            td.text-center 240201533
          tr
            td Orientar investigación formativa según referentes técnicos.
            td.text-center 240201064
          

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso
    h6 Nivel de competencias a demostrar en el proceso de ingreso por tipo de certificación
    ul.lista-ul.ms-5
        li 
          i.fas.fa-angle-right
          | Nivel: educación media.
        li 
          i.fas.fa-angle-right
          | Grado: Undécimo.
        li 
          i.fas.fa-angle-right
          | Requiere certificación académica: Sí.
        li 
          i.fas.fa-angle-right
          | Requiere formación para el trabajo y desarrollo humano: No.
        li 
          i.fas.fa-angle-right
          | Requiere experiencia laboral: No.
        li 
          i.fas.fa-angle-right
          | Edad mínima: 16 años.
        li 
          i.fas.fa-angle-right
          | Requisitos adicionales: Equipo de cómputo y acceso a internet garantizado.
        li 
          i.fas.fa-angle-right
          | Restricciones de ingreso: Ninguna. Ley estatutaria No. 1618 del 27 de febrero de 2013.
    h6 Aspectos actitudinales, motivacionales y de interés
    ul.lista-ul.ms-5
        li 
          i.fas.fa-angle-right
          | Gusto por áreas básicas como la física y las matemáticas.
        li 
          i.fas.fa-angle-right
          | Interés por las tecnologías de la información y la comunicación.
        li 
          i.fas.fa-angle-right
          | Gusto por el campo de la electrónica.
        li 
          i.fas.fa-angle-right
          | Interés por trabajar con máquinas, equipos y herramientas.
        li 
          i.fas.fa-angle-right
          | Interés por los avances tecnológicos.
        li 
          i.fas.fa-angle-right
          | Preferencia por actividades que requieren planeación, organización, minuciosidad, rigurosidad y seguimiento de procedimiento.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de egreso
    p El egresado del programa Tecnología en Desarrollo de Productos Electrónicos será competente para realizar el estudio, definición, concepción y desarrollo de tarjetas y productos electrónicos, con capacidad para desarrollar actividades como: gestionar el proceso de fabricación y puesta a punto de prototipos para productos electrónicos con la calidad y fiabilidad requeridas y con los costes acordados, interpretación de diagramas esquemáticos, elaboración de planos electrónicos, caracterización de componentes electrónicos, controlar la gestión de residuos eléctricos y electrónicos, elaborar y hacer seguimiento a los planes de mantenimiento, documentar técnicamente los proyectos de desarrollo de productos electrónicos y participar en la elaboración de protocolos de pruebas. Para ello hará uso de herramientas de diseño asistido por computador y manufactura asistida por computador (CAD/CAM), sistemas de planificación de recursos, además de diversas tecnologías en el desarrollo de prototipos funcionales.
      br
      br
      |Se podrá desempeñar en grandes, medianas y pequeñas empresas dedicadas al diseño, desarrollo y fabricación de productos electrónicos y se ubica principalmente en las áreas funcionales: prototipado, ensayos de calidad, producción, investigación y desarrollo en electrónica, pudiéndose especializar en un área determinada o desarrollar su labor según el tipo y tamaño de la empresa; además tendrá la capacidad emprendedora e innovadora para resolver dificultades analizando el entorno. Se caracterizará por ser honesto, respetuoso y responsable en el cumplimiento de las actividades que realiza y en el manejo y cuidado de los equipos.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia metodológica
    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en el utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
      br
      br
      |Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
      ul.lista-ul
        li 
          i.fas.fa-check
          | El instructor - Tutor
        li 
          i.fas.fa-check
          | El entorno
        li 
          i.fas.fa-check
          | Las TIC
        li 
          i.fas.fa-check
          | El trabajo colaborativo








  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
