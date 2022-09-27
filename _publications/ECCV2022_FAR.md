---
title: "<ul><li>
Chenjie Cao<sup><a>*</a></sup>, <u>Qiaole Dong<sup><a>*</a></sup></u>, and Yanwei Fu<sup><a title='Corresponding author'>✉</a></sup>. 
**Learning Prior Feature and Attention Enhanced Image Inpainting.** ECCV 2022. (* indicates co-first authour)</ul></li>"
collection: publications
permalink: /publication/2_ECCV2022_FAR
excerpt: '
  [<span class="underline-on-hover" style="color:#FF6F6F">Abstract</span>](../publication/2_ECCV2022_FAR)
\| [<span class="underline-on-hover" style="color:#FF6F6F">Full text</span>](https://arxiv.org/pdf/2208.01837.pdf)
\| [<span class="underline-on-hover" style="color:#FF6F6F">Data and code</span>](https://github.com/ewrfcas/MAE-FAR)
'
---

<br><center><img src="https://github.com/ewrfcas/MAE-FAR/blob/page/static/images/overview.png"></center>

### Abstract:

<p style='text-align: justify;'>
Many recent inpainting works have achieved impressive results by leveraging Deep Neural Networks (DNNs) to model various prior information for image restoration.
Unfortunately, the performance of these methods is largely limited by the representation ability of vanilla Convolutional Neural Networks (CNNs) backbones.
On the other hand, Vision Transformers (ViT) with self-supervised pre-training have shown great potential for many visual recognition and object detection tasks.
A natural question is whether the inpainting task can be greatly benefited from the ViT backbone?
However, it is nontrivial to directly replace the new backbones in inpainting networks, as the inpainting is an inverse problem fundamentally different from the recognition tasks.
To this end, this paper incorporates the pre-training based Masked AutoEncoder (MAE) into the inpainting model, which enjoys richer informative priors to enhance the inpainting process.
Moreover, we propose to use attention priors from MAE to make the inpainting model learn more long-distance dependencies between masked and unmasked regions.
Sufficient ablations have been discussed about the inpainting and the self-supervised pre-training models in this paper.
Besides, experiments on both Places2 and FFHQ demonstrate the effectiveness of our proposed model.
</p>

[<span class="underline-on-hover" style="color:#FF6F6F">Full text</span>](https://arxiv.org/pdf/2208.01837.pdf)
\| [<span class="underline-on-hover" style="color:#FF6F6F">Data and code</span>](https://github.com/ewrfcas/MAE-FAR)
