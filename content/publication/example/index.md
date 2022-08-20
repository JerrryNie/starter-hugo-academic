---
abstract: >-
  Unsupervised question answering is an attractive task due to its independence
  on labeled data. Previous works usually make use of heuristic rules as well as
  pre-trained models to construct data and train QA models. However, most of
  these works regard named entity (NE) as the only answer type, which ignores
  the high diversity of answers in the real world. To tackle this problem, we
  propose a novel unsupervised method by diversifying answers, named DiverseQA.
  Specifically, the proposed method is composed of three modules: data
  construction, data augmentation and denoising filter. Firstly, the data
  construction module extends the extracted named entity into a longer sentence
  constituent as the new answer span to construct a QA dataset with diverse
  answers. Secondly, the data augmentation module adopts an answer-type
  dependent data augmentation process via adversarial training in the embedding
  level. Thirdly, the denoising filter module is designed to alleviate the noise
  in the constructed data. Extensive experiments show that the proposed method
  outperforms previous unsupervised models on five benchmark datasets, including
  SQuADv1.1, NewsQA, TriviaQA, BioASQ, and DuoRC. Besides, 

  the proposed method shows strong performance in the few-shot learning setting.
slides: example
url_pdf: ""
publication_types:
  - "1"
authors:
  - admin
  - Heyan Huang
  - Zewen Chi
  - Xian-Ling Mao
author_notes: []
publication: COLING 2022
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
  tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
  condimentum.
url_dataset: ""
url_project: ""
publication_short: In *ICW*
url_source: ""
url_video: ""
title: Unsupervised Question Answering via Answer Diversifying
subtitle: QA, QA, Q
doi: ""
featured: true
tags: []
projects:
  - example
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
date: 2013-07-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
