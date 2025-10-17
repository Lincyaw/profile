---
title: "An Empirical Study of SOTA RCA Models: From Oversimplified Benchmarks to Realistic Failures"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Aoyang Fang
  - Songhan Zhang
  - Yifan Yang
  - Haotong Wu
  - Junjielong Xu
  - Xuyang Wang
  - Rui Wang
  - Manyi Wang
  - Qisheng Lu
  - Pinjia He

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: "2025-08-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Arxiv

abstract: "While cloud-native microservice architectures have transformed software development, their complexity makes Root Cause Analysis (RCA) both crucial and challenging. Although many data-driven RCA models have been proposed, we find that existing benchmarks are often oversimplified and fail to capture real-world conditions. Our preliminary study shows that simple rule-based methods can match or even outperform state-of-the-art (SOTA) models on four widely used benchmarks, suggesting performance overestimation due to benchmark simplicity. To address this, we systematically analyze popular RCA benchmarks and identify key limitations in fault injection, call graph design, and telemetry patterns. Based on these insights, we develop an automated framework to generate more realistic benchmarks, yielding a dataset of 1,430 validated failure cases from 9,152 injections, covering 25 fault types under dynamic workloads with hierarchical ground-truth labels and verified SLI impact. Re-evaluation of 11 SOTA models on this dataset shows low Top@1 accuracy (average 0.21, best 0.37) and significantly longer execution times. Our analysis highlights three common failure patterns: scalability issues, observability blind spots, and modeling bottlenecks."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - study
  - root cause analysis

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ""
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

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
