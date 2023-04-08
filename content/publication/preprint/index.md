---
abstract: Existing space-time video super-resolution (ST-VSR) methods fail to achieve high-quality reconstruction 
  since they failto fully explore the spatial-temporal correlations, long-rangecomponents in particular.
  Although the recurrent structure for ST-VSR adopts bidirectional propagation to aggregate information from the entire video, 
  collecting the temporal information between the past and future via one-stage representations inevitably loses the long-range relations. 
  To alleviate the limitation, this paper proposes an immediate storeand-fetch network to promote long-range correlation learning, 
  where the stored information from the past and future can be refetched to help the representation of the current frame. 
  Specifically, the proposed network consists of two modules, a backward recurrent module (BRM) and 
  a forward recurrent module (FRM). The former first performs backward inference from future to past, while storing future
  super-resolution (SR) information for each frame. Following that, the latter performs forward inference from past to future 
  to super-resolve all frames, while storing past SR information for each frame. Since FRM inherits SR information
  from BRM, therefore, spatial and temporal information from the entire video sequence is immediately stored and fetched,
  which allows drastic improvement for ST-VSR. Extensive experiments both on ST-VSR and space video super-resolution
  (S-VSR) as well as time video super-resolution (T-VSR) have demonstrated the effectiveness of our proposed method over
  other state-of-the-art methods on public datasets.
authors:
- admin
date: "2023-02-07T00:00:00Z"
doi: ""
featured: false
image:
  caption: ""
  focal_point: ""
  preview_only: false
links:
- name: Custom Link
  url: 
projects:
- internal-project
publication: ""
publication_short: ""
publication_types:
- "3"
publishDate: "2017-01-01T00:00:00Z"
slides: example
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
  ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
tags:
- Source Themes
title: Store and Fetch Immediately Everything Is All You Need for Space-Time Video Super-resolution (AAAI 2023)
url_code: https://github.com/hhhhhumengshun/SFI-STVR
url_dataset: '#'
url_pdf: '#'
url_poster: '#'
url_project: ""
url_slides: ""
url_source: '#'
url_video: '#'
---