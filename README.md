# Universal Depth Estimation Across Diverse Conditions

[**Paper**](https://arxiv.org/abs/2403.05056) | [**Project Page**](https://hitcslj.github.io/ssd/)

Official implementation of UDE: Universal Depth Estimation Across Diverse Conditions

[Yifan Mao](https://jluwula.github.io/), [Jian Liu](https://hitcslj.github.io/), Xianming Liu

<p align="center">All the code, datasets, and model weights will be released before December, 2024 🏗️ 🚧 🔨</p>


Abstract: *Monocular depth estimation is a pivotal task in computer vision, with broad applications across various fields. While existing deep learning-based methods have shown success in controlled environments, they often struggle in diverse real-world conditions such as variable lighting and adverse weather, leading to degraded accuracy and reliability.
In this paper, we introduce a novel framework, Universal Depth Estimation (UDE), which leverages stable diffusion priors to enhance robustness, enabling accurate depth estimation across a wide range of challenging scenarios. Central to our approach is the Generative Diffusion Translation (GDT) model, which addresses the scarcity of training data in complex conditions by jointly utilizing text and image prompts to control the generated image style while extracting structural information from the depth map. Furthermore, we improve the generalization of the knowledge distillation framework by introducing a new loss function, Reliability-Guided Distillation (RGD) Loss. This novel loss mechanism allows student models to learn more effectively from the teacher model by masking pixels with unreliable depth estimates.Our experimental results demonstrate that UDE significantly outperforms state-of-the-art methods on several challenging public datasets, establishing it as a robust solution for depth estimation under diverse conditions.*


<div align=center>
<img src="assets/ssd_pipeline.png" width="100%"/>
</div>



## Generative diffusion-model based translation
GDT translated images in nuScenes.

<!-- <div align=center>
<img src="assets/gdt_pipeline.png" width="100%"/>
</div> -->

<div align=center>
<img src="assets/gdt_results.png" width="100%"/>
</div>


## Self-supervised depth estimation results

<div align=center>
<img src="assets/self-supervised.png" width="100%"/>
</div>

## Supervised depth estimation results

<div align=center>
<img src="assets/supervised.png" width="100%"/>
</div>

## BibTeX

```bibtex
@article{mao2024stealing,
  title={Stealing Stable Diffusion Prior for Robust Monocular Depth Estimation},
  author={Mao, Yifan and Liu, Jian and Liu, Xianming},
  journal={arXiv preprint arXiv:2403.05056},
  year={2024}
}
```
