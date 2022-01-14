+++
# Date this page was created.
date = "2022-01-14"

# Project title.
title = "ExpressScan: plaque analysis through high-throughput imaging"

# Project summary to display on homepage.
summary = "Applying machine-learning for the analysis of pathological slides."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "images/slides_shutterstock_114197461_squared.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["high-throughput-imaging", "slideToolKit", "CellProfiler", "machine-learning", "deep-learning", "ExpressScan", "whole-slide imaging"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/slides_shutterstock_114197461_broad.png"
caption = "Image credit: [**Pan Xunbin**](https://www.shutterstock.com/g/defun)"

+++

Since the start of the [Athero-Express Biobank Study](http://www.atheroexpress.nl) in 2002 we have collected atherosclerotic plaque samples of over 3,500 patients. Each of these samples have been stained for various plaque characteristics, including smooth muscle cells based on smooth-muscle cell actin (*SMA*), macrophages based on *CD68*, intraplaque hemorrhage, and intraplaque microvessels based on *CD34* among others. </br></br>The community standard is to analyze histological slides manually, with the downside of inter- and intra-observer variability leading to a "noisy" phenotype. To improve on this we have recently started to scan all slides (some 35,000!) at high-resolution using standard pathology scanners, alongside we have developed **slideToolkit** ([Nelissen BGL et al. PLoS One 2014 | PMID: 25372389](https://www.ncbi.nlm.nih.gov/pubmed/25372389) and our [GitHub-page](https://github.com/swvanderlaan/slideToolkit)) to process the large image files efficiently on a high-performance computer cluster. After checking, renaming (if needed), and masking non-tissue material, **slideToolkit** parses the images into tiles which accommodates parallel analyses on the HPC; these analyses are carried out using [CellProfiler (developed by the BROAD Institute)](http://www.cellprofiler.org) which is reliant on standardized protocols based on training datasets. </br>This has proven to result in highly reproducible data ([Nelissen et al. PLoS One 2014 | PMID: 25541691](https://www.ncbi.nlm.nih.gov/pubmed/25541691)). Preliminary genetic analyses have also exceeded our expectations, as we are entering the final stages of scanning. A first milestone is the [recent preprint](post/a-story-about-expressscan/index.md) reporting on the observational analyses, but there is more to come! 

