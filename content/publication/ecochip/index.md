---
title: 'ECO-CHIP: Estimation of Carbon Footprint of Chiplet-based Architectures for Sustainable VLSI'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Nikhil Matkar
  - Sarma Vrudhula
  - Sachin S. Sapatnekar
  - Vidya A. Chhabria

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-03-06T00:00:00Z'
doi: '10.1109/HPCA57654.2024.00058'

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *HPCA 2024*
publication_short: In *HPCA'24*

abstract: Decades of progress in energy-efficient and low-power design have successfully reduced the operational carbon footprint in the semiconductor industry. However, this has led to increased embodied emissions, arising from design, manufacturing, and packaging. While existing research has developed tools to analyze embodied carbon for traditional monolithic systems, these tools do not apply to near-mainstream heterogeneous integration (HI) technologies. HI systems offer significant potential for sustainable computing by minimizing carbon emissions through two key strategies “reducing” computation by “reusing” pre-designed chiplet IP blocks and adopting hierarchical approaches to system design. The reuse of chiplets across multiple designs, even spanning multiple generations of ICs, can substantially reduce carbon emissions throughout the lifespan. This paper introduces ECO-CHIP, a carbon analysis tool designed to assess the potential of HI systems toward sustainable computing by considering scaling, chip let, and packaging yields, design complexity, and even overheads associated with advanced packaging techniques. Experimental results from ECO-CHIP demonstrate that HI can reduce embodied carbon emissions by up to 30% compared to traditional monolithic systems. ECO-CHIP is integrated with other chiplet simulators and is applied to chiplet disaggregation considering other metrics such as power, area, and cost. ECO-CHIP suggests that HI can pave the way for sustainable computing practices.

# Summary. An optional shortened abstract.
summary: Carbon footprint estimator for heterogenous chiplet-based systems. ECO-CHIP is an analysis tool that analyzes the operational and embodied CFP (design, manufacturing, and packaging). The tool supports the following HI and packaging architectures- RDL fanout, silicon bridge-based, passive and active interposer, and 3D integration. The tool evaluates the crucial package/assembly carbon emissions essential for HI systems, considering size, yield, and assembly process. In addition, it also estimates design CFP.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2306.09434'
url_code: 'https://github.com/ASU-VDA-Lab/ECO-CHIP'
url_dataset: ''
url_poster: 'publication/ecochip/ecochip_poster.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'ECO-CHIP'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#C projects:
#C   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#C slides: example
---
