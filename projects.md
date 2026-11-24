---
layout: default
title: Projects
ref: projects
permalink: /projects/
---

## Projects

Selected engineering projects from my undergraduate studies and research. Each one lists the problem, what I built, and the tools I used.

### Research projects

<ul class="entries">
  <li>
    <span class="title"><a href="https://github.com/emftech/OCE_AcquisitionProtocols_Simulator" target="_blank">OCE acquisition protocol simulator</a></span>, 2026 <span class="cat">MATLAB, k-Wave</span>
    <span class="desc">A simulation framework that asks how well a stiffness map can be recovered for a given OCT scan pattern and timing. It simulates wave propagation in homogeneous and inclusion-bearing media, samples the wavefield where and when the OCT beam actually is (on a 200 kHz A-line clock, optionally with eye saccades), recovers the wavefield for MB and SBM protocols, estimates phase speed with 1D, 2D and TV-regularized phase-gradient methods, and scores accuracy, precision and CNR.</span>
    <span class="links"><a href="https://github.com/emftech/OCE_AcquisitionProtocols_Simulator" target="_blank">Code</a> | <a href="{{ '/files/machado-2026-thesis.pdf' | relative_url }}" target="_blank">Thesis</a></span>
    <figure class="project-fig"><img src="{{ '/assets/img/projects/sbm-framework.png' | relative_url }}" alt="Diagram of the Synchronized BM-mode protocol: each frame samples the harmonic wave at a later phase, and stacking frames recovers the wavefield in equivalent time" loading="lazy"></figure>
  </li>
  <li>
    <span class="title"><a href="https://github.com/emftech/OCE_Experimental_Protocols" target="_blank">Experimental OCE protocols on swept-source and spectral-domain OCT</a></span>, 2026 <span class="cat">MATLAB, LabVIEW</span>
    <span class="desc">Hardware implementation of the MB and SBM protocols: a galvanometer scan-pattern and trigger generator integrated with LabVIEW, NI-DAQ analog outputs and an AlazarTech digitizer on GIBIO's 1300 nm swept-source OCT, ported to a 1310 nm spectral-domain system, plus the processing chain from raw spectra to wavefield videos and elastograms.</span>
    <span class="links"><a href="https://github.com/emftech/OCE_Experimental_Protocols" target="_blank">Code</a></span>
    <figure class="project-fig"><img src="{{ '/assets/img/projects/mb-wavefield.png' | relative_url }}" alt="Experimental en-face particle-velocity maps of a 3509 Hz wave measured with 8 meridians, without and with directional filtering" loading="lazy"></figure>
  </li>
  <li>
    <span class="title"><a href="https://ieeexplore.ieee.org/abstract/document/9251504" target="_blank">Reverberant shear wave elastography of skeletal muscle</a></span>, 2020–2022 <span class="cat">MATLAB</span>
    <span class="desc">Medical Imaging Laboratory (LIM), PUCP. A feasibility study, which I led as first author, of measuring muscle viscoelasticity in vivo from a reverberant shear-wave field: ultrasound data processing, shear-wave speed estimators and fitting of rheological models, with results consistent with the literature. Presented at IEEE IUS 2020.</span>
    <span class="links"><a href="https://ieeexplore.ieee.org/abstract/document/9251504" target="_blank">Paper</a> | <a href="https://facultad-ciencias-ingenieria.pucp.edu.pe/2020/10/05/ieee-reconoce-aporte-de-estudiante-al-estudio-de-patologias-neuromusculares-2/" target="_blank">PUCP news</a></span>
  </li>
</ul>

### Computer vision and AI

<ul class="entries">
  <li>
    <span class="title"><a href="https://drive.google.com/drive/folders/1MffLEybS2iC9bgiQa8MO-nob0zb5-mXR?usp=sharing" target="_blank">Vision-guided robotic obstetric ultrasound</a></span>, 2024 <span class="cat">Python, YOLO, OpenCV, ROS</span>
    <span class="desc">Electronic Project 1 (IEE219), PUCP. I led the computer vision module in a team of five that automates a force-monitored ultrasound sweep of a pregnant-abdomen phantom with a UR5 robotic arm. I trained a YOLOv11n detector on a custom-labeled dataset to find the scanning region (confidence about 0.85, 45–75 ms per frame), calibrated the camera with Zhang's method (0.03 px reprojection error), and fused pinhole back-projection with LiDAR depth to turn detections into 3D targets for the arm in ROS and Gazebo. I also benchmarked monocular depth estimation with Depth-Anything-V2.</span>
    <span class="links"><a href="https://drive.google.com/drive/folders/1MffLEybS2iC9bgiQa8MO-nob0zb5-mXR?usp=sharing" target="_blank">Project files</a></span>
  </li>
  <li>
    <span class="title"><a href="https://drive.google.com/drive/folders/12xs0UrMlJ7mMJWJeZ9GL1aKQvfDJlHDJ" target="_blank">IrisDetect: diabetes screening from iris texture</a></span>, 2022 <span class="cat">MATLAB, Python</span>
    <span class="desc">Founder and team lead of Deep Bioshock. A screening system that segments the iris, encodes it with Log-Gabor filters, extracts texture features and classifies them with machine learning models to flag diabetes-related changes. It won 1st place at the Hackathon Smart Solutions #13, AI for the SDGs (IEEE Peru Section and UNMSM, IEEE INTERCON 2022).</span>
    <span class="links"><a href="https://drive.google.com/drive/folders/12xs0UrMlJ7mMJWJeZ9GL1aKQvfDJlHDJ" target="_blank">Project files</a> | <a href="https://drive.google.com/file/d/10VnWwCZKjpQsarAvEQh2tiBbVk7BxcZg/view?usp=sharing" target="_blank">Log-Gabor encoding</a> | <a href="https://drive.google.com/file/d/101z6tD9UT3j7f3-QZPw5jE4F63uV4WHx/view?usp=sharing" target="_blank">Texture features</a> | <a href="https://drive.google.com/file/d/1iL0uop5CRHmjKD08nPQ9LYDuhpT369vO/view?usp=share_link" target="_blank">Award</a></span>
  </li>
</ul>

### Teaching material

<ul class="entries">
  <li>
    <span class="title"><a href="https://www.youtube.com/playlist?list=PL7bL4LFhkgGXAJhe_PzeOg4TWkMV_w-6p" target="_blank">Signals and Systems in MATLAB</a></span>, 2021–present <span class="cat">MATLAB</span>
    <span class="desc">A video course in Spanish, made for the Association of Electronics Engineering Students (AEE) at PUCP, that goes from LTI systems to image processing. More lectures and exam walkthroughs are on the <a href="{{ '/teaching/' | relative_url }}">Teaching</a> page.</span>
  </li>
</ul>
