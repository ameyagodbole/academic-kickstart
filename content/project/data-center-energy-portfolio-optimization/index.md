---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Data Center Energy Portfolio Optimization"
summary: "Proposed, implemented and tested reinforcement learning and imitation learning based agents for data center battery controllers. Outlined future work directions."
authors: []
tags: ["RL","optimization"]
categories: []
date: 2020-04-19

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

**Mentor:** [Dr. Mohammad Hajiesmaili](https://groups.cs.umass.edu/hajiesmaili/) (CICS, UMass Amherst), [Dr. Philip Thomas](https://people.cs.umass.edu/~pthomas/) (CICS, UMass AmherstCICS, UMass Amherst)

This project deals with the problem of online inventory management with demand constraints. In particular, given a time-varying pricing and demand function for electricity and the ability to store a limited amount of electricity for future use (inventory), the task is to minimize the cost of buying electricity while meeting the demand at every time instant.

The existing state-of-the-art techniques [1] propose a behavior rule that is analytically shown to have the lowest possible worst case cost ratio. The authors have shown that the method also works well in the average case against several competitive baselines. However, this rule based method does not learn or adapt to the distributions of price and demand. This project attempted to develop methods using Reinforcement Learning to see whether there is room for improvement by learning from interactions with this environment.

After setting up the RL problem with the price and demand variations as the environment and the battery control as the agent, I applied a range of standard RL algorithms as well as imitation learning (DAGGER [2]). The oracle for imitation learning was the optimal offline solution.

Outcomes: The RL methods are difficult to train for this problem and even with hyperparameter tuning, the best performing agents cannot beat the SotA baseline. The imitation learning agent fares better than the RL agents ans is competitive with the SotA (but not better).

I ended the project by outlining avenues for future work including dynamically changing action spaces and two-stage control. Although I am no longer working on this problem, this project is being actively worked on by Prof. Hajiesmaili.

[1]: [Online Inventory Management with Application to Energy Procurement in Data Centers](https://arxiv.org/abs/1901.04372) 
[2]: [A Reduction of Imitation Learning and Structured Prediction to No-Regret Online Learning](https://arxiv.org/abs/1011.0686)
