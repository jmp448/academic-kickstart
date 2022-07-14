---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Inference after latent variable estimation for single-cell RNA sequencing data"
authors: [Anna Neufeld, Lucy L. Gao, Joshua Popp, Alexis Battle, Daniela Witten]
date: 2022-07-01T23:24:07-04:00
doi: "https://doi.org/10.48550/arXiv.2207.00554"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-11-01T23:24:07-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: ""

abstract: "In the analysis of single-cell RNA sequencing data, researchers often characterize the variation between cells by estimating a latent variable, such as cell type or pseudotime, representing some aspect of the individual cell's state. They then test each gene for association with the estimated latent variable. If the same data are used for both of these steps, then standard methods for computing p-values and confidence intervals in the second step will fail to achieve statistical guarantees such as Type 1 error control. Furthermore, approaches such as sample splitting that can be applied to solve similar problems in other settings are not applicable in this context. In this paper, we introduce count splitting, a flexible framework that allows us to carry out valid inference in this setting, for virtually any latent variable estimation technique and inference approach, under a Poisson assumption. We demonstrate the Type 1 error control and power of count splitting in a simulation study, and apply count splitting to a dataset of pluripotent stem cells differentiating to cardiomyocytes."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2207.00554.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
