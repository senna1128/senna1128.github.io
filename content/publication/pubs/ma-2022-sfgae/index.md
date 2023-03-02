---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'SFGAE: a Self-feature-based Graph Autoencoder Model for miRNA--disease Associations
  Prediction'
subtitle: ''
summary: ''
authors:
- Mingyuan Ma
- Sen Na
- Xiaolu Zhang
- Congzhou Chen
- Jin Xu
tags: []
categories: []
date: '2022-08-01'
lastmod: 2023-03-01T13:31:59-08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-03-01T21:31:59.295013Z'
publication_types:
- '2'
abstract: 'Increasing evidence has suggested that microRNAs (miRNAs) are important biomarkers of various diseases. Numerous graph neural network (GNN) models have been proposed for predicting miRNA–disease associations. However, the existing GNN-based methods have over-smoothing issue—the learned feature embeddings of miRNA nodes and disease nodes are indistinguishable when stacking multiple GNN layers. This issue makes the performance of the methods sensitive to the number of layers, and significantly hurts the performance when more layers are employed. In this study, we resolve this issue by a novel self-feature-based graph autoencoder model, shortened as SFGAE. The key novelty of SFGAE is to construct miRNA-self embeddings and disease-self embeddings, and let them be independent of graph interactions between two types of nodes. The novel self-feature embeddings enrich the information of typical aggregated feature embeddings, which aggregate the information from direct neighbors and hence heavily rely on graph interactions. SFGAE adopts a graph encoder with attention mechanism to concatenate aggregated feature embeddings and self-feature embeddings, and adopts a bilinear decoder to predict links. Our experiments show that SFGAE achieves state-of-the-art performance. In particular, SFGAE improves the average AUC upon recent [GAEMDA](https://doi.org/10.1093/bib/bbaa240) on the benchmark datasets HMDD v2.0 and HMDD v3.2, and consistently performs better when less (e.g. 10%) training samples are used. Furthermore, SFGAE effectively overcomes the over-smoothing issue and performs stably well on deeper models (e.g. eight layers). Finally, we carry out case studies on three human diseases, colon neoplasms, esophageal neoplasms and kidney neoplasms, and perform a survival analysis using kidney neoplasm as an example. The results suggest that SFGAE is a reliable tool for predicting potential miRNA–disease associations.
'
publication: '*Briefings in Bioinformatics*'
doi: 10.1093/bib/bbac340
#links:
#- name: URL
#  url: https://doi.org/10.1093/bib/bbac340
---
