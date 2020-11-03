---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Probabilistic Case-based Reasoning for Open-World Knowledge Graph Completion"
authors:
- Rajarshi Das
- admin
- Nicholas Monath
- Manzil Zaheer
- Andrew McCallum
date: 2020-10-18
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-02T16:04:42-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: "***Findings of The 2020 Conference on Empirical Methods in Natural Language Processing 2020***"
publication_short: "***Findings of EMNLP 2020***"

abstract: "A case-based reasoning (CBR) system solves a new problem by retrieving `cases' that are similar to the given problem. If such a system can achieve high accuracy, it is appealing owing to its simplicity, interpretability, and scalability. In this paper, we demonstrate that such a system is achievable for reasoning in knowledge-bases (KBs). Our approach predicts attributes for an entity by gathering reasoning paths from similar entities in the KB. Our probabilistic model estimates the likelihood that a path is effective at answering a query about the given entity. The parameters of our model can be efficiently computed using simple path statistics and require no iterative optimization. Our model is non-parametric, growing dynamically as new entities and relations are added to the KB. On several benchmark datasets our approach significantly outperforms other rule learning approaches and performs comparably to state-of-the-art embedding-based approaches. Furthermore, we demonstrate the effectiveness of our model in an 'open-world' setting where new entities arrive in an online fashion, significantly outperforming state-of-the-art approaches and nearly matching the best offline method."

# Summary. An optional shortened abstract.
summary: ""

tags: ["KBC","CBR"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/abs/2010.03548"
url_code: "https://github.com/ameyagodbole/Prob-CBR"
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
projects: ["case-based-reasoning"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
