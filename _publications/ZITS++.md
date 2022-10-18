---
title: "
Chenjie Cao<a>*</a>, <u>Qiaole Dong<a>*</a></u>, and Yanwei Fu<sup><a title='Corresponding author'>✉</a></sup>. 
<b>ZITS++: Image Inpainting by Improving the Incremental Transformer on Structural Priors.</b> Preprint, 2022. (<a>*</a> indicates co-first authour)"
collection: publications
permalink: /publication/ZITS++
excerpt: '
  [<span class="underline-on-hover" style="color:#FF6F6F">Abstract</span>](../publication/ZITS++)
\| [<span class="underline-on-hover" style="color:#FF6F6F">Paper</span>](https://arxiv.org/abs/2210.05950)
'
---

### Abstract:

<p style='text-align: justify;'>
The image inpainting task fills missing areas of a corrupted image. Despite impressive results have been achieved 
recently, it is still challenging to restore corrupted images with both vivid textures and reasonable structures. 
Some previous methods only tackle regular textures while losing holistic structures limited by receptive fields of 
Convolution Neural Networks (CNNs). To this end, we study learning a Zero-initialized residual addition based 
Incremental Transformer on Structural priors (ZITS++), an improved model over our conference ZITS model. Specifically, 
given one corrupt image, we present the Transformer Structure Restorer (TSR) module to restore holistic structural 
priors at low image resolution, which are further upsampled by Simple Structure Upsampler (SSU) module to higher image 
resolution. Further, to well recover image texture details, we take the Fourier CNN Texture Restoration (FTR) module, 
which has both the Fourier and large-kernel attention convolutions. Typically, FTR can be independently pre-trained 
without image structural priors. Furthermore, to enhance the FTR, the upsampled structural priors from TSR are further 
processed by Structure Feature Encoder (SFE), and updating the FTR by a novel incremental training strategy of 
Zero-initialized Residual Addition (ZeroRA). Essentially, a new masking positional encoding is proposed to encode the 
large irregular masks. Extensive experiments on various datasets validate the efficacy of our model compared with other 
competitors. We also conduct extensive ablation to compare and verify various priors for image inpainting tasks.
</p>

[<span class="underline-on-hover" style="color:#FF6F6F">Paper</span>](https://arxiv.org/abs/2210.05950)
