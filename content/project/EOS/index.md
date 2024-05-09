---
title: EOS
summary: 'Eos is known as the goddess of dawn in Greek mythology. The Eos Dataset is a set of numerical Nbody simulations of the Universe, investigating the cosmological evolution of primordial interactions taking place at the origin of the Universe.'
tags:
  - EOS
  - N-body Simulations
  - Cosmology
date: '2023-08-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  # caption: Photo by rawpixel on Unsplash
  # focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---



<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


## Introduction

The Eos Dataset is a suite of N-body simulations of the universe at large scales. It follows the dynamics of more than \\(300 \\) billion particles over a total volume of about \\(700 \\) \\( ( \\) Gpc \\(/h)^3 \\).

The goal of the dataset is to investigate the imprint of primordial non-Gaussianity in the evolution of large-scale structures at low redshift. Primordial non-Gaussianity is the observational signature of primordial interactions taking place during inflation, and therefore an essential observational window into the particle content and micro-physics of inflation. 

The current version of the dataset features simulations with quadratic local- and equilateral-type primordial non-Gaussianity initial conditions, as well as several more with Gaussian initial conditions and varying cosmology. The simulations have been used in a number of papers, primarily involving the study of the power spectrum and bispectrum of matter and halos. A complete bibliography of papers using the dataset is provided at the end of this page.




## Description of the Dataset

