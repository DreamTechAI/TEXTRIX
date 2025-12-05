# TEXTRIX: Latent Attribute Grid for Native Texture Generation and Beyond

<div align="center">
  <a href="https://www.neural4d.com/research-page/textrix/" target="_blank"><img src="https://img.shields.io/badge/Project%20Page-Website-blue?logo=googlechrome&logoColor=white" height="22px"></a>
  <a href="https://arxiv.org/abs/2512.02993" target="_blank"><img src="https://img.shields.io/badge/ArXiv-2512.02993-b31b1b?logo=arxiv&logoColor=white" height="22px"></a>
</div>

<br>

<div align="center">
    <strong>Yifei Zeng</strong><sup>1,2*</sup>&emsp;
    <strong>Yajie Bao</strong><sup>1,2*</sup>&emsp;
    <strong>Jiachen Qian</strong><sup>3,2</sup>&emsp;
    <strong>Shuang Wu</strong><sup>1,2</sup>&emsp;
    <strong>Youtian Lin</strong><sup>1</sup>&emsp;
    <br>
    <strong>Hao Zhu</strong><sup>1</sup>&emsp;
    <strong>Buyu Li</strong><sup>4</sup>&emsp;
    <strong>Feihu Zhang</strong><sup>2</sup>&emsp;
    <strong>Xun Cao</strong><sup>1</sup>&emsp;
    <strong>Yao Yao</strong><sup>1&dagger;</sup>
</div>

<div align="center">
    <br>
    <sup>1</sup>Nanjing University&emsp;
    <sup>2</sup>DreamTech&emsp;
    <sup>3</sup>HKU&emsp;
    <sup>4</sup>OriginArk
    <br>
    <small>(* Equal Contribution, &dagger; Corresponding Author)</small>
</div>

<br>

<div style="background: #fff; box-shadow: 0 4px 12px rgba(0,0,0,.15); display: inline-block; padding: 0px;">
    <img id="teaser" src="assets/teaser.png" alt="Teaser image of TEXTRIX" width="100%"/>
</div>

**Seamless texturing and precise segmentation with TEXTRIX.** Our model generates geometrically aligned textures and segmentations from a single-view input, avoiding the inter-view inconsistencies that commonly affect prevailing 3D generation.

---

## ✨ News
- **[2025/12/05]** 🚀 We have released the paper and project page!
- **[Coming Soon]** 🔨 Code and model weights will be released soon. Please stay tuned!

## 📝 Abstract

Prevailing 3D texture generation methods, which often rely on multi-view fusion, are frequently hindered by inter-view inconsistencies and incomplete coverage of complex surfaces, limiting the fidelity and completeness of the generated content. 

To overcome these challenges, we introduce **TEXTRIX**, a native 3D attribute generation framework for high-fidelity texture synthesis and downstream applications such as precise 3D part segmentation. Our approach constructs a **latent 3D attribute grid** and leverages a **Diffusion Transformer equipped with sparse attention**, enabling direct coloring of 3D models in volumetric space and fundamentally avoiding the limitations of multi-view fusion. 

Built upon this native representation, the framework naturally extends to high-precision 3D segmentation by training the same architecture to predict semantic attributes on the grid. Extensive experiments demonstrate state-of-the-art performance on both tasks, producing seamless, high-fidelity textures and accurate 3D part segmentation with precise boundaries.

## 📖 Citation

If you find our work useful for your research, please consider citing our paper:

```bibtex
@article{zeng2025textrix,
  title={TEXTRIX: Latent Attribute Grid for Native Texture Generation and Beyond},
  author={Yifei Zeng and Yajie Bao and Jiachen Qian and Shuang Wu and Youtian Lin and Hao Zhu and Buyu Li and Feihu Zhang and Xun Cao and Yao Yao},
  journal={arXiv preprint arXiv:2512.02993},
  year={2025}
}