---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Regularized Hierarchical Feature Learning with Non-negative Sparsity and Selectivity for Image Classification"
authors: [Bingyuan Liu, Jing Liu, Xiao Bai, Hanqing Lu]
date: 2014-08-24
doi: "10.1109/ICPR.2014.736"

# Schedule page publish date (NOT publication's date).
publishDate: 2014-08-24

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Pattern Recognition"
publication_short: "ICPR"

abstract: "Recently, many deep networks are proposed to learn hierarchical image representation to replace traditional hand-designed features. To enhance the ability of the generative model to tackle discriminative computer vision tasks (e.g. image classification), we propose a hierarchical deconvolutional network with two biologically inspired properties incorporated, i.e., non-negative sparsity and selectivity. First, we propose a single layer deconvolutional model with a raw image as input, attempting to decompose the input as a weighted sum of feature maps convolving with filters. Here, the filters are the model parameters common to all the inputs, while the feature maps and the summing weights are specific to the input. The non-negative sparsity is formulated as the /i-norm regularizer on the feature map, which is used to generate feature representations for image classification. And the selectivity is forced on the filters to make different filters active different inputs, through requiring the sparsity on the summing weights specifically. The two properties are summarized into an overall cost function, which can be solved with an alternatively iterative algorithm. Then, we build multiple layer deconvolutional network by stacking the single models, where the next-layer inputs are the results of a 3D max-pooling operation on the inferred feature maps of the front layer, and train the network in a greedy layer wise scheme. Finally, we explore the feature maps of each layer to generate the image representations and input them to a SVM classifier for the classification task. Experiments on two image benchmark datasets of Caltech-101 and Caltech-256 demonstrate the encouraging performance of our model compared with other deep feature learning models as well as some hand-designed features."

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
