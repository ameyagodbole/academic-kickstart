---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A Simple Approach to Case-Based Reasoning in Knowledge Bases"
authors: ["Rajarshi Das", "admin", "Shehzaad Dhuliawala", "Manzil Zaheer", "Andrew McCallum"]
date: 2020-06-24
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-02T14:13:23-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "***Automated Knowledge Base Construction 2020***"
publication_short: "***AKBC 2020***"

abstract: "We present a surprisingly simple yet accurate approach to reasoning in knowledge graphs (KGs) that requires *no training*, and is reminiscent of case-based reasoning in classical artificial intelligence (AI). Consider the task of finding a target entity given a source entity and a binary relation. Our approach finds multiple *graph path patterns* that connect similar source entities through the given relation, and looks for pattern matches starting from the query source. Using our method, we obtain new state-of-the-art accuracy, outperforming all previous models, on NELL-995 and FB-122. We also demonstrate that our model is robust in low data settings, outperforming recently proposed meta-learning approaches."

# Summary. An optional shortened abstract.
summary: ""

tags: ["KBC","CBR"]
categories: []
featured: false
award: "**Best Paper Runner-up**"

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://openreview.net/forum?id=AEY9tRqlU7"
url_code: "https://github.com/rajarshd/CBR-AKBC"
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
