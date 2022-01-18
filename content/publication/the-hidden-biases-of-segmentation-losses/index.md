---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "The hidden label-marginal biases of segmentation losses"
authors: [Bingyuan Liu, Jose Dolz, Adrian Galdran, Riadh Kobbi, Ismail Ben Ayed]
date: 2021-04-18
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-04-20

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: ""

abstract: "Most segmentation losses are arguably variants of the Cross-Entropy (CE) or Dice losses. In the abundant segmentation literature, there is no clear consensus as to which of these losses is a better choice, with varying performances for each across different benchmarks and applications. In this work, we develop a theoretical analysis that links these two types of losses, exposing their advantages and weaknesses. First, we provide a constrained-optimization perspective showing that CE and Dice share a much deeper connection than previously thought: They both decompose into label-marginal penalties and closely related ground-truth matching penalties. Then, we provide bound relationships and an information-theoretic analysis, which uncover hidden label-marginal biases: Dice has an intrinsic bias towards specific extremely imbalanced solutions, whereas CE implicitly encourages the ground-truth region proportions. Our theoretical results explain the wide experimental evidence in the medical-imaging literature, whereby Dice losses bring improvements for imbalanced segmentation. It also explains why CE dominates natural-image problems with diverse class proportions, in which case Dice might have difficulty adapting to different label-marginal distributions. Based on our theoretical analysis, we propose a principled and simple solution, which enables to control explicitly the label-marginal bias. Our loss integrates CE with explicit 1 regularization, which encourages label marginals to match target class proportions, thereby mitigating class imbalance but without losing generality. Comprehensive experiments and ablation studies over different losses and applications validate our theoretical analysis, as well as the effectiveness of our explicit label-marginal regularizers."

# Summary. An optional shortened abstract.
summary: ""

tags: [image segmentation, medical image segmentation]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: arxiv
  url: https://arxiv.org/abs/2104.08717
  icon_pack: ai
  icon: arxiv

- name: code
  url: https://github.com/by-liu/SegLossBias
  icon_pack: fab
  icon: github

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
