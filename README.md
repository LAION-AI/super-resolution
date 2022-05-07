# super-resolution
This is the LAION repository for creating open super-resolution models with the help of LAION-5B subsets.

1) Create LAION-5B high-resolution subset
2) Train models

## Project outline
- [x] Collecting datasets
- [ ] Establish training pipeline and architecture
- [ ] Create big model

## Datasets
- [170M subset of LAION-5B](https://huggingface.co/datasets/laion/laion-high-resolution), of high-resolution (>= 1024x1024) images (metadata 26GB, data 80TB, aws s3 ls s3://s-laion/laion-high-resolution/)
- [VQGAN 16k reconstructions](https://huggingface.co/datasets/johnowhitaker/vqgan16k_reconstruction)

## Methods
- [Swin transformer theory](https://sh-tsang.medium.com/review-swin-transformer-3438ea335585)
- [Swin transformer github](https://github.com/JingyunLiang/SwinIR)
- [BasicSR github repository](https://github.com/xinntao/BasicSR)
- [Image Super-Resolution via Iterative Refinement](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement)