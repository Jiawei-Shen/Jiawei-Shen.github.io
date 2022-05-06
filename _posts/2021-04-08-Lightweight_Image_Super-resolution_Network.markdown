---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_Lightweight image super-resolution with mobile share-source network
title: Lightweight image super-resolution with mobile share-source network

# post specific
# if not specified, .name will be used from _data/owner.yml
author: "J Du, W Wei, C Fan, L Zou, J Shen, Z Zhou, Z Chen"
# multiple category is not supported
category: Computer Vision
# multiple tag entries are possible
tags: [Computer Vision, Machine Learning]
# thumbnail image for post
img: ":lightweigt_superresolution.png"
# disable comments on this page
comments_disable: true

# publish date
date: 2020-04-08 11:32:53 +0900

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

Within the development of the deep convolutional neural network, the great achievements had been made in the single-image super-resolution (SISR) task. However, the higher performance always comes with the deeper layers which also brings larger numbers of network operations and parameters that make it hard to implement in practice. In our work, a lightly super-resolution, named Mobile Share- Source Network (MSSN), is purposed to address these practical issues. In MSSN, a high-efficiency block, the mobile adaptive weighted residual unit, is designed to fulfill the need for the reduction in both parameters and the Mult-Adds while maintaining the performance with importing the deep separable convolution. Moreover, it brings into the Adaptive Weighted Share-Source Skip Connection, getting abundant information from the shallow layer which helps reconstruct better images. The experimental results show that our network has fewer numbers of parameters and operations than the state-of-the-art lightweight network while maintaining high reconstruction quality comparing with many state-of-the-art super-resolution methods in terms of both peak signal-to-noise ratio (PSNR) and structural similarity index metrics (SSIM).

[The Link to the paper](https://ieeexplore.ieee.org/abstract/document/9045996/)
