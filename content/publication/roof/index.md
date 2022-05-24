---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Intuitive and Efficient Roof Modeling for Reconstruction and Synthesis"
authors: [Jing Ren, admin, Bojian Wu, Jianqiang Huang, Lubin Fan, Maks Ovsjanikov, Peter Wonka]
date: 2021-09-16T23:51:50+03:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-09-16T23:51:50+03:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM Trans. on Graphics (Proc. of SIGGRAPH Asia 2021)"
publication_short: ""

abstract: "We propose a novel and flexible roof modeling approach that can be used for constructing planar 3D polygon roof meshes. Our method uses a graph structure to encode roof topology and enforces the roof validity by optimizing a simple but effective planarity metric we propose. This approach is significantly more efficient than using general purpose 3D modeling tools such as 3ds Max or SketchUp, and more powerful and expressive than specialized tools such as the straight skeleton. Our optimization-based formulation is also flexible and can accommodate different styles and user preferences for roof modeling. We showcase two applications. The first application is an interactive roof editing framework that can be used for roof design or roof reconstruction from aerial images. We highlight the efficiency and generality of our approach by constructing a mesh-image paired dataset consisting of 2539 roofs. Our second application is a generative model to synthesize new roof meshes from scratch. We use our novel dataset to combine machine learning and our roof optimization techniques, by using transformers and graph convolutional networks to model roof topology, and our roof optimization methods to enforce the planarity constraint."

# Summary. An optional shortened abstract.
# summary: "We found a link between shape reconstruction and few-shot learning."

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
  url: https://arxiv.org/abs/2109.07683
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
