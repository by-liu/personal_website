---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Detection guided deconvolutional network for hierarchical feature learning"
authors: [Bingyuan Liu, Jing Liu, Hanqing Lu]
date: 2015-08-01
doi: "10.1016/j.patcog.2015.02.002"

# Schedule page publish date (NOT publication's date).
publishDate: 2015-08-01

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Pattern Recognition"
publication_short: "Pattern Recognition"

abstract: "Deep learning models have gained significant interest as a way of building hierarchical image representation. However, current models still perform far behind human vision system because of the lack of selective property, the lack of high-level guidance for learning and the weakness to learn from few examples. To address these problems, we propose a detection-guided hierarchical learning algorithm for image representation. First, we train a multi-layer deconvolutional network in an unsupervised bottom-up scheme. During the training process, we use each raw image as an input, and decompose an image using multiple alternating layers of non-negative convolutional sparse coding and max-pooling. Inspired from the observation that the filters in top layer can be selectively activated by different high-level structures of images, i.e., one or partial filters should correspond to a particular object class, we update the filters in network by minimizing the reconstruction errors of the corresponding feature maps with respect to certain object detection maps obtained by a set of pre-trained detectors. With the fine-tuned network, we can extract the features of given images in a purely unsupervised way with no need of detectors. We evaluate the proposed feature representation on the task of object recognition, for which an SVM classifier with spatial pyramid matching kernel is used. Experiments on the datasets of PASCAL VOC 2007, Caltech-101 and Caltech-256 demonstrate that our approach outperforms some recent hierarchical feature descriptors as well as classical hand-crafted features."

# Summary. An optional shortened abstract.
summary: ""

tags: [deep learning, image classification, object detection]
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
