---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Auxiliary Task Reweighting for Minimum-data Learning"
authors: ["**Baifeng Shi**", Judy Hoffman, Kate Saenko, Trevor Darrell, Huijuan Xu]
date: 2020-08-11T12:41:37+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-11T12:41:37+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Conference on Neural Information Processing Systems (**NeurIPS 2020**)"
publication_short: "*Conference on Neural Information Processing Systems* (**NeurIPS 2020**)"

abstract: "Auxiliary tasks are widely used to address the lack of data by providing additional supervision in **semi/self-supervised learning, transfer learning, reinforcement learning**, *etc*. Assigning the **importance weights** for different auxiliary tasks
remains a crucial, and largely understudied, research question. In this work, we formulate the problem as minimizing the **information required** to learn the main task. With the key insight that *information required for inference can be reduced by a good prior*, we propose an algorithm to automatically reweight auxiliary tasks so that the **surrogate prior** given by the weighted likelihood of auxiliary tasks is optimized. We further reduce the optimization problem into **minimizing the $l^2$ distance** between main/auxliary task gradients by adopting tools including **Langevin dynamics, Fisher divergence**, *etc*. Our algorithm finds the optimal weights and minimizes the required data under various settings, as supported by both **theoretical guarantees and experimental observations**."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2010.08244
url_code: https://github.com/bfshi/ARML_Auxiliary_Task_Reweighting
url_dataset:
url_poster:
url_project: https://sites.google.com/view/auxiliary-task-reweighting/home
url_slides: https://drive.google.com/file/d/1UiNHBztUVJbhvDJTmFww7v4ZPSdXD4DM/view
url_source:
url_video: https://www.youtube.com/watch?v=B2i6z6HefGw

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
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
