---
title: "Exploiting Transfer Learning and Hand-Crafted Features in a Unified Neural Model for Identifying Actionable Informative Tweets"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Abu Nowshed Chy
- Umme Aymun Siddiqua
- Masaki Aono

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: 2021-01-01
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Journal of Information Processing, Vol.29, pp.16-29
# publication_short: In *ICW*

abstract: During emergencies and disaster situations, microblogging sites, especially twitter, can be used as a source of providing situational information needs. Monitoring and identifying informative tweets from tweet streams provide enormous opportunities for public safety personnel in coordinating aid operations as well as conducting the post-incident analysis. However, the brevity of tweets and noisy tweet contents makes it challenging to extract the situational information effectively and identify the tweets based on different information types. In this paper, we propose a neural network model with a naive rule-based classifier for actionable informative tweets classification. In our proposed neural architecture, we exploit the transfer learning features from a pre-trained sentence embeddings model along with a rich set of hand-crafted features to train a multilayer perceptron (MLP) network. In addition, we employ the state-of-the-art LSTM variants, nested LSTMs (NLSTMs) to capture the long-term dependency effectively. On top of nested LSTMs, we perform the convolution using multiple kernels (CMK) to obtain the higher-level representation of tweets. Experiments on the 2018 TREC incident streams (TREC-IS) dataset show that our proposed neural model learns the contextual information effectively and achieves the overall best result compared to the state-of-the-art methods.

# Summary. An optional shortened abstract.
keywords: microblog incident streams, actionable information, crisis informatics, disasters, nested LSTMs, convolution using multiple kernels, transfer learning features, hand-crafted features.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.jstage.jst.go.jp/article/ipsjjip/29/0/29_16/_pdf'
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

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
