
## 关注我们
<div align=center>
<p>门头沟学院AI视觉实验室御用公众号 | 学术 | 科研 | 就业</p>
<p>扫描下方二维码，然后回复关键词“<b>进群</b>”，即可加入“读者交流群”</p>
<img src="https://github.com/CVHuber/awesome-cv/blob/main/640.jfif" width = "250" height = "270" alt="欢迎大家关注我们的公众号CVHub，每日都给大家带来原创、多领域、有深度的前沿AI论文解读与工业成熟解决方案！">
</div>


<font size=6><center><big><b> Awesome Computer Vision [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) </b></big></center></font>

This is a list of computer vison related resources. 

The timeline follows the time of arxiv.org publication.

Please feel free to [pull requests](https://github.com/CVHub520/awesome-computer-vision/pulls) or [open an issue](https://github.com/CVHub520/awesome-computer-vision/issues) to add papers.

---

<font size=5><center><b> Table of Contents </b> </center></font>
- [Awesome Classification](#awesome-classification)

- [Awesome Segmentation](#awesome-segmentation)

- [Awesome Detection](#awesome-detection)

- [Awesome Low Level Vison](#awesome-low-level-vison)

- [Awesome 3D Vision](#awesome-3d-vision)
    - [Awesome 3D Classification & Detection & Segmentation](#awesome-3d-classification--detection--segmentation)
    - [Awesome 3D Representations](#awesome-3d-representations)
    - [Awesome 3D Reconstruction](#awesome-3d-reconstruction)
    - [Awesome Depth & Flow Estimation](#awesome-depth--flow-estimation)
    - [Awesome Neural Rendering](#awesome-neural-rendering)
    - [Awesome SLAM](#awesome-slam)
- [Awesome Diffusion](#awesome-diffusion)

- [Awesome Network Architectures And Techniques](#awesome-network-architectures-and-techniques)

- [Awesome Optimization Methods](#awesome-optimization-methods)

- [Awesome Face Recognition](#awesome-face-recognition)

# Awesome Classification
## Articles And Interpretation
| Type |  简称 |   |   |   |   |   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  | | |
|  | CNN | Trans | CNN&Trans | RNN | GEN | Other |
| 网络类型 | CNN | Transformer | CNN + Transformer | RNN |  GAN/Diffusion | GNN... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Sup | UnSup | Self | Semi | FSL | ZSL |
| 监督方式 |  Supervised Learning |  Unsupervised Learning | Self-Supervised Learning | Semi-Supervised Learning |  Few-shot Learning | Zero-shot Learning |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | FGC |  | - | - | - | - |
| 任务类型 |  Fine-Grained Classification |    | -| - | -| - |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Medical |-| - | - | - | Other |
|  其他特性 | Medical Image Classification |  - | -| - | - | - |

| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     
|Shape-Aware Fine-Grained Classification of Erythroid Cells | | __`CNN&Trans`__ __`Sup`__  __`FGC`__   __`Medical`__   |      |[GitHub![](https://img.shields.io/github/stars/wangye8899/bmec?style=social)](https://github.com/wangye8899/bmec) | [BMEC：基于形状感知的红细胞细粒度分类](https://mp.weixin.qq.com/s/zr6ODsmj85JsnQ1Uoq2xdg)  |
## Blogs 
## Libraies


# Awesome Segmentation
## Articles And Interpretation
| Type |  简称 |   |   |   |   |   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  | | |
|  | CNN | Trans | CNN&Trans | RNN | GEN | Other |
| 网络类型 | CNN | Transformer | CNN + Transformer | RNN |  GAN/Diffusion | GNN... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Sup | UnSup | Self | Semi | Meta | Other |
| 监督方式 |  Supervised Learning |  Unsupervised Learning | Self-Supervised Learning | Semi-Supervised Learning |  Meta Learning | Weakly-Supervised... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Semantic | Instance | Video | Medical | Aut | Other |
| 任务类型 | Semantic Segmentation | Instance Segmentation |   Video Segmentation  | Medical Segmentation |  Autonomous Driving Segmentation | Saliency Segmentation... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | MultiModal | UH-Res | Adv | - | - | Other |
|  其他特性 | MultiModal Learning |  Ultra-high Resolution | Adversarial Training | - | - | - |



| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     
|Delivering Arbitrary-Modal Semantic Segmentation | CVPR 2023 | __`CNN&Trans`__ __`Sup`__  __`Semantic`__  __`MultiModal`__  |      |[GitHub![](https://img.shields.io/github/stars/jamycheung/DELIVER?style=social)](https://github.com/jamycheung/DELIVER) | [基于编解码架构的强大语义分割基线，解锁多模态语义分割的正确姿势](https://zhuanlan.zhihu.com/p/613293738)  |
| ISDNet: Integrating Shallow and Deep Networks for Efficient Ultra-high Resolution Segmentation | CVPR 2022 | __`CNN`__ __`Sup`__  __`Semantic`__  __`UH-Res`__ |        | [GitHub![](https://img.shields.io/github/stars/cedricgsh/ISDNet?style=social)](https://github.com/cedricgsh/ISDNet) | [探索超高分辨率图像分割的高效之道](https://zhuanlan.zhihu.com/p/611138087)  |
| Multi-modal contrastive mutual learning and pseudo-label re-learning for semi-supervised medical image segmentation | MIA 2023  | __`CNN`__ __`Semi`__  __`Medical`__  __`MultiModal`__ |        |- | [用于半监督医学图像分割的多模态对比互学习和伪标签再学习方法](https://mp.weixin.qq.com/s/r_5g9I4MGoydpZ2pOix1sA)  |
| Class-Aware Adversarial Transformers for Medical Image Segmentation | NeuraIPS 2022  | __`CNN&Trans`__ __`Sup`__  __`Adv`__  |        |- | [最新类别感知对抗Transformer分割网络CASTformer](https://mp.weixin.qq.com/s/qAq54Tg_j9AekmMeMwFnwQ)  |
| DAE-Former: Dual Attention-guided Efficient Transformer for Medical Image Segmentation | NeuraIPS 2022  | __`Trans`__ __`Sup`__  __`Medical`__  |        |[GitHub![](https://img.shields.io/github/stars/mindflow-institue/daeformer?style=social)](https://github.com/mindflow-institue/daeformer)  | [DAE-Former：高效双重注意力引导的Transformer网络称霸医学图像分割任务](https://mp.weixin.qq.com/s/RL45_CKwKAwN9hm1t4vUJA)  |



##  Blogs 
- [语义分割大盘点](http://automl.chalearn.org/)
- [关于语义分割的亿点思考](https://zhuanlan.zhihu.com/p/595753988)

## Libraies
- [mmsegmentation](https://github.com/open-mmlab/mmsegmentation)
- [PaddleSeg](https://github.com/open-mmlab/mmsegmentation)



# Awesome Detection
## Articles And Interpretation
| Type |  简称 |   |   |   |   |   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  | | |
|  | CNN | Trans | CNN&Trans | RNN | GEN | Other |
| 网络类型 | CNN | Transformer | CNN + Transformer | RNN |  GAN/Diffusion | GNN... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Sup | UnSup | Self | Semi | FSL | ZSL |
| 监督方式 |  Supervised Learning |  Unsupervised Learning | Self-Supervised Learning | Semi-Supervised Learning |  Few-shot Learning | Zero-shot Learning |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Small | Moving | Oriented | Body | Head | Other |
| 任务类型 |  Small Object Detection |  Moving Object Detection  | Oriented Object Detection| Body Detection | Head Detection| License Plate Detection... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | RGB-D | Real-Time | Video | OpenWorld | Aerial | Other |
|  其他特性 | RGB-D Salient Object Detection |  Real-Time Object Detection | Video Salient Object Detection | Open World Object Detection | Object Detection In Aerial Images | - |

| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     
|Open World DETR: Transformer based Open World Object Detection | CVPR 2022 | __`CNN&Trans`__ __`Sup`__  __`Semi`__   __`OpenWorld`__  |      |[GitHub![](https://img.shields.io/github/stars/akshitac8/OW-DETR?style=social)](https://github.com/akshitac8/OW-DETR) | [基于DETR的开放世界目标检测——从入门到喜欢](https://mp.weixin.qq.com/s/AAqc_XuRS9MTyU4nuO_6qw)  |

## Blogs 
## Libraies


# Awesome 3D Classification
## Articles And Interpretation
| Type |  简称 |   |   |   |   |   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  | | |
|  | CNN | Trans | CNN&Trans | RNN | GEN | Other |
| 网络类型 | CNN | Transformer | CNN + Transformer | RNN |  GAN/Diffusion | GNN... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Sup | UnSup | Self | Semi | Meta | Other |
| 监督方式 |  Supervised Learning |  Unsupervised Learning | Self-Supervised Learning | Semi-Supervised Learning |  Meta Learning | Weakly-Supervised... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Semantic | Instance | Video | Medical | Aut | Other |
| 任务类型 | Semantic Segmentation | Instance Segmentation |   Video Segmentation  | Medical Segmentation |  Autonomous Driving Segmentation | Saliency Segmentation... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | MultiModal | UH-Res | - | - | - | Other |
|  其他特性 | MultiModal Learning |  Ultra-high Resolution | - | - | - | - |

| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     

## Blogs 
## Libraies

# Awesome 3D Detection
## Articles And Interpretation
| Type |  简称 |   |   |   |   |   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  | | |
|  | CNN | Trans | CNN&Trans | RNN | GEN | Other |
| 网络类型 | CNN | Transformer | CNN + Transformer | RNN |  GAN/Diffusion | GNN... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Sup | UnSup | Self | Semi | Meta | Other |
| 监督方式 |  Supervised Learning |  Unsupervised Learning | Self-Supervised Learning | Semi-Supervised Learning |  Meta Learning | Weakly-Supervised... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Semantic | Instance | Video | Medical | Aut | Other |
| 任务类型 | Semantic Segmentation | Instance Segmentation |   Video Segmentation  | Medical Segmentation |  Autonomous Driving Segmentation | Saliency Segmentation... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | MultiModal | UH-Res | - | - | - | Other |
|  其他特性 | MultiModal Learning |  Ultra-high Resolution | - | - | - | - |

| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     


## Blogs 
## Libraies

# Awesome 3D Segmentation
## Articles And Interpretation
| Type |  简称 |   |   |   |   |   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  | | |
|  | CNN | Trans | CNN&Trans | RNN | GEN | Other |
| 网络类型 | CNN | Transformer | CNN + Transformer | RNN |  GAN/Diffusion | GNN... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Sup | UnSup | Self | Semi | Meta | Other |
| 监督方式 |  Supervised Learning |  Unsupervised Learning | Self-Supervised Learning | Semi-Supervised Learning |  Meta Learning | Weakly-Supervised... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Semantic | Instance | Video | Medical | Aut | Other |
| 任务类型 | Semantic Segmentation | Instance Segmentation |   Video Segmentation  | Medical Segmentation |  Autonomous Driving Segmentation | Saliency Segmentation... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | MultiModal | UH-Res | - | - | - | Other |
|  其他特性 | MultiModal Learning |  Ultra-high Resolution | - | - | - | - |

| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     
|  :fire::fire: UNETR++: Delving into Efficient and Accurate 3D Medical Image Segmentation | CVPR 2022 | __`CNN&Trans`__ __`Sup`__  __`Semantic`__  __`Medical`__ |        | [GitHub![](https://img.shields.io/github/stars/Amshaker/unetr_plus_plus?style=social)](https://github.com/Amshaker/unetr_plus_plus) | [UNETR++：轻量级的共享权重Transformer称霸医学图像分割领域](https://mp.weixin.qq.com/s/fcF5WibfFADnMI1TLaNPng)  |

## Blogs 
## Libraies

# Awesome Low Level Vison
## Articles And Interpretation
## Blogs 
## Libraies

# Awesome 3D Vision
# Awesome 3D Representations
## Articles And Interpretation
## Blogs 
## Libraies


# Awesome 3D Reconstruction
## Articles And Interpretation
## Blogs 
## Libraies


# Awesome Depth & Flow Estimation
## Articles And Interpretation
| Type |  简称 |   |   |   |   |   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  | | |
|  | CNN | Trans | CNN&Trans | RNN | GEN | Other |
| 网络类型 | CNN | Transformer | CNN + Transformer | RNN |  GAN/Diffusion | GNN... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Sup | UnSup | Self | Semi | FSL | ZSL |
| 监督方式 |  Supervised Learning |  Unsupervised Learning | Self-Supervised Learning | Semi-Supervised Learning |  Few-shot Learning | Zero-shot Learning |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Mono | Stereo | Match | Flow |  |  |
| 任务类型 | Monocular Depth Estimation | Stereo Depth Estimation  |   Stereo Match  | Optical Flow Estimation |    |  |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Night | Rel | Met | Rel&Met | Out | In |
|  其他特性 | Nighttime |  Relative Depth | Metric Depth | Relative & Metric Depth |Outdoor Domain | Indoor Domain |



| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     
|  :fire: ZoeDepth: Zero-shot Transfer by Combining Relative and Metric Depth | - | __`CNN&Trans`__ __`ZSL`__  __`Mono`__  __`Rel&Met`__ |   NYU REL 0.075   |[GitHub![](https://img.shields.io/github/stars/isl-org/ZoeDepth?style=social)](https://github.com/isl-org/ZoeDepth) | [第一个结合相对和绝对深度的多模态单目深度估计网络](https://zhuanlan.zhihu.com/p/615166220)  |
| Lite-Mono: A Lightweight CNN and Transformer Architecture for Self-Supervised Monocular Depth Estimation | CVPR 2023 | __`CNN&Trans`__ __`Self`__  __`Mono`__  __`Rel`__  |    KITTI REL 0.102   |[GitHub![](https://img.shields.io/github/stars/noahzn/Lite-Mono?style=social)](https://github.com/noahzn/Lite-Mono) | [一种新的轻量级自监督单目深度估计方法](https://zhuanlan.zhihu.com/p/614680720)  |


## Blogs 
## Libraies


# Awesome Neural Rendering
## Articles And Interpretation
## Blogs 
## Libraies


# Awesome SLAM
## Articles And Interpretation
## Blogs 
## Libraies


# Awesome Diffusion
## Articles And Interpretation
| Type |  简称 |   |   |   |   |   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  | | |
|  | CNN | Trans | CNN&Trans | RNN | GEN | Other |
| 网络类型 | CNN | Transformer | CNN + Transformer | RNN |  GAN/Diffusion | GNN... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Sup | UnSup | Self | Semi | FSL | ZSL |
| 监督方式 |  Supervised Learning |  Unsupervised Learning | Self-Supervised Learning | Semi-Supervised Learning |  Few-shot Learning | Zero-shot Learning |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  |  | Lang | T2I | T2V | T23D | I2T |  |
| 任务类型 | Language | Text-to-Text  |  Text-to-Image    | Text-to-Video  | Text-to-3D  |  Image-to-Text  |  |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | MultiModal| ImgGen |ImgEdit | ILU |    |    |
|  其他特性 | MultiModal Learning | Image Generation |Image Editing | Image-and-Language Understanding  |     |  |


| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     
| SINE: SINgle Image Editing with Text-to-Image Diffusion Models | CVPR 2023 | __`GEN`__ __`T2I`__  __`Lang`__ __`ImgEdit`__  |      |[GitHub![](https://img.shields.io/github/stars/zhang-zx/SINE?style=social)](https://github.com/zhang-zx/SINE) | [SINE: 一种基于扩散模型的单图像编辑解决方案](https://mp.weixin.qq.com/s/zZztD_HkXCiCu_3Fc07yTg)  |
| InstructPix2Pix: Learning to Follow Image Editing Instructions | CVPR 2023 (Highlight) | __`GEN`__ __`T2I`__  __`Lang`__ __`ImgEdit`__  |       |[GitHub![](https://img.shields.io/github/stars/noahzn/Lite-Mono?style=social)](https://github.com/noahzn/Lite-Mono) | [InstructPix2Pix: 一种无需微调新的快速图像编辑方法](https://mp.weixin.qq.com/s/cJtqmpnkSWSMK4BxLLLm7g)  |
| Diffusion Art or Digital Forgery? Investigating Data Replication in Diffusion Models | CVPR 2023 (Highlight) | __`GEN`__ __`T2I`__  __`Lang`__ __`ImgEdit`__  |       | - | [一文深度剖析扩散模型究竟学到了什么？](https://mp.weixin.qq.com/s/mf-bGv9i7pypHYKbU7U1Ng)  |
| Image-and-Language Understanding from Pixels Only |  | __`GEN`__ __`I2T`__  __`MultiModal`__ __`ILU`__  |       | - | [CLIPPO：利用Transformer建立多模态模型新范式！](https://mp.weixin.qq.com/s/HZcAMMiiduwxUwaBqjWgCw)  |
| GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models |  | __`GEN`__ __`T2I`__  __`ImgGen`__ |       | [GitHub![](https://img.shields.io/github/stars/openai/glide-text2im?style=social)](https://github.com/openai/glide-text2im)  | [OpenAI 年度最新力作 GLIDE：新生代文本引导扩散模型](https://mp.weixin.qq.com/s/sDd1A3HBqKgMnrNSooOqcw)  |

## Blogs 

## Libraies


# Awesome Network Architectures And Techniques
## Articles And Interpretation
| Type |  简称 |   |   |   |   |   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  | | |
|  | CNN | Trans | CNN&Trans | RNN | GEN | Other |
| 网络类型 | CNN | Transformer | CNN + Transformer | RNN |  GAN/Diffusion | GNN... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Sup | UnSup | Self | Semi | Meta | Other |
| 监督方式 |  Supervised Learning |  Unsupervised Learning | Self-Supervised Learning | Semi-Supervised Learning |  Meta Learning | Weakly-Supervised... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | NAS | Distill | Pruning | Quant | Transfer | Other |
| 任务类型 | Neural Architecture Search | Knowledge Distillation |  Network Pruning  | Network Quantization |  Transfer Learning | Reinforcement Learning... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | MultiModal |  | - | - | - | Other |
|  其他特性 | MultiModal Learning |   | - | - | - | - |



| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     
|Rethinking Vision Transformers for MobileNet Size and Speed | NeurIPs 2022 | __`Trans`__ __`Sup`__   |  -   |[GitHub![](https://img.shields.io/github/stars/snap-research/EfficientFormer?style=social)](https://github.com/snap-research/EfficientFormer) | [EfficientFormerV2: Transformer家族中的MobileNet](https://mp.weixin.qq.com/s/CWir9KFQ_W34kJ_bMeY5KQ)  |
|FlexiViT: One Model for All Patch Sizes |  | __`Trans`__ __`Sup`__   |  -   |[GitHub![](https://img.shields.io/github/stars/google-research/big_vision?style=social)](https://github.com/google-research/big_vision) | [FlexiViT: 谷歌手把手教你如何灵活切片](https://mp.weixin.qq.com/s/melu4UePAq301dZpjxsL2A)  |
|ConvNeXt V2: Co-designing and Scaling ConvNets with Masked Autoencoders |  | __`CNN`__ __`Sup`__   |  -   |[GitHub![](https://img.shields.io/github/stars/facebookresearch/ConvNeXt-V2?style=social)](https://github.com/facebookresearch/ConvNeXt-V2) | [ConvNeXt-V2：当 MAE 遇见 ConvNeXt 会碰撞出怎样的火花？](https://mp.weixin.qq.com/s/6msbFRNpsO9BVL7-yi-wYA)  |

## Blogs 
## Libraies


# Awesome Optimization Methods
## Articles And Interpretation
| Type |  简称 |   |   |   |   |   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  | | |
|  | CNN | Trans | CNN&Trans | RNN | GEN | Other |
| 网络类型 | CNN | Transformer | CNN + Transformer | RNN |  GAN/Diffusion | GNN... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Sup | UnSup | Self | Semi | Meta | Other |
| 监督方式 |  Supervised Learning |  Unsupervised Learning | Self-Supervised Learning | Semi-Supervised Learning |  Meta Learning | Weakly-Supervised... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Loss | Data | - | - | - | Other |
| 任务类型 | Loss Function  | Data Augmentation |  -  | - |  - | ... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | MultiModal |  | - | - | - | Other |
|  其他特性 | MultiModal Learning |   | - | - | - | - |



| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     
|LMFLOSS: A Hybrid Loss For Imbalanced Medical Image Classification |  | __`CNN`__ __`Loss`__   |  -   | | [LMFLOSS：用于解决不平衡医学图像分类的新型混合损失函数](https://mp.weixin.qq.com/s/G8hyI4F-WWpcPG4UYPbfdQ)  |

## Blogs 
## Libraies

# Awesome Face Recognition
## Articles And Interpretation
| Type |  简称 |   |   |   |   |   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  | | |
|  | CNN | Trans | CNN&Trans | RNN | GEN | Other |
| 网络类型 | CNN | Transformer | CNN + Transformer | RNN |  GAN/Diffusion | GNN... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Sup | UnSup | Self | Semi | FSL | ZSL |
| 监督方式 |  Supervised Learning |  Unsupervised Learning | Self-Supervised Learning | Semi-Supervised Learning |  Few-shot Learning | Zero-shot Learning |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | - | - | - | - | - | - |
| 任务类型 |  - |  -  | -| - | -| -... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | - | - | - | - | - | - |
|  其他特性 | - | - | - | - | - | - |

| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     
|BoundaryFace: A mining framework with noise label self-correction for Face Recognition | ECCV 2022 | __`CNN`__   |      |[GitHub![](https://img.shields.io/github/stars/SWJTU-3DVision/BoundaryFace?style=social)](https://github.com/SWJTU-3DVision/BoundaryFace) | [人脸识别新方法 BoundaryFace：一种基于噪声标签自校正框架(附源码实现)](https://mp.weixin.qq.com/s/U0luh7njdp2e3AjKoNfZbQ)  |
## Blogs 
## Libraies