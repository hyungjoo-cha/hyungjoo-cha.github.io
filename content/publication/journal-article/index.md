---
title: "An Exact A $\^{}$\{$*$\}$ $-Based Tree Search Algorithm for TSP With Sequence-and-Load Dependent Risk"
authors:
- admin
- Chanho Lee
- Chi Xie
- Qing-Chang Lu
- Joonyup Eun
- Taesu Cheong

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Intelligent Transportation Systems, 25*(9)"
publication_short: "IEEE ITS"

abstract: The hazardous material transportation requires extensive care owing to the disastrous consequences of accidents, such as chemical spills or radioactive exposures. Consequently, a minimum risk delivery plan that is dynamically decided by the cargo load of the vehicle at each customer must be scheduled. We introduce a traveling salesman problem (TSP) with a sequence-and-load dependent risk, which differs from the conventional TSP as the arc costs are determined by the hazardous cargo load at each decision epoch. We define our problem in a dynamic programming formulation and present mixed-integer linear program with a nonlinear objective function. To efficiently retrieve exact optimal solutions, we propose an iterative-deepening A*-based tree search algorithm using admissible lower and efficient upper bound algorithms for guaranteed optimality. Numerical experiments indicate that the proposed algorithm outperforms a current state-of-the-art solver. An ablation study and sensitivity analysis demonstrate the effectiveness of the proposed algorithm and derive managerial insights.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10502342
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
