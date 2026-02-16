---
title: 'Large language model based mutations in genetic improvement'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Alexander E. I. Brownlee
  - James Callan
  - Karine Even-Mendoza
  - Alina Geiger
  - Carol Hanna
  - Justyna Petke
  - Federica Sarro
  - Dominik Sobania 

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2023-12-10'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-21'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Automated Software Engineering Journal
# publication_short: In International symposium on search based software engineering

abstract: Ever since the first large language models (LLMs) have become available, both academics and practitioners have used them to aid software engineering tasks. However, little research as yet has been done in combining search-based software engineering (SBSE) and LLMs. In this paper, we evaluate the use of LLMs as mutation operators for genetic improvement (GI), an SBSE approach, to improve the GI search process. In a preliminary work, we explored the feasibility of combining the Gin Java GI toolkit with OpenAI LLMs in order to generate an edit for the JCodec tool. Here we extend this investigation involving three LLMs and three types of prompt, and five real-world software projects. We sample the edits at random, as well as using local search. We also conducted a qualitative analysis to understand why LLM-generated code edits break as part of our evaluation. Our results show that, compared with conventional statement GI edits, LLMs produce fewer unique edits, but these compile and pass tests more often, with the OpenAI model finding test-passing edits 77% of the time. The OpenAI and Mistral LLMs are roughly equal in finding the best run-time improvements. Simpler prompts are more successful than those providing more context and examples. The qualitative analysis reveals a wide variety of areas where LLMs typically fail to produce valid edits commonly including inconsistent formatting, generating non-Java syntax, or refusing to provide a solution.  

tags:
  - Large Langage Models
  - Genetic Improvement

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  # ids:
  #   doi: 10.5555/123456

# Custom links
links:
  - type: paper
    label: Paper
    url: "https://link.springer.com/article/10.1007/s10515-024-00473-6"
  # - type: code
  #   url: https://github.com/HugoBlox/kit
  # - type: dataset
  #   url: https://github.com/HugoBlox/kit
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/kit
  # - type: video
  #   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
