---
title: 'NeuroFilter: Privacy Guardrails for Conversational LLM Agents'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ferdinando Fioretto (UVA)

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2026-01-15T07:00:00Z'
# doi: 'https://doi.org/10.48550/arXiv.2301.12204'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-15T07:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: Under Review (Preprint at arXiv:2601.14660)
publication_short: arXiv:2601.14660

abstract: Agentic Large Language Models (LLMs) are models able to reason, plan, and execute tools over unstructured data. These abilities are enabling transformative applications in domains spanning from personal assistant, financial, and legal domains. While these systems can substantially improve productivity and service quality, effective agency typically requires access to sensitive personal or organizational information. However, this access introduces critical inference-time privacy risks, specifically regarding contextually appropriate information disclosure. While recent studies highlight the inability of agentic LLMs to consistently adhere to privacy norms, existing defenses often rely on auxiliary LLM-based monitors. However, these defenses are expensive and offer limited protection against attacks that are robust to semantic censorship. To contrast this background, this paper proposes a notion of privacy filters based on activation probing. We show that these filters are both computationally efficient and effective for both single-turn and multi-turn conversational settings. Furthermore, this work provides the first systematic investigation into probing model internals across a conversation trajectory, moving beyond static, single-prompt analysis to capture the evolving state of privacy-sensitive interactions.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://arxiv.org/pdf/2601.14660'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

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
