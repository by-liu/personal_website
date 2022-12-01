---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Segmentation with mixed supervision: Confidence maximization helps knowledge distillation"
authors: [Bingyuan Liu, Christian Desrosiers, Ismail Ben Ayed, Jose Dolz]
date: 2022-11-07
doi: "10.1016/j.media.2022.102670"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-07

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Medical Image Analysis"
publication_short: "MedIA"

abstract: "Despite achieving promising results in a breadth of medical image segmentation tasks, deep neural networks require large training datasets with pixel-wise annotations. Obtaining these curated datasets is a cumbersome process which limits the applicability in scenarios. Mixed supervision is an appealing alternative for mitigating this obstacle. In this work, we propose a dual-branch architecture, where the upper branch (teacher) receives strong annotations, while the bottom one (student) is driven by limited supervision and guided by the upper branch. Combined with a standard cross-entropy loss over the labeled pixels, our novel formulation integrates two important terms: (i) a Shannon entropy loss defined over the less-supervised images, which encourages confident student predictions in the bottom branch; and (ii) a KL divergence term, which transfers the knowledge (i.e., predictions) of the strongly supervised branch to the less-supervised branch and guides the entropy (student-confidence) term to avoid trivial solutions. We show that the synergy between the entropy and KL divergence yields substantial improvements in performance. We also discuss an interesting link between Shannon-entropy minimization and standard pseudo-mask generation, and argue that the former should be preferred over the latter for leveraging information from unlabeled pixels. We evaluate the effectiveness of the proposed formulation through a series of quantitative and qualitative experiments using two publicly available datasets. Results demonstrate that our method significantly outperforms other strategies for semantic segmentation within a mixed-supervision framework, as well as recent semi-supervised approaches. Our code is publicly available: https://github.com/by-liu/ConfKD."

# Summary. An optional shortened abstract.
summary: ""

tags: [image segmentation, medical image segmentation, knowledge distillation]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: arxiv
  url: https://arxiv.org/abs/2109.10902
  icon_pack: ai
  icon: arxiv

- name: code
  url: https://github.com/by-liu/ConfKD
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
