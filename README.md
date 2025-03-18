# <span style="color: turquoise; font-size: 2rem; text-transform: uppercase;">Proyectos</span>

<style>
  details {
    margin-top: 1rem;
  }
  summary.section {
    font-size: 2rem; /* Tamaño de fuente de los títulos */
    font-weight: bold;
  }
  summary.project {
    font-size: 1.5rem; /* Tamaño de fuente de los proyectos */
    font-weight: bold;
    list-style: none; /* Ocultar el triángulo invertido */
  }
  summary.project::-webkit-details-marker {
    display: none; /* Ocultar el triángulo invertido en navegadores WebKit */
  }
  details p, details h2 {
    font-size: 1.5rem; /* Tamaño de fuente del contenido */
    margin-left: 40px; /* Margen izquierdo para los proyectos */
  }
  figure {
    margin-left: 20px; /* Margen izquierdo para las figuras */
    height: auto; /* Mantener la proporción de las imágenes */
  }
  figure img {
    max-width: 80%; /* Tamaño máximo de las imágenes */
    height: auto; /* Mantener la proporción de las imágenes */
  }
  figcaption {
    text-align: center; /* Centrar el texto de los títulos */
    font-style: italic; /* Estilo itálico para los títulos */
  }
</style>

<details>
  <summary class="section">Hidrología superficial</summary>
  
  <details>
    <summary class="project">1. Análisis de Precipitaciones</summary>

Descargué datos de precipitación del Servicio Meteorológico Nacional de una estación de la subcuenca de Zapotitlán, Guerrero. Procesé los datos en Python. Hice una serie mensual y anual. También obtuve la precipitación promedio mensual.

**Herramientas:** Python

**Resultado:**

<figure>
  <img src="images/Hidrologia_superficial/precmensual.jpeg" alt="Proyecto 1">
  <figcaption>Precipitación mensual</figcaption>
  <img src="images/Hidrologia_superficial/precanual.jpeg" alt="Proyecto 2">
  <figcaption>Precipitación anual</figcaption>
  <img src="images/Hidrologia_superficial/promediomensual.jpeg" alt="Proyecto 3">
  <figcaption>Precipitación promedio mensual</figcaption>
</figure>
  </details>


  <details>
    <summary class="project">2. Simulación de infiltración</summary>

Trabajé con datos de intensidad de lluvia de una estación del Observatorio Hidrológico de Instituto de Ingeniería de la UNAM. Apliqué el método de tasa de infiltración constante para estimar la pérdida de agua por infiltración ante una tormenta severa, asumiendo que el suelo tiene siempre la misma capacidad de infiltración. Convertí las tasas de precipitación y de infiltración a láminas y grafiqué la Curva Masa.

**Herramientas:** Python

**Resultado:**

<figure>
  <img src="images/Hidrologia_superficial/curvamasa.jpeg" alt="Proyecto 4">
  <figcaption>Curva Masa</figcaption>
</figure>
  </details>

  <details>
    <summary class="project">3. Análisis de caudal</summary>

**Herramientas:** Python

**Resultado:**

<figure>
  <img src="images/Hidrologia_superficial/caudaldiaria.jpeg" alt="Proyecto 5">
  <figcaption>Caudal a escala diaria</figcaption>
  <img src="images/Hidrologia_superficial/caudalmensual.jpeg" alt="Proyecto 6">
  <figcaption>Caudal a escala mensual</figcaption>
</figure>
  </details>

  
</details>

<details>
  <summary class="section">Hidrología subterránea</summary>
  
  <details>
    <summary class="project">1. Red de flujo</summary>

Hice la red de flujo de agua subterránea de la zona de Piedras Negras, Coahuila. Primero obtuve curvas de elevación de nivel estático a partir de una interpolación por el método de kriging, empleando los softwares SGEMS, SAGA GIS y QGIS. Después, elaboré un mapa de la piezometría y la geología de la zona; con base en este mapa dibujé las líneas de flujo.

**Herramientas:** SGeMS, SAGA GIS y QGIS.

**Resultado:**

<figure>
  <img src="images/Hidrologia_subterranea/mapa_base (1).png" alt="Proyecto 7">
  <figcaption>Red de flujo</figcaption>
</figure>
  </details>

  
</details>

<details>
  <summary class="section">SIG y Percepción Remota</summary>
  
  <details>
    <summary class="project">1.	Calibración radiométrica y corrección atmosféricas</summary>

Trabajé una imagen Landsat-7 en ENVI. Utilicé las herramientas radiometric calibration y flaash atmospheric correction. Utilicé una combinación RGB (4, 3, 2); se observa la vegetación en tonos rojos y un cuerpo de agua en azul.

**Herramientas:** ENVI

**Resultado:**

<figure>
  <img src="images/SIGPR/Correcion.jpeg" alt="Proyecto 8">
  <figcaption>Red de flujo</figcaption>
</figure>
  </details>

  <details>
    <summary class="project">2. 2.	Clasificación supervisada y no supervisada</summary>

Realicé una clasificación supervisada y no supervisada de una escena Landsat 8 del área de la Bahía de San Francisco. La escena pertenece al 3 de marzo de 2015. Realicé esta clasificación en ENVI. Hice los dos tipos de clasificación utilizando la herramienta Classification Workflow. También, obtuve las estadísticas de cada clasificación y calculé el área en hectáreas de cada cobertura.
    
**Herramientas:** ENVI

**Resultado:**

<figure>
  <img src="images/SIGPR/clasificacionnosup.jpeg" alt="Proyecto 9">
  <figcaption>Clasificación no supervisada</figcaption>
  <img src="images/SIGPR/clasificacionsup.jpeg" alt="Proyecto 10">
  <figcaption>Clasificación supervisada</figcaption>
</figure>
  </details>

  <details>
    <summary class="project">3. 3.	Digitalización de geomorfología</summary>

Digitalicé, manualmente, la geomorfología de la zona fronteriza entre Querétaro e Hidalgo con base en el mapa altimétrico de la zona.

**Herramientas:** QGIS

**Resultado:**

<figure>
  <img src="images/SIGPR/alt.jpeg" alt="Proyecto 11">
  <figcaption>Mapa altimétrico</figcaption>
  <img src="images/SIGPR/dig.jpeg" alt="Proyecto 12">
  <figcaption>Mapa geomorfológico</figcaption>
</figure>
  </details>

  
</details>
