---
title: 'Psycholinguistic Tripartite Graph Network for Personality Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Feifan Yang
  - Haolan Ouyang
  - Xiaojun Quan

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-08-01T00:00:00Z'
doi: '10.18653/v1/2021.acl-long.326'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
# publication: In *Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing*
publication_short: In ***ACL 2021***, Main Conference, Pages 4229–4239, 2021

abstract: 'Most of the recent work on personality detection from online posts adopts multifarious deep neural networks to represent the posts and builds predictive models in a data-driven manner, without the exploitation of psycholinguistic knowledge that may unveil the connections between one’s language use and his psychological traits. In this paper, we propose a psycholinguistic knowledge-based tripartite graph network, TrigNet, which consists of a tripartite graph network and a BERT-based graph initializer. The graph network injects structural psycholinguistic knowledge in LIWC, a computerized instrument for psycholinguistic analysis, by constructing a heterogeneous tripartite graph. The initializer is employed to provide initial embeddings for the graph nodes. To reduce the computational cost in graph learning, we further propose a novel flow graph attention network (GAT) that only transmits messages between neighboring parties in the tripartite graph. Benefiting from the tripartite graph, TrigNet can aggregate post information from a psychological perspective, which is a novel way of exploiting domain knowledge. Extensive experiments on two datasets show that TrigNet outperforms the existing state-of-art model by 3.47 and 2.10 points in average F1. Moreover, the flow GAT reduces the FLOPS and Memory measures by 38% and 32%, respectively, in comparison to the original GAT in our setting.'

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
  links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
  url_code: 'https://github.com/TaoYang225/TrigNet'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
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
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). --> 