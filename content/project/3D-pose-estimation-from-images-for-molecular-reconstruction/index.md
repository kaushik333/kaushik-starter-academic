---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "3D Pose Estimation From Images for Molecular Reconstruction"
summary: "This is a DARPA Physics of AI project where the broad goal is to integrate physics constraints into neural networks so as to learn representations that respect these constriants. One of the applications we were addressing was to perform 3D recosntruction of molecule given various 2D projections of the same. The imaging procedure, Cryo-EM is very noisy and is hard to obtain many image. There is also no control over the angle at which the molecule is images as they are taken randomly. Furthermore, the molecule considered also has icosohedral symmetry. The goal of the project is to first estimate the 3D (euler or quaternion) angles of each of these images, and then perform 3D reconstruction of the molecule. A maximum likelihood based approach (Hetero) is first used to estimate these angles which serves as a ground truth and then a neural network is learned to regress these angles. We also develop a disentangled VAE to learn the angles explicitly at the latent space and then use latent space interpolations to generate images of unseen angles and in-turn obtain better 3D reconstruction. "
authors: []
tags: []
categories: []
date: 2020-04-05

# Optional external URL for project (replaces project detail page).
external_link: ""

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

abstract: ""
url_code: "https://github.com/PhysicsOfAI/PhysicsAI4Imaging/tree/master/Method2"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
