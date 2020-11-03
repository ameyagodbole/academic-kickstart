+++
title = "Siamese Neural Networks with Random Forest for detecting duplicate question pairs"
date = 2018-01-28
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin","Aman Dalmia","Sunil Kumar Sahu"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["4"]

# Publication name and optional abbreviated version.
publication = "***arXiv***"
publication_short = "***arXiv***"

# Abstract and optional shortened version.
abstract = "Determining whether two given questions are semantically similar is a fairly challenging task given the different structures and forms that the questions can take. In this paper, we use Gated Recurrent Units(GRU) in combination with other highly used machine learning algorithms like Random Forest, Adaboost and SVM for the similarity prediction task on a dataset released by Quora, consisting of about 400k labeled question pairs. We got the best result by using the Siamese adaptation of a Bidirectional GRU with a Random Forest classifier, which landed us among the top 24% in the competition Quora Question Pairs hosted on Kaggle."
abstract_short = "Trained a Siamese Gated Recurrent Unit (GRU) RNN over sentence pairs to detect duplicate questions, securing a position in the top 25% among 3000+ teams on Kaggle."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = ["quora_question_pairs"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["NLP","ensemble","GRU","RNN"]

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1801.07288.pdf"
url_preprint = ""
url_code = "https://github.com/dalmia/Quora-Question-Pairs"
url_dataset = ""
url_project = "https://dalmia.github.io/Quora-Question-Pairs/"
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
