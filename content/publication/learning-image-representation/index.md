---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning representative and discriminative image representation by deep appearance and spatial coding"
authors: [Bingyuan Liu, Jing Liu, Hanqing Lu]
date: 2015-07-01
doi: "10.1016/j.cviu.2015.03.006"

# Schedule page publish date (NOT publication's date).
publishDate: 2015-07-01

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computer Vision and Image Understanding"
publication_short: "CVIU"

abstract: "How to build a suitable image representation remains a critical problem in computer vision. Traditional Bag-of-Feature (BoF) based models build image representation by the pipeline of local feature extraction, feature coding and spatial pooling. However, three major shortcomings hinder the performance, i.e., the limitation of hand-designed features, the discrimination loss in local appearance coding and the lack of spatial information. To overcome the above limitations, in this paper, we propose a generalized BoF-based framework, which is hierarchically learned by exploring recently developed deep learning methods. First, with raw images as input, we densely extract local patches and learn local features by stacked Independent Subspace Analysis network. The learned features are then transformed to appearance codes by sparse Restricted Boltzmann Machines. Second, we perform spatial max-pooling on a set of over-complete spatial regions, which is generated by covering various spatial distributions, to incorporate more flexible spatial information. Third, a structured sparse Auto-encoder is proposed to explore the region representations into the image-level signature. To learn the proposed hierarchy, we layerwise pre-train the network in unsupervised manner, followed by supervised fine-tuning with image labels. Extensive experiments on different benchmarks, i.e., UIUC-Sports, Caltech-101, Caltech-256, Scene-15 and MIT Indoor-67, demonstrate the effectiveness of our proposed model."

# Summary. An optional shortened abstract.
summary: ""

tags: [deep learning, unsupervised learning, image classification]
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
