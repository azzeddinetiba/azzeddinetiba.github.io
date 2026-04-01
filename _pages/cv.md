---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **PhD in Applied Mathematics / Scientific Machine Learning**, CNAM (Conservatoire National des Arts et Métiers), Paris, 2021–2024
  * *Machine learning strategies for accelerating numerical simulations of fluid-structure interaction*
  * Supervised by Pr. I. Mortazavi, Pr. F. De Vuyst, T. Dairay, J-P. Berro Ramirez
  * HAL Id: [tel-05269807](https://theses.hal.science/tel-05269807)
* **Summer School – Scientific Machine Learning**, CEMRACS 2023, CIRM, Marseille, July 2023
* **Mechanical Engineering Degree**, ENSAM (École Nationale Supérieure d'Arts et Métiers), Paris, 2017–2021
  * Silver Medal – Rank: 83/1180

Work Experience
======
* **Computational R&D Engineer** — Michelin, Clermont-Ferrand (Dec 2024 – Present)
  * Part of a team developing and modernizing a large-scale industrial finite element framework.
   <!-- designed for massively parallel HPC environments
  * Led the development of a coupling interface between the parallel solver and ML-based external packages, ensuring MPI scalability across the integration layer (mpi4py)
  * Developed advanced tyre simulation features with complex boundary conditions handling
  * Supervised an internship on fluid-structure interaction simulations -->

* **PhD Student — Research Engineer** — M2N, CNAM / Michelin / Altair, Paris (Nov 2021 – Oct 2024)
  * Machine Learning-based Reduced Order Models (ROMs) for fluid-structure interaction (FSI)
  * Studied and extended data-driven system identification methods
  * Developed new techniques to couple ROMs and classical methods for FSI simulations
  * Developed ML-based methods to accelerate convergence of FSI coupling algorithms
  * Contributed to open-source scientific software and maintained in-house ROM packages
  * Published 2 journal articles and multiple international conference communications

* **Visiting PhD Student** — Esteco (previously Optimad), Turin (Feb 2024 – Mar 2024)
  * Explored stability properties of data-driven reduced order models

* **Substitute Teacher** — CNAM, Paris (Sep 2022 – Jan 2024)
  * Taught practical work on Numerical Methods, Fluid Mechanics and Functional Analysis

* **Simulation Research Engineer (Master's Thesis)** — Dassault Systèmes, Vélizy-Villacoublay (Mar 2021 – Aug 2021)
  * Data-Driven Computational Mechanics (DDCM)
  * Studied numerical convergence and extension to non-elastic and multiscale problems
  * Extended the approach using manifold learning and noisy optimization techniques
  * Developed in-house code and its coupling with a finite element solver

* **Simulation Software QA Intern** — Coventor Inc. (Lam Research), Villebon-sur-Yvette (Jun 2020 – Aug 2020)
  * Wrote tests for meshing features of MEMS+, involving numerical analysis and electromechanical modeling

Technical Skills
======
* **Programming**: Python, C++, C, Matlab
* **Scientific Computing**: PETSc, KratosMultiphysics, FEniCS, scikit-fem, NumPy, PyTorch, scikit-learn, PyVista, Paraview
* **Tools**: Git, Linux, LaTeX
* **Scientific Expertise**: Linear Algebra, Dynamical Systems, Nonlinear Solvers, Computational Mechanics, Finite Element Method, Multiphysics Coupling, Reduced-Order Modeling, Manifold Learning

Languages
======
* **English** (TOEIC: 985/990)
* **French**
* **Arabic**

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Gallery
======
* **PhD Thesis — Video Abstract**: An illustrative summary of the main contributions of my PhD thesis on ML-accelerated fluid-structure interaction simulations. [Watch the video](/gallery/)
