---
title: "Joint Multisided Exposure Fairness for Recommendation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Bhaskar Mitra
- Chen Ma
- Fernando Diaz
- Xue Liu

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-04-01"
doi: "10.1145/3477495.3532007"

# Schedule page publish date (NOT publication's date).

publishDate: "2022-04-01"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval*
publication_short: In *SIGIR 2022*

abstract: Prior research on exposure fairness in the context of recommender systems has focused mostly on disparities in the exposure of individual or groups of items to individual users of the system. The problem of how individual or groups of items may be systemically under or over exposed to groups of users, or even all users, has received relatively less attention. However, such systemic disparities in information exposure can result in observable social harms, such as withholding economic opportunities from historically marginalized groups *allocative harm* or amplifying gendered and racialized stereotypes *representational harm*. Previously, Diaz et al. developed the *expected exposure* metric---that incorporates existing user browsing models that have previously been developed for information retrieval---to study fairness of content exposure to individual users. We extend their proposed framework to formalize a family of exposure fairness metrics that model the problem jointly from the perspective of both the consumers and producers. Specifically, we consider group attributes for both types of stakeholders to identify and mitigate fairness concerns that go beyond individual users and items towards more systemic biases in recommendation. Furthermore, we study and discuss the relationships between the different exposure fairness dimensions proposed in this paper, as well as demonstrate how stochastic ranking policies can be optimized towards said fairness goals.

# Summary. An optional shortened abstract.
summary: Prior works on fairness in recommendation mostly only mode the fairness of different stakeholders seperately. In our work, we first model the interactional behavoir between the consumer side and the producer side. We care not only whether the content is over/under exposed but also to whom and in what context.

tags: [Fairness, Multisided, Recommendation, Metric Analysis]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2205.00048.pdf'
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
- p2022_SIGIR_JMEFair

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
