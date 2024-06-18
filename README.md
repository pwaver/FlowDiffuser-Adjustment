# [CVPR 2024] FlowDiffuser: Advancing Optical Flow Estimation with Diffusion Models

<h4 align="center">Ao Luo<sup>1,2</sup>, Xin Li<sup>3</sup>, Fan Fang<sup>3</sup>, Jiangyu Liu<sup>2</sup>, Haoqiang Fan<sup>2</sup>, and Shuaicheng Liu<sup>4,2</sup></h4>
<h4 align="center">1. Southwest Jiaotong University &emsp; 2. Megvii Research &emsp; 3.Group 42</h4>
<h4 align="center">4. University of Electronic Science and Technology of China</h4>

This project provides the official implementation of '[**FlowDiffuser: Advancing Optical Flow Estimation with Diffusion Models**](https://openaccess.thecvf.com/content/CVPR2024/papers/Luo_FlowDiffuser_Advancing_Optical_Flow_Estimation_with_Diffusion_Models_CVPR_2024_paper.pdf)'.

## Abstract
Optical flow estimation, a process of predicting pixel-wise displacement between consecutive frames, has commonly been approached as a regression task in the age of deep learning. Despite notable advancements, this de facto paradigm unfortunately falls short in generalization performance when trained on synthetic or constrained data. Pioneering a paradigm shift, we reformulate optical flow estimation as a conditional flow generation challenge, unveiling FlowDiffuser — a new family of optical flow models that could have stronger learning and generalization capabilities. FlowDiffuser estimates optical flow through a ‘noise-to-flow’ strategy, progressively eliminating noise from randomly generated flows conditioned on the provided pairs. To optimize accuracy and efficiency, our FlowDiffuser incorporates a novel Conditional Recurrent Denoising Decoder (Conditional-RDD), streamlining the flow estimation process. It incorporates a unique Hidden State Denoising (HSD) paradigm, effectively leveraging the information from previous time steps. Moreover, FlowDiffuser can be easily integrated into existing flow networks, leading to significant improvements in performance metrics compared to conventional implementations. Experiments on challenging benchmarks, including Sintel and KITTI, demonstrate the effectiveness of our FlowDiffuser with superior performance to existing state-of-the-art models. 


## Overview

![FlowDiffuser](https://github.com/LA30/FlowDiffuser/assets/47421121/3d90bb6b-a3a0-411d-b8f6-66119f08b2b2)

![comparison](https://github.com/LA30/FlowDiffuser/assets/47421121/5463a1a7-c9bd-4596-afe5-d5b0c0ed7b40)


## Code coming soon
