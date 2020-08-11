---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "3D Reconstruction of Novel Object Shapes from Single Images"
authors: ["Anh Thai", "Stefan Stojanov", "Vijay Upadhya", "Jim Rehg"]
date: 2020-06-14
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "3D Reconstruction of Novel Object Shapes from Single Images"
publication_short: "3DShapeGen"

abstract: "The key challenge in single image 3D shape reconstruction is to ensure that deep models can generalize to shapes which were not part of the training set. This is difficult because the algorithm must infer the occluded portion of the surface by leveraging the shape characteristics of the training data, and can therefore be vulnerable to overfitting. Such generalization to unseen categories of objects is a function of architecture design and training approaches. This paper introduces SDFNet, a novel shape prediction architecture and training approach which supports effective generalization. We provide an extensive investigation of the factors which influence generalization accuracy and its measurement, ranging from the consistent use of 3D shape metrics to the choice of rendering approach and the large-scale evaluation on unseen shapes using ShapeNetCore.v2 and ABC. We show that SDFNet provides state-of-the-art performance on seen and unseen shapes relative to existing baseline methods GenRe and OccNet. We provide the first large-scale experimental evaluation of generalization performance. The codebase released with this article will allow for the consistent evaluation and comparison of methods for single image shape reconstruction."

# Summary. An optional shortened abstract.
summary: "Key issues that affect generalization to unseen shapes in single-view 3D shape reconstruction."

tags: ["Deep Learning", "3D"]
categories: ["3D"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2006.07752.pdf
url_code: https://github.com/devlearning-gt/3DShapeGen
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
