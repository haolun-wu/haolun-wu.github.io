---
title: "Teacher-Student Architecture for Knowledge Distillation: A Survey"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Chengming Hu
- Xuan Li
- Dan Liu
- admin
- Xi Chen
- Ju Wang
- Xue Liu


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-08-08"
# doi: "10.1145/3477495.3532007"

# Schedule page publish date (NOT publication's date).

publishDate: "2023-08-08"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ "2" ]

# Publication name and optional abbreviated publication name.
publication: In *arXiv e-print 2308.04268*
publication_short: In *arXiv 2023*

abstract: Although Deep neural networks (DNNs) have shown a strong capacity to solve large-scale problems in many areas, such DNNs are hard to be deployed in real-world systems due to their voluminous parameters. To tackle this issue, Teacher-Student architectures were proposed, where simple student networks with a few parameters can achieve comparable performance to deep teacher networks with many parameters. Recently, Teacher-Student architectures have been effectively and widely embraced on various knowledge distillation (KD) objectives, including knowledge compression, knowledge expansion, knowledge adaptation, and knowledge enhancement. With the help of Teacher-Student architectures, current studies are able to achieve multiple distillation objectives through lightweight and generalized student networks. Different from existing KD surveys that primarily focus on knowledge compression, this survey first explores Teacher-Student architectures across multiple distillation objectives. This survey presents an introduction to various knowledge representations and their corresponding optimization objectives. Additionally, we provide a systematic overview of Teacher-Student architectures with representative learning algorithms and effective distillation schemes. This survey also summarizes recent applications of Teacher-Student architectures across multiple purposes, including classification, recognition, generation, ranking, and regression. Lastly, potential research directions in KD are investigated, focusing on architecture design, knowledge quality, and theoretical studies of regression-based learning, respectively. Through this comprehensive survey, industry practitioners and the academic community can gain valuable insights and guidelines for effectively designing, learning, and applying Teacher-Student architectures on various distillation objectives.

# Summary. An optional shortened abstract.
summary: We propose a method to model users' multi-interets leanring from their multi-behavior.

tags: [ Knowledge Distillation, DNN ]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2308.04268.pdf'
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
  - p2023_KD_Survey

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
