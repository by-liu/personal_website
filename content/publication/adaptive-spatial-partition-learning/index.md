---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Adaptive spatial partition learning for image classification"
authors: [Bingyuan Liu, Jing Liu, Hanqing Lu]
date: 2014-10-22
doi: "10.1016/j.neucom.2014.03.057"

# Schedule page publish date (NOT publication's date).
publishDate: 2014-10-22

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Neurocomputing"
publication_short: "Neurocomputing"

abstract: "Spatial Pyramid Matching is a successful extension of bag-of-feature model to embed spatial information of local features, in which the image is divided into a sequence of increasingly finer girds, and the grids are taken as uniform spatial partitions in ad-hoc manner without any theoretical motivation. Obviously, the uniform spatial partition cannot adapt to different spatial distribution across image categories. To this end, we propose a data-driven approach to adaptively learn the discriminative spatial partitions corresponding to each class, and explore them for image classification. First, a set of over-complete spatial partitions covering kinds of spatial distribution of local features are created in a flexible manner, and we concatenate the feature representations of each partitioned region. Then we adopt a discriminative learning formulation with the group sparse constraint to find a sparse mapping from the feature representation to the label space. To further enhance the robustness of the model, we compress the feature representation by removing the dimensions corresponding to those unimportant partitioned regions, and explore the compressed representation to generate a multi-region matching kernel prepared to train a one-versus-others SVM classifier. The experiments on three object datasets (i.e. Caltech-101, Caltech-256, Pascal VOC 2007), and one scene dataset (i.e. 15-Scenes) demonstrate the effectiveness of our proposed method."

# Summary. An optional shortened abstract.
summary: ""

tags: [sparse coding, image classification]
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
