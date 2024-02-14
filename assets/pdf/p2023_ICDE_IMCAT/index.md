---
title: "Intent-aware Multi-source Contrastive Alignment for Tag-enhanced Recommendation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yingxue Zhang
- Chen Ma
- Wei Guo
- Ruiming Tang
- Xue Liu
- Mark Coates

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-03-01"

# Schedule page publish date (NOT publication's date).

publishDate: "2023-03-01"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *the 39th IEEE International Conference on Data Engineering*
publication_short: In *ICDE 2023*

abstract: To offer accurate and diverse recommendation services, recent methods use auxiliary information to foster the learning process of user and item representations. Many stateof-the-art (SOTA) methods fuse different sources of information (user, item, knowledge graph, tags, etc.) into a graph and use Graph Neural Networks (GNNs) to introduce the auxiliary information through the message passing paradigm. In this work, we seek an alternative framework that is light and effective through self-supervised learning across different sources of information, particularly for the commonly accessible item tag information. We use a self-supervision signal to pair users with the auxiliary information (tags) associated with the items they have interacted with before. To achieve the pairing, we create a proxy training task. For a given item, the model predicts which is the correct pairing between the representations obtained from the users that have interacted with this item and the tags assigned to it. This design provides an efficient solution, using the auxiliary information directly to enhance the quality of user and item embeddings. User behavior in recommendation systems is driven by the complex interactions of many factors behind the users’ decision-making processes. To make the pairing process more fine-grained and avoid embedding collapse, we propose a user intent-aware self-supervised pairing process where we split the user embeddings into multiple sub-embedding vectors. Each sub-embedding vector captures a specific user intent via self-supervised alignment with a particular cluster of tags. We integrate our designed framework with various recommendation models, demonstrating its flexibility and compatibility. Through comparison with numerous SOTA methods on seven real-world datasets, we show that our method can achieve better performance while requiring less training time. This indicates the potential of applying our approach on web-scale datasets.

# Summary. An optional shortened abstract.
summary: In this work, we seek a framework that is light and effective through self-supervised learning across different sources of information, particularly for the commonly accessible item tag information, to offer accurate recommendations. We construct a self-supervision signal to better fuse the multi-source information. We further extend it as an intent-aware self-supervised pairing process to distinguish different user interests behind the users’ decision-making processes.

tags: [Multi-interest, Recommendation, Contrastive Learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2211.06370.pdf'
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
- p2023_ICDE_IMCAT

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
