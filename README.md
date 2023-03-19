<link rel="stylesheet" type="text/css" href="./style.css">

## 关注我们
门头沟学院AI视觉实验室御用公众号 | 学术 | 科研 | 就业</p>
<p>扫描下方二维码，然后回复关键词“<b>进群</b>”，即可加入“读者交流群”</p>
<img src="https://github.com/CVHuber/awesome-cv/blob/main/640.jfif" width = "250" height = "270" alt="欢迎大家关注我们的公众号CVHub，每日都给大家带来原创、多领域、有深度的前沿AI论文解读与工业成熟解决方案！">



<font size=6><center><big><b> Awesome Computer Vision [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) </b></big></center></font>

This is a list of computer vison related resources. 

Please feel free to [pull requests](https://github.com/CVHub520/awesome-computer-vision/pulls) or [open an issue](https://github.com/CVHub520/awesome-computer-vision/issues) to add papers.

---

Table of Contents
- [Awesome Classification](#awesome-segmentation)
    - [Blogs](#awesome-segmentation-blogs)
    - [Libraies](#awesome-segmentation-libraies)
    - [Articles And Interpretation](#awesome-segmentation-articles-and-interpretation)
- [Awesome Segmentation](#awesome-segmentation)
    - [Blogs](#awesome-segmentation-blogs)
    - [Libraies](#awesome-segmentation-libraies)
    - [Articles And Interpretation](#awesome-segmentation-articles-and-interpretation)
- [Awesome Detection](#awesome-segmentation)
    - [Blogs](#awesome-segmentation-blogs)
    - [Libraies](#awesome-segmentation-libraies)
    - [Articles And Interpretation](#awesome-segmentation-articles-and-interpretation)
- [Awesome Low Level Vison](#awesome-segmentation)
    - [Blogs](#awesome-segmentation-blogs)
    - [Libraies](#awesome-segmentation-libraies)
    - [Articles And Interpretation](#awesome-segmentation-articles-and-interpretation)
- [Awesome 3D Vision](#awesome-segmentation)
    - [Blogs](#awesome-segmentation-blogs)
    - [Libraies](#awesome-segmentation-libraies)
    - [Articles And Interpretation](#awesome-segmentation-articles-and-interpretation)
- [Awesome Diffusion](#awesome-segmentation)
    - [Blogs](#awesome-segmentation-blogs)
    - [Libraies](#awesome-segmentation-libraies)
    - [Articles And Interpretation](#awesome-segmentation-articles-and-interpretation)
- [Awesome Network Architectures And Techniques)](#awesome-segmentation)
    - [Blogs](#awesome-segmentation-blogs)
    - [Libraies](#awesome-segmentation-libraies)
    - [Articles And Interpretation](#awesome-segmentation-articles-and-interpretation)
- [Awesome Optimization Methods)](#awesome-segmentation)
    - [Blogs](#awesome-segmentation-blogs)
    - [Libraies](#awesome-segmentation-libraies)
    - [Articles And Interpretation](#awesome-segmentation-articles-and-interpretation)

# Awesome Segmentation
## Awesome Segmentation Blogs 
- [语义分割大盘点](http://automl.chalearn.org/)
- [关于语义分割的亿点思考](https://zhuanlan.zhihu.com/p/595753988)

## Awesome Segmentation Libraies
- [mmsegmentation](https://github.com/open-mmlab/mmsegmentation)
- [PaddleSeg](https://github.com/open-mmlab/mmsegmentation)


## Awesome Segmentation Articles And Interpretation


| Type | C | T | CT | R | G | Other |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  网络类型 | CNN|  Transformer |  CNN + Transformer |  RNN |  GAN/Diffusion |  GNN... |


| Type | Sup | UnSup | Self | Semi | Meta | Other |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  监督方式 | Supervised Learning|  Unsupervised Learning |  Self-Supervised Learning |  Semi-Supervised Learning |  Meta Learning |  Weakly-Supervised... |



| Type | SS | IS | Vid | Med | AD | Other |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  任务 | Semantic|  Instance |  Video |  Medical |  Autonomous Driving |  Saliency... |


| Type | MM | UHR | - | - | - | Other |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  其他特性 | MultiModal Learning|  Ultra-high Resolution |  - |  - |  - |  - |







| Paper | Publication | Type | Code | 性能 |  解读 | 
| :- | :---| :---:| :---: | :---: |    :---: |     
|     |     |      |       |      |     |
| :fire::fire: Delivering Arbitrary-Modal Semantic Segmentation | CVPR 2023 | CT/Sup/SS/MM |   COCO:XXX   |[GitHub](https://github.com/jamycheung/DELIVER) | [基于编解码架构的强大语义分割基线，解锁多模态语义分割的正确姿势](https://zhuanlan.zhihu.com/p/613293738)  |
| ISDNet: Integrating Shallow and Deep Networks for Efficient Ultra-high Resolution Segmentation | CVPR 2022 | C/Sup/SS/UHR |   COCO:XXX     | [GitHub](https://github.com/cedricgsh/ISDNet) | [探索超高分辨率图像分割的高效之道](https://zhuanlan.zhihu.com/p/611138087)  |


<svg fill="none" viewBox="0 0 600 300" width="600" height="300" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        @keyframes hi  {
            0% { transform: rotate( 0.0deg) }
           10% { transform: rotate(14.0deg) }
           20% { transform: rotate(-8.0deg) }
           30% { transform: rotate(14.0deg) }
           40% { transform: rotate(-4.0deg) }
           50% { transform: rotate(10.0deg) }
           60% { transform: rotate( 0.0deg) }
          100% { transform: rotate( 0.0deg) }
        }

        .container {
          background-color: black;

          width: 100%;
          height: 300px;

          display: flex;
          justify-content: center;
          align-items: center;
          color: white;

          font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
        }

        .hi {
          animation: hi 1.5s linear -0.5s infinite;
          display: inline-block;
          transform-origin: 70% 70%;
        }

        @media (prefers-reduced-motion) {
          .hi {
            animation: none;
          }
        }
      </style>

      <div class="container">
        <h1>Hi there, my name is Nikola <div class="hi">👋</div></h1>
      </div>
    </div>
  </foreignObject>
</svg>


