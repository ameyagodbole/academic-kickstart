---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Case-Based Reasoning"
summary: "Applied CBR to knowledge graph completition with competitive results. Demonstrated usage instances where it outperforms existing embedding-based methods. Working to extend functionality to raw text."
authors: []
tags: []
categories: []
date: 2020-10-18

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

**Mentor:** Dr. Andrew McCallum (CICS, UMass Amherst)

**Collaborator:** [Rajarshi Das](http://rajarshd.github.io/), [Nicholas Monath](https://people.cs.umass.edu/~nmonath/), [Manzil Zaheer](http://www.manzil.ml/)

A knowledge graph (KG) is formed by the entities as nodes and relations between entities as directed edges. KG completion is the problem of answering queries of the type (`e`, `r`, ?) i.e. given a query entity `e` and query relation `r`, find the entity `e_ans` that has the relation `r` with `e`. As you can imagine, this task is used to complete partial KGs by guessing missing edges.

Given a new problem, a *Case-based Reasoning system*:
1. **Retrieves** similar cases seem in the past
2. **Reuses** solutions to previously solved cases
3. **Revises** solutions to apply to the current query
4. **Retains** modified solutions as new cases

We adapt this system for knowledge graph completion by using the training graph as the store of solved cases. Similar entities are found by nearest neighbors using a simple one-hot representation based on connected relations (this captures the notion of entity types). Solutions are paths (sequence of relations) that reach the answer node. Then starting from the query entity, we traverse the graph using the paths collected. If such a system can achieve high accuracy, it is appealing owing to its simplicity, interpretability, and scalability.

We demonstrated that this simple system is highly performant in [`A Simple Approach to Case-Based Reasoning in Knowledge Bases`]({{< ref "/publication/a-simple-approach-to-case-based-reasoning-in-knowledge-bases/index.md" >}}).

After performing an error analysis on this system, we then imposed a probabilistic structure to allow the system to weight the answers. Concretely, we use the prior probability of a path reaching the tail entity for the given query relation and the precision of that path type to downweight spurious paths. We use clustering to help aggregate probabilitities. We demonstrated in [`Probabilistic Case-based Reasoning for Open-World Knowledge Graph Completion`]({{< ref "/publication/probabilistic-case-based-reasoning-for-open-world-knowledge-graph-completion/index.md" >}}) that this systems matches/outperforms baselines on FB122, WN18RR and Nell-995. Moreover, we demonstrated that this method can be applied to dynamic *growing* KGs with minimal overhead whereas the best embedding based methods deteriorate with successive KG updates.

Future Work: We are experimenting with extending this reasoning strategy to question answering systems. A lot of challenges arise with moving from the structured world of knowledge graphs to unstructured text.
