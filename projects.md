---
layout: default
title: Projects
permalink: /projects/
---

## Projects

Selected engineering projects from my undergraduate studies and research. Each one lists the problem, what I built, and the tools I used.

<p class="todo-block"><strong>Placeholder:</strong> the two research projects below come from your public GitHub repos. I still need 2 to 4 course or personal projects: name, year, context, 2 to 3 sentences, tools, and a link or image.</p>

### Research projects

<ul class="entries">
  <li>
    <span class="title"><a href="https://github.com/emftech/OCE_AcquisitionProtocols_Simulator" target="_blank">OCE acquisition protocol simulator</a></span>, 2026 <span class="cat">MATLAB · k-Wave</span>
    <span class="desc">A simulation framework that asks how well a stiffness map can be recovered for a given OCT scan pattern and timing. It simulates wave propagation in homogeneous and inclusion-bearing media, samples the wavefield where and when the OCT beam actually is (on a 200 kHz A-line clock, optionally with eye saccades), recovers the wavefield for MB and SBM protocols, estimates phase speed with 1D, 2D and TV-regularized phase-gradient methods, and scores accuracy, precision and CNR.</span>
    <span class="links"><a href="https://github.com/emftech/OCE_AcquisitionProtocols_Simulator" target="_blank">Code</a> | <a href="https://github.com/emftech/OCE_AcquisitionProtocols_Simulator/blob/main/docs/Machado_2026_Thesis_Acquisition_Protocol_NonCylindrical_WaveBased_OCE.pdf" target="_blank">Thesis</a></span>
    <figure class="project-fig"><img src="{{ '/assets/img/projects/sbm-framework.png' | relative_url }}" alt="Diagram of the Synchronized BM-mode protocol: each frame samples the harmonic wave at a later phase, and stacking frames recovers the wavefield in equivalent time" loading="lazy"></figure>
  </li>
  <li>
    <span class="title"><a href="https://github.com/emftech/OCE_Experimental_Protocols" target="_blank">Experimental OCE protocols on swept-source and spectral-domain OCT</a></span>, 2026 <span class="cat">MATLAB · LabVIEW</span>
    <span class="desc">Hardware implementation of the MB and SBM protocols: a galvanometer scan-pattern and trigger generator integrated with LabVIEW, NI-DAQ analog outputs and an AlazarTech digitizer on GIBIO's 1300 nm swept-source OCT, ported to a 1310 nm spectral-domain system, plus the processing chain from raw spectra to wavefield videos and elastograms.</span>
    <span class="links"><a href="https://github.com/emftech/OCE_Experimental_Protocols" target="_blank">Code</a></span>
    <figure class="project-fig"><img src="{{ '/assets/img/projects/mb-wavefield.png' | relative_url }}" alt="Experimental en-face particle-velocity maps of a 3509 Hz wave measured with 8 meridians, without and with directional filtering" loading="lazy"></figure>
  </li>
</ul>

### Signal and image processing

<ul class="entries">
  <li>
    <span class="title">[Project name]</span>, [Year] <span class="cat">DSP</span>
    <span class="desc">[Course or context. Problem, approach and result in two sentences.]</span>
    <span class="links"><a href="#">Code</a> | <a href="#">Report</a></span>
  </li>
  <li>
    <span class="title">[Project name]</span>, [Year] <span class="cat">Image processing</span>
    <span class="desc">[Course or context. Problem, approach and result in two sentences.]</span>
    <span class="links"><a href="#">Code</a> | <a href="#">Demo</a></span>
  </li>
</ul>

### Electronics and data

<ul class="entries">
  <li>
    <span class="title">[Project name]</span>, [Year] <span class="cat">Electronics</span>
    <span class="desc">[Hardware, embedded or instrumentation project.]</span>
    <span class="links"><a href="#">Report</a></span>
  </li>
  <li>
    <span class="title">[Project name]</span>, [Year] <span class="cat">Data science</span>
    <span class="desc">[Modelling, machine learning or data analysis project.]</span>
    <span class="links"><a href="#">Notebook</a></span>
  </li>
</ul>
