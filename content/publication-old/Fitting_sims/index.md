---
title: "Fitting covariance matrix models to
simulations"
authors:
- Alessandra Fumagalli
- admin
- Alex Saro
- Emiliano Sefusatti
- Anze Slosar
- Pierluigi Monaco
- Alfonso Veropalumbo
date: "2022-12-15T00:00:00Z"
doi: "10.1088/1475-7516/2022/12/022"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Cosmology and Astroparticle Physics"
publication_short: ""

abstract: Data analysis in cosmology requires reliable covariance matrices. Covariance matrices derived from numerical simulations often require a very large number of realizations to be accurate. When a theoretical model for the covariance matrix exists, the parameters of the model can often be fit with many fewer simulations. We write a likelihood-based method for performing such a fit.  We demonstrate how a model covariance matrix can be tested by examining the appropriate chi2 distributions from simulations. We show that if model covariance has amplitude freedom, the expectation value of second moment of chi2 distribution with a wrong covariance matrix will always be larger than one using the true covariance matrix. By combining these steps together, we provide a way of producing reliable covariances without ever requiring running a large number of simulations. We demonstrate our method on two examples. First, we measure the two-point correlation function of halos from a large set of 10000 mock halo catalogs. We build a model covariance with 2 free parameters, which we fit using our procedure. The resulting best-fit model covariance obtained from just 100 simulation realizations proves to be as reliable as the numerical covariance matrix built from the full 10000 set. We also test our method on a setup where the covariance matrix is large by measuring the halo bispectrum for thousands of triangles for the same set of mocks. We build a block diagonal model covariance with 2 free parameters as an improvement over the diagonal Gaussian covariance. Our model covariance passes the chi2 test only partially in this case, signaling that the model is insufficient even using free parameters, but significantly improves over the Gaussian one.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://iopscience.iop.org/article/10.1088/1475-7516/2022/12/022/pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

