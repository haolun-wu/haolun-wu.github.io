---
title: "Knowledge-Enhanced Top-K Recommendation in Poincare Ball"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Chen Ma
- Liheng Ma
- Yingxue Zhang
- admin
- Mark Coates
- Xue Liu

# Author notes (optional)



date: "2021-10-01"
doi: ""

# Schedule page publish date (NOT publication's date).

publishDate: "2021-10-01"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *the 35th AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI 2021*

abstract: Personalized recommender systems are increasingly important as more content and services become available and users struggle to identify what might interest them. Thanks to the ability for providing rich information, knowledge graphs (KGs) are being incorporated to enhance the recommendation performance and interpretability. To effectively make use of the knowledge graph, we propose a recommendation model in the hyperbolic space, which facilitates the learning of the hierarchical structure of knowledge graphs. Furthermore, a hyperbolic attention network is employed to determine the relative importances of neighboring entities of a certain item. In addition, we propose an adaptive and finegrained regularization mechanism to adaptively regularize items and their neighboring representations. Via a comparison using three real-world datasets with stateof-the-art methods, we show that the proposed model outperforms the best existing models by 2-16% in terms of NDCG@K on Top-K recommendation.

# Summary. An optional shortened abstract.
summary: To model the hierarchical structure of KG, we map the entity and relation embeddings of the KG into the Poincare ball along with user and item embeddings. To the best of our knowledge, ours is the first work to consider knowledge-enhanced recommendation in the hyperbolic space.

tags: [Knowledge-enhanced, Recommendation, Hyperbolic Space]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.aaai.org/AAAI21Papers/AAAI-5365.MaC.pdf'
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
- p2021_AAAI_HyperKnow

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
