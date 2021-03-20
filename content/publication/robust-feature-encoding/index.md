---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robust Feature Encoding with Neighborhood Information for Image Classification"
authors: [Bingyuan Liu, Jing Liu, Chunjie Zhang, Maolin Chen, Hanqing Lu]
date: 2013-07-26
doi: "10.1109/ICIG.2013.178"

# Schedule page publish date (NOT publication's date).
publishDate: 2013-07-26

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Image and Graphics"
publication_short: "ICIG"

abstract: "The bag of visual words (BoW) model is one of the most successful model in image classification task. However, the major problem of the BoW model lies in the determination of visual words, which consists of codebook training and feature encoding phases. The traditional K-means and hard-assignment method completely ignore the structure of the local feature space, leading to high loss of information. To alleviate the information loss, we propose to incorporate the neighborhood information of the features into the codebook training and feature encoding process. We firstly propose a model to roughly measure the influence of the distribution of the neighboring features. Then we combine the proposed model with the traditional K-means method in a probability perspective to train the visual codebook. Finally, in the feature encoding phase, both the hard-assignment and soft-assignment method are improved with the proposed neighborhood information term. We investigate our method on two popular datasets: 15-Scenes and Caltech-101. Experimental results demonstrate the effectiveness of our proposed method."

# Summary. An optional shortened abstract.
summary: ""

tags: [image classification]
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
