---
title: "Reinforcement learning for mutation operator selection in automated program repair"
authors:
- Carol Hanna
- Aymeric Blot
- Justyna Petke

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# date: "2015-09-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-25"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In Automated Software Engineering Journal.
# publication_short: ""

abstract: Automated program repair techniques aim to aid software developers with the challenging task of fixing bugs. In heuristic-based program repair, a search space of mutated program variants is explored to find potential patches for bugs. Most commonly, every selection of a mutation operator during search is performed uniformly at random, which can generate many buggy, even uncompilable programs. Our goal is to reduce the generation of variants that do not compile or break intended functionality which waste considerable resources. In this paper, we investigate the feasibility of a reinforcement learning-based approach for the selection of mutation operators in heuristic-based program repair. Our proposed approach is programming language, granularity-level, and search strategy agnostic and allows for easy augmentation into existing heuristic-based repair tools. We conducted an extensive empirical evaluation of four operator selection techniques, two reward types, two credit assignment strategies, two integration methods, and three sets of mutation operators using 30,080 independent repair attempts. We evaluated our approach on 353 real-world bugs from the Defects4J benchmark. The reinforcement learning-based mutation operator selection results in a higher number of test-passing variants, but does not exhibit a noticeable improvement in the number of bugs patched in comparison with the baseline, uniform random selection. While reinforcement learning has been previously shown to be successful in improving the search of evolutionary algorithms, often used in heuristic-based program repair, it has yet to demonstrate such improvements when applied to this area of research.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Reinforcement Learning
- Genetic Improvement
- Automated Program Repair

featured: false

hugoblox:
  # ids:
  #   arxiv: 1512.04133v1

links:
  - type: Paper
    url: https://link.springer.com/article/10.1007/s10515-025-00501-z
  # - type: code
  #   url: https://github.com/HugoBlox/kit
  # - type: dataset
  #   url: ""
  # - type: poster
  #   url: ""
  # - type: project
  #   url: ""
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: ""
  # - type: video
  #   url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
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
<!-- 
> [!NOTE]
> Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
