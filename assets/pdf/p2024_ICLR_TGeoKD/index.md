---
title: "Less or More From Teacher: Exploiting Trilateral Geometry For Knowledge Distillation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin$^*$
  - Chengming Hu$^*$
  - Xuan Li
  - Chen Ma
  - Xi Chen
  - Jun Yan
  - Boyu Wang
  - Xue Liu


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-01-16"
# doi: "10.1145/3477495.3532007"

# Schedule page publish date (NOT publication's date).

publishDate: "2024-01-16"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ "2" ]

# Publication name and optional abbreviated publication name.
publication: In *ICLR 2024*
publication_short: In *ICLR 2024*

abstract: Knowledge distillation aims to train a compact student network using soft supervision from a larger teacher network and hard supervision from ground truths. However, determining an optimal knowledge fusion ratio that balances these supervisory signals remains challenging. Prior methods generally resort to a constant or heuristic-based fusion ratio, which often falls short of a proper balance. In this study, we introduce a novel adaptive method for learning a sample-wise knowledge fusion ratio, exploiting both the correctness of teacher and student, as well as how well the student mimics the teacher on each sample. Our method naturally leads to the intra-sample trilateral geometric relations among the student prediction (S), teacher prediction (T), and ground truth (G). To counterbalance the impact of outliers, we further extend to the inter-sample relations, incorporating the teacher’s global average prediction (T¯) for samples within the same class. A simple neural network then learns the implicit mapping from the intra- and inter-sample relations to an adaptive, sample-wise knowledge fusion ratio in a bilevel-optimization manner. Our approach provides a simple, practical, and adaptable solution for knowledge distillation that can be employed across various architectures and model sizes. Extensive experiments demonstrate consistent improvements over other loss re-weighting methods on image classification, attack detection, and click-through rate prediction.
# Summary. An optional shortened abstract.
summary: We propose a simple and effective approach on improving the sample-wise knowledge fusion tradeoff in knowledge distillation through capturing the intra-sample and inter-sample trilateral relations among <teacher, student, ground truth>.

tags: [ Knowledge Distillation, Sample Re-weighting ]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2312.15112.pdf'
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
  - p2024_ICLR_TGeoKD

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
