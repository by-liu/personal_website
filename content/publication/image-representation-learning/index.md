---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Image Representation Learning by Deep Appearance and Spatial Coding"
authors: [Bingyuan Liu, Jing Liu, Zechao Li, Hanqing Lu]
date: 2014-11-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2015-01-01

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Asian Conference on Computer Vision"
publication_short: "ACCV"

abstract: "The bag of feature model is one of the most successful model to represent an image for classification task. However, the discrimination loss in the local appearance coding and the lack of spatial information hinder its performance. To address these problems, we propose a deep appearance and spatial coding model to build more optimal image representation for the classification task. The proposed model is a hierarchical architecture consisting of three operations: appearance coding, max-pooling and spatial coding. Firstly, with an image as input, we extract a set of local descriptors and adopt the appearance coding to encode them into high-dimensional robust vectors. Then max-pooling is performed within the over spatial partitioned grids to incorporate spatial information. After that, spatial coding is carried out to increasingly integrate the region vectors to a global image signature. Finally, the resulting image representation are employed to train a one-versus-others SVM classifier. In the learning of the proposed model, we layerwisely pre-train the network and then perform supervised fine-tuning with image labels. The experiments on three image benchmark datasets (i.e. 15-Scenes, PASCAL VOC 2007 and Caltech-256) demonstrate the effectiveness of our proposed model."

# Summary. An optional shortened abstract.
summary: ""

tags: [deep learning, sparse coding, image classification]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

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