The simulations were run at the [Baobab Cluster](https://baobabmaster.unige.ch/enduser/src/enduser/enduser.html) at University of Geneva and at the [Cartesius](https://userinfo.surfsara.nl/systems/cartesius/description) and [Snellius](https://servicedesk.surfsara.nl/wiki/display/WIKI/Snellius ) super computers, which are part of the Dutch national computing facilities. The nonlinear motion of particles through time was calculated using with the publicly available [Gadget2 code](https://wwwmpa.mpa-garching.mpg.de/gadget/). The initial conditions were generated the code [2LPTic](https://cosmo.nyu.edu/roman/2LPT/) for Gaussian initial conditions and its counterpart [2LPTicNG](https://cosmo.nyu.edu/roman/2LPT/) for local non-Gaussian initial conditions. For equilateral-type non-Gaussianities, we used [l-picola](https://cullanhowlett.github.io/l-picola/). All initial conditions start at \\(z_i=99\\). Snapshots are saved at redshifts \\( z = 0, 1, 2 \\) except for the high resolution runs G85HR and NG500HR for which only high redshifts are saved \\( z = 9, 9.5, 10, 10.5, 11 \\).

The following table summarizes the dataset:


<table style="text-align:center">
  <tr>
    <th>ID</th>
    <th>\( \Omega_m \)</th>
    <th>\( \Omega_b \)</th>
    <th>\( h \)</th>
    <th>\( n_s \)</th>
    <th>\( \sigma_8 \)</th>
    <th>\( f_{\rm NL}^{\rm loc} \)</th>
    <th>\( f_{\rm NL}^{\rm equil} \)</th>
    <th>realizations</th>
    <th>\(N_p^{\frac 13}\)</th>
    <th>\(L_{\rm box}\) Mpc/h</th>
  </tr>
  <tr style="border-bottom: 3px solid #FFF;">
  <tr>
    <td>G85L</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.85</td>
    <td>0</td>
    <td>0</td>
    <td>15</td>
    <td>1536</td>
    <td>2000</td>
  </tr>
   <tr>
    <td>NG10L</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.85</td>
    <td>10</td>
    <td>0</td>
    <td>15</td>
    <td>1536</td>
    <td>2000</td>
  </tr>
  <tr>
    <td>NG250L</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.85</td>
    <td>250</td>
    <td>0</td>
    <td>15</td>
    <td>1536</td>
    <td>2000</td>
  </tr>
  <tr>
    <td>NGm250L</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.85</td>
    <td>-250</td>
    <td>0</td>
    <td>15</td>
    <td>1536</td>
    <td>2000</td>
  </tr>
  <tr>
    <td>ENGm30L</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.85</td>
    <td>0</td>
    <td>-30</td>
    <td>15</td>
    <td>1536</td>
    <td>2000</td>
  </tr>
  <tr>
    <td>ENGm100L</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.85</td>
    <td>0</td>
    <td>-100</td>
    <td>15</td>
    <td>1536</td>
    <td>2000</td>
  </tr>
  <tr>
    <td>ENGm1000L</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.85</td>
    <td>0</td>
    <td>-1000</td>
    <td>15</td>
    <td>1536</td>
    <td>2000</td>
  </tr>
  <tr>
    <td>G83L</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.83</td>
    <td>0</td>
    <td>0</td>
    <td>3</td>
    <td>1536</td>
    <td>2000</td>
  </tr>
  <tr>
    <td>G87L</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.87</td>
    <td>0</td>
    <td>0</td>
    <td>3</td>
    <td>1536</td>
    <td>2000</td>
  </tr>
  <tr>
    <td>G85S</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.85</td>
    <td>0</td>
    <td>0</td>
    <td>5</td>
    <td>1024</td>
    <td>1000</td>
  </tr>
  <tr>
    <td>NG250S</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.85</td>
    <td>250</td>
    <td>0</td>
    <td>5</td>
    <td>1024</td>
    <td>1000</td>
  </tr>
  <tr>
    <td>NGm250S</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.85</td>
    <td>-250</td>
    <td>0</td>
    <td>5</td>
    <td>1024</td>
    <td>1000</td>
  </tr>
  <tr>
    <td>ENGm1000S</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.85</td>
    <td>0</td>
    <td>-1000</td>
    <td>5</td>
    <td>1024</td>
    <td>1000</td>
  </tr>
  <tr>
    <td>G83S</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.83</td>
    <td>0</td>
    <td>0</td>
    <td>5</td>
    <td>1024</td>
    <td>1000</td>
  </tr>
  <tr>
    <td>G87S</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.87</td>
    <td>0</td>
    <td>0</td>
    <td>5</td>
    <td>1024</td>
    <td>1000</td>
  </tr>
  <tr>
    <td>G85HR</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.87</td>
    <td>0</td>
    <td>0</td>
    <td>30</td>
    <td>512</td>
    <td>64</td>
  </tr>
  <tr>
    <td>NG500HR</td>
    <td>0.3</td>
    <td>0.045</td>
    <td>0.7</td>
    <td>0.967</td>
    <td>0.87</td>
    <td>500</td>
    <td>0</td>
    <td>30</td>
    <td>512</td>
    <td>64</td>
  </tr>
</table>


## Analysis and Postprocessing

The Eos datasets includes halo catalogues, measurements of matter, halo and cross power spectra and bispectra, and topological data analysis using persistent homology. Here we provide further details on these measurements.

### Halo catalogs

The halo catalogs are produced using [Rockstar](https://bitbucket.org/gfcstanford/rockstar/src/master/), for which we use a linking length of \\( \lambda= 0.28 \\).  For the set of large box runs (L), we look at halos with a minimum of 50 particles in it, which corresponds to a minimum mass of \\( M\_{min} =  9.2\times 10^{12} M_\odot \\).

### Power Spectra

The power spectrum of matter and halos is measured by interpolating particles (halos) on a discrete grid using fourth-order interpolation with interlacing as described in [Sefusatti et al. (2016)](https://academic.oup.com/mnras/article/460/4/3624/2609122) to get a density field and compute correlations of binned Fourier modes. Density files are also saved for grids of size \\( 768^3 \\). The code used to perform the measurements is a python-Fortran hybrid based on [PowerI4](https://github.com/sefusatti/PowerI4).

### Bispectrum

The bispectrum of matter and halos is measured by computing correlations of binned Fourier modes using density files as described in the previous section. Binning of Fourier modes and measured triangles is defined as in [Oddo et al. (2019)](https://doi.org/10.1088/1475-7516/2020/03/056).  The code used to perform the measurements is a python-Fortran hybrid based on the same techniques defined in the Power Spectrum.

### Persistent Homology

This section will be available soon. For info refer to these publications: [2009.04819](https://arxiv.org/pdf/2009.04819.pdf) and [2203.08262](https://arxiv.org/pdf/2203.08262.pdf).

## Access to Data

Data from the Eos Dataset is accessible at all levels (particle snapshots, halo catalogs, power spectra and bispectra) by [contacting me](mailto:matteo.1biagetti@gmail.com) and providing a short description of the project. In the near future, part of the data will be made openly accessible.

## References

When referencing the Eos Dataset, the main publications to cite are:

"Verifying the consistency relation for the scale-dependent bias from local primordial non-Gaussianity"  
*Matteo Biagetti, Titouan Lazeyras, Tobias Baldauf, Vincent Desjacques, Fabian Schmidt*  
Published in: Mon.Not.Roy.Astron.Soc. (2017) [Volume 468, Number 3](https://doi.org/10.1093/mnras/stx714) e-Print: [1611.04901](https://arxiv.org/abs/1611.04901) [astro-ph.CO]

"The Persistence of Large Scale Structures I: Primordial non-Gaussianity"  
*Matteo Biagetti, Alex Cole, Gary Shiu*  
Published in: Journal of Cosmology and Astroparticle Physics, (2021) [Volume 04, Number 061](https://iopscience.iop.org/article/10.1088/1475-7516/2021/04/061) e-Print: [2009.04819](https://arxiv.org/abs/2009.04819) [astro-ph.CO]

More publications involving the dataset:

"Fisher Forecasts for Primordial non-Gaussianity from Persistent Homology"  
*Matteo Biagetti, Juan Calles, Lina Castiblanco, Alex Cole, Jorge Noreña*  
Submitted to JCAP e-Print: [2203.08262](https://arxiv.org/pdf/2203.08262.pdf) [astro-ph.CO]


"The Covariance of Squeezed Bispectrum Configurations"  
*Matteo Biagetti, Lina Castiblanco, Jorge Noreña, Emiliano Sefusatti*  
Submitted to JCAP e-Print: [2111.05887](https://arxiv.org/pdf/2111.05887.pdf) [astro-ph.CO]

"The reach of next-to-leading-order perturbation theory for the matter bispectrum"  
*Davit Alkhanishvili, Cristiano Porciani, Emiliano Sefusatti, Matteo Biagetti, Andrei Lazanu, Andrea Oddo*  
Submitted to MNRAS e-Print: [2107.08054](https://arxiv.org/pdf/2107.08054.pdf) [astro-ph.CO]

"Primordial Non-Gaussianity from Biased Tracers: Likelihood Analysis of Real-Space Power Spectrum and Bispectrum"  
*Azadeh Moradinezhad Dizgah, Matteo Biagetti, Emiliano Sefusatti, Vincent Desjacques, Jorge Noreña*  
Published in: Journal of Cosmology and Astroparticle Physics, (2021) [Volume 05, Number 015] (https://iopscience.iop.org/article/10.1088/1475-7516/2021/05/015) e-Print: [2010.14523](https://arxiv.org/abs/2010.14523) [astro-ph.CO]

"Measurement of Void Bias Using Separate Universe Simulations"  
*Kwan Chuen Chan, Yin Li, Matteo Biagetti, Nico Hamaus*  
Published in: The Astrophysical Journal, (2020) [Volume 889, Number 2](https://iopscience.iop.org/article/10.3847/1538-4357/ab64ec)   e-Print: [1909.03736](https://arxiv.org/abs/1909.03736) [astro-ph.CO]

"Constraint of Void Bias on Primordial non-Gaussianity"  
*Kwan Chuen Chan, Nico Hamaus, Matteo Biagetti*  
Published in: Phys.Rev.D 99 (2019) [Volume 99, Number 12](https://doi.org/10.1103/PhysRevD.99.121304) e-Print: [1812.04024](https://arxiv.org/abs/1812.04024) [astro-ph.CO]

"Abundance of peaks and dips in 3D mass and halo density fields: a test for cosmology"  
*Adi Nusser, Matteo Biagetti, Vincent Desjacques*  
Published in: Mon.Not.Roy.Astron.Soc. 480 (2018) [Volume 480, Number 2](https://doi.org/10.1093/mnras/sty1961) e-Print:[1804.05328](https://arxiv.org/abs/1804.05328) [astro-ph.CO]

