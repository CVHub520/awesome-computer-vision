
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


# Awesome Classification
## Articles And Interpretation
## Blogs 
## Libraies


# Awesome Segmentation
## Articles And Interpretation
| Type |  简称 |   |   |   |   |   |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  | | |
|  | C | T | CT | R | G | Other |
| 网络类型 | CNN | Transformer | CNN + Transformer | RNN |  GAN/Diffusion | GNN... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | Sup | UnSup | Self | Semi | Meta | Other |
| 监督方式 |  Supervised Learning |  Unsupervised Learning | Self-Supervised Learning | Semi-Supervised Learning |  Meta Learning | Weakly-Supervised... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | SS | IS | Vid | Med | AD | Other |
| 任务类型 | Semantic Segmentation | Instance Segmentation |   Video Segmentation  | Medical Segmentation |  Autonomous Driving Segmentation | Saliency Segmentation... |
|  |  |  |  |  | | |
|  |  |  |  |  | | |
|  | MM | UHR | - | - | - | Other |
|  其他特性 | MultiModal Learning |  Ultra-high Resolution | - | - | - | - |



| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     
|     |     |      |       |      |     |
| :fire::fire: Delivering Arbitrary-Modal Semantic Segmentation | CVPR 2023 | CT/Sup/SS/MM |   COCO:XXX   |[GitHub![](https://img.shields.io/github/stars/jamycheung/DELIVER?style=social)](https://github.com/jamycheung/DELIVER) | [基于编解码架构的强大语义分割基线，解锁多模态语义分割的正确姿势](https://zhuanlan.zhihu.com/p/613293738)  |
| ISDNet: Integrating Shallow and Deep Networks for Efficient Ultra-high Resolution Segmentation | CVPR 2022 | C/Sup/SS/UHR |   COCO:XXX     | [GitHub![](https://img.shields.io/github/stars/cedricgsh/ISDNet?style=social)](https://github.com/cedricgsh/ISDNet) | [探索超高分辨率图像分割的高效之道](https://zhuanlan.zhihu.com/p/611138087)  |

https://img.shields.io/github/stars/jamycheung/DELIVER?style=social

##  Blogs 
- [语义分割大盘点](http://automl.chalearn.org/)
- [关于语义分割的亿点思考](https://zhuanlan.zhihu.com/p/595753988)

## Libraies
- [mmsegmentation](https://github.com/open-mmlab/mmsegmentation)
- [PaddleSeg](https://github.com/open-mmlab/mmsegmentation)



# Awesome Detection
## Articles And Interpretation
## Blogs 
## Libraies


# Awesome 3D Classification & Detection & Segmentation
## Articles And Interpretation
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
|  | C | T | CT | R | G | Other |
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
|  | Nt | RD | MD | RD&MD | Out | In |
|  其他特性 | Nighttime |  Relative Depth | Metric Depth | Relative & Metric Depth |Outdoor Domain | Indoor Domain |



| Paper | Publication | Type | 性能 | 代码 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     
|     |     |      |       |      |     |
|  :fire: ZoeDepth: Zero-shot Transfer by Combining Relative and Metric Depth | - | CT/ZSL/Mono/RD&MD |   NYU REL 0.075   |[GitHub![](https://img.shields.io/github/stars/isl-org/ZoeDepth?style=social)](https://github.com/isl-org/ZoeDepth) | [第一个结合相对和绝对深度的多模态单目深度估计网络](https://zhuanlan.zhihu.com/p/615166220)  |
| Lite-Mono: A Lightweight CNN and Transformer Architecture for Self-Supervised Monocular Depth Estimation | CVPR 2023 | CT/Self/Mono/RD |    KITTI REL 0.102   |[GitHub![](https://img.shields.io/github/stars/noahzn/Lite-Mono?style=social)](https://github.com/noahzn/Lite-Mono) | [一种新的轻量级自监督单目深度估计方法](https://zhuanlan.zhihu.com/p/614680720)  |


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
## Blogs 
## Libraies


# Awesome Network Architectures And Techniques
## Articles And Interpretation
## Blogs 
## Libraies


# Awesome Optimization Methods
## Articles And Interpretation
## Blogs 
## Libraies