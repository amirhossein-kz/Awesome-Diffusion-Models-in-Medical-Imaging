# Diffusion Models in Medical Imaging

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/amirhossein-kz/Awesome-Diffusion-Models-in-Medical-Imaging) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

:fire::fire:This is a collection of awesome articles about diffusion models in the medical imaging:fire::fire:

- Our survey paper on MedIA: [Diffusion Models in Medical Imaging: A Comprehensive Survey](https://www.sciencedirect.com/science/article/pii/S1361841523001068) :heart:
- Our survey paper on arXiv: [Diffusion Models for Medical Image Analysis: A Comprehensive Survey](https://arxiv.org/abs/2211.07804) :heart:

#### Citation
```python
@article{kazerouni2023diffusion,
  title={Diffusion models in medical imaging: A comprehensive survey},
  author={Kazerouni, Amirhossein and Aghdam, Ehsan Khodapanah and Heidari, Moein and Azad, Reza and Fayyaz, Mohsen and Hacihaliloglu, Ilker and Merhof, Dorit},
  journal={Medical Image Analysis},
  pages={102846},
  year={2023},
  publisher={Elsevier}
}
```

## Updates
- **Third release:** June 3, 2023
- :sunglasses: April 8, 2023: Our paper is accepted for publication in the **Medical Image Analysis Journal (IF: 13.83)** :sunglasses:
- **Second release:** March 29, 2023
- **First release:** November 14, 2022

## Contents
- [Survey Papers](#survey-papers)

- [Papers](#papers)
  - [Anomaly Detection](#anomaly-detection)
  - [Denoising](#denoising)
  - [Segmentation](#segmentation)
  - [Image-to-Image Translation](#image-to-image-translation)
  - [Reconstruction](#reconstruction)
  - [Image Generation](#image-generation)
  - [Text-to-Image](#text-to-image)
  - [Registration](#registration)
  - [Classification](#classification)
  - [Object Detection](#object-detection)
  - [Inpainting](#inpainting)
  - [Super Resolution](#super-resolution)
  - [Adversarial Attacks](#adversarial-attacks)
  - [Time Series](#time-series)
  - [Other Applications](#other-applications)
  - [Multi-task](#multi-task)
  
## Survey Papers

**Diffusion Models for Time Series Applications: A Survey** \
*Lequan Lin, Zhengkun Li, Ruikun Li, Xuliang Li, Junbin Gao* \
[1st May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.00624)]

**A Comprehensive Survey on Knowledge Distillation of Diffusion Models** \
*Weijian Luo* \
[9th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.04262)] 

**A Survey on Graph Diffusion Models: Generative AI in Science for Molecule, Protein and Material** \
*Mengchun Zhang, Maryam Qamar, Taegoo Kang, Yuna Jung, Chenshuang Zhang, Sung-Ho Bae, Chaoning Zhang* \
[4th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.01565)] 

**Audio Diffusion Model for Speech Synthesis: A Survey on Text To Speech and Speech Enhancement in Generative AI** \
*Chenshuang Zhang, Chaoning Zhang, Sheng Zheng, Mengchun Zhang, Maryam Qamar, Sung-Ho Bae, In So Kweon* \
[23th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.13336)] 

**Diffusion Models in NLP: A Survey** \
*Yuansong Zhu, Yu Zhao* \
[14th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.07576)] 

**Text-to-image Diffusion Model in Generative AI: A Survey** \
*Chenshuang Zhang, Chaoning Zhang, Mengchun Zhang, In So Kweon* \
[14th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.07909)] 

**Diffusion Models for Non-autoregressive Text Generation: A Survey** \
*Yifan Li, Kun Zhou, Wayne Xin Zhao, Ji-Rong Wen* \
[12th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.06574)] 

**Diffusion Models in Bioinformatics: A New Wave of Deep Learning Revolution in Action** \
*Zhiye Guo, Jian Liu, Yanli Wang, Mengrui Chen, Duolin Wang, Dong Xu, Jianlin Cheng* \
[13th Feb., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2302.10907)] \

**Generative Diffusion Models on Graphs: Methods and Applications** \
*Wenqi Fan, Chengyi Liu, Yunqing Liu, Jiatong Li, Hang Li, Hui Liu, Jiliang Tang, Qing Li* \
[6th Feb., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2302.02591)] 

**Diffusion Models for Medical Image Analysis: A Comprehensive Survey** \
*Amirhossein Kazerouni, Ehsan Khodapanah Aghdam, Moein Heidari, Reza Azad, Mohsen Fayyaz, Ilker Hacihaliloglu, Dorit Merhof* \
[14th Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.07804)]

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

**Mask, Stitch, and Re-Sample: Enhancing Robustness and Generalizability in Anomaly Detection through Automatic Diffusion Models** \
*Cosmin I. Bercea, Michael Neumayr, Daniel Rueckert, Julia A. Schnabel* \
[31st May, 2023][arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2305.19643)]

**Unsupervised Anomaly Detection in Medical Images Using Masked Diffusion Model** \
*Hasan Iqbal, Umar Khalid, Jing Hua, Chen Chen* \
[31st May, 2023][arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2305.19867)] [[Github](https://github.com/hasan1292/mDDPM)]

**Reversing the Abnormal: Pseudo-Healthy Generative Networks for Anomaly Detection** \
*Cosmin I Bercea, Benedikt Wiestler, Daniel Rueckert, Julia A Schnabel* \
[15th Mar., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2303.08452)]

**Patched Diffusion Models for Unsupervised Anomaly Detection in Brain MRI** \
*Finn Behrendt, Debayan Bhattacharya, Julia Krüger, Roland Opfer, Alexander Schlaefer* \
[7th Mar., 2023] [MIDL, 2023]<br>
[[Paper](https://arxiv.org/abs/2303.03758)] [[Github](https://github.com/FinnBehrendt/patched-Diffusion-Models-UAD)]

**Dissolving Is Amplifying: Towards Fine-Grained Anomaly Detection** \
*Jian Shi, Pengyi Zhang, Ni Zhang, Hakim Ghazzai, Yehia Massoud* \
[28th Feb., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2302.14696)]

**The role of noise in denoising models for anomaly detection in medical images** \
*Antanas Kascenas, Pedro Sanchez, Patrick Schrempf, Chaoyang Wang, William Clackett, Shadia S. Mikhael, Jeremy P. Voisey, Keith Goatman, Alexander Weir, Nicolas Pugeault, Sotirios A. Tsaftaris, Alison Q. O'Neil* \
[19th Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.08330)] [[Github](https://github.com/AntanasKascenas/DenoisingAE)]

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

**A Diffusion Probabilistic Prior for Low-Dose CT Image Denoising** \
*Xuan Liu, Yaoqin Xie, Songhui Diao, Shan Tan, Xiaokun Liang* \
[25th May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.15887)]

**CoreDiff: Contextual Error-Modulated Generalized Diffusion Model for Low-Dose CT Denoising and Generalization** \
*Qi Gao, Zilong Li, Junping Zhang, Yi Zhang, Hongming Shan* \
[4th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.01814)]

**DDM2: Self-Supervised Diffusion MRI Denoising with Generative Diffusion Models** \
*Tiange Xiang, Mahmut Yurt, Ali B Syed, Kawin Setsompop, Akshay Chaudhari* \
[6th Feb., 2023] [ICLR, 2023] \
[[Paper](https://arxiv.org/abs/2302.03018)] [[Github](https://github.com/StanfordMIMI/DDM2)]

**Low-Dose CT Using Denoising Diffusion Probabilistic Model for 20× Speedup** \
*Wenjun Xia, Qing Lyu, Ge Wang* \
[29th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2209.15136)]

**PET image denoising based on denoising diffusion probabilistic models** \
*Kuang Gong, Keith A. Johnson, Georges El Fakhri, Quanzheng Li, Tinsu Pan* \
[13th Sep., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2209.06167)]

**Unsupervised Denoising of Retinal OCT with Diffusion Probabilistic Model** \
*Dewei Hu, Yuankai K. Tao, Ipek Oguz* \
[27th Jan., 2022] [Medical Imaging 2022: Image Processing] \
[[Paper](https://arxiv.org/abs/2201.11760)] [[Github](https://github.com/DeweiHu/OCT_DDPM)]

---

### Segmentation

**Brain tumor segmentation using synthetic MR images -- A comparison of GANs and diffusion models** \
*Muhammad Usman Akbar, Måns Larsson, and Anders Eklund* \
[5th Jun., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.02986)]

**Semi-supervised Brain Tumor Segmentation Using Diffusion Models** \
*Ahmed Alshenoudy, Bertram Sabrowsky-Hirsch, Stefan Thumfart, Michael Giretzlehner, Erich Kobler* \
[1st Jun., 2023] [AIAI, 2023] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-34111-3_27)] [[Github](https://github.com/risc-mi/braintumor-ddpm)]

**Multi-Level Global Context Cross Consistency Model for Semi-Supervised Ultrasound Image Segmentation with Diffusion Model** \
*Fenghe Tang, Jianrui Ding, Lingtao Wang, Min Xian, Chunping Ning* \
[16th May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.09447)] [[Github](https://github.com/FengheTan9/Multi-Level-Global-Context-Cross-Consistency)]

**Unsupervised Discovery of 3D Hierarchical Structure with Generative Diffusion Features** \
*Nurislam Tursynbek, Marc Niethammer* \
[28th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.00067)]

**DiffuseExpand: Expanding dataset for 2D medical image segmentation using diffusion models** \
*Shitong Shao, Xiaohan Yuan, Zhen Huang, Ziming Qiu, Shuai Wang, Kevin Zhou* \
[26th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.13416)] [[Github](https://anonymous.4open.science/r/DiffuseExpand/README.md)]

**Ambiguous Medical Image Segmentation using Diffusion Models** \
*Aimon Rahman, Jeya Maria Jose Valanarasu, Ilker Hacihaliloglu, Vishal M Patel* \
[10th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.04745)] [[Github](https://github.com/aimansnigdha/Ambiguous-Medical-Image-Segmentation-using-Diffusion-Models)]

**BerDiff: Conditional Bernoulli Diffusion Model for Medical Image Segmentation** \
*Tao Chen, Chenhui Wang, Hongming Shan* \
[10th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.04429)]

**Diffusion Models for Memory-efficient Processing of 3D Medical Images** \
*Florentin Bieder, Julia Wolleb, Alicia Durrer, Robin Sandkühler, Philippe C. Cattin* \
[27th Mar., 2023] [MIDL, 2023] \
[[Paper](https://arxiv.org/abs/2303.15288)]

**Distribution Aligned Diffusion and Prototype-guided network for Unsupervised Domain Adaptive Segmentation** \
*Haipeng Zhou, Lei Zhu, Yuyin Zhou* \
[22nd Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.12313)] [[Github](https://github.com/haipengzhou856/DPNet)]

**Diff-UNet: A Diffusion Embedded Network for Volumetric Segmentation** \
*Zhaohu Xing, Liang Wan, Huazhu Fu, Guang Yang, Lei Zhu* \
[18th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.10326)] [[Github](https://github.com/ge-xing/Diff-UNet)]

**Stochastic Segmentation with Conditional Categorical Diffusion Models** \
*Lukas Zbinden, Lars Doorenbos, Theodoros Pissas, Raphael Sznitman, Pablo Márquez-Neila* \
[15th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.08888)] [[Github](https://github.com/LarsDoorenbos/ccdm-stochastic-segmentation)]

**Importance of Aligning Training Strategy with Evaluation for Diffusion Models in 3D Multiclass Segmentation** \
*Yunguan Fu, Yiwen Li, Shaheer U. Saeed, Matthew J. Clarkson, Yipeng Hu* \
[10th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.06040)] [[Github](https://github.com/mathpluscode/ImgX-DiffSeg)]

**Score-Based Generative Models for Medical Image Segmentation using Signed Distance Functions** \
*Lea Bogensperger, Dominik Narnhofer, Filip Ilic, Thomas Pock* \
[10th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.05966)]

**MedSegDiff-V2: Diffusion based Medical Image Segmentation with Transformer** \
*Junde Wu, Rao Fu, Huihui Fang, Yu Zhang, Yanwu Xu* \
[19th Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.11798)] [[Github](https://github.com/WuJunde/MedSegDiff)]

**Improved HER2 Tumor Segmentation with Subtype Balancing using Deep Generative Networks** \
*Mathias Öttl, Jana Mönius, Matthias Rübner, Carol I. Geppert, Jingna Qiu, Frauke Wilm, Arndt Hartmann, Matthias W. Beckmann, Peter A. Fasching, Andreas Maier, Ramona Erber, Katharina Breininger* \
[11th Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.06150)] 

**MedSegDiff: Medical Image Segmentation with Diffusion Probabilistic Model** \
*Junde Wu, Huihui Fang, Yu Zhang, Yehui Yang, Yanwu Xu* \
[1st Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.00611)] [[Github](https://github.com/WuJunde/MedSegDiff)]

**Accelerating Diffusion Models via Pre-segmentation Diffusion Sampling for Medical Image Segmentation** \
*Xutao Guo, Yanwu Yang, Chenfei Ye, Shang Lu, Yang Xiang, Ting Ma* \
[27th Oct., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2210.17408)] 

**Diffusion Adversarial Representation Learning for Self-supervised Vessel Segmentation** \
*Boah Kim, Yujin Oh, Jong Chul Ye* \
[19th Sep., 2022] [ICLR, 2023] \
[[Paper](https://arxiv.org/abs/2209.14566)] 

**Can segmentation models be trained with fully synthetically generated data?** \
*Virginia Fernandez, Walter Hugo Lopez Pinaya, Pedro Borges, Petru-Daniel Tudosiu, Mark S Graham, Tom Vercauteren, M Jorge Cardoso* \
[17th Sep., 2022] [MICCAI Workshop , 2022] \
[[Paper](https://arxiv.org/abs/2209.08256)] 

**Diffusion Models for Implicit Image Segmentation Ensembles** \
*Julia Wolleb, Robin Sandkühler, Florentin Bieder, Philippe Valmaggia, Philippe C. Cattin* \
[6th Dec., 2021] [MIDL, 2022] \
[[Paper](https://arxiv.org/abs/2112.03145)] [[Github](https://github.com/juliawolleb/diffusion-based-segmentation)]

---

### Image-to-Image Translation

**Cycle-guided Denoising Diffusion Probability Model for 3D Cross-modality MRI Synthesis** \
*Shaoyan Pan, Chih-Wei Chang, Junbo Peng, Jiahan Zhang, Richard L.J. Qiu, Tonghe Wang, Justin Roper, Tian Liu, Hui Mao, Xiaofeng Yang* \
[28th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.00042)]

**Zero-shot Medical Image Translation via Frequency-Guided Diffusion Models** \
*Yunxiang Li, Hua-Chieh Shao, Xiao Liang, Liyuan Chen, Ruiqi Li, Steve Jiang, Jing Wang, You Zhang* \
[5th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.02742)] [[Github](https://github.com/Kent0n-Li/FGDM)]

**Class-Guided Image-to-Image Diffusion: Cell Painting from Brightfield Images with Class Labels** \
*Jan Oscar Cross-Zamirski, Praveen Anand, Guy Williams, Elizabeth Mouchet, Yinhai Wang, Carola-Bibiane Schönlieb* \
[15th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.08863)] [[Github](https://github.com/crosszamirski/guided-I2I)]

**Diffusion Models for Contrast Harmonization of Magnetic Resonance Images** \
*Alicia Durrer, Julia Wolleb, Florentin Bieder, Tim Sinnecker, Matthias Weigel, Robin Sandkühler, Cristina Granziera, Özgür Yaldizli, Philippe C. Cattin* \
[14th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.08189)] 

**Zero-shot-Learning Cross-Modality Data Translation Through Mutual Information Guided Stochastic Diffusion** \
*Zihao Wang, Yingyu Yang, Maxime Sermesant, Hervé Delingette, Ona Wu* \
[31st Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.13743)] 

**Brain PET Synthesis from MRI Using Joint Probability Distribution of Diffusion Model at Ultrahigh Fields** \
*Xie Taofeng, Cao Chentao, Cui Zhuoxu, Li Fanshi, Wei Zidong, Zhu Yanjie, Li Ye, Liang Dong, Jin Qiyu, Chen Guoqing, Wang Haifeng* \
[16th Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.08901)] 

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

---

### Reconstruction

**Solving Inverse Problems with Score-Based Generative Priors learned from Noisy Data** \
*Asad Aali, Marius Arvinte, Sidharth Kumar, Jonathan I. Tamir* \
[2nd May., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.01166)]

**SPIRiT-Diffusion: Self-Consistency Driven Diffusion Model for Accelerated MRI** \
*Zhuo-Xu Cui, Chentao Cao, Jing Cheng, Sen Jia, Hairong Zheng, Dong Liang, Yanjie Zhu* \
[11th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.05060)]

**Sub-volume-based Denoising Diffusion Probabilistic Model for Cone-beam CT Reconstruction from Incomplete Data** \
*Wenjun Xia, Chuang Niu, Wenxiang Cong, Ge Wang* \
[22nd Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.12861)]

**Improving 3D Imaging with Pre-Trained Perpendicular 2D Diffusion Models** \
*Suhyeon Lee, Hyungjin Chung, Minyoung Park, Jonghyuk Park, Wi-Sun Ryu, Jong Chul Ye* \
[15th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.08440)]

**Fast Diffusion Sampler for Inverse Problems by Geometric Decomposition** \
*Hyungjin Chung, Suhyeon Lee, Jong Chul Ye* \
[10th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.05754)]

**Diffusion Denoising for Low-Dose-CT Model** \
*Runyi Li* \
[27th Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.11482)]  

**Annealed Score-Based Diffusion Model for MR Motion Artifact Reduction** \
*Gyutaek Oh, Jeong Eun Lee, Jong Chul Ye* \
[8th Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.03027)]   

**Universal Generative Modeling in Dual-domain for Dynamic MR Imaging** \
*Chuanming Yu, Yu Guan, Ziwen Ke, Dong Liang, Qiegen Liu* \
[15th Dec., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2212.07599)]   
 
**SPIRiT-Diffusion: SPIRiT-driven Score-Based Generative Modeling for Vessel Wall imaging** \
*Chentao Cao, Zhuo-Xu Cui, Jing Cheng, Sen Jia, Hairong Zheng, Dong Liang, Yanjie Zhu* \
[14th Dec., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2212.11274)]   
 
**One Sample Diffusion Model in Projection Domain for Low-Dose CT Imaging** \
*Bin Huang, Liu Zhang, Shiyu Lu, Boyu Lin, Weiwen Wu, Qiegen Liu* \
[7th Dec., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2212.03630)]  
 
**DOLCE: A Model-Based Probabilistic Diffusion Framework for Limited-Angle CT Reconstruction** \
*Jiaming Liu, Rushil Anirudh, Jayaraman J. Thiagarajan, Stewart He, K. Aditya Mohan, Ulugbek S. Kamilov, Hyojin Kim* \
[22nd Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.12340)] 

**Solving 3D Inverse Problems using Pre-trained 2D Diffusion Models** \
*Hyungjin Chung, Dohoon Ryu, Michael T. McCann, Marc L. Klasky, Jong Chul Ye* \
[19th Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.10655)] [[Github](https://github.com/HJ-harry/DiffusionMBIR)]

**Patch-Based Denoising Diffusion Probabilistic Model for Sparse-View CT Reconstruction** \
*Wenjun Xia, Wenxiang Cong, Ge Wang* \
[18th Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.10388)] 

**Accelerated Motion Correction for MRI using Score-Based Generative Models** \
*Brett Levac, Ajil Jalal, Jonathan I. Tamir* \
[1st Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.00199)] 

**Self-Score: Self-Supervised Learning on Score-Based Models for MRI Reconstruction** \
*Zhuo-Xu Cui, Chentao Cao, Shaonan Liu, Qingyong Zhu, Jing Cheng, Haifeng Wang, Yanjie Zhu, Dong Liang* \
[2nd Sep., 2022] [IEEE TMI, 2022] \
[[Paper](https://arxiv.org/abs/2209.00835)] 

**One-shot Generative Prior in Hankel-k-space for Parallel Imaging Reconstruction** \
*Hong Peng, Chen Jiang, Jing Cheng, Minghui Zhang, Shanshan Wang, Dong Liang, Qiegen Liu* \
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
[2nd Jun., 2022] [NeurIPS, 2022] \
[[Paper](https://arxiv.org/abs/2206.00941)] 

**WKGM: Weight-K-space Generative Model for Parallel Imaging Reconstruction** \
*Zongjiang Tu, Die Liu, Xiaoqing Wang, Chen Jiang, Pengwen Zhu, Minghui Zhang, Shanshan Wang, Dong Liang, Qiegen Liu* \
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
[15th Nov., 2021] [ICLR, 2022] <br>
 [[Paper](https://arxiv.org/abs/2111.08005)] [[Github](https://github.com/yang-song/score_inverse_problems)]
 
**Score-based diffusion models for accelerated MRI** <br>
*Hyungjin Chung, Jong chul Ye*<br>
[8th Oct., 2021] [MIA, 2021]<br>
[[Paper](https://arxiv.org/abs/2110.05243)] [[Github](https://github.com/yang-song/score_inverse_problems)]

**Robust Compressed Sensing MRI with Deep Generative Priors** <br>
*Ajil Jalal, Marius Arvinte, Giannis Daras, Eric Price, Alexandros G. Dimakis, Jonathan I. Tamir*<br>
[3rd Aug., 2021] [NeurIPS, 2021]<br>
[[Paper](https://arxiv.org/abs/2108.01368)] [[Github](https://github.com/utcsilab/csgm-mri-langevin)]

---

### Image Generation

**Diffusion Models for Realistic CT Image Generation** \
*Maialen Stephens Txurio, Karen López-Linares Román, Andrés Marcos-Carrión, Pilar Castellote-Huguet, José M. Santabárbara-Gómez, Iván Macía Oliver, Miguel A. González Ballester * \
[31th May, 2023] [KES, 2023] \
[[Paper](https://link.springer.com/chapter/10.1007/978-981-99-3311-2_30)]

**Evaluating the feasibility of using Generative Models to generate Chest X-Ray Data** \
*Muhammad Danyal Malik, Danish Humair* \
[30th May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.18927)] [[Github](https://github.com/mdanyalmalik/chest-xray-synthesis)] 

**Conditional Diffusion Models for Semantic 3D Medical Image Synthesis** \
*Zolnamar Dorjsembe, Hsing-Kuo Pao, Sodtavilan Odonchimed, Furen Xiao* \
[29th May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.18453)]

**GenerateCT: Text-Guided 3D Chest CT Generation** \
*Ibrahim Ethem Hamamci, Sezgin Er, Enis Simsar, Alperen Tezcan, Ayse Gulnihan Simsek, Furkan Almas, Sevval Nil Esirgun, Hadrien Reynaud, Sarthak Pati, Christian Bluethgen, Bjoern Menze* \
[25th May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.16037)] [[Github](https://github.com/ibrahimethemhamamci/GenerateCT)] 

**Beware of diffusion models for synthesizing medical images -- A comparison with GANs in terms of memorizing brain tumor images** \
*Muhammad Usman Akbar, Wuhao Wang, Anders Eklund* \
[12th May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.07644)]

**Generation of Structurally Realistic Retinal Fundus Images with Diffusion Models** \
*Sojung Go, Younghoon Ji, Sang Jun Park, Soochahn Lee* \
[11th May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.06813)]

**Echo from noise: synthetic ultrasound image generation using diffusion models for real image segmentation** \
*David Stojanovski, Uxio Hermida, Pablo Lamata, Arian Beqiri, Alberto Gomez* \
[9th May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.05424)] [[Github](https://github.com/david-stojanovski/echo_from_noise)] 

**Synthesizing PET images from High-field and Ultra-high-field MR images Using Joint Diffusion Attention Model** \
*Taofeng Xie, Chentao Cao, Zhuoxu Cui, Yu Guo, Caiying Wu, Xuemei Wang, Qingneng Li, Zhanli Hu, Tao Sun, Ziru Sang, Yihang Zhou, Yanjie Zhu, Dong Liang, Qiyu Jin, Guoqing Chen, Haifeng Wang* \
[6th May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.03901)]

**High-Fidelity Image Synthesis from Pulmonary Nodule Lesion Maps using Semantic Diffusion Model** \
*Xuan Zhao, Benjamin Hou* \
[2nd May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.01138)] 

**Denoising Diffusion Medical Models** \
*Pham Ngoc Huy, Tran Minh Quan* \
[19th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.09383)] 

**Mask-conditioned latent diffusion for generating gastrointestinal polyp images** \
*Roman Macháček, Leila Mozaffari, Zahra Sepasdar, Sravanthi Parasa, Pål Halvorsen, Michael A. Riegler, Vajira Thambawita* \
[11th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.05233)] [[Github](https://github.com/simulamet-host/conditional-polyp-diffusion)]

**MedGen3D: A Deep Generative Framework for Paired 3D Image and Mask Generation** \
*Kun Han, Yifeng Xiong, Chenyu You, Pooya Khosravi, Shanlin Sun, Xiangyi Yan, James Duncan, Xiaohui Xie* \
[8th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.04106)]

**Towards Realistic Ultrasound Fetal Brain Imaging Synthesis** \
*Michelle Iskandar, Harvey Mannering, Zhanxiang Sun, Jacqueline Matthew, Hamideh Kerdegari, Laura Peralta, Miguel Xochicale* \
[8th Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.03941)] [[Github](https://github.com/budai4medtech/midl2023)] 

**2D Medical Image Synthesis Using Transformer-based Denoising Diffusion Probabilistic Model** \
*Shaoyan Pan, Tonghe Wang, Richard L J Qiu, Marian Axente, Chih-Wei Chang, Junbo Peng, Ashish B Patel, Joseph Shelton, Sagar A Patel, Justin Roper* \
[4th Apr., 2023] [Physics in Medicine & Biology, 2023] \
[[Paper](https://iopscience.iop.org/article/10.1088/1361-6560/acca5c/meta)]

**ViT-DAE: Transformer-driven Diffusion Autoencoder for Histopathology Image Analysis** \
*Xuan Xu, Saarthak Kapse, Rajarsi Gupta, Prateek Prasanna* \
[3rd Apr., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2304.01053)]

**DDMM-Synth: A Denoising Diffusion Model for Cross-modal Medical Image Synthesis with Sparse-view Measurement Embedding** \
*Xiaoyue Li, Kai Shang, Gaoang Wang, Mark D. Butala* \
[28th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.15770)]

**CoLa-Diff: Conditional Latent Diffusion Model for Multi-Modal MRI Synthesis** \
*Lan Jiang, Ye Mao, Xi Chen, Xiangfeng Wang, Chao Li* \
[24th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.14081)]

**Feature-Conditioned Cascaded Video Diffusion Models for Precise Echocardiogram Synthesis** \
*Hadrien Reynaud, Mengyun Qiao, Mischa Dombrowski, Thomas Day, Reza Razavi, Alberto Gomez, Paul Leeson, Bernhard Kainz* \
[22nd Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.12644)] [[Github](https://github.com/HReynaud/EchoDiffusion)] 

**NASDM: Nuclei-Aware Semantic Histopathology Image Generation Using Diffusion Models** \
*Aman Shrivastava, P. Thomas Fletcher* \
[20th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.11477)]

**Cascaded Latent Diffusion Models for High-Resolution Chest X-ray Synthesis** \
*Tobias Weber, Michael Ingrisch, Bernd Bischl, David Rügamer* \
[20th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.11224)]

**Efficiently Training Vision Transformers on Structural MRI Scans for Alzheimer's Disease Detection** \
*Nikhil J. Dhinagar, Sophia I. Thomopoulos, Emily Laltoo, Paul M. Thompson* \
[14th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.08216)]

**DDFM: Denoising Diffusion Model for Multi-Modality Image Fusion** \
*Zixiang Zhao, Haowen Bai, Yuanzhi Zhu, Jiangshe Zhang, Shuang Xu, Yulun Zhang, Kai Zhang, Deyu Meng, Radu Timofte, Luc Van Gool* \
[13th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.06840)] 

**Bi-parametric prostate MR image synthesis using pathology and sequence-conditioned stable diffusion** \
*Shaheer U. Saeed, Tom Syer, Wen Yan, Qianye Yang, Mark Emberton, Shonit Punwani, Matthew J. Clarkson, Dean C. Barratt, Yipeng Hu* \
[3rd Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.02094)] 

**Denoising Diffusion Probabilistic Models for Generation of Realistic Fully-Annotated Microscopy Image Data Sets** \
*Dennis Eschweiler, Johannes Stegmaier* \
[2nd Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.10227)] [[Github](https://github.com/stegmaierj/DiffusionModelsForImageSynthesis)] [[Synthetic Dataset](https://osf.io/dnp65/)]

**Conversion of the Mayo LDCT Data to Synthetic Equivalent through the Diffusion Model for Training Denoising Networks with a Theoretically Perfect Privacy** \
*Yongyi Shi, Ge Wang* \
[16th Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.06604)] 

**Generating Realistic 3D Brain MRIs Using a Conditional Diffusion Probabilistic Model** \
*Wei Peng, Ehsan Adeli, Qingyu Zhao, Kilian M Pohl* \
[15th Dec., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2212.08034)] 

**SADM: Sequence-Aware Diffusion Model for Longitudinal Medical Image Generation** \
*Jee Seok Yoon, Chenghao Zhang, Heung-Il Suk, Jia Guo, Xiaoxiao Li* \
[16th Dec., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2212.08228)]

**Diffusion Probabilistic Models beat GANs on Medical Images** \
*Gustav Müller-Franzes, Jan Moritz Niehues, Firas Khader, Soroosh Tayebi Arasteh, Christoph Haarburger, Christiane Kuhl, Tianci Wang, Tianyu Han, Sven Nebelung, Jakob Nikolas Kather, Daniel Truhn* \
[14th Dec., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2212.07501)] 

**Improving dermatology classifiers across populations using images generated by large diffusion models** \
*Luke W. Sagers, James A. Diao, Matthew Groh, Pranav Rajpurkar, Adewole S. Adamson, Arjun K. Manrai* \
[23rd Nov., 2022] [NeurIPS Workshop, 2022] \
[[Paper](https://arxiv.org/abs/2211.13352)] 

**Seeing Beyond the Brain: Conditional Diffusion Model with Sparse Masked Modeling for Vision Decoding** \
*Zijiao Chen, Jiaxin Qing, Tiange Xiang, Wan Lin Yue, Juan Helen Zhou* \
[13th Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.06956)] 

**An unobtrusive quality supervision approach for medical image annotation** \
*Sonja Kunzmann, Mathias Öttl, Prathmesh Madhu, Felix Denzinger, Andreas Maier* \
[11th Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.06146)] 

**Medical Diffusion: Denoising Diffusion Probabilistic Models for 3D Medical Image Generation** \
*Firas Khader, Gustav Mueller-Franzes, Soroosh Tayebi Arasteh, Tianyu Han, Christoph Haarburger, Maximilian Schulze-Hagen, Philipp Schad, Sandy Engelhardt, Bettina Baessler, Sebastian Foersch, Johannes Stegmaier, Christiane Kuhl, Sven Nebelung, Jakob Nikolas Kather, Daniel Truhn* \
[7th Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.03364)] [[Github](https://github.com/FirasGit/medicaldiffusion)]

**Generation of Anonymous Chest Radiographs Using Latent Diffusion Models for Training Thoracic Abnormality Classification Systems** \
*Kai Packhäuser, Lukas Folle, Florian Thamm, Andreas Maier* \
[2nd Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.01323)] 

**Spot the fake lungs: Generating Synthetic Medical Images using Neural Diffusion Models** \
*Hazrat Ali, Shafaq Murad, Zubair Shah* \
[2nd Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.00902)] 

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
[27th Jan., 2022] [MICCAI, 2022] \
[[Paper](https://arxiv.org/abs/2206.13295)] [[Github](https://github.com/torchddm/ddm)]

**Three-Dimensional Medical Image Synthesis with Denoising Diffusion Probabilistic Models** \
*Zolnamar Dorjsembe, Sodtavilan Odonchimed, Furen Xiao* \
[22nd Apr., 2022] [MIDL, 2022] \
[[Paper](https://openreview.net/pdf?id=Oz7lKWVh45H)] [[Github](https://github.com/torchddm/ddm)]

---

### Text-to-Image

**Pay Attention: Accuracy Versus Interpretability Trade-off in Fine-tuned Diffusion Models** \
*Mischa Dombrowski, Hadrien Reynaud, Johanna P. Müller, Matthew Baugh, Bernhard Kainz* \
[31st Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.17908)] [[Github](https://github.com/MischaD/chest-distillation)]

**Medical diffusion on a budget: textual inversion for medical image generation** \
*Bram de Wilde, Anindo Saha, Richard P.G. ten Broek, Henkjan Huisman* \
[23rd Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.13430)]

**Diffusion-based Data Augmentation for Skin Disease Classification: Impact Across Original Medical Datasets to Fully Synthetic Images** \
*Mohamed Akrout, Bálint Gyepesi, Péter Holló, Adrienn Poór, Blága Kincső, Stephen Solis, Katrina Cirone, Jeremy Kawahara, Dekker Slade, Latif Abid, Máté Kovács, István Fazekas* \
[12th Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.04802)]

**RoentGen: Vision-Language Foundation Model for Chest X-ray Generation** \
*Pierre Chambon, Christian Bluethgen, Jean-Benoit Delbrouck, Rogier Van der Sluijs, Małgorzata Połacin, Juan Manuel Zambrano Chaves, Tanishq Mathew Abraham, Shivanshu Purohit, Curtis P. Langlotz, Akshay Chaudhari* \
[23rd Nov., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2211.12737)]

**Adapting Pretrained Vision-Language Foundational Models to Medical Imaging Domains** \
*Pierre Chambon, Christian Bluethgen, Curtis P. Langlotz, Akshay Chaudhari* \
[9th Oct., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2210.04133)]

---

### Registration

**DiffuseMorph: Unsupervised Deformable Image Registration Along Continuous Trajectory Using Diffusion Models** \
*Boah Kim, Inhwa Han, Jong Chul Ye* \
[9th Dec., 2021] [ECCV, 2022] \
[[Paper](https://arxiv.org/abs/2112.05149)] 

---

### Classification

**DiffMIC: Dual-Guidance Diffusion Network for Medical Image Classification** \
*Yijun Yang, Huazhu Fu, Angelica I. Aviles-Rivero, Carola-Bibiane Schönlieb, Lei Zhu* \
[19th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.10610)] [[Github](https://github.com/scott-yjyang/DiffMIC)]

---

### Object Detection

**Diffusion-Based Hierarchical Multi-Label Object Detection to Analyze Panoramic Dental X-rays** \
*Ibrahim Ethem Hamamci, Sezgin Er, Enis Simsar, Anjany Sekuboyina, Mustafa Gundogar, Bernd Stadlinger, Albert Mehl, Bjoern Menze* \
[11th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.06500)] [[Github](https://github.com/ibrahimethemhamamci/HierarchicalDet)]

---

### Inpainting

**Multitask Brain Tumor Inpainting with Diffusion Models: A Methodological Report** \
*Pouria Rouzrokh, Bardia Khosravi, Shahriar Faghani, Mana Moassefi, Sanaz Vahdati, Bradley J. Erickson* \
[21st Oct., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2210.12113)] [[GitHub](https://github.com/Mayo-Radiology-Informatics-Lab/MBTI)] [[Online Tool](https://1f1f559d51c361e2.gradio.app/)]

---

### Super Resolution

**Self-similarity-based super-resolution of photoacoustic angiography from hand-drawn doodles** \
*Yuanzheng Ma, Wangting Zhou, Rui Ma, Sihua Yang, Yansong Tang, Xun Guan* \
[2nd May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.01165)] [[GitHub](https://github.com/yuanzhengthu/handDrawnPAAImages)]

**DisC-Diff: Disentangled Conditional Diffusion Model for Multi-Contrast MRI Super-Resolution** \
*Ye Mao, Lan Jiang, Xi Chen, Chao Li* \
[24th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.13933)]

---

### Adversarial Attacks

**On enhancing the robustness of Vision Transformers: Defensive Diffusion** \
*Raza Imam, Muhammad Huzaifa, Mohammed El-Amine Azz* \
[14th May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.08031)] [[GitHub](https://github.com/Muhammad-Huzaifaa/Defensive_Diffusion)]

**Fight Fire With Fire: Reversing Skin Adversarial Examples by Multiscale Diffusive and Denoising Aggregation Mechanism** \
*Yongwei Wang, Yuan Li, Zhiqi Shen* \
[22nd Aug., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2208.10373)]

---

### Time Series

**Restoration of Time-Series Medical Data with Diffusion Model** \
*Jiwoon Lee, Cheolsoo Park* \
[6th Oct., 2022] [ICCE-Asia, 2022] \
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
[23rd Mar., 2022] [IEEE TMI, 2022] \
[[Paper](https://arxiv.org/abs/2203.12621)]

---

### Other Applications

**Semantic Latent Space Regression of Diffusion Autoencoders for Vertebral Fracture Grading** \
*Matthias Keicher, Matan Atad, David Schinz, Alexandra S. Gersing, Sarah C. Foreman, Sophia S. Goller, Juergen Weissinger, Jon Rischewski, Anna-Sophia Dietrich, Benedikt Wiestler, Jan S. Kirschke, Nassir Navab* \
[21st Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.12031)]

**AugDiff: Diffusion based Feature Augmentation for Multiple Instance Learning in Whole Slide Image** \
*Zhuchen Shao, Liuxi Dai, Yifeng Wang, Haoqian Wang, Yongbing Zhang* \
[11th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.06371)]

**Brain Diffuser: An End-to-End Brain Image to Brain Network Pipeline** \
*Xuhang Chen, Baiying Lei, Chi-Man Pun, Shuqiang Wang* \
[11th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.06410)]

**Learning Enhancement From Degradation: A Diffusion Model For Fundus Image Enhancement** \
*Puijin Cheng, Li Lin, Yijin Huang, Huaqing He, Wenhan Luo, Xiaoying Tang* \
[8th Mar., 2023][arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.04603)]

**DiffusionCT: Latent Diffusion Model for CT Image Standardization** \
*Md Selim, Jie Zhang, Michael A. Brooks, Ge Wang, Jin Chen* \
[20th Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.08815)]

**Diffusion Model based Semi-supervised Learning on Brain Hemorrhage Images for Efficient Midline Shift Quantification** \
*Shizhan Gong, Cheng Chen, Yuqi Gong, Nga Yan Chan, Wenao Ma, Calvin Hoi-Kwan Mak, Jill Abrigo, Qi Dou* \
[1st Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.00409)]
