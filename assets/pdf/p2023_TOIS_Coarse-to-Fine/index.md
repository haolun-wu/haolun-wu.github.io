---
title: "Coarse-to-Fine Knowledge-Enhanced Multi-Interest Learning Framework for Multi-Behavior Recommendation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chang Meng
  - Ziqi Zhao
  - Wei Guo
  - Yingxue Zhang
  - admin
  - Chen Gao
  - Dong Li
  - Xiu Li
  - Ruiming Tang


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-06-26"
# doi: "10.1145/3477495.3532007"

# Schedule page publish date (NOT publication's date).

publishDate: "2023-06-26"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [ "2" ]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Information Systems*
publication_short: In *TOIS 2023*

abstract: Multi-types of behaviors (e.g., clicking, adding to cart, purchasing, etc.) widely exist in most real-world recommendation scenarios, which are beneficial to learn users’ multi-faceted preferences. As dependencies are explicitly exhibited by the multiple types of behaviors, effectively modeling complex behavior dependencies is crucial for multi-behavior prediction. The state-of-the-art multibehavior models learn behavior dependencies indistinguishably with all historical interactions as input. However, different behaviors may reflect different aspects of user preference, which means that some irrelevant interactions may play as noises to the target behavior to be predicted. To address the aforementioned limitations, we introduce multi-interest learning to the multi-behavior recommendation. More specifically, we propose a novel Coarse-to-fine Knowledge-enhanced Multi-interest Learning (CKML) framework to learn shared and behavior-specific interests for different behaviors. CKML introduces two advanced modules, namely Coarsegrained Interest Extracting (CIE) and Fine-grained Behavioral Correlation (FBC), which work jointly to capture fine-grained behavioral dependencies. CIE uses knowledge-aware information to extract initial representations of each interest. FBC incorporates a dynamic routing scheme to further assign each behavior among interests. Additionally, we use the self-attention mechanism to correlate different behavioral information at the interest level. Empirical results on three real-world datasets verify the effectiveness and efficiency of our model in exploiting multi-behavior data. Further experiments demonstrate the effectiveness of each module and the robustness and superiority of the shared and specific modelling paradigm for multi-behavior data.

# Summary. An optional shortened abstract.
summary: We propose a method to model users' multi-interets leanring from their multi-behavior.

tags: [ Recommendation, Knowledge-enhanced, Multi-interest ]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2208.01849.pdf'
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
  - p2023_TOIS_Coarse-to-Fine

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
