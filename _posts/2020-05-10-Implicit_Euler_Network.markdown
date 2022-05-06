---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_Implicit Euler ODE networks for single-image dehazing
title: Implicit Euler ODE networks for single-image dehazing

# post specific
# if not specified, .name will be used from _data/owner.yml
author: "J Shen, Z Li, L Yu, GS Xia, W Yang"
# multiple category is not supported
category: Computer Vision
# multiple tag entries are possible
tags: [Computer Vision, Machine Learning]
# thumbnail image for post
img: ":post_pic1.png"
# disable comments on this page
comments_disable: true

# publish date
date: 2020-05-10 11:32:53 +0900

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

Deep convolutional neural networks (CNN) have been applied for image dehazing tasks, where the residual network (ResNet) is often adopted as the basic component to avoid the vanishing gradient problem. Recently, many works indicate that the ResNet can be considered as the explicit Euler forward approximation of an ordinary differential equation (ODE). In this paper, we extend the explicit forward approximation to the implicit backward counterpart, which can be realized via a recursive neural network, named IM-block. Given that, we propose an efficient end-to-end multi-level implicit network (MI-Net) for the single image dehazing problem. Moreover, multi-level fusing (MLF) mechanism and residual channel attention block (RCA-block) are adopted to boost performance of our network. Experiments on several dehazing benchmark datasets demonstrate that our method outperforms existing methods and achieves the state-of-the-art performance.

[The Link to the paper](http://openaccess.thecvf.com/content_CVPRW_2020/html/w14/Shen_Implicit_Euler_ODE_Networks_for_Single-Image_Dehazing_CVPRW_2020_paper.html)
