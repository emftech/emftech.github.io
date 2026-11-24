---
layout: default
title: Investigación
ref: research
permalink: /es/research/
---

## Investigación

<div class="affiliation">
  <i class="fa-solid fa-microscope" aria-hidden="true"></i>
  <span>Grupo de Investigación en Biofotónica y Óptica Biomédica (GIBIO), <a href="https://www.pucp.edu.pe/" target="_blank">PUCP</a></span>
</div>

<ul class="chips">
  <li>Elastografía por coherencia óptica</li>
  <li>Tomografía de coherencia óptica</li>
  <li>Elastografía por ultrasonido</li>
  <li>Procesamiento digital de señales</li>
  <li>Procesamiento y reconstrucción de imágenes</li>
  <li>Problemas inversos</li>
</ul>

<hr />

### Artículos en revistas

<ul class="entries">
  <li>
    <span class="title">Artículo sobre la validación experimental del protocolo de modo BM sincronizado (SBM)</span> <span class="cat">En curso</span>
    <span class="desc">El estudio de validación del protocolo de adquisición de mi tesis está en marcha, con miras a una revista Q1. Los autores y el título se publicarán aquí cuando el manuscrito sea enviado.</span>
    <span class="links"><a href="https://github.com/emftech/OCE_Experimental_Protocols" target="_blank">Código experimental</a></span>
  </li>
</ul>

### Artículos en congresos

<ul class="entries">
  <li>
    <span class="title"><a href="https://ieeexplore.ieee.org/abstract/document/9251504" target="_blank">Feasibility of reverberant shear wave elastography for in vivo assessment of skeletal muscle viscoelasticity</a></span>, 2020 <span class="cat">Elastografía por ultrasonido</span><br />
    <span class="authors"><span class="me">E. Machado</span>, S. E. Romero, G. Flores, et al. <span class="venue">2020 IEEE International Ultrasonics Symposium (IUS), en línea.</span></span>
    <details>
      <summary>Resumen | <a href="https://ieeexplore.ieee.org/abstract/document/9251504" target="_blank">IEEE Xplore</a> | <a href="https://doi.org/10.1109/IUS46767.2020.9251504" target="_blank">DOI</a> | <a href="https://facultad-ciencias-ingenieria.pucp.edu.pe/2020/10/05/ieee-reconoce-aporte-de-estudiante-al-estudio-de-patologias-neuromusculares-2/" target="_blank">Nota PUCP</a></summary>
      <p>Mi primer artículo, escrito a los 19 años como estudiante de Ingeniería Biomédica en el Laboratorio de Imágenes Médicas (LIM) de la PUCP. Evaluamos si la elastografía reverberante de ondas de corte puede medir la viscoelasticidad del músculo esquelético in vivo: procesé los datos de ultrasonido, construí estimadores de velocidad de onda de corte en MATLAB y ajusté modelos reológicos, con resultados consistentes con la literatura. Fue uno de cinco trabajos seleccionados para el simposio, junto a estudiantes de doctorado en su mayoría, y la <a href="https://facultad-ciencias-ingenieria.pucp.edu.pe/2020/10/05/ieee-reconoce-aporte-de-estudiante-al-estudio-de-patologias-neuromusculares-2/" target="_blank">PUCP lo reconoció</a>. 10 citas.</p>
    </details>
  </li>
</ul>

### Resúmenes y pósteres

