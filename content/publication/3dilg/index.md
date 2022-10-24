---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "3DILG: Irregular Latent Grids for 3D Generative Modeling"
authors: [admin, Matthias Niessner, Peter Wonka]
date: 2022-10-12T23:42:44+03:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-10-12T23:42:44+03:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Thirty-Sixth Conference on Neural Information Processing Systems*
publication_short: In *NeurIPS 2022*

abstract: "We propose a new representation for encoding 3D shapes as neural fields. The representation is designed to be compatible with the transformer architecture and to benefit both shape reconstruction and shape generation. Existing works on neural fields are grid-based representations with latents being defined on a regular grid. In contrast, we define latents on irregular grids which facilitates our representation to be sparse and adaptive. In the context of shape reconstruction from point clouds, our shape representation built on irregular grids improves upon grid-based methods in terms of reconstruction accuracy. For shape generation, our representation promotes high-quality shape generation using auto-regressive probabilistic models. We show different applications that improve over the current state of the art. First, we show results of probabilistic shape reconstruction from a single higher resolution image. Second, we train a probabilistic model conditioned on very low resolution images. Third, we apply our model to category-conditioned generation. All probabilistic experiments confirm that we are able to generate detailed and high quality shapes to yield the new state of the art in generative 3D shape modeling."

# Summary. An optional shortened abstract.
summary: "We proposed a method for representing shapes as irregular latent grids. This representation enables 3d generative modeling with autoregressive transformers."

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

links:
- name: arxiv
  icon: arxiv
  icon_pack: ai
  url: https://arxiv.org/abs/2205.13914
- name: Code
  icon: code
  icon_pack: fas
  url: https://github.com/1zb/3DILG/
- name: OpenReview
  icon: file-pdf
  icon_pack: fa
  url: https://openreview.net/forum?id=RO0wSr3R7y-
- name: Project Website
  icon: globe
  icon_pack: fa
  url: https://1zb.github.io/3DILG/
url_pdf:
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
