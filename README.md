Reading list for research topics in Vison Transformers.

We list the most popular methods for Vision Transformer, if I missed something, please submit a request.
(Note: We show the date of the first version of Arxiv here. But the link of paper is the lastest version.)


## Supervied Vision Transformers as backbone models.

Date|Method|Conference|Title|Code
-----|----|-----|-----|-----
2020-10-22|ViT|ICLR 2021|[AN IMAGE IS WORTH 16X16 WORDS: TRANSFORMERS FOR IMAGE RECOGNITION AT SCALE](https://arxiv.org/abs/2010.11929)|[ViT](https://github.com/google-research/vision_transformer)
2020-12-23|DeiT|ICML 2021|[Training data-efficient image transformers & distillation through attention](https://arxiv.org/pdf/2012.12877.pdf)|[DeiT](https://github.com/facebookresearch/deit)
2021-02-24|PVT|ICCV 2021(Oral)|[Pyramid Vision Transformer: A Versatile Backbone for Dense Prediction without Convolutions](https://arxiv.org/pdf/2102.12122.pdf)|[PVT](https://github.com/whai362/PVT)
2021-02-27|TNT|Arxiv 2021|[Transformer in Transformer](https://arxiv.org/pdf/2103.00112.pdf)|[TNT](https://gitee.com/mindspore/mindspore/tree/master/model_zoo/research/cv/TNT)
2021-03-25|Swin|ICCV 2021(Best)|[Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/pdf/2103.14030v2.pdf)|[Swin-Transformer](https://github.com/microsoft/Swin-Transformer)
2021-04-21|MViT|ICCV2021|[Multiscale Vision Transformers](https://arxiv.org/pdf/2104.11227.pdf)|[MViT](https:/github.com/facebookresearch/SlowFast)
2021-06-04|RegionViT|ICLR 2022|[RegionViT: Regional-to-Local Attention for Vision Transformers](https://arxiv.org/abs/2106.02689)|[RegionViT](https://github.com/ibm/regionvit)
2021-06-11|Twins|Arxiv 2021|[Twins: Revisiting the Design of Spatial Attention in Vision Transformers](https://arxiv.org/abs/2104.13840)|[Twins](https://github.com/Meituan-AutoML/Twins)
2021-11-30|Shunted-Transformer|Arxiv 2021|[Shunted Self-Attention via Multi-Scale Token Aggregation](https://arxiv.org/pdf/2112.13085.pdf)|[Shunted-Transformer](https://github.com/OliverRensu/Shunted-Transformer)
2021-12-02|MViT v2|Arxiv 2021|[Improved Multiscale Vision Transformers for Classification and Detection](https://arxiv.org/pdf/2112.01526.pdf)| None
2021-12-24|SimViT|Arxiv 2021|[SimViT: Exploring a Simple Vision Transformer with sliding windows](https://arxiv.org/pdf/2112.13085.pdf)|[SimViT](https://github.com/ucasligang/SimViT)
2022-04-19|TCFormer|CVPR 2022(Oral)|[Not All Tokens Are Equal: Human-centric Visual Analysis via Token Clustering Transformer](https://arxiv.org/pdf/2204.08680.pdf)|[TCFormer](https://github.com/zengwang430521/TCFormer)
2022-06-02|EfficientFormer|Arxiv 2022|[EfficientFormer: Vision Transformers at MobileNet Speed](https://arxiv.org/pdf/2206.01191.pdf)|[EfficientFormer](https://github.com/snap-research/EfficientFormer)

updating......

## Supervied Vision Transformers as specific models.
Image Synthesis:
Date|Method|Conference|Title|Code
-----|----|-----|-----|-----
2020-12-17|Taming Transformer|CVPR 2021(Oral)|[Taming Transformers for High-Resolution Image Synthesis](https://openaccess.thecvf.com/content/CVPR2021/papers/Esser_Taming_Transformers_for_High-Resolution_Image_Synthesis_CVPR_2021_paper.pdf)|[TamingTransformer](https://github.com/CompVis/taming-transformers)
2021-xx-xx|TransGAN|NeurIPS 2021|[TransGAN: Two Pure Transformers Can Make One Strong GAN, and That Can Scale Up](https://proceedings.neurips.cc/paper/2021/file/7c220a2091c26a7f5e9f1cfb099511e3-Paper.pdf)|[TransGAN](https://github.com/VITA-Group/TransGAN)

## Self-supervied Vision Transformers as backbone models.
Date|Method|Conference|Title|Code
-----|----|-----|-----|-----
2021-04-05|MoCo v3|ICCV 2021(Oral)|[An Empirical Study of Training Self-Supervised Vision Transformers](https://arxiv.org/pdf/2104.02057.pdf)|[Moco v3](https://github.com/facebookresearch/moco-v3)
2021-06-14|BeiT|ICLR 2022(Oral)|[BEiT: BERT Pre-Training of Image Transformers](https://arxiv.org/abs/2106.08254)|[BeiT](https://github.com/microsoft/unilm/tree/master/beit)
2021-11-11|MAE|Arxiv 2021|[Masked Autoencoders Are Scalable Vision Learners](https://arxiv.org/pdf/2111.06377.pdf)|[MAE](https://github.com/facebookresearch/mae)
2021-11-15|iBoT|Arxiv 2021|[iBOT: Image BERT Pre-Training with Online Tokenizer](https://arxiv.org/pdf/2111.07832.pdf)|[iBoT](https://github.com/bytedance/ibot)
2021-11-18|SimMIM|Arxiv 2021|[SimMIM: A Simple Framework for Masked Image Modeling](https://arxiv.org/pdf/2111.09886.pdf)|[SimMIM](https://github.com/microsoft/SimMIM)
2021-12-16|MaskFeat|Arxiv 2021|[Masked Feature Prediction for Self-Supervised Visual Pre-Training](https://arxiv.org/pdf/2112.09133.pdf)|None
2021-12-20|SplitMask|Arxiv 2021|[Are Large-scale Datasets Necessary for Self-Supervised Pre-training?](https://arxiv.org/pdf/2112.10740.pdf)|None
2022-01-19|RePre|Arxiv 2022|[RePre: Improving Self-Supervised Vision Transformer with Reconstructive Pre-training](https://arxiv.org/pdf/2201.06857.pdf)|None
2022-02-07|CAE|Arxiv 2022|[Context Autoencoder for Self-Supervised Representation Learning](https://arxiv.org/pdf/2202.03026.pdf)|None

Todo:iBoT,DINO

## Surveys

Date|Conference/journal|Title|
-----|----|-----
2020-12-23 (latest version: 2021-02-23)|TPAMI|[A Survey on Vision Transformer](https://arxiv.org/pdf/2012.12556.pdf)
2021-01-04 (latest version: 2022-01-19)|ACM Computing Surveys|[Transformers in vision: A survey](https://arxiv.org/pdf/2101.01169.pdf)
2022-05-10 (latest version: 2022-08-06)|Knowledge-Based Systems|[Vision transformers for dense prediction: A survey](https://www.sciencedirect.com/science/article/pii/S0950705122007821)