<ul class="entries">
  <li id="lauw-2026">
    <span class="title">Development of an Acquisition Protocol for Non-Cylindrical Wave Propagation in Wave-Based Optical Coherence Elastography</span>, 2026 <span class="cat">Póster</span><br />
    <span class="authors"><span class="me">E. Machado</span>, A. A. Cifuentes-Cuadros, F. Zvietcovich.</span>
    <span class="venue"><a href="https://sites.google.com/pucp.edu.pe/ieeeuffc-lauw2026/home" target="_blank">IEEE UFFC Latin American Ultrasonics Workshop (LAUW 2026)</a>, PUCP, Lima, Perú, 14 al 16 de julio de 2026.</span>
    <p class="desc">La OCE basada en ondas mide qué tan rígido es un tejido, como la córnea, a partir de la velocidad con que viajan por él pequeñas ondas mecánicas. El barrido estándar, el modo MB multimeridiano, supone que la onda se propaga en círculos desde la fuente, lo que falla cuando una zona blanda local, como en el queratocono, deforma el frente de onda. Construimos un marco de simulación que mide ese error y propusimos el modo BM sincronizado (SBM), que recupera el campo de onda 2D completo en tiempo equivalente: en simulación logró mayor contraste que el modo MB con resolución comparable y un barrido mucho más corto, y ya funciona en dos sistemas OCT.</p>
    <span class="links"><a href="{{ '/files/lauw2026-poster.pdf' | relative_url }}" target="_blank"><i class="fa-solid fa-file-pdf" aria-hidden="true"></i> Póster en PDF</a> | <a href="https://sites.google.com/pucp.edu.pe/ieeeuffc-lauw2026/home" target="_blank">Web del taller</a> | <a href="https://ieee-uffc.org/event/workshop/ieee-uffc-latin-american-ultrasonics-workshop-2026" target="_blank">Ficha en IEEE UFFC</a></span>
    <div class="gallery">
      <figure><img src="{{ '/assets/img/lauw2026/poster.jpg' | relative_url }}" alt="Estefano junto al póster del LAUW 2026" loading="lazy"></figure>
      <figure><img src="{{ '/assets/img/lauw2026/presenting.jpg' | relative_url }}" alt="Estefano explica el póster a un estudiante de posgrado en el LAUW 2026" loading="lazy"></figure>
    </div>
  </li>
</ul>

### Tesis

<ul class="entries">
  <li>
    <span class="title"><a href="{{ '/files/machado-2026-thesis.pdf' | relative_url }}" target="_blank">Development of an Acquisition Protocol for Non-Cylindrical Wave Propagation in Wave-Based Optical Coherence Elastography</a></span>, 2026 <span class="cat">Tesis de pregrado</span><br />
    <span class="authors"><span class="me">E. Machado</span>. Asesor: Prof. Fernando Zvietcovich. <span class="venue">Pontificia Universidad Católica del Perú.</span></span>
    <details>
      <summary>Resumen | <a href="{{ '/files/machado-2026-thesis.pdf' | relative_url }}" target="_blank">Tesis en PDF</a> | <a href="https://github.com/emftech/OCE_AcquisitionProtocols_Simulator/blob/main/docs/Machado_2026_Thesis_Acquisition_Protocol_NonCylindrical_WaveBased_OCE.pdf" target="_blank">Copia en alta resolución en GitHub</a> | <a href="https://github.com/emftech/OCE_AcquisitionProtocols_Simulator" target="_blank">Simulador</a> | <a href="https://github.com/emftech/OCE_Experimental_Protocols" target="_blank">Código experimental</a></summary>
      <p>La OCE basada en ondas estima la rigidez del tejido a partir de la velocidad de ondas mecánicas, pero la mayoría de protocolos de barrido supone que las ondas se propagan de forma cilíndrica desde la fuente. La tesis propone el modo BM sincronizado (SBM), un barrido BM ráster sincronizado con una excitación armónica, de modo que los cuadros apilados muestrean cada píxel en tiempo equivalente, con compensación de fase por píxel y estimación de velocidad por gradiente de fase 2D. En simulaciones con k-Wave, con inclusiones rígidas y movimiento ocular simulado, el SBM mantuvo una relación contraste-ruido mayor que el modo MB multimeridiano y alcanzó una resolución espacial comparable con una adquisición mucho más corta. Ambos protocolos se implementaron en sistemas OCT de fuente barrida (200 kHz) y de dominio espectral (50 kHz).</p>
    </details>
  </li>
</ul>
