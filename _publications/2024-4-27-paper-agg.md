---
title: "AGG: Attention-Based Gated Convolutional GAN with Prior Guidance for Image Inpainting"
collection: publications
permalink: /publication/2024-4-27-paper-agg
excerpt: 'The codes is in [AGGNet](https://github.com/Shawn-Yu-1/AGGNet).'
date: 2024-04-24
venue: 'Neural Computing and Applications'
paperurl: 'https://link.springer.com/article/10.1007/s00521-024-09785-w'
citation: 'Xiankang Yu, Lei Dai, Zhihua Chen, et al. AGG: attention-based gated convolutional GAN with prior guidance for image inpainting[J]. Neural Computing and Applications, 2024: 1-17.'
---
Image inpainting has made great achievements recently, but it is often tough to generate a semantically consistent image when faced with large missing areas in complex scenes. To address semantic and structural alignment in existing methods for image inpainting, this paper proposes an end-to-end attention-based gated convolution GAN with prior guidance named AGG, which designs the spatial and channel attention mechanisms for full extraction of semantic and structural features. Moreover, AGG constructs the attention-based upsampling module based on the channel attention to refine the feature map and capture more details from features of up-level low sizes. AGG uses the image contour as prior, allowing the gated convolution and attention mechanism may fill the image efficiently by focusing on the contour information. The attention-based gated convolution can effectively capture the global features and compensate for the limitations of the restricted receptive field of the naive convolution. Compared to other models, AGG generates images with finer outline features and no common problems such as the watermark and blur, which shows the best overall performance on the Paris StreetView, CelebA-HQ, and Places2 datasets. The best FID, LPIPS, PSNR, and SSIM values achieved by AGG are 2.18, 0.046, 30.82, and 0.951 on the CelebA-HQ dataset, with at least 3.21% and 6.52% performance improvement on FID and LPIPS compared to state-of-the-art methods, respectively. The source code will be available at <https://github.com/Shawn-Yu-1/AGGNet>.

<!--[Download paper here](http://academicpages.github.io/files/paper3.pdf)-->

Citation

```
@article{yu2024agg,
  title={AGG: attention-based gated convolutional GAN with prior guidance for image inpainting},
  author={Yu, Xiankang and Dai, Lei and Chen, Zhihua and Sheng, Bin},
  journal={Neural Computing and Applications},
  pages={12589--12604},
  year={2024},
  volume={36},
  number={20},
  publisher={Springer}
}
```