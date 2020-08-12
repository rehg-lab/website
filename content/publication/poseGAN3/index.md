---
title: "Unsupervised 3D Pose Estimation With Geometric Self-Supervision"
authors:
- Ching-Hang Chen
- Ambrish Tyagi
- Amit Agrawal
- Dylan Drover
- Stefan Stojanov
- admin
date: "2017-06-15"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 
publication_short: ""

abstract: We present an unsupervised learning approach to re-cover 3D human pose from 2D skeletal joints extracted from a single image. Our method does not require any multi-view image data, 3D skeletons, correspondences between 2D-3D points, or use previously learned 3D priors during training. A lifting network accepts 2D landmarks as inputs and generates a corresponding 3D skeleton estimate. Dur-ing training, the recovered 3D skeleton is reprojected on random camera viewpoints to generate new'synthetic'2D poses. By lifting the synthetic 2D poses back to 3D and re-projecting them in the original camera view, we can de-fine self-consistency loss both in 3D and in 2D. The training can thus be self supervised by exploiting the geometric self-consistency of the lift-reproject-lift process. We show that self-consistency alone is not sufficient to generate realistic skeletons, however adding a 2D pose discriminator enables the lifter to output valid 3D poses. Additionally, to learn from 2D poses' in the wild', we train an unsupervised 2D domain adapter network to allow for an expansion of 2D data. This improves results and demonstrates the useful-ness of 2D pose data for unsupervised 3D lifting. Results on Human3. 6M dataset for 3D human pose estimation demon-strate that our approach improves upon the previous un-supervised methods by 30% and outperforms many weakly supervised approaches that explicitly use 3D data.


# Summary. An optional shortened abstract.
summary: CVPR 2019


tags:
- 3D Pose Estimation
featured: false

links:
# - name: Custom Link
# url: http://example.org
url_pdf: https://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Unsupervised_3D_Pose_Estimation_With_Geometric_Self-Supervision_CVPR_2019_paper.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
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
# slides: example
---
