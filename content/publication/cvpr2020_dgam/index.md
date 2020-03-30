---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Weakly-Supervised Action Localization by Generative Attention Modeling"
authors: ["**Baifeng Shi**", Qi Dai, Yadong Mu, Jingdong Wang]
date: 2020-02-24T18:04:39+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-24T18:04:39+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Conference on Computer Vision and Pattern Recognition"
publication_short: "*IEEE Conference on Computer Vision and Pattern Recognition* (**CVPR 2020**)"

abstract: "Weakly-supervised temporal action localization is a problem of learning an
action localization model with only video-level action labeling available. The
general framework largely relies on the classification activation, which
employs an attention model to identify the action-related frames and then
categorizes them into different classes. Such method results in the
action-context confusion issue: context frames near action clips tend to be
recognized as action frames themselves, since they are closely related to the
specific classes. To solve the problem, in this paper we propose to model the
class-agnostic frame-wise probability conditioned on the frame attention using
conditional Variational Auto-Encoder (VAE). With the observation that the
context exhibits notable difference from the action at representation level, a
probabilistic model, i.e., conditional VAE, is learned to model the likelihood
of each frame given the attention. By maximizing the conditional probability
with respect to the attention, the action and non-action frames are well
separated. Experiments on THUMOS14 and ActivityNet1.2 demonstrate advantage of
our method and effectiveness in handling action-context confusion problem. Code
is now available on GitHub."

# Summary. An optional shortened abstract.
summary: "summary"

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

url_pdf: http://arxiv.org/abs/2003.12424
url_code: https://github.com/bfshi/DGAM-Weakly-Supervised-Action-Localization
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
