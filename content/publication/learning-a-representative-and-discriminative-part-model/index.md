---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning a Representative and Discriminative Part Model with Deep Convolutional Features for Scene Recognition"
authors: [Bingyuan Liu, Jing Liu, Jingqiao Wang, Hanqing Lu]
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

abstract: "The discovery of key and distinctive parts is critical for scene parsing and understanding. However, it is a challenging problem due to the weakly supervised condition, i.e., no annotation for parts is available. To address above issues, we propose a unified framework for learning a representative and discriminative part model with deep convolutional features. Firstly, we employ selective search method to generate regions that are more likely to be centered around the distinctive parts, which is used as parts training set. Then, the feature of each part region is extracted by forward propagating it into the Convolutional Neural Network (CNN). The CNN network is pre-trained by the large auxiliary ImageNet dataset and then fine-tuned on the particular scene images. To learn the parts model, we build a mid-level part dictionary based on sparse coding with a discriminative regularization. The two terms, i.e., the sparse reconstruction error term and the label consistent term, indicate the representative and discriminative properties respectively. Finally, we apply the learned parts model to build image-level representation for the scene recognition task. Extensive experiments demonstrate that we achieve state-of-the-art performances on the standard scene benchmarks, i.e. Scene-15 and MIT Indoor-67."

# Summary. An optional shortened abstract.
summary: ""

tags: [deep learning, sparse coding, scene recognition]
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
