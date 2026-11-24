---
layout: default
title: Proyectos
ref: projects
permalink: /es/projects/
---

## Proyectos

Proyectos de ingeniería seleccionados de mi pregrado y mi investigación. Cada uno indica el problema, lo que construí y las herramientas que usé.

### Proyectos de investigación

<ul class="entries">
  <li>
    <span class="title"><a href="https://github.com/emftech/OCE_AcquisitionProtocols_Simulator" target="_blank">Simulador de protocolos de adquisición para OCE</a></span>, 2026 <span class="cat">MATLAB, k-Wave</span>
    <span class="desc">Un marco de simulación que responde qué tan bien se puede recuperar un mapa de rigidez con un patrón y una temporización de barrido OCT dados. Simula la propagación de ondas en medios homogéneos y con inclusiones, muestrea el campo de onda donde y cuando realmente está el haz OCT (con un reloj de líneas A de 200 kHz y, opcionalmente, movimientos sacádicos), recupera el campo de onda con los protocolos MB y SBM, estima la velocidad de fase con métodos de gradiente de fase 1D, 2D y regularizados por TV, y evalúa exactitud, precisión y CNR.</span>
    <span class="links"><a href="https://github.com/emftech/OCE_AcquisitionProtocols_Simulator" target="_blank">Código</a> | <a href="{{ '/files/machado-2026-thesis.pdf' | relative_url }}" target="_blank">Tesis</a></span>
    <figure class="project-fig"><img src="{{ '/assets/img/projects/sbm-framework.png' | relative_url }}" alt="Diagrama del protocolo de modo BM sincronizado: cada cuadro muestrea la onda armónica en una fase posterior y al apilarlos se recupera el campo de onda en tiempo equivalente" loading="lazy"></figure>
  </li>
  <li>
    <span class="title"><a href="https://github.com/emftech/OCE_Experimental_Protocols" target="_blank">Protocolos experimentales de OCE en OCT de fuente barrida y de dominio espectral</a></span>, 2026 <span class="cat">MATLAB, LabVIEW</span>
    <span class="desc">Implementación en hardware de los protocolos MB y SBM: un generador de patrones de barrido de galvanómetros y de disparo integrado con LabVIEW, salidas analógicas NI-DAQ y un digitalizador AlazarTech en el OCT de fuente barrida de 1300 nm del GIBIO, portado a un sistema de dominio espectral de 1310 nm, y la cadena de procesamiento desde los espectros crudos hasta videos del campo de onda y elastogramas.</span>
    <span class="links"><a href="https://github.com/emftech/OCE_Experimental_Protocols" target="_blank">Código</a></span>
    <figure class="project-fig"><img src="{{ '/assets/img/projects/mb-wavefield.png' | relative_url }}" alt="Mapas experimentales en face de velocidad de partícula de una onda de 3509 Hz medida con 8 meridianos, sin y con filtrado direccional" loading="lazy"></figure>
  </li>
  <li>
    <span class="title"><a href="https://ieeexplore.ieee.org/abstract/document/9251504" target="_blank">Elastografía reverberante de ondas de corte en músculo esquelético</a></span>, 2020–2022 <span class="cat">MATLAB</span>
    <span class="desc">Laboratorio de Imágenes Médicas (LIM), PUCP. Un estudio de factibilidad, que lideré como primer autor, para medir la viscoelasticidad del músculo in vivo a partir de un campo reverberante de ondas de corte: procesamiento de datos de ultrasonido, estimadores de velocidad de onda de corte y ajuste de modelos reológicos, con resultados consistentes con la literatura. Presentado en el IEEE IUS 2020.</span>
    <span class="links"><a href="https://ieeexplore.ieee.org/abstract/document/9251504" target="_blank">Artículo</a> | <a href="https://facultad-ciencias-ingenieria.pucp.edu.pe/2020/10/05/ieee-reconoce-aporte-de-estudiante-al-estudio-de-patologias-neuromusculares-2/" target="_blank">Nota PUCP</a></span>
  </li>
</ul>

### Visión por computadora e IA

<ul class="entries">
  <li>
    <span class="title"><a href="https://drive.google.com/drive/folders/1MffLEybS2iC9bgiQa8MO-nob0zb5-mXR?usp=sharing" target="_blank">Ecografía obstétrica robótica guiada por visión</a></span>, 2024 <span class="cat">Python, YOLO, OpenCV, ROS</span>
    <span class="desc">Proyecto Electrónico 1 (IEE219), PUCP. Lideré el módulo de visión por computadora en un equipo de cinco que automatiza, con un brazo robótico UR5, un barrido ecográfico con control de fuerza sobre un fantoma de abdomen gestante. Entrené un detector YOLOv11n con un conjunto de datos etiquetado por nosotros para ubicar la región de barrido (confianza cercana a 0.85, 45–75 ms por cuadro), calibré la cámara con el método de Zhang (error de reproyección de 0.03 px) y fusioné la retroproyección del modelo pinhole con la profundidad de un LiDAR para convertir las detecciones en objetivos 3D para el brazo en ROS y Gazebo. También comparé la estimación de profundidad monocular con Depth-Anything-V2.</span>
    <span class="links"><a href="https://drive.google.com/drive/folders/1MffLEybS2iC9bgiQa8MO-nob0zb5-mXR?usp=sharing" target="_blank">Archivos del proyecto</a></span>
  </li>
  <li>
    <span class="title"><a href="https://drive.google.com/drive/folders/12xs0UrMlJ7mMJWJeZ9GL1aKQvfDJlHDJ" target="_blank">IrisDetect: tamizaje de diabetes a partir de la textura del iris</a></span>, 2022 <span class="cat">MATLAB, Python</span>
    <span class="desc">Fundador y líder del equipo Deep Bioshock. Un sistema de tamizaje que segmenta el iris, lo codifica con filtros Log-Gabor, extrae características de textura y las clasifica con modelos de machine learning para detectar cambios asociados a la diabetes. Obtuvo el 1.er puesto en el Hackathon Smart Solutions #13, IA para los ODS (IEEE Sección Perú y UNMSM, IEEE INTERCON 2022).</span>
    <span class="links"><a href="https://drive.google.com/drive/folders/12xs0UrMlJ7mMJWJeZ9GL1aKQvfDJlHDJ" target="_blank">Archivos del proyecto</a> | <a href="https://drive.google.com/file/d/10VnWwCZKjpQsarAvEQh2tiBbVk7BxcZg/view?usp=sharing" target="_blank">Codificación Log-Gabor</a> | <a href="https://drive.google.com/file/d/101z6tD9UT3j7f3-QZPw5jE4F63uV4WHx/view?usp=sharing" target="_blank">Características de textura</a> | <a href="https://drive.google.com/file/d/1iL0uop5CRHmjKD08nPQ9LYDuhpT369vO/view?usp=share_link" target="_blank">Premio</a></span>
  </li>
</ul>

### Material docente

<ul class="entries">
  <li>
    <span class="title"><a href="https://www.youtube.com/playlist?list=PL7bL4LFhkgGXAJhe_PzeOg4TWkMV_w-6p" target="_blank">Curso de Señales y Sistemas en MATLAB</a></span>, 2021–presente <span class="cat">MATLAB</span>
    <span class="desc">Un curso en video, creado para la Asociación de Estudiantes de Ingeniería Electrónica (AEE) de la PUCP, que va desde los sistemas LTI hasta el procesamiento de imágenes. Hay más clases y resoluciones de exámenes en la página de <a href="{{ '/es/teaching/' | relative_url }}">Docencia</a>.</span>
  </li>
</ul>
