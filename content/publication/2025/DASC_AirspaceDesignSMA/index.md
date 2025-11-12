---
published: true
title: 'Bio-inspired Algorithm for Designing an AdaptiveCyclic Corridor for UAS Traffic Management'
authors:
  - Matthieu_Verdoucq
  - Rodolphe_Fremond
  - Zeynep_Bilgin
  - admin
date: '2025-09-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-09-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In 44$^th$ Digital Avionics Systems Conference, 2025
publication_short: In DASC 2025

abstract: This paper presents a novel bio-inspired methodfor designing cyclic airspace   corridors   to   support   high-throughput, bidirectional flows of Unmanned Aircraft Systemsat  Very  Low  Level.  We  adapt  the  Slime-Mold  Algorithm  togenerate  corridors  by  modeling  vertiports  as  attractors,  no-fly  zones  as  repulsors,  and  using  a  discretized  pheromonefield  to  guide  agent  behavior.  Agents  operate  in  three  roles:explorers,  exploiters,  and  trail-thickeners,  and  interact  solelyvia pheromone diffusion and decay. A food timer mechanismregulates  exploration  based  on  the  average  spacing  betweenvertiports.   From   the   resulting   pheromone   distribution,   aCatmull–Rom spline is fitted to extract a smooth, continuouscorridor. The design is evaluated using five criteria; vertiportproximity,  no-fly  zone  avoidance,  self-intersection,  curvaturesmoothness,  and  total  length.  We  evaluate  our  approach  onthree  large-scale  urban  scenarios  with  up  to  15  vertiportsand  10  no-fly  zones.  Results  show  convergence  within  200iterations,  rapid  adaptation  to  topological  changes,  and  thepotential to support more complex corridor structures givingpromises  to  the  method’s  suitability  for  real-time,  dynamicairspace  design  in  UAS  traffic  management.

# Summary. An optional shortened abstract.
summary: Airspace Design using Slime-Mold Algorithm.

tags:
  - Airspace Design
  - Cyclic Corridor
  - Slime-Mold Algorithm
  - Urban Air Mobility
  - UTM

featured: true

links:
  # - name: Custom Link
  #   url: '#'
url_pdf: '/publication/2025/DASC_AirspaceDesignSMA/SMA_4_Designing_Adaptive_C3_4_UTM.pdf'
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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
slides: '/publication/2025/DASC_AirspaceDesignSMA/DASC_SMA_presentation.pdf'
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
