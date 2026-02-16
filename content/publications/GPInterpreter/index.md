---
title: 'Improving a Parallel C++ Intel AVX-512 SIMD Linear Genetic Programming Interpreter'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - William B Langdon
  - Carol Hanna


# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-01-01'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-01'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In International Workshop on Genetic Improvement@ ICSE
# publication_short: In International Workshop on Genetic Improvement@ ICSE

abstract: We use evolution to speedup the Single Instruction Multiple Data (SIMD) parallel interpreter for Peter Nordin’s linear genetic programming GPengine. MAGPIE (Machine Automated General Performance Improvement via Evolution of software) is provided with existing hand-optimised source code, its revision history and the Intel 256 bit SSE intrinsics documentation as XML. Fitness is measured via perf’s hardware instruction count, while validity and safety are enforced through systematic test cases and memory sandbox protection via Linux mprotect. In a matter of hours local search discovered small, non-obvious program modifications that improve the performance of 128 lines of SIMD C++ code by 2%, without sacrificing correctness. We see genetic improvement can effectively exploit Intel Advanced Vector Extensions (AVX) parallelism, automatically refining complex code that is difficult for human developers to optimise reliably.

tags:
  - Genetic Improvement
  - Evolutionary Computation

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
    url: "https://solar.cs.ucl.ac.uk/pdf/langdon_2026_GI.pdf"
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
