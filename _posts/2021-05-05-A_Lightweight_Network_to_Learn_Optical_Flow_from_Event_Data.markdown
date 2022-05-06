---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_A Lightweight Network to Learn Optical Flow from Event Data
title: A Lightweight Network to Learn Optical Flow from Event Data

# post specific
# if not specified, .name will be used from _data/owner.yml
author: "Z Li, J Shen, R Liu"
# multiple category is not supported
category: Computer Vision
# multiple tag entries are possible
tags: [Computer Vision, Machine Learning]
# thumbnail image for post
img: ":ICPR21.png"
# disable comments on this page
comments_disable: true

# publish date
date: 2021-05-05 11:32:53 +0900

# seo
# if not specified, date will be used.
#meta_modify_date: 2021-08-10 11:32:53 +0900
# check the meta_common_description in _data/lang/[language].yml
#meta_description: ""

# optional
# if you enabled image_viewer_posts you don't need to enable this. This is only if image_viewer_posts = false
#image_viewer_on: true
# if you enabled image_lazy_loader_posts you don't need to enable this. This is only if image_lazy_loader_posts = false
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false
---

## Abstraction

Existing deep neural networks have found success in estimation of event-based optical flow, but are at the expense of complicated architectures. Moreover, few prior works discuss how to tackle with the noise problem of event camera, which would severely contaminate the data quality and make estimation an ill-posed problem. In this work, we present a lightweight pyramid network with attention mechanism to learn optical flow from events data. Specially, the network is designed according to two-well established principles: Laplacian pyramidal decomposition and channel attention mechanism. By integrating Laplacian pyramidal processing into CNN, the learning problem is simplified into several subproblems at each pyramid level, which can be handled by a relatively shallow network with few parameters. The channel attention block, embedded in each pyramid level, treats channels of feature map unequally and provides extra flexibility in suppressing background noises. The size of the proposed network is about only 5% of previous methods while our method still achieves state-of-the-art performance on the benchmark dataset. The experimental video samples of continuous flow estimation is presented at: https://github.com/xfleezy/blob.

[The Link to the paper](http://openaccess.thecvf.com/content_CVPRW_2020/html/w14/Shen_Implicit_Euler_ODE_Networks_for_Single-Image_Dehazing_CVPRW_2020_paper.html)
