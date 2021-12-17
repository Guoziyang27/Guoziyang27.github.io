---
title: "TacticFlow: Visual Analytics of Ever-Changing Tactics in Racket Sports"
authors:
- Wu Jiang
- Dongyu Liu
- admin
- Qingyang Xu
- Yingcai Wu
date: "2021-09-29T00:00:00Z"
doi: 10.1109/TVCG.2021.3114832

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Visualization and Computer Graphics ( Early Access )*
publication_short: In *IEEE TVCG*

abstract: Event sequence mining is often used to summarize patterns from hundreds of sequences but faces special challenges when handling racket sports data. In racket sports (e.g., tennis and badminton), a player hitting the ball is considered a multivariate event consisting of multiple attributes (e.g., hit technique and ball position). A rally (i.e., a series of consecutive hits beginning with one player serving the ball and ending with one player winning a point) thereby can be viewed as a multivariate event sequence. Mining frequent patterns and depicting how patterns change over time is instructive and meaningful to players who want to learn more short-term competitive strategies (i.e., tactics) that encompass multiple hits. However, players in racket sports usually change their tactics rapidly according to the opponent's reaction, resulting in ever-changing tactic progression. In this work, we introduce a tailored visualization system built on a novel multivariate sequence pattern mining algorithm to facilitate explorative identification and analysis of various tactics and tactic progression. The algorithm can mine multiple non-overlapping multivariate patterns from hundreds of sequences effectively. Based on the mined results, we propose a glyph-based Sankey diagram to visualize the ever-changing tactic progression and support interactive data exploration. Through two case studies with four domain experts in tennis and badminton, we demonstrate that our system can effectively obtain insights about tactic progression in most racket sports. We further discuss the strengths and the limitations of our system based on domain experts' feedback.

# Summary. An optional shortened abstract.
summary: "Mining frequent patterns and depicting how patterns change over time is instructive and meaningful to players who want to learn more short-term competitive strategies (i.e., tactics) that encompass multiple hits. However, players in racket sports usually change their tactics rapidly according to the opponent's reaction, resulting in ever-changing tactic progression. In this work, we introduce a tailored visualization system built on a novel multivariate sequence pattern mining algorithm to facilitate explorative identification and analysis of various tactics and tactic progression."

tags:
- IEEE VIS
featured: true


url_pdf: https://zjuidg.org/source/projects/tacticflow/tacticflow.pdf
url_code: https://osf.io/9x4yp/
url_video: https://www.youtube.com/watch?v=Qc2kxgqtw0g

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
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
