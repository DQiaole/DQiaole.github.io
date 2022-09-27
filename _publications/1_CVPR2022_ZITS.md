---
title: "<b>+</b> 
<u>Qiaole Dong<sup><a>*</a></sup></u>, Chenjie Cao<sup><a>*</a></sup>, and Yanwei Fu<sup><a title='Corresponding author'>✉</a></sup>. 
**Incremental transformer structure enhanced image inpainting with masking positional encoding.** CVPR 2022. (* indicates co-first authour)"
collection: publications
permalink: /publication/1_CVPR2022_ZITS
excerpt: '
  [<span class="underline-on-hover" style="color:#FF6F6F">Abstract</span>](../publication/1_CVPR2022_ZITS)
\| [<span class="underline-on-hover" style="color:#FF6F6F">Full text</span>](https://openaccess.thecvf.com/content/CVPR2022/papers/Dong_Incremental_Transformer_Structure_Enhanced_Image_Inpainting_With_Masking_Positional_Encoding_CVPR_2022_paper.pdf)
\| [<span class="underline-on-hover" style="color:#FF6F6F">Source code</span>](https://github.com/DQiaole/ZITS_inpainting)
'
---

<br><center><img src="https://github.com/DQiaole/ZITS_inpainting/blob/main/imgs/overview.jpg"></center> 

### Abstract:

<p style='text-align: justify;'>
Image inpainting has made significant advances in recent years.
However, it is still challenging to recover corrupted images with both vivid textures and reasonable structures.
Some specific methods only tackle regular textures while losing holistic structures due to the limited receptive
fields of convolutional neural networks (CNNs). On the other hand, attention-based models can learn better
long-range dependency for the structure recovery, but they are limited by the heavy computation for inference
with large image sizes. To address these issues, we propose to leverage an additional structure restorer to
facilitate the image inpainting incrementally. The proposed model restores holistic image structures with a
powerful attention-based transformer model in a fixed low-resolution sketch space. Such a grayscale space is
easy to be upsampled to larger scales to convey correct structural information. Our structure restorer can
be integrated with other pretrained inpainting models efficiently with the zero-initialized residual addition.
Furthermore, a masking positional encoding strategy is utilized to improve the performance with large irregular masks.
Extensive experiments on various datasets validate the efficacy of our model compared with other competitors.
</p>

[<span class="underline-on-hover" style="color:#FF6F6F">Full text</span>](https://openaccess.thecvf.com/content/CVPR2022/papers/Dong_Incremental_Transformer_Structure_Enhanced_Image_Inpainting_With_Masking_Positional_Encoding_CVPR_2022_paper.pdf)
\| [<span class="underline-on-hover" style="color:#FF6F6F">Data and code</span>](https://github.com/DQiaole/ZITS_inpainting)
