# Diffusion Models in Medical Imaging

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

:fire::fire:This is a collection of awesome articles about diffusion models in the medical imaging:fire::fire:

## Contents
- [Survey Papers in Vision](#survey-papers-in-vision)

- [Papers](#papers)
  - [Anomaly Detection](#anomaly-detection)
  - [Denoising](#denoising)
  - [Segmentation](#segmentation)
  - [Image-to-Image Translation](#image-to-image-translation)
  - [Reconstruction](#reconstruction)
  - [Image Generation](#image-generation)
  - [Biology and Molecular Generation](#biology-and-molecular-generation)
  - [Inpainting](#inpainting)
  - [Adversarial Attacks](#adversarial-attacks)
  - [Text-to-Image](#text-to-image)
  - [Time Series](#time-series)
  - [Multi-task](#multi-task)
  
## Survey Papers in Vision

**Efficient Diffusion Models for Vision: A Survey** \
*Anwaar Ulhaq, Naveed Akhtar, Ganna Pogrebna* \
[7th Oct., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2210.09292)]

**Diffusion Models in Vision: A Survey** \
*Florinel-Alin Croitoru, Vlad Hondru, Radu Tudor Ionescu, Mubarak Shah* \
[10th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/pdf/2209.04747.pdf)] [[Github](https://github.com/CroitoruAlin/Diffusion-Models-in-Vision-A-Survey)]

**A Survey on Generative Diffusion Model** \
*Hanqun Cao, Cheng Tan, Zhangyang Gao, Guangyong Chen, Pheng-Ann Heng, Stan Z. Li* \
[6th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/pdf/2209.02646.pdf)] [[Github](https://github.com/chq1155/A-Survey-on-Generative-Diffusion-Model)]

**Diffusion Models: A Comprehensive Survey of Methods and Applications** \
*Ling Yang, Zhilong Zhang, Yang Song, Shenda Hong, Runsheng Xu, Yue Zhao, Yingxia Shao, Wentao Zhang, Bin Cui, Ming-Hsuan Yang* \
[2nd Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/pdf/2209.00796)] [[Github](https://github.com/YangLing0818/Diffusion-Models-Papers-Survey-Taxonomy)]

## Papers

### Anomaly Detection

**What is Healthy? Generative Counterfactual Diffusion for Lesion Localization** \
*Pedro Sanchez, Antanas Kascenas, Xiao Liu, Alison Q. O'Neil, Sotirios A. Tsaftaris* \
[25th Jul., 2022] [MICCAI Workshop, 2022] \
[[Paper](https://arxiv.org/abs/2207.12268)] [[Github](https://github.com/vios-s/Diff-SCM)]

**AnoDDPM: Anomaly Detection with Denoising Diffusion Probabilistic Models using Simplex Noise** \
*Julian Wyatt, Adam Leach, Sebastian M. Schmon, Chris G. Willcocks* \
[1st Jun., 2022] [CVPR Workshop, 2022] \
[[Paper](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Wyatt_AnoDDPM_Anomaly_Detection_With_Denoising_Diffusion_Probabilistic_Models_Using_Simplex_CVPRW_2022_paper.pdf)] [[Github](https://github.com/Julian-Wyatt/AnoDDPM)]

**The Swiss Army Knife for Image-to-Image Translation: Multi-Task Diffusion Models** \
*Julia Wolleb, Robin Sandkühler, Florentin Bieder, Philippe C. Cattin* \
[6th Apr., 2022] [arXiv, 2022]<br>
[[Paper](https://arxiv.org/abs/2204.02641)]

**Diffusion Models for Medical Anomaly Detection** <br>
*Julia Wolleb, Florentin Bieder, Robin Sandkühler, Philippe C. Cattin*<br>
[8th Mar., 2022] [MICCAI, 2022]<br>
[[Paper](https://arxiv.org/abs/2203.04306)] [[Github](https://github.com/JuliaWolleb/diffusion-anomaly)]
 
---

### Denoising

**Low-Dose CT Using Denoising Diffusion Probabilistic Model for 20× Speedup** \
*Wenjun Xia, Qing Lyu, Ge Wang* \
[29th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2209.15136)]

**Unsupervised Denoising of Retinal OCT with Diffusion Probabilistic Model** \
*Dewei Hu, Yuankai K. Tao, Ipek Oguz* \
[27th Jan., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2201.11760)] [[Github](https://github.com/DeweiHu/OCT_DDPM)]

**PET image denoising based on denoising diffusion probabilistic models** \
*Kuang Gong, Keith A. Johnson, Georges El Fakhri, Quanzheng Li, Tinsu Pan* \
[13th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2209.06167)]

---

### Segmentation

**Diffusion Adversarial Representation Learning for Self-supervised Vessel Segmentation** \
*Boah Kim, Yujin Oh, Jong Chul Ye* \
[19th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2209.14566)] 

**Can segmentation models be trained with fully synthetically generated data?** \
*Virginia Fernandez, Walter Hugo Lopez Pinaya, Pedro Borges, Petru-Daniel Tudosiu, Mark S Graham, Tom Vercauteren, M Jorge Cardoso* \
[17th Sep., 2022] [MICCAI Workshop , 2022] \
[[Paper](https://arxiv.org/abs/2209.08256)] 

**Diffusion Models for Implicit Image Segmentation Ensembles** \
*Julia Wolleb, Robin Sandkühler, Florentin Bieder, Philippe Valmaggia, Philippe C. Cattin* \
[6th Dec., 2021] [MIDL, 2021] \
[[Paper](https://arxiv.org/abs/2112.03145)][[Github](https://github.com/juliawolleb/diffusion-based-segmentation)]

---

### Image-to-Image Translation

**Conversion Between CT and MRI Images Using Diffusion and Score-Matching Models** \
*Qing Lyu, Ge Wang* \
[24th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2209.12104)] 

**Unsupervised Medical Image Translation with Adversarial Diffusion Models** \
*Muzaffer Özbey, Salman UH Dar, Hasan A Bedel, Onat Dalmaz, Şaban Özturk, Alper Güngör, Tolga Çukur* \
[17th Jul., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2207.08208)]

**A Novel Unified Conditional Score-based Generative Framework for Multi-modal Medical Image Completion** \
*Xiangxi Meng, Yuning Gu, Yongsheng Pan, Nizhuan Wang, Peng Xue, Mengkang Lu, Xuming He, Yiqiang Zhan, Dinggang Shen* \
[7th Jul., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2207.03430)]

**DiffuseMorph: Unsupervised Deformable Image Registration Along Continuous Trajectory Using Diffusion Models** \
*Boah Kim, Inhwa Han, Jong Chul Ye* \
[9th Dec., 2021] [ECCV, 2022] \
[[Paper](https://arxiv.org/abs/2112.05149)] 

---

### Reconstruction
 
**Self-Score: Self-Supervised Learning on Score-Based Models for MRI Reconstruction** \
*Zhuo-Xu Cui, Chentao Cao, Shaonan Liu, Qingyong Zhu, Jing Cheng, Haifeng Wang, Yanjie Zhu, Dong Liang* \
[2nd Sep., 2022] [IEEE TMI, 2022] \
[[Paper](https://arxiv.org/abs/2209.00835)] 

**One-shot Generative Prior in Hankel-k-space for Parallel Imaging Reconstruction** \
*Chentao Cao, Zhuo-Xu Cui, Shaonan Liu, Dong Liang, Yanjie Zhu* \
[15th Aug., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2208.07181)] [[Github](https://github.com/yqx7150/hkgm)]

**High-Frequency Space Diffusion Models for Accelerated MRI** \
*Chentao Cao, Zhuo-Xu Cui, Shaonan Liu, Dong Liang, Yanjie Zhu* \
[10th Aug., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2208.05481)]

**Adaptive Diffusion Priors for Accelerated MRI Reconstruction** <br>
*Salman UH Dar, Şaban Öztürk, Yilmaz Korkmaz, Gokberk Elmas, Muzaffer Özbey, Alper Güngör, Tolga Çukur*<br>
[12th Jul., 2022] [arXiv, 2022]<br>
[[Paper](https://arxiv.org/abs/2207.05876)]

**Improving Diffusion Models for Inverse Problems using Manifold Constraints** \
*Hyungjin Chung, Byeongsu Sim, Dohoon Ryu, Jong Chul Ye* \
[2nd Jun., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2206.00941)] 

**WKGM: Weight-K-space Generative Model for Parallel Imaging Reconstruction** \
*Hyungjin Chung, Byeongsu Sim, Dohoon Ryu, Jong Chul Ye* \
[8th May, 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2205.03883)] [[Github](https://github.com/yqx7150/wkgm)]

**Towards performant and reliable undersampled MR reconstruction via diffusion model sampling**<br>
*Cheng Peng, Pengfei Guo, S. Kevin Zhou, Vishal Patel, Rama Chellappa*<br>
 [8th Mar., 2022] [MICCAI, 2022]<br>
 [[Paper](https://arxiv.org/abs/2203.04292)] [[Github](https://github.com/cpeng93/diffuserecon)]
 
**Measurement-conditioned Denoising Diffusion Probabilistic Model for Under-sampled Medical Image Reconstruction**<br>
*Yutong Xie, Quanzheng Li*<br>
 [5th Mar., 2022] [MICCAI, 2022]<br>
 [[Paper](https://arxiv.org/abs/2203.03623)] [[Github](https://github.com/Theodore-PKU/MC-DDPM)]
 
**MRI Reconstruction via Data Driven Markov Chain with Joint Uncertainty Estimation**<br>
*Guanxiong Luo, Martin Heide, Martin Uecker*<br>
 [3rd Feb., 2022] [arXiv, 2022]<br>
 [[Paper](https://arxiv.org/abs/2202.01479)] [[Github](https://github.com/mrirecon/spreco)]

**Come-Closer-Diffuse-Faster: Accelerating Conditional Diffusion Models for Inverse Problems through Stochastic Contraction** <br>
*Hyungjin Chung, Byeongsu Sim, Jong Chul Ye*<br>
[9th Dec., 2021] [CVPR, 2021]<br>
[[Paper](https://arxiv.org/abs/2112.05146)]

**Solving Inverse Problems in Medical Imaging with Score-Based Generative Models**<br>
*Yang Song, Liyue Shen, Lei Xing, Stefano Ermon*<br>
[15th Nov., 2021] [NeurIPS Workshop, 2021] <br>
 [[Paper](https://arxiv.org/abs/2111.08005)] [[Github](https://github.com/yang-song/score_inverse_problems)]
 
**Score-based diffusion models for accelerated MRI** <br>
*Hyungjin Chung, Jong chul Ye*<br>
[8th Oct., 2021] [MIA, 2021]<br>
[[Paper](https://arxiv.org/abs/2111.08005)] [[Github](https://github.com/yang-song/score_inverse_problems)]

**Robust Compressed Sensing MRI with Deep Generative Priors** <br>
*Ajil Jalal, Marius Arvinte, Giannis Daras, Eric Price, Alexandros G. Dimakis, Jonathan I. Tamir*<br>
[3rd Aug., 2021] [NeurIPS, 2021]<br>
[[Paper](https://arxiv.org/abs/2111.08005)] [[Github](https://github.com/utcsilab/csgm-mri-langevin)]

---

### Image Generation

**A Morphology Focused Diffusion Probabilistic Model for Synthesis of Histopathology Images** \
*Puria Azadi Moghadam, Sanne Van Dalen, Karina C. Martin, Jochen Lennerz, Stephen Yip, Hossein Farahani, Ali Bashashati* \
[27th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2209.13167)] 

**Brain Imaging Generation with Latent Diffusion Models** \
*Walter H. L. Pinaya, Petru-Daniel Tudosiu, Jessica Dafflon, Pedro F da Costa, Virginia Fernandez, Parashkev Nachev, Sebastien Ourselin, M. Jorge Cardoso* \
[15th Sep., 2022] [MICCAI Workshop, 2022] \
[[Paper](https://arxiv.org/abs/2209.07162)] 

**A Diffusion Model Predicts 3D Shapes from 2D Microscopy Images** \
*Dominik J. E. Waibel, Ernst Röell, Bastian Rieck, Raja Giryes, Carsten Marr* \
[30th Aug., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2208.14125)] [[Github](https://github.com/marrlab/dispr)]

**Diffusion Deformable Model for 4D Temporal Medical Image Generation** \
*Boah Kim, Jong Chul Ye* \
[27th Jan., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2206.13295)] [[Github](https://github.com/torchddm/ddm)]

**Three-Dimensional Medical Image Synthesis with Denoising Diffusion Probabilistic Models** \
*Zolnamar Dorjsembe, Sodtavilan Odonchimed, Furen Xiao* \
[22nd Apr., 2022] [MIDL, 2022] \
[[Paper](https://arxiv.org/abs/2206.13295)] [[Github](https://github.com/torchddm/ddm)]

---

### Biology and Molecular Generation

**Protein Sequence and Structure Co-Design with Equivariant Translation** \
*Chence Shi, Chuanrui Wang, Jiarui Lu, Bozitao Zhong, Jian Tang* \
[17th Oct., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2210.08761)]

**Equivariant 3D-Conditional Diffusion Models for Molecular Linker Design** \
*Ilia Igashov, Hannes Stärk, Clément Vignac, Victor Garcia Satorras, Pascal Frossard, Max Welling, Michael Bronstein, Bruno Correia* \
[11th Oct., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2210.05274)] [[Github](https://github.com/igashov/difflinker)]

**Dynamic-Backbone Protein-Ligand Structure Prediction with Multiscale Generative Diffusion Models** \
*Zhuoran Qiao, Weili Nie, Arash Vahdat, Thomas F. Miller III, Anima Anandkumar* \
[30th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2209.15171)] 

**Equivariant Energy-Guided SDE for Inverse Molecular Design** \
*Fan Bao, Min Zhao, Zhongkai Hao, Peiyao Li, Chongxuan Li, Jun Zhu* \
[30th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2209.15408)]

**Protein structure generation via folding diffusion** \
*Kevin E. Wu, Kevin K. Yang, Rianne van den Berg, James Y. Zou, Alex X. Lu, Ava P. Amini* \
[30th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2209.15611)] 

**MDM: Molecular Diffusion Model for 3D Molecule Generation** \
*Lei Huang, Hengtong Zhang, Tingyang Xu, Ka-Chun Wong* \
[13th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2209.05710)] 

**Diffusion-based Molecule Generation with Informative Prior Bridges** \
*Lemeng Wu, Chengyue Gong, Xingchao Liu, Mao Ye, Qiang Liu* \
[2nd Sep., 2022] [NeurIPS, 2022] \
[[Paper](https://arxiv.org/abs/2209.00865)]

**Antigen-Specific Antibody Design and Optimization with Diffusion-Based Generative Models** \
*Shitong Luo, Yufeng Su, Xingang Peng, Sheng Wang, Jian Peng, Jianzhu Ma* \
[11th Jul., 2022] [BioRXiv, 2022] \
[[Paper](https://www.biorxiv.org/content/10.1101/2022.07.10.499510v1)]

**Diffusion probabilistic modeling of protein backbones in 3D for the motif-scaffolding problem** \
*Brian L. Trippe, Jason Yim, Doug Tischer, Tamara Broderick, David Baker, Regina Barzilay, Tommi Jaakkola* \
[8th Jun., 2022] [CoRR, 2022] \
[[Paper](https://arxiv.org/abs/2206.04119)] 

**Torsional Diffusion for Molecular Conformer Generation** \
*Bowen Jing, Gabriele Corso, Regina Barzilay, Tommi S. Jaakkola* \
[1st Jun., 2022] [ICLR Workshop, 2022] \
[[Paper](https://arxiv.org/abs/2206.01729)] [[Github](https://github.com/gcorso/torsional-diffusion)]

**Protein Structure and Sequence Generation with Equivariant Denoising Diffusion Probabilistic Models** \
*Namrata Anand, Tudor Achim* \
[26th May, 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2205.15019)] [[Github](https://github.com/lucidrains/ddpm-ipa-protein-generation)] [[Project](https://nanand2.github.io/proteins/)]

**A Score-based Geometric Model for Molecular Dynamics Simulations** \
*Fang Wu, Qiang Zhang, Xurui Jin, Yinghui Jiang, Stan Z. Li* \
[19th Apr., 2022] [CoRR, 2022] \
CoRR 2022. [[Paper](https://arxiv.org/abs/2204.08672)] 

**Equivariant Diffusion for Molecule Generation in 3D** \
*Emiel Hoogeboom, Victor Garcia Satorras, Clément Vignac, Max Welling* \
[31st Mar., 2022] [ICML, 2022] \
[[Paper](https://arxiv.org/abs/2203.17003)] [[Github](https://github.com/ehoogeboom/e3_diffusion_for_molecules)] 

**GeoDiff: a Geometric Diffusion Model for Molecular Conformation Generation** \
*Minkai Xu, Lantao Yu, Yang Song, Chence Shi, Stefano Ermon, Jian Tang* \
[6th Mar., 2022] [ICLR, 2022] \
[[Paper](https://arxiv.org/abs/2203.02923)] [[Github](https://github.com/MinkaiXu/GeoDiff)]

**Crystal Diffusion Variational Autoencoder for Periodic Material Generation** \
*Tian Xie, Xiang Fu, Octavian-Eugen Ganea, Regina Barzilay, Tommi Jaakkola*\
[12th Oct., 2021] [NeurIPS, 2021] \
[[Paper](https://arxiv.org/abs/2110.06197)] [[Github](https://github.com/txie-93/cdvae)]

**Predicting Molecular Conformation via Dynamic Graph Score Matching** \
*Shitong Luo, Chence Shi, Minkai Xu, Jian Tang* \
[22th May, 2021] [NeurIPS, 2021] \
[[Paper](https://proceedings.neurips.cc/paper/2021/hash/a45a1d12ee0fb7f1f872ab91da18f899-Abstract.html)]


---

### Inpainting

**Multitask Brain Tumor Inpainting with Diffusion Models: A Methodological Report** \
*Pouria Rouzrokh, Bardia Khosravi, Shahriar Faghani, Mana Moassefi, Sanaz Vahdati, Bradley J. Erickson* \
[21st Oct., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2210.12113)] [[Github](https://github.com/Mayo-Radiology-Informatics-Lab/MBTI)] [[Online Tool](https://1f1f559d51c361e2.gradio.app/)]

---

### Adversarial Attacks

**Fight Fire With Fire: Reversing Skin Adversarial Examples by Multiscale Diffusive and Denoising Aggregation Mechanism** \
*Yongwei Wang, Yuan Li, Zhiqi Shen* \
[22nd Aug., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2208.10373)]

---

### Text-to-Image

**Adapting Pretrained Vision-Language Foundational Models to Medical Imaging Domains** \
*Pierre Chambon, Christian Bluethgen, Curtis P. Langlotz, Akshay Chaudhari* \
[9th Oct., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2210.04133)]

---

### Time Series

**Restoration of Time-Series Medical Data with Diffusion Model** \
*Jiwoon Lee, Cheolsoo Park* \
[6th Oct., 2022] [arXiv, 2022] \
[[Paper](https://www.researchgate.net/profile/Jiwoon-Lee-3/publication/363520751_Restoration_of_Time-Series_Medical_Data_with_Diffusion_Model/links/63210895071ea12e362ee672/Restoration-of-Time-Series-Medical-Data-with-Diffusion-Model.pdf)]

---

### Multi-task

**Anatomically constrained CT image translation for heterogeneous blood vessel segmentation** \
*Giammarco La Barbera, Haithem Boussaid, Francesco Maso, Sabine Sarnacki, Laurence Rouet, Pietro Gori, Isabelle Bloch* \
[4th Oct., 2022] [BMVC, 2022] \
[[Paper](https://arxiv.org/abs/2210.01713)]

**Fast Unsupervised Brain Anomaly Detection and Segmentation with Diffusion Models** \
*Walter H. L. Pinaya, Mark S. Graham, Robert Gray, Pedro F Da Costa, Petru-Daniel Tudosiu, Paul Wright, Yee H. Mah, Andrew D. MacKinnon, James T. Teo, Rolf Jager, David Werring, Geraint Rees, Parashkev Nachev, Sebastien Ourselin, M. Jorge Cardos* \
[7th Jun., 2022] [MICCAI, 2022] \
[[Paper](https://arxiv.org/abs/2206.03461)] 

**MR Image Denoising and Super-Resolution Using Regularized Reverse Diffusion** \
*Hyungjin Chung, Eun Sun Lee, Jong Chul Ye* \
[23rd Mar., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2203.12621)]

