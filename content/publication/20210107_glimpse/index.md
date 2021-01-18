---
title: "Efficient phasing and imputation of low-coverage sequencing data using large reference panels"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Diogo M. Ribeiro
- Robin J. Hofmeister
- Olivier Delaneau

# Author notes (optional)
author_notes: ""

date: "2021-01-17T00:00:00Z"
doi: "10.1038/s41588-020-00756-0"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Nature Genetics*
publication_short: In *Nature Genetics*

abstract: Low-coverage whole-genome sequencing followed by imputation has been proposed as a cost-effective genotyping approach for disease and population genetics studies. However, its competitiveness against SNP arrays is undermined because current imputation methods are computationally expensive and unable to leverage large reference panels. Here, we describe a method, GLIMPSE, for phasing and imputation of low-coverage sequencing datasets from modern reference panels. We demonstrate its remarkable performance across different coverages and human populations. GLIMPSE achieves imputation of a genome for less than US$1 in computational cost, considerably outperforming other methods and improving imputation accuracy over the full allele frequency range. As a proof of concept, we show that 1× coverage enables effective gene expression association studies and outperforms dense SNP arrays in rare variant burden tests. Overall, this study illustrates the promising potential of low-coverage imputation and suggests a paradigm shift in the design of future genomic studies.

# Summary. An optional shortened abstract.
summary: In this work, we address the challenge of genotype imputation and haplotype phasing of low-coverage sequencing datasets using a reference panel of haplotypes. To this aim, we propose a novel method, GLIMPSE (Genotype Likelihoods Imputation and PhaSing mEthod), that is designed for large-scale studies and reference panels, typically comprising thousands of genomes. We show the remarkable performance of GLIMPSE using low-coverage whole genome sequencing data for both European and African American populations, and we demonstrate that low-coverage sequencing can be confidently used in downstream analyses. We provide GLIMPSE as a part of an open source software suite that makes imputation for low-coverage sequencing data as convenient as for traditional SNP array platforms.

tags: 
- Statistical Genomics
- low-coverage
- imputation
- phasing

categories:
- Genetics

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.nature.com/articles/s41588-020-00756-0.pdf'
url_code: 'https://github.com/odelaneau/GLIMPSE'
url_dataset: ''
url_poster: ''
url_project: 'https://odelaneau.github.io/GLIMPSE/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**GLIMPSE**](https://odelaneau.github.io/GLIMPSE)'
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- Statistical Genetics

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the *Cite* button above to import publication metadata into your reference management software.
{{% /callout %}}
