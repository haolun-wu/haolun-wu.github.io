---
title: "Multi-FR: A Multi-objective Optimization Framework for Multi-stakeholder Fairness-aware Recommendation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Chen Ma
  - Bhaskar Mitra
  - Fernando Diaz
  - Xue Liu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-08-01"
# doi: "10.1145/3477495.3532007"

# Schedule page publish date (NOT publication's date).

publishDate: "2022-08-01"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ "2" ]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Information Systems*
publication_short: In *TOIS 2022*

abstract: Nowadays, most online services are hosted on multi-stakeholder marketplaces, where consumers and producers may have different objectives. Conventional recommendation systems, however, mainly focus on maximizing consumers' satisfaction by recommending the most relevant items to each individual. This may result in unfair exposure of items, thus jeopardizing producer benefits. Additionally, they do not care whether consumers from diverse demographic groups are equally satisfied. To address these limitations, we propose a multi-objective optimization framework for fairness-aware recommendation, Multi-FR, that adaptively balances accuracy and fairness for various stakeholders with Pareto optimality guarantee. We first propose four fairness constraints on consumers and producers. In order to train the whole framework in an end-to-end way, we utilize the smooth rank and stochastic ranking policy to make these fairness criteria differentiable and friendly to back-propagation. Then, we adopt the multiple gradient descent algorithm to generate a Pareto set of solutions, from which the most appropriate one is selected by the Least Misery Strategy. The experimental results demonstrate that Multi-FR largely improves recommendation fairness on multiple stakeholders over the state-of-the-art approaches while maintaining almost the same recommendation accuracy. The training efficiency study confirms our model's ability to simultaneously optimize different fairness constraints for many stakeholders efficiently.

# Summary. An optional shortened abstract.
summary: We propose a multi-objective optimization framework for fairness-aware recommendation, Multi-FR, that adaptively balances accuracy and fairness for various stakeholders with Pareto optimality guarantee.

tags: [ Fairness, Multi-stakeholder, Recommendation, Pareto Optimal ]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2105.02951.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

  # Featured image
  # To use, add an image named `featured.jpg/png` to your page's folder. 




# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - p2022_TOIS_MultiFR

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
