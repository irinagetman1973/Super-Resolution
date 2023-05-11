# Super-Resolution

This is some of the research I have been conducting as part of my internship with RisosEnterprises Ltd(https://risosenterprises.com/) , a start-up company developing a revolutionary hand held technology to detect waterborne particulates. My primary area of responsibility is Super Resolution, and the research presented here focuses on developing novel techniques to enhance the resolution of low-resolution images.

After analysing current State-Of-The-Art Image Super Resolution models on   📈 [Papers with Codes](https://paperswithcode.com/task/image-super-resolution), I decided to start with HAT model as a current champion in x4 upscaling.

 ## HAT: Hybrid Attention Transformer for Image Super-Resolution
 HAT model significantly outperforms existing state-of-the-art methods, demonstrating marked improvements in image super-resolution performance.
 

 
 [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/activating-more-pixels-in-image-super/image-super-resolution-on-bsd100-2x-upscaling)](https://paperswithcode.com/sota/image-super-resolution-on-bsd100-2x-upscaling?p=activating-more-pixels-in-image-super)
 
 [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/activating-more-pixels-in-image-super/image-super-resolution-on-bsd100-3x-upscaling)](https://paperswithcode.com/sota/image-super-resolution-on-bsd100-3x-upscaling?p=activating-more-pixels-in-image-super)
 
 [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/activating-more-pixels-in-image-super/image-super-resolution-on-manga109-2x)](https://paperswithcode.com/sota/image-super-resolution-on-manga109-2x?p=activating-more-pixels-in-image-super)
 
 and showed state-of-the-art results on other benchmarks such as Set14, Set5, Urban100.

## References
This work makes use of the following resources:

### GitHub Repository
1. [Activating More Pixels in Image Super-Resolution Transformer](https://github.com/XPixelGroup/HAT) by XPixelGroup:

```bibtex
@article{chen2022activating,
  title={Activating More Pixels in Image Super-Resolution Transformer},
  author={Chen, Xiangyu and Wang, Xintao and Zhou, Jiantao and Dong, Chao},
  journal={arXiv preprint arXiv:2205.04437},
  year={2022}
}}


2. [Dataset Preparation] (https://github.com/XPixelGroup/BasicSR/blob/master/docs/DatasetPreparation.md)
