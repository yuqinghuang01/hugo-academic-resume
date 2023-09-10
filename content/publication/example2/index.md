---
title: "Advanced Surgical Planning - Implant Recognition"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Sarper Ertekin
- Orhun Görkem
- Yuqing Huang
- Laura Roduner

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-06-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication:
publication_short:

abstract: This paper originates from a student project in cooperation with ETH Zurich and CustomSurg and aims to support surgeons during complex bone fracture surgeries using HoloLens to detect, track and label implants. Modern technology contributes massively to 3D Vision. Therefore, deploying Microsoft HoloLens in surgeries is not far-fetched, although relatively novel. There are many possible applications, while CustomSurg provided us with the opportunity to detect their custom implants and set the groundwork for HoloLens application in surgery, which we approached with off-device computation. YOLOv5 deployed on a server communicates bidirectionally with HoloLens to send a captured image via TCP to the server, which processes the image and sends back information regarding the implant's bounding box and the label. Bounding boxes were obtained using HoloLens spatial mapping and several coordinate transformations. Our model is trained on synthetic data generated in Unity and yields almost perfect results on synthetic images while slightly less accurate for real images due to domain gaps. This problem was addressed and tackled by manually adjusting the training data. Finally, Vuforia is used to compare our model to market solutions. It is also used to additionally track handheld implants which is not yet included in our data set but lacks robustness to sudden movements of the target object.

# Summary. An optional shortened abstract.
summary: This project results from ETH’s and CustomSurg’s joint interest and collaboration in terms of 3D Vision with HoloLens and is realized over a span of 3 months as part of the lecture 3D Vision. In the framework of this project we focus on choosing the correct implant, by recoginizing it in HoloLens, tracing it, detecting the implant’s type and rendering said type with the implant’s bounding box in HoloLens. This way, surgeons can visually confirm that the present implant is truly the implant chosen for a particular surgery.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
- name: PDF
    url: 'uploads/cil_report.pdf'

url_pdf: ''
url_code: 'https://github.com/sarpermelikertekin/3dv-project-advanced-surgical-planning-implant-recognition'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: CustomSurg'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
