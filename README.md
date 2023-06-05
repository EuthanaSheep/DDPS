# DDPS

[`Arxiv`]() | [`Demo with InternGPT`](https://github.com/OpenGVLab/InternGPT)

Official Implementation of **DDPS** (Denoising Diffusion Prior for Segmentation).

> **Denoising Diffusion Semantic Segmentation with Mask Prior Modeling**
> <br/>
> Zeqiang Lai, Yuchen duan, Jifeng Dai, Ziheng Li, Ying Fu, Hongsheng Li, Yu Qiao, and Wenhai Wang

<img width="700" alt="arch" src="https://github.com/OpenGVLab/DDPS/assets/26198430/769ad1f2-d5b9-442e-bd0a-9211be705dc1">

## **Abstract**

> The evolution of semantic segmentation has long been dominated by learning more discriminative image representations for classifying each pixel. Despite the prominent advancements, the priors of segmentation masks themselves, e.g., geometric and semantic constraints, are still under-explored. In this paper, we propose to ameliorate the semantic segmentation quality of existing discriminative approaches with a mask prior modeled by a recently developed denoising diffusion generative model. Beginning with a unified architecture that adapts diffusion models for mask prior modeling, we focus this work on a specific instantiation with discrete diffusion and identify a variety of key design choices for its successful application. Our exploratory analysis revealed several important findings, including: (1) a simple integration of diffusion models into semantic segmentation is not sufficient, and a poorly-designed diffusion process might lead to degradation in segmentation performance; (2) during the training, the object to which noise is added is more important than the type of noise; (3) during the inference, the strict diffusion denoising scheme may not be essential and can be relaxed to a simpler scheme that even works better. We evaluate the proposed prior mod- eling with several off-the-shelf segmentors, and our experimental results on ADE20K and Cityscapes demonstrate that our approach could achieve competitively quantitative performance and more appealing visual quality.

## 🌟 News

- [ ] Release training code.
- [ ] Integrate an online demo of DDPS into [InternGPT](https://github.com/OpenGVLab/InternGPT).

## Evaluation

- Mask Prior Modeling

<img width="450" alt="prior" src="https://github.com/OpenGVLab/DDPS/assets/26198430/3bec572b-c2b5-4094-9fdb-b9f3fcf41333">

## Citation

If you find this work helpful, please consider cite our paper.

```bibtex
@misc{lai2023ddps,
  title = {Denoising Diffusion Semantic Segmentation with Mask Prior Modeling},
  author = {Zeqiang Lai and Yuchen duan and Jifeng Dai and Ziheng Li and Ying Fu and Hongsheng Li and Yu Qiao and Wenhai Wang},
  publisher = {arXiv},
  year = {2023},
}
```

## Acknowledgement

[MMSegmentation](https://github.com/open-mmlab/mmsegmentation) &ensp;  [VQDiffusion](https://github.com/cientgu/VQ-Diffusion)  &ensp;  [Segformer](https://github.com/NVlabs/SegFormer) &ensp; [Diffusers](https://github.com/huggingface/diffusers)

