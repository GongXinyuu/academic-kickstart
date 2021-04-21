---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Talk in Lyft"
event: 
event_url:
location:
address:
  street:
  city:
  region:
  postcode:
  country:
summary: I'm invited to give a talk about my recent work "Sandwich Batch Normalization".
abstract: "We present Sandwich Batch Normalization (SaBN), an embarrassingly easy improvement of Batch Normalization (BN) with only a few lines of code changes. SaBN is motivated by addressing the inherent feature distribution heterogeneity that one can be identified in many tasks, which can arise from data heterogeneity (multiple input domains) or model heterogeneity (dynamic architectures, model conditioning, etc.). Our SaBN factorizes the BN affine layer into one shared sandwich affine layer, cascaded by several parallel independent affine layers. Concrete analysis reveals that, during optimization, SaBN promotes balanced gradient norms while still preserving diverse gradient directions: a property that many application tasks seem to favor. We demonstrate the prevailing effectiveness of SaBN as a drop-in replacement in four tasks: conditional image generation, neural architecture search (NAS), adversarial training, and arbitrary style transfer. Leveraging SaBN immediately achieves better Inception Score and FID on CIFAR-10 and ImageNet conditional image generation with three state-of-the-art GANs; boosts the performance of a state-of-the-art weight-sharing NAS algorithm significantly on NAS-Bench-201; substantially improves the robust and standard accuracies for adversarial defense; and produces superior arbitrary stylized results."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-04-20T014:00:00-05:00
#date_end: 2021-04-21T01:45:35-05:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2021-04-20T14:00:35-05:00

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: https://drive.google.com/file/d/196jRSfKimuAYHHHWtwHYxu2KklRQyNsK/view

url_code: https://github.com/VITA-Group/Sandwich-Batch-Normalization
url_pdf: https://arxiv.org/pdf/2102.11382.pdf
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
