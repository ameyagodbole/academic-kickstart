+++
title = "Progressively Balanced Multi-class Neural Trees"
date = 2018-02-28
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin","Spoorthy Bhat","Prithwijit Guha"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "***Twenty Fourth National Conference on Communications (2018)***"
publication_short = "***NCC 2018***"

# Abstract and optional shortened version.
abstract = "Decision trees are discriminative classifiers that hierarchically partition the input space to achieve regions containing instances having uniform class label. Existing works in this area have mostly focused on C4.5 trees that learn axis aligned partitions. On the other hand, neural trees learn oblique partitions from data and use lesser number of decision nodes hosting perceptrons. However, these perceptrons are susceptible to data imbalances. This motivated us to propose a progressively balanced neural tree where training dataset are balanced prior to perceptron learning. The second contribution is the optimization of the decision function with respect to entropy impurity based objective functions. This formulation also allows a parent node to have more than two child nodes. The proposed algorithm is benchmarked on ten standard datasets against three baseline multi-class classification algorithms."
abstract_short = "Proposed and tested an entropy impurity based objective function for incorporating a learnable perceptron into the decision tree framework."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = ["progressively_balanced_multiclass_neural_trees"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["decision trees","ML","classification"]

# Links (optional).
url_pdf = "https://ieeexplore.ieee.org/document/8599945"
url_preprint = ""
url_code = "https://github.com/ameyagodbole/augmented-dtree"
url_dataset = ""
url_project = ""
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
