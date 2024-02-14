---
title: "Adapting Triplet Importance of Implicit Feedback for Personalized Recommendation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Chen Ma
- Yingxue Zhang
- Xue Liu
- Ruiming Tang
- Mark Coates

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
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *the 31st ACM International Conference on Information and Knowledge Management*
publication_short: In *CIKM 2022*

abstract: Implicit feedback is frequently used for developing personalized recommendation services due to its ubiquity and accessibility in real-world systems. In order to effectively utilize such information, most research adopts the pairwise ranking method on constructed training triplets $\langle$\textit{user, positive item, negative item}$\rangle$ and aims to distinguish between positive items and negative items for each user. However, most of these methods treat all the training triplets equally, which ignores the subtle difference between different positive or negative items. On the other hand, even though some other works make use of the auxiliary information (e.g., dwell time) of user behaviors to capture this subtle difference, such auxiliary information is hard to obtain. To mitigate the aforementioned problems, we propose a novel training framework named Triplet Importance Learning (TIL), which adaptively learns the importance score of training triplets. We devise two strategies for the importance score generation and formulate the whole procedure as a bilevel optimization, which does not require any rule-based design. We integrate the proposed training procedure with several Matrix Factorization (MF)- and Graph Neural Network (GNN)-based recommendation models, demonstrating the compatibility of our framework. Via a comparison using three real-world datasets with many state-of-the-art methods, we show that our proposed method outperforms the best existing models by 3-21\% in terms of Recall@k for the top-$k$ recommendation. 

# Summary. An optional shortened abstract.
summary: We propose a novel training framework named Triplet Importance Learning (TIL), which adaptively learns the importance score of training triplets. We devise two strategies for the importance score generation and formulate the whole procedure as a bilevel optimization, which does not require any rule-based design.

tags: [Data Importance, Recommendation, Implicit Feedback, Bilevel Optimization]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2208.01709.pdf'
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
- p2022_CIKM_TIL

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
