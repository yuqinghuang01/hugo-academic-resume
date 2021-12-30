---
title: "Accurate Summary-based Cardinality Estimation Through the Lens of Cardinality Estimation Graphs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jeremy Chen
- Yuqing Huang
- Mushi Wang
- Semih Salihoglu
- Ken Salem

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-05-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication:
publication_short:

abstract: We study two classes of summary-based cardinality estimators that use statistics about input relations and small-size joins in the context of graph database management systems: (i) optimistic estimators that make uniformity and conditional independence assumptions; and (ii) the recent pessimistic estimators that use information theoretic linear programs. We begin by addressing the problem of how to make accurate estimates for optimistic estimators. We model these estimators as picking bottom-to-top paths in a cardinality estimation graph (CEG), which contains sub-queries as nodes and weighted edges between sub-queries that represent average degrees. We outline a space of heuristics to make an optimistic estimate in this framework and show that effective heuristics depend on the structure of the input queries. We observe that on acyclic queries and queries with small-size cycles, using the maximum-weight path is an effective technique to address the well known underestimation problem for optimistic estimators. We show that on a large suite of datasets and workloads, the accuracy of such estimates is up to three orders of magnitude more accurate in mean q-error than some prior heuristics that have been proposed in prior work. In contrast, we show that on queries with larger cycles these estimators tend to overestimate, which can partially be addressed by using minimum weight paths and more effectively by using an alternative CEG. We then show that CEGs can also model the recent pessimistic estimators. This surprising result allows us to connect two disparate lines of work on optimistic and pessimistic estimators, adopt an optimization from pessimistic estimators to optimistic ones, and provide insights into the pessimistic estimators, such as showing that there are alternative combinatorial solutions to the linear programs that define them.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
