---
title: "Visual Analytics of Multivariate Event Sequence Data in Racquet Sports"
authors:
- Jiang Wu
- admin
- Zuobin Wang
- Qingyang Xu
- Yingcai Wu
date: "2020-10-25T00:00:00Z"
doi: 10.1109/VAST50239.2020.00009

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2020 IEEE Conference on Visual Analytics Science and Technology (VAST)*
publication_short: "In *IEEE VAST*"

abstract: In this work, we propose a generic visual analytics framework to support tactic analysis based on data collected from racquet sports (such as tennis and badminton). The proposed approach models each rally in a game as a sequence of hits (i.e., events) until one athlete scores a point. Each hit can be described with a set of attributes, such as the positions of the ball and the techniques used to hit the ball (such as drive and volley in tennis). Thus, the mentioned sequence of hits can be viewed as a multivariate event sequence. By detecting and analyzing the multivariate subsequences that frequently occur in the rallies (namely, tactical patterns), athletes can gain insights into the playing styles adopted by their opponents, and therefore help them identify systematic weaknesses of the opponents and develop counter strategies in matches. To support such analysis effectively, we propose a steerable multivariate sequential pattern mining algorithm with adjustable weights over event attributes, such that the domain expert can obtain frequent tactical patterns according to the attributes specified by himself. We also propose a re-configurable glyph design to help users simultaneously analyze multiple attributes of the hits. The framework further supports comparative analysis of the tactical patterns, e.g., for different athletes or the same athlete playing under different conditions. By applying the framework on two datasets collected in tennis and badminton matches, we demonstrate that the system is generic and effective for tactic analysis in sports and can help identify signature techniques used by individual athletes. Finally, we discuss the strengths and limitations of the proposed approach based on the feedback from the domain experts.

# Summary. An optional shortened abstract.
summary: "By detecting and analyzing the multivariate subsequences that frequently occur in the rallies (namely, tactical patterns), athletes can gain insights into the playing styles adopted by their opponents, and therefore help them identify systematic weaknesses of the opponents and develop counter strategies in matches. We propose visual analytics system based on a steerable multivariate sequential pattern mining algorithm and a re-configurable glyph design to meet the different needs of domain experts and address the complexity of visualizing multivariate data."

tags:
- IEEE VIS
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://zjuidg.org/source/projects/esrac/esrac.pdf


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---