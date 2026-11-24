---
layout: default
title: Research
ref: research
permalink: /research/
---

## Research

<div class="affiliation">
  <i class="fa-solid fa-microscope" aria-hidden="true"></i>
  <span>Biophotonics and Biomedical Optics Research Group (GIBIO), <a href="https://www.pucp.edu.pe/" target="_blank">PUCP</a></span>
</div>

<ul class="chips">
  <li>Optical coherence elastography</li>
  <li>Optical coherence tomography</li>
  <li>Ultrasound elastography</li>
  <li>Digital signal processing</li>
  <li>Image processing and reconstruction</li>
  <li>Inverse problems</li>
</ul>

<hr />

### Journal papers

<ul class="entries">
  <li>
    <span class="title">Journal paper on the experimental validation of the Synchronized BM-mode (SBM) protocol</span> <span class="cat">In progress</span>
    <span class="desc">The validation study of the acquisition protocol from my thesis is under way, aimed at a Q1 journal. Authors and title will be listed here once the manuscript is submitted.</span>
    <span class="links"><a href="https://github.com/emftech/OCE_Experimental_Protocols" target="_blank">Experimental code</a></span>
  </li>
</ul>

### Conference papers

<ul class="entries">
  <li>
    <span class="title"><a href="https://ieeexplore.ieee.org/abstract/document/9251504" target="_blank">Feasibility of reverberant shear wave elastography for in vivo assessment of skeletal muscle viscoelasticity</a></span>, 2020 <span class="cat">Ultrasound elastography</span><br />
    <span class="authors"><span class="me">E. Machado</span>, S. E. Romero, G. Flores, et al. <span class="venue">2020 IEEE International Ultrasonics Symposium (IUS), held online.</span></span>
    <details>
      <summary>Summary | <a href="https://ieeexplore.ieee.org/abstract/document/9251504" target="_blank">IEEE Xplore</a> | <a href="https://doi.org/10.1109/IUS46767.2020.9251504" target="_blank">DOI</a> | <a href="https://facultad-ciencias-ingenieria.pucp.edu.pe/2020/10/05/ieee-reconoce-aporte-de-estudiante-al-estudio-de-patologias-neuromusculares-2/" target="_blank">PUCP news</a></summary>
      <p>My first paper, written at 19 as a biomedical engineering undergraduate in the Medical Imaging Laboratory (LIM) at PUCP. We tested whether reverberant shear wave elastography can measure the viscoelasticity of skeletal muscle in vivo: I processed the ultrasound data, built shear-wave speed estimators in MATLAB and fitted rheological models, with results consistent with the literature. It was one of five works selected for the symposium, alongside mostly Ph.D. students, and <a href="https://facultad-ciencias-ingenieria.pucp.edu.pe/2020/10/05/ieee-reconoce-aporte-de-estudiante-al-estudio-de-patologias-neuromusculares-2/" target="_blank">PUCP recognized it</a>. Cited 10 times.</p>
    </details>
  </li>
</ul>

### Abstracts and posters

<ul class="entries">
  <li id="lauw-2026">
    <span class="title">Development of an Acquisition Protocol for Non-Cylindrical Wave Propagation in Wave-Based Optical Coherence Elastography</span>, 2026 <span class="cat">Poster</span><br />
    <span class="authors"><span class="me">E. Machado</span>, A. A. Cifuentes-Cuadros, F. Zvietcovich.</span>
    <span class="venue"><a href="https://sites.google.com/pucp.edu.pe/ieeeuffc-lauw2026/home" target="_blank">IEEE UFFC Latin American Ultrasonics Workshop (LAUW 2026)</a>, PUCP, Lima, Peru, July 14–16, 2026.</span>
    <p class="desc">Wave-based OCE measures how stiff a tissue such as the cornea is by tracking how fast small mechanical waves travel through it. The standard scan, multimeridian MB mode, assumes the wave spreads in circles from its source, which breaks down when a local soft region, as in keratoconus, bends the wavefront. We built a simulation framework that measures this error and proposed Synchronized BM-mode (SBM), which recovers the full 2D wavefield in equivalent time: in simulation it gave higher contrast than MB mode at comparable resolution with a much shorter scan, and it now runs on two OCT systems.</p>
    <span class="links"><a href="{{ '/files/lauw2026-poster.pdf' | relative_url }}" target="_blank"><i class="fa-solid fa-file-pdf" aria-hidden="true"></i> Poster PDF</a> | <a href="https://sites.google.com/pucp.edu.pe/ieeeuffc-lauw2026/home" target="_blank">Workshop website</a> | <a href="https://ieee-uffc.org/event/workshop/ieee-uffc-latin-american-ultrasonics-workshop-2026" target="_blank">IEEE UFFC listing</a></span>
    <div class="gallery">
      <figure><img src="{{ '/assets/img/lauw2026/poster.jpg' | relative_url }}" alt="Estefano next to the LAUW 2026 poster" loading="lazy"></figure>
      <figure><img src="{{ '/assets/img/lauw2026/presenting.jpg' | relative_url }}" alt="Estefano explaining the poster to a graduate student at LAUW 2026" loading="lazy"></figure>
    </div>
  </li>
</ul>

### Thesis

<ul class="entries">
  <li>
    <span class="title"><a href="{{ '/files/machado-2026-thesis.pdf' | relative_url }}" target="_blank">Development of an Acquisition Protocol for Non-Cylindrical Wave Propagation in Wave-Based Optical Coherence Elastography</a></span>, 2026 <span class="cat">B.Sc. thesis</span><br />
    <span class="authors"><span class="me">E. Machado</span>. Advisor: Prof. Fernando Zvietcovich. <span class="venue">Pontificia Universidad Católica del Perú.</span></span>
    <details>
      <summary>Summary | <a href="{{ '/files/machado-2026-thesis.pdf' | relative_url }}" target="_blank">Thesis PDF</a> | <a href="https://github.com/emftech/OCE_AcquisitionProtocols_Simulator/blob/main/docs/Machado_2026_Thesis_Acquisition_Protocol_NonCylindrical_WaveBased_OCE.pdf" target="_blank">Full-resolution copy on GitHub</a> | <a href="https://github.com/emftech/OCE_AcquisitionProtocols_Simulator" target="_blank">Simulator</a> | <a href="https://github.com/emftech/OCE_Experimental_Protocols" target="_blank">Experimental code</a></summary>
      <p>Wave-based OCE estimates tissue stiffness from the speed of mechanical waves, but most scan protocols assume waves spread cylindrically from the source. The thesis proposes Synchronized BM-mode (SBM), a raster BM scan locked to a harmonic excitation so that stacked frames sample each pixel in equivalent time, with per-pixel phase compensation and 2D phase-gradient speed estimation. In k-Wave simulations with stiff inclusions and simulated eye motion, SBM kept a higher contrast-to-noise ratio than multimeridian MB mode and reached comparable spatial resolution with a much shorter acquisition. Both protocols were implemented on swept-source (200 kHz) and spectral-domain (50 kHz) OCT systems.</p>
    </details>
  </li>
</ul>
