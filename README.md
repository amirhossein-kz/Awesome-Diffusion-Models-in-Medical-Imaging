# <p align=center>`Awesome Diffusion Models in Medical Imaging`</p> #

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/amirhossein-kz/Awesome-Diffusion-Models-in-Medical-Imaging)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

:fire::fire: This is a collection of awesome articles about diffusion models in medical imaging:fire::fire:

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
- We have now achieved more than 1K stars 🌟—thank you community for your support! If you're interested in contributing to this repository, please don't hesitate to send me a message. Thank you!
- Check out our new paper accepted in MICCAI 2023 PRIME Workshop: [DermoSegDiff: A Boundary-aware Segmentation Diffusion Model for Skin Lesion Delineation](https://arxiv.org/abs/2308.02959) 🥳
- **Third release:** June 3, 2023
- :sunglasses: April 8, 2023: Our paper is accepted for publication in the **Medical Image Analysis Journal (IF: 13.83)** :sunglasses:
- **Second release:** March 29, 2023
- **First release:** November 14, 2022

## Contents
- [Survey Papers](#survey-papers)
- [Challenge Reports](#challenge-reports)

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
  - [Image Restoration](#image-restoration)
    - [Inpainting](#inpainting)
    - [Super Resolution](#super-resolution)
    - [Enhancement](#enhancement)
  - [Editing](#editing)
  - [Adversarial Attacks](#adversarial-attacks)
  - [Fairness](#fairness)
  - [Time Series](#time-series)
  - [Audio](#audio)
  - [Other Applications](#other-applications)
  - [Multi-task](#multi-task)

## Survey Papers

**Generative Artificial Intelligence in Medical Imaging: Foundations, Progress, and Clinical Translation** \
*Xuanru Zhou, Cheng Li, Shuqiang Wang, Ye Li, Tao Tan, Hairong Zheng, Shanshan Wang* \
[07th Aug., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2508.09177v1)]

**Computationally Efficient Diffusion Models in Medical Imaging: A Comprehensive Review** \
*Abdullah, Tao Huang, Ickjai Lee, Euijoon Ahn* \
[09th May, 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2505.07866v1)]

**Diffusion Models in 3D Vision: A Survey** \
*Zhen Wang, Dongyuan Li, Yaozu Wu, Tianyu He, Jiang Bian, Renhe Jiang* \
[07th Oct., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2410.04738v3)]

**Foundation Models for Music: A Survey** \
*Yinghao Ma, Anders Øland, Anton Ragni, Bleiz MacSen Del Sette, Charalampos Saitis, Chris Donahue, Chenghua Lin, Christos Plachouras, Emmanouil Benetos, Elona Shatri, Fabio Morreale, Ge Zhang, György Fazekas, Gus Xia, Huan Zhang, Ilaria Manco, Jiawen Huang, Julien Guinot, Liwei Lin, Luca Marinelli, Max W. Y. Lam, Megha Sharma, Qiuqiang Kong, Roger B. Dannenberg, Ruibin Yuan, Shangda Wu, Shih-Lun Wu, Shuqi Dai, Shun Lei, Shiyin Kang, Simon Dixon, Wenhu Chen, Wenhao Huang, Xingjian Du, Xingwei Qu, Xu Tan, Yizhi Li, Zeyue Tian, Zhiyong Wu, Zhizheng Wu, Ziyang Ma, Ziyu Wang* \
[26th Aug., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2408.14340)] [[GitHub](https://github.com/nicolaus625/FM4Music)] [Music Generation - Music Therapy & Medical Applications]

**A Comprehensive Survey on Diffusion Models and Their Applications** \
*Md Manjurul Ahsan, Shivakumar Raman, Yingtao Liu, Zahed Siddique* \
[1st Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2408.10207)]

**Physics-Inspired Generative Models in Medical Imaging: A Review** \
*Dennis Hein, Afshin Bozorgpour, Dorit Merhof, Ge Wang* \
[15th Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.10856)]

**Diffusion Models in Low-Level Vision: A Survey** \
*Chunming He, Yuqi Shen, Chengyu Fang, Fengyang Xiao, Longxiang Tang, Yulun Zhang, Wangmeng Zuo, Zhenhua Guo, Xiu Li* \
[16th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.11138)] [[GitHub](https://github.com/ChunmingHe/awesome-diffusion-models-in-low-level-vision)]

**Artifact Reduction in 3D and 4D Cone-beam Computed Tomography Images with Deep Learning -- A Review** \
*Mohammadreza Amirian, Daniel Barco, Ivo Herzig, Frank-Peter Schilling* \
[27th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.18565)]

**A Survey of Emerging Applications of Diffusion Probabilistic Models in MRI** \
*Yuheng Fan, Hanxi Liao, Shiqi Huang, Yimin Luo, Huazhu Fu, Haikun Qi* \
[18th Nov., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2311.11383)]

**A Comprehensive Review of Generative AI in Healthcare** \
*Yasin Shokrollahi, Sahar Yarmohammadtoosky, Matthew M. Nikahd, Pengfei Dong, Xianqi Li, Linxia Gu* \
[24th Jul., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.00795)]

**Generative AI for Medical Imaging: extending the MONAI Framework** :fire: \
*Walter H. L. Pinaya, Mark S. Graham, Eric Kerfoot, Petru-Daniel Tudosiu, Jessica Dafflon, Virginia Fernandez, Pedro Sanchez, Julia Wolleb, Pedro F. da Costa, Ashay Patel, Hyungjin Chung, Can Zhao, Wei Peng, Zelong Liu, Xueyan Mei, Oeslle Lucena, Jong Chul Ye, Sotirios A. Tsaftaris, Prerna Dogra, Andrew Feng, Marc Modat, Parashkev Nachev, Sebastien Ourselin, M. Jorge Cardoso* \
[27th Jul., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2307.15208)] [[Github](https://github.com/Project-MONAI/GenerativeModels)]

**Deep Learning Approaches for Data Augmentation in Medical Imaging: A Review** \
*Aghiles Kebaili, Jérôme Lapuyade-Lahorgue, Su Ruan* \
[24th Jul., 2023] [Journal of Imaging, 2023] \
[[Paper](https://arxiv.org/abs/2307.13125)]

**A Comprehensive Survey on Generative Diffusion Models for Structured Data** \
*Heejoon Koo, To Eun Kim* \
[7th Jun., 2023] [arXiv, 2023]  \
[[Paper](https://arxiv.org/abs/2306.04139)]

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
[[Paper](https://arxiv.org/abs/2302.10907)]

**Generative Diffusion Models on Graphs: Methods and Applications** \
*Wenqi Fan, Chengyi Liu, Yunqing Liu, Jiatong Li, Hang Li, Hui Liu, Jiliang Tang, Qing Li* \
[6th Feb., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2302.02591)]

**Diffusion Models in Medical Imaging: A Comprehensive Survey** :fire: \
*Amirhossein Kazerouni, Ehsan Khodapanah Aghdam, Moein Heidari, Reza Azad, Mohsen Fayyaz, Ilker Hacihaliloglu, Dorit Merhof* \
[14th Nov., 2022] [MedIA Journal, 2023] \
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

## Challenge Reports

**Federated Learning for Medical Image Classification: A Comprehensive Benchmark** \
*Zhekai Zhou, Guibo Luo, Mingzhi Chen, Zhenyu Weng, Yuesheng Zhu* \
[07th Apr., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.05238v1)]

**Report on the AAPM Grand Challenge on deep generative modeling for learning medical image statistics** \
*Rucha Deshpande, Varun A. Kelkar, Dimitrios Gotsis, Prabhat Kc, Rongping Zeng, Kyle J. Myers, Frank J. Brooks, Mark A. Anastasio* \
[2nd May] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.01822)] [[Website](https://www.aapm.org/GrandChallenge/DGM-Image/)]

## Papers

### Anomaly Detection

**Denoising Diffusion Models for Anomaly Localization in Medical Images** \
*Cosmin I. Bercea, Philippe C. Cattin, Julia A. Schnabel, Julia Wolleb* \
[31th Oct., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2410.23834v1)]

**Leveraging the Mahalanobis Distance to enhance Unsupervised Brain MRI Anomaly Detection** \
*Finn Behrendt, Debayan Bhattacharya, Robin Mieling, Lennart Maack, Julia Krüger, Roland Opfer, Alexander Schlaefer* \
[03th Oct., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2407.12474)] [[GitHub](https://github.com/FinnBehrendt/Mahalanobis-Unsupervised-Anomaly-Detection)]

**CADD: Context aware disease deviations via restoration of brain images using normative conditional diffusion models** \
*Ana Lawry Aguila, Ayodeji Ijishakin, Juan Eugenio Iglesias, Tomomi Takenaga, Yukihiro Nomura, Takeharu Yoshikawa, Osamu Abe, Shouhei Hanaoka* \
[05th Aug., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2508.03594v1)]

**Unsupervised anomaly detection using Bayesian flow networks: application to brain FDG PET in the context of Alzheimer's disease** \
*Hugues Roy, Reuben Dorent, Ninon Burgos* \
[23th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.17486v1)]

**Harnessing EHRs for Diffusion-based Anomaly Detection on Chest X-rays** \
*Harim Kim, Yuhan Wang, Minkyu Ahn, Heeyoul Choi, Yuyin Zhou, Charmgil Hong* \
[22th May., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2505.17311v1)]

**HDM: Hybrid Diffusion Model for Unified Image Anomaly Detection** \
*Zekang Weng, Jinjin Shi, Jinwei Wang, Zeming Han* \
[26th Feb., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2502.19200v1)]

**MAD-AD: Masked Diffusion for Unsupervised Brain Anomaly Detection** \
*Farzad Beizaee, Gregory Lodygensky, Christian Desrosiers, Jose Dolz* \
[24th Feb., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2502.16943v3)]

**Synomaly Noise and Multi-Stage Diffusion: A Novel Approach for Unsupervised Anomaly Detection in Medical Images** \
*Yuan Bi, Lucie Huang, Ricarda Clarenbach, Reza Ghotbi, Angelos Karlas, Nassir Navab, Zhongliang Jiang* \
[06th Nov., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2411.04004v2)]

**MCDDPM: Multichannel Conditional Denoising Diffusion Model for Unsupervised Anomaly Detection in Brain MRI** \
*Vivek Kumar Trivedi, Bheeshm Sharma, P. Balamurugan* \
[29th Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.19623)] [[GitHub](https://github.com/vivekkumartri/MCDDPM)]

**Diffusion Models with Ensembled Structure-Based Anomaly Scoring for Unsupervised Anomaly Detection** \
*Finn Behrendt, Debayan Bhattacharya, Lennart Maack, Julia Krüger, Roland Opfer, Robin Mieling, Alexander Schlaefer* \
[22nd Aug., 2024] [ISBI, 2024]<br>
[[Paper](https://ieeexplore.ieee.org/abstract/document/10635828)] [[Github](https://github.com/FinnBehrendt/Ensembled-SSIM-for-Unsupervised-Anomaly-Detection)]

**Combining Reconstruction-based Unsupervised Anomaly Detection with Supervised Segmentation for Brain MRIs** \
*Finn Behrendt, Debayan Bhattacharya, Lennart Maack, Julia Krüger, Roland Opfer, Alexander Schlaefer* \
[6th Jun., 2024] [MIDL, 2024]<br>
[[Paper](https://openreview.net/forum?id=iWfUcg4FrD)] [[Github](https://github.com/FinnBehrendt/Supervised-Anomaly-Detection-with-Diffusion-Models)]

**Binary Noise for Binary Tasks: Masked Bernoulli Diffusion for Unsupervised Anomaly Detection** \
*Julia Wolleb, Florentin Bieder, Paul Friedrich, Peter Zhang, Alicia Durrer, Philippe C. Cattin* \
[18th Mar., 2024] [arXiv, 2024]<br>
[[Paper](https://arxiv.org/abs/2403.11667)] [[Github](https://github.com/JuliaWolleb/Anomaly_berdif)]

**Diffusion Models with Implicit Guidance for Medical Anomaly Detection** \
*Cosmin I. Bercea, Benedikt Wiestler, Daniel Rueckert, Julia A. Schnabel* \
[13th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.08464)] [[GitHub](https://github.com/ci-ber/THOR_DDPM)]

**Objective and Interpretable Breast Cosmesis Evaluation with Attention Guided Denoising Diffusion Anomaly Detection Model** \
*Sangjoon Park, Yong Bae Kim, Jee Suk Chang, Seo Hee Choi, Hyungjin Chung, Ik Jae Lee, Hwa Kyung Byun* \
[28th Feb., 2024] [arXiv, 2024]<br>
[[Paper](https://arxiv.org/abs/2402.18362)]

**MAEDiff: Masked Autoencoder-enhanced Diffusion Models for Unsupervised Anomaly Detection in Brain Images** \
*Rui Xu, Yunke Wang, Bo Du* \
[19th Jan., 2024] [arXiv, 2024]<br>
[[Paper](https://arxiv.org/abs/2401.10561)]

**Unsupervised Anomaly Detection using Aggregated Normative Diffusion** \
*Alexander Frotscher, Jaivardhan Kapoor, Thomas Wolfers, Christian F. Baumgartner* \
[4th Dec., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2312.01904)] [[Github](https://github.com/alexanderfrotscher/ANDi)]

**DISYRE: Diffusion-Inspired SYnthetic REstoration for Unsupervised Anomaly Detection** \
*Sergio Naval Marimont, Matthew Baugh, Vasilis Siomos, Christos Tzelepis, Bernhard Kainz, Giacomo Tarroni* \
[26th Nov., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2311.15453)]

**Guided Reconstruction with Conditioned Diffusion Models for Unsupervised Anomaly Detection in Brain MRIs** \
*Finn Behrendt, Debayan Bhattacharya, Robin Mieling, Lennart Maack, Julia Krüger, Roland Opfer, Alexander Schlaefer* \
[7th Dec., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2310.08654)] [[Github](https://github.com/FinnBehrendt/Conditioned-Diffusion-Models-UAD)]

**Histogram- and Diffusion-Based Medical Out-of-Distribution Detection** \
*Evi M.C. Huijben, Sina Amirrajab, Josien P.W. Pluim* \
[12th Oct., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2310.06420)] [[Github](https://github.com/evihuijben/mood_challenge)]

**AnoDODE: Anomaly Detection with Diffusion ODE** \
*Xianyao Hu, Congming Jin* \
[10th Aug., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2310.06420)]

**Modality Cycles with Masked Conditional Diffusion for Unsupervised Anomaly Segmentation in MRI** \
*Ziyun Liang, Harry Anthony, Felix Wagner, Konstantinos Kamnitsas* \
[30th Aug., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2308.16150)] [[Github](https://github.com/ZiyunLiang/MMCCD)]

**Diffusion Models for Counterfactual Generation and Anomaly Detection in Brain Images** \
*Alessandro Fontanella, Grant Mair, Joanna Wardlaw, Emanuele Trucco, Amos Storkey* \
[3rd Aug., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2308.02062)] [[Github](https://github.com/alessandro-f/Dif-fuse)]

**SANO: Score-Based Diffusion Model for Anomaly Localization in Dermatology** \
*Alvaro Gonzalez-Jimenez, Simone Lionetti, Marc Pouly, Alexander A. Navarini* \
[18th Jun., 2023] [CVPR Workshop, 2023] \
[paper](https://openaccess.thecvf.com/content/CVPR2023W/VAND/html/Gonzalez-Jimenez_SANO_Score-Based_Diffusion_Model_for_Anomaly_Localization_in_Dermatology_CVPRW_2023_paper.html)]

**Mask, Stitch, and Re-Sample: Enhancing Robustness and Generalizability in Anomaly Detection through Automatic Diffusion Models** \
*Cosmin I. Bercea, Michael Neumayr, Daniel Rueckert, Julia A. Schnabel* \
[31st May, 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2305.19643)]

**Unsupervised Anomaly Detection in Medical Images Using Masked Diffusion Model** \
*Hasan Iqbal, Umar Khalid, Jing Hua, Chen Chen* \
[31st May, 2023] [MICCAI MLMI Workshop, 2023]<br>
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
[19th Jan., 2023] [MedIA Journal, 2023] \
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

**DiffDenoise: Self-Supervised Medical Image Denoising with Conditional Diffusion Models** \
*Basar Demir, Yikang Liu, Xiao Chen, Eric Z. Chen, Lin Zhao, Boris Mailhe, Terrence Chen, Shanhui Sun* \
[31st Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.00264v1)]

**Ultrasound Imaging based on the Variance of a Diffusion Restoration Model** \
*Yuxin Zhang, Clément Huneau, Jérôme Idier, Diana Mateus* \
[17th Jun., 2024] [EUSIPCO] \
[[Paper](https://arxiv.org/pdf/2403.15316)] [[Github](https://github.com/Yuxin-Zhang-Jasmine/DRUSvar)]

**Dose-aware Diffusion Model for 3D Low-dose PET: Multi-institutional Validation with Reader Study and Real Low-dose Data** \
*Huidong Xie, Weijie Gan, Bo Zhou, Ming-Kai Chen, Michal Kulon, Annemarie Boustani, Benjamin A. Spencer, Reimund Bayerlein, Xiongchao Chen, Qiong Liu, Xueqi Guo, Menghua Xia, Yinchi Zhou, Hui Liu, Liang Guo, Hongyu An, Ulugbek S. Kamilov, Hanzhong Wang, Biao Li, Axel Rominger, Kuangyu Shi, Ge Wang, Ramsey D. Badawi, Chi Liu* \
[2nd May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.12996)]

**Implicit Image-to-Image Schrodinger Bridge for CT Super-Resolution and Denoising** \
*Yuang Wang, Siyeop Yoon, Pengfei Jin, Matthew Tivnan, Zhennong Chen, Rui Hu, Li Zhang, Zhiqiang Chen, Quanzheng Li, Dufan Wu* \
[10th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.06069)]

**SDDPM: Speckle Denoising Diffusion Probabilistic Models** \
*Soumee Guha, Scott T. Acton* \
[17th Nov., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2311.10868)]

**Deep Ultrasound Denoising Using Diffusion Probabilistic Models** \
*Hojat Asgariandehkordi, Sobhan Goudarzi, Adrian Basarab, Hassan Rivaz* \
[12th Jun., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.07440)]

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
[13th Sep., 2022] [European Journal of Nuclear Medicine and Molecular Imaging, 2022] \
[[Paper](https://arxiv.org/abs/2209.06167)]

**Unsupervised Denoising of Retinal OCT with Diffusion Probabilistic Model** \
*Dewei Hu, Yuankai K. Tao, Ipek Oguz* \
[27th Jan., 2022] [Medical Imaging 2022: Image Processing] \
[[Paper](https://arxiv.org/abs/2201.11760)] [[Github](https://github.com/DeweiHu/OCT_DDPM)]

---

### Segmentation

**Aleatoric Uncertainty Medical Image Segmentation Estimation via Flow Matching** \
*Phi Van Nguyen, Ngoc Huynh Trinh, Duy Minh Lam Nguyen, Phu Loc Nguyen, Quoc Long Tran* \
[30th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.22418v1)] [[Github](https://github.com/huynhspm/Data-Uncertainty)]   

**Flow Stochastic Segmentation Networks** \
*Fabio De Sousa Ribeiro, Omar Todd, Charles Jones, Avinash Kori, Raghav Mehta, Ben Glocker* \
[24th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.18838v1)] [[Github](https://github.com/biomedia-mira/flow-ssn)]   

**LEAF: Latent Diffusion with Efficient Encoder Distillation for Aligned Features in Medical Image Segmentation** \
*Qilin Huang, Tianyu Lin, Zhiguang Chen, Fudan Zheng* \
[24th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.18214v1)] [[Github](https://leafseg.github.io/leaf/)]   

**Robust Noisy Pseudo-label Learning for Semi-supervised Medical Image Segmentation Using Diffusion Model** \
*Lin Xi, Yingliang Ma, Cheng Wang, Sandra Howell, Aldo Rinaldi, Kawal S. Rhode* \
[22nd Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.16429v1)]

**Latent Space Synergy: Text-Guided Data Augmentation for Direct Diffusion Biomedical Segmentation** \
*Muhammad Aqeel, Maham Nazir, Zanxi Ruan, Francesco Setti* \
[21st Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.15361v1)]

**SegDT: A Diffusion Transformer-Based Segmentation Model for Medical Imaging** \
*Salah Eddine Bekhouche, Gaby Maroun, Fadi Dornaika, Abdenour Hadid* \
[21st Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.15595v1)] [[Github](https://github.com/Bekhouche/SegDT)]   

**DiffOSeg: Omni Medical Image Segmentation via Multi-Expert Collaboration Diffusion Model** \
*Han Zhang, Xiangde Luo, Yong Chen, Kang Li* \
[17th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.13087v1)] [[Github](https://github.com/string-ellipses/DiffOSeg)]  

**Diffusion Model-based Data Augmentation Method for Fetal Head Ultrasound Segmentation** \
*Fangyijie Wang, Kevin Whelan, Félix Balado, Kathleen M. Curran, Guénolé Silvestre* \
[30th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.23664v2)]

**Contrastive Learning with Diffusion Features for Weakly Supervised Medical Image Segmentation** \
*Dewen Zeng, Xinrong Hu, Yu-Jen Chen, Yawen Wu, Xiaowei Xu, Yiyu Shi* \
[30th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.23460v1)]

**Inpainting is All You Need: A Diffusion-based Augmentation Method for Semi-supervised Medical Image Segmentation** \
*Xinrong Hu, Yiyu Shi* \
[28th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.23038v1)]

**CLAIM: Clinically-Guided LGE Augmentation for Realistic and Diverse Myocardial Scar Synthesis and Segmentation** \
*Farheen Ramzan, Yusuf Kiberu, Nikesh Jathanna, Shahnaz Jamil-Copley, Richard H. Clayton, Chen Chen* \
[18th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.15549v2)] [[Github](https://github.com/farheenjabeen/CLAIM-Scar-Synthesis)]  

**Echo-DND: A dual noise diffusion model for robust and precise left ventricle segmentation in echocardiography** \
*Abdur Rahman, Keerthiveena Balraj, Manojkumar Ramteke, Anurag Singh Rathore* \
[18th Jun., 2025] [Discover Applied Sciences (Springer Nature), 2025] \
[[Paper](http://arxiv.org/abs/2506.15166v1)] [[Github](https://github.com/abdur75648/Echo-DND)] [[Project Page](https://abdur75648.github.io/Echo-DND/)]   

**Unleashing Diffusion and State Space Models for Medical Image Segmentation** \
*Rong Wu, Ziqi Chen, Liming Zhong, Heng Li, Hai Shu* \
[15th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.12747v2)] [[Github](https://github.com/Rows21/k-Means_Mask_Mamba)] 

**Enhancing Privacy: The Utility of Stand-Alone Synthetic CT and MRI for Tumor and Bone Segmentation** \
*André Ferreira, Kunpeng Xie, Caroline Wilpert, Gustavo Correia, Felix Barajas Ordonez, Tiago Gil Oliveira, Maike Bode, Robert Siepmann, Frank Hölzle, Rainer Röhrig, Jens Kleesiek, Daniel Truhn, Jan Egger, Victor Alves, Behrus Puladi* \
[13th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.12106v1)] [[Github](https://github.com/ShadowTwin41/generative_networks)]  

**TumorGen: Boundary-Aware Tumor-Mask Synthesis with Rectified Flow Matching** \
*Shengyuan Liu, Wenting Chen, Boyun Zheng, Wentao Pan, Xiang Li, Yixuan Yuan* \
[30th May, 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2505.24687v1)]

**Beyond Labels: Zero-Shot Diabetic Foot Ulcer Wound Segmentation with Self-attention Diffusion Models and the Potential for Text-Guided Customization** \
*Abderrachid Hamrani, Daniela Leizaola, Renato Sousa, Jose P. Ponce, Stanley Mathis, David G. Armstrong, Anuradha Godavarty* \
[24th Apr., 2025] [IEEE Journal of Biomedical and Health Informatics, 2025] \
[[Paper](http://arxiv.org/abs/2504.17628v1)]

**TextDiffSeg: Text-guided Latent Diffusion Model for 3d Medical Images Segmentation** \
*Kangbo Ma* \
[16th Apr., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.11825v1)]

**Diffusion Based Ambiguous Image Segmentation** \
*Jakob Lønborg Christensen, Morten Rieger Hannemose, Anders Bjorholm Dahl, Vedrana Andersen Dahl* \
[08th Apr., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.05977v1)]

**Semi-Supervised Biomedical Image Segmentation via Diffusion Models and Teacher-Student Co-Training** \
*Luca Ciampi, Gabriele Lagani, Giuseppe Amato, Fabrizio Falchi* \
[2nd Apr., 2025] [arXiv, 2025] \ 
[[Paper](http://arxiv.org/abs/2504.01547v1)] [[GitHub](https://github.com/ciampluca/diffusion_semi_supervised_biomedical_image_segmentation)] 

**Diff-CL: A Novel Cross Pseudo-Supervision Method for Semi-supervised Medical Image Segmentation** \
*Xiuzhen Guo, Lianyuan Yu, Ji Shi, Na Lei, Hongxiao Wang* \
[12th Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.09408v1)]

**DiffAtlas: GenAI-fying Atlas Segmentation via Image-Mask Diffusion** \
*Hantao Zhang, Yuhe Liu, Jiancheng Yang, Weidong Guo, Xinyuan Wang, Pascal Fua* \
[09th Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.06748v1)] [[GitHub](https://github.com/M3DV/DiffAtlas)]  

**Conditional diffusion model with spatial attention and latent embedding for medical image segmentation** \
*Behzad Hejrati, Soumyanil Banerjee, Carri Glide-Hurst, Ming Dong* \
[10th Feb., 2025] [MICCAI, 2024] \
[[Paper](http://arxiv.org/abs/2502.06997v2)] [[GitHub](https://github.com/Hejrati/cDAL/)]  

**Medical Semantic Segmentation with Diffusion Pretrain** \
*David Li, Anvar Kurmukov, Mikhail Goncharov, Roman Sokolov, Mikhail Belyaev* \
[31st Jan., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2501.19265v1)]

**MedSegDiffNCA: Diffusion Models With Neural Cellular Automata for Skin Lesion Segmentation** \
*Avni Mittal, John Kalkhof, Anirban Mukhopadhyay, Arnav Bhavsar* \
[05th Jan., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2501.02447v1)]

**Bridging Classification and Segmentation in Osteosarcoma Assessment via Foundation and Discrete Diffusion Models** \
*Manh Duong Nguyen, Dac Thai Nguyen, Trung Viet Nguyen, Homi Yamada, Huy Hieu Pham, Phi Le Nguyen* \
[03rd Jan., 2025] [ISBI, 2025] \
[[Paper](http://arxiv.org/abs/2501.01932v1)] [[Github](https://github.com/nmduonggg/FDDM)]   

**Structure-Aware Stylized Image Synthesis for Robust Medical Image Segmentation** \
*Jie Bao, Zhixin Zhou, Wen Jung Li, Rui Luo* \
[05th Dec., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2412.04296v1)] [[Github](https://github.com/luo-lorry/Stylized-Medical-Segmentation)]  

**vesselFM: A Foundation Model for Universal 3D Blood Vessel Segmentation** \
*Bastian Wittmann, Yannick Wattenberg, Tamaz Amiranashvili, Suprosanna Shit, Bjoern Menze* \
[26th Nov., 2024] [CVPR, 2025] \
[[Paper](http://arxiv.org/abs/2411.17386v2)] [[Github](https://github.com/bwittmann/vesselFM)] 

**ScribbleVS: Scribble-Supervised Medical Image Segmentation via Dynamic Competitive Pseudo Label Selection** \
*Tao Wang, Xinlin Zhang, Yuanbin Chen, Yuanbo Zhou, Longxuan Zhao, Tao Tan, Tong Tong* \
[15th Nov., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2411.10237v1)] [[GitHub](https://github.com/ortonwang/ScribbleVS)]    

**Comparative Study of Probabilistic Atlas and Deep Learning Approaches for Automatic Brain Tissue Segmentation from MRI Using N4 Bias Field Correction and Anisotropic Diffusion Pre-processing Techniques** \
*Mohammad Imran Hossain, Muhammad Zain Amin, Daniel Tweneboah Anyimadu, Taofik Ahmed Suleiman* \
[08th Nov., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2411.05456v1)] [[GitHub](https://github.com/imran-maia/IBSR_18_BraTSeg_Deep_Learning)]   

**Generalizable Single-Source Cross-modality Medical Image Segmentation via Invariant Causal Mechanisms** \
*Boqi Chen, Yuanzhi Zhu, Yunke Ao, Sebastiano Caprara, Reto Sutter, Gunnar Rätsch, Ender Konukoglu, Anna Susmelj* \
[07th Nov., 2024] [WACV, 2025] \ 
[[Paper](http://arxiv.org/abs/2411.05223v1)] [[GitHub](https://github.com/ratschlab/ICMSeg)]  

**Enhancing Medical Image Segmentation with Deep Learning and Diffusion Models** \
*Houze Liu, Tong Zhou, Yanlin Xiang, Aoran Shen, Jiacheng Hu, Junliang Du* \
[21th Nov., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2411.14353v2)]

**PGDiffSeg: Prior-Guided Denoising Diffusion Model with Parameter-Shared Attention for Breast Cancer Segmentation** \
*Feiyan Feng, Tianyu Liu, Hong Wang, Jun Zhao, Wei Li, Yanshen Sun* \
[23th Oct., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2410.17812v1)]

**AdaptDiff: Cross-Modality Domain Adaptation via Weak Conditional Semantic Diffusion for Retinal Vessel Segmentation** \
*Dewei Hu, Hao Li, Han Liu, Jiacheng Wang, Xing Yao, Daiwei Lu, Ipek Oguz* \
[06th Oct., 2024] [SASHIMI, 2024] \
[[Paper](http://arxiv.org/abs/2410.04648v1)] [[GitHub](https://github.com/DeweiHu/AdaptDiff)] 

**Diffuse-UDA: Addressing Unsupervised Domain Adaptation in Medical Image Segmentation with Appearance and Structure Aligned Diffusion Models** \
*Haifan Gong, Yitao Wang, Yihan Wang, Jiashun Xiao, Xiang Wan, Haofeng Li* \
[12th Aug., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2408.05985)]

**Advancing Medical Image Segmentation: Morphology-Driven Learning with Diffusion Transformer** \
*Sungmin Kang, Jaeha Song, Jihie Kim* \
[1st Aug., 2024] [BMVC, 2024] \
[[Paper](https://arxiv.org/abs/2408.00347)]

**FDiff-Fusion:Denoising diffusion fusion network based on fuzzy learning for 3D medical image segmentation** \
*Weiping Ding, Sheng Geng, Haipeng Wang, Jiashuang Huang, Tianyi Zhou* \
[21st Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2408.02075)]

**Panoptic Segmentation of Mammograms with Text-To-Image Diffusion Model** \
*Kun Zhao, Jakub Prokop, Javier Montalt Tordera, Sadegh Mohammadi* \
[19th Jul., 2024] [DGM4MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2407.14326)] [[GitHub](https://github.com/NVlabs/ODISE)]

**Denoising Diffusions in Latent Space for Medical Image Segmentation** \
*Fahim Ahmed Zaman, Mathews Jacob, Amanda Chang, Kan Liu, Milan Sonka, Xiaodong Wu* \
[17th Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.12952)] [[GitHub](https://github.com/LDSeg/LDSeg)]

**DiffRect: Latent Diffusion Label Rectification for Semi-supervised Medical Image Segmentation** \
*Xinyu Liu, Wuyang Li, Yixuan Yuan* \
[13th Jul., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2407.09918)] [[GitHub](https://github.com/CUHK-AIM-Group/DiffRect)]

**FairDiff: Fair Segmentation with Point-Image Diffusion** \
*Wenyi Li, Haoran Xu, Guiyu Zhang, Huan-ang Gao, Mingju Gao, Mengyu Wang, Hao Zhao* \
[8th Jul., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2407.06250)] [[GitHub](https://github.com/wenyi-li/FairDiff)]

**Enhancing Label-efficient Medical Image Segmentation with Text-guided Diffusion Models** \
*Chun-Mei Feng* \
[7th Jul., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2407.05323)] [[GitHub](https://github.com/chunmeifeng/TextDiff)]

**HiDiff: Hybrid Diffusion Framework for Medical Image Segmentation** \
*Tao Chen, Chenhui Wang, Zhihao Chen, Yiming Lei, Hongming Shan* \
[3rd Jul., 2024] [IEEE TMI, 2024] \
[[Paper](https://arxiv.org/abs/2407.03548)] [[GitHub](https://github.com/takimailto/HiDiff)]

**Stable Diffusion Segmentation for Biomedical Images with Single-step Reverse Process** \
*Tianyu Lin, Zhiguang Chen, Zhonghao Yan, Weijiang Yu, Fudan Zheng* \
[26th Jun., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2406.18361)] [[GitHub](https://github.com/lin-tianyu/Stable-Diffusion-Seg)]

**CriDiff: Criss-cross Injection Diffusion Framework via Generative Pre-train for Prostate Segmentation** \
*Tingwei Liu, Miao Zhang, Leiye Liu, Jialong Zhong, Shuyao Wang, Yongri Piao, Huchuan Lu* \
[20th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.14186)] [[GitHub](https://github.com/LiuTingWed/CriDiff)]

**Pancreatic Tumor Segmentation as Anomaly Detection in CT Images Using Denoising Diffusion Models** \
*Reza Babaei, Samuel Cheng, Theresa Thai, Shangqing Zhao* \
[4th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.02653)]

**Reliable Source Approximation: Source-Free Unsupervised Domain Adaptation for Vestibular Schwannoma MRI Segmentation** \
*Hongye Zeng, Ke Zou, Zhihao Chen, Rui Zheng, Huazhu Fu* \
[25th May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.16102)] [[GitHub](https://github.com/zenghy96/Reliable-Source-Approximation)]

**CTS: A Consistency-Based Medical Image Segmentation Model** \
*Kejia Zhang, Lan Zhang, Haiwei Pan, Baolong Yu* \
[14th May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.09056)] [[GitHub](https://github.com/LanHEU/CTS)]

**FlowSDF: Flow Matching for Medical Image Segmentation Using Distance Transforms** \
*Lea Bogensperger, Dominik Narnhofer, Alexander Falk, Konrad Schindler, Thomas Pock* \
[28th May, 2024] [IJCV, 2024] \
[[Paper](http://arxiv.org/abs/2405.18087v2)] [[GitHub](https://github.com/leabogensperger/FlowSDF)] 

**Discrepancy-based Diffusion Models for Lesion Detection in Brain MRI** \
*Keqiang Fan, Xiaohao Cai, Mahesan Niranjan* \
[8th May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.04974)]

**DiffSeg: A Segmentation Model for Skin Lesions Based on Diffusion Difference** \
*Zhihao Shuai, Yinan Chen, Shunqiang Mao, Yihan Zho, Xiaohong Zhang* \
[25th Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.16474)]

**Analysing Diffusion Segmentation for Medical Images** \
*Mathias Öttl, Siyuan Mei, Frauke Wilm, Jana Steenpass, Matthias Rübner, Arndt Hartmann, Matthias Beckmann, Peter Fasching, Andreas Maier, Ramona Erber, Katharina Breininger* \
[21st Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.11323)]

**Diffusion and Multi-Domain Adaptation Methods for Eosinophil Segmentation** \
*Kevin Lin, Donald Brown, Sana Syed, Adam Greene* \
[17th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.11323)]

**Polyp-DDPM: Diffusion-Based Semantic Polyp Synthesis for Enhanced Segmentation** \
*Zolnamar Dorjsembe, Hsing-Kuo Pao, Furen Xiao* \
[6th Feb., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2402.04031)] [[Github](https://github.com/mobaidoctor/polyp-ddpm)]

**Surf-CDM: Score-Based Surface Cold-Diffusion Model For Medical Image Segmentation** \
*Fahim Ahmed Zaman, Mathews Jacob, Amanda Chang, Kan Liu, Milan Sonka, Xiaodong Wu* \
[19th Dec., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2312.12649)]

**LSegDiff: A Latent Diffusion Model for Medical Image Segmentation** \
*Fahim Ahmed Zaman, Mathews Jacob, Amanda Chang, Kan Liu, Milan Sonka, Xiaodong Wu* \
[7th Dec., 2023] [SOICT, 2023] \
[[Paper](https://scholar.archive.org/work/2brq7udaqbglnfnmy44drkt55i/access/wayback/https://dl.acm.org/doi/pdf/10.1145/3628797.3629010)]

**Robust semi-supervised segmentation with timestep ensembling diffusion models** \
*Margherita Rosnati, Melanie Roschewitz, Ben Glocker* \
[13th Nov., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2311.07421)]

**A 3D generative model of pathological multi-modal MR images and segmentations** \
*Virginia Fernandez, Walter Hugo Lopez Pinaya, Pedro Borges, Mark S. Graham, Tom Vercauteren, M. Jorge Cardoso* \
[8th Nov., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2311.04552)] [[Github](https://github.com/virginiafdez/brainSPADE3D_rel)]

**One-shot Localization and Segmentation of Medical Images with Foundation Models** \
*Deepa Anand, Gurunath Reddy M, Vanika Singhal, Dattesh D. Shanbhag, Shriram KS, Uday Patil, Chitresh Bhushan, Kavitha Manickam, Dawei Gui, Rakesh Mullick, Avinash Gopal, Parminder Bhatia, Taha Kass-Hout* \
[28th Oct., 2023] [arXiv, 2023] \
[[Paper](http://arxiv.org/abs/2310.18642v1)]

**Towards Generic Semi-Supervised Framework for Volumetric Medical Image Segmentation** \
*Haonan Wang, Xiaomeng Li* \
[17th Oct., 2023] [NeurIPS, 2023] \
[[Paper](https://openreview.net/forum?id=NibgkUin5n)] [[Github](https://github.com/xmed-lab/GenericSSL)]

**Certification of Deep Learning Models for Medical Image Segmentation** \
*Othmane Laousy, Alexandre Araujo, Guillaume Chassagnon, Nikos Paragios, Marie-Pierre Revel, Maria Vakalopoulou* \
[5th Oct., 2023] [MICCAI, 2023] \
[[Paper](https://arxiv.org/abs/2310.03664)] [[Github](https://github.com/othmanela/medical_cert_seg)]

**Introducing Shape Prior Module in Diffusion Model for Medical Image Segmentation** \
*Zhiqing Zhang, Guojia Fan, Tianyong Liu, Nan Li, Yuyang Liu, Ziyu Liu, Canwei Dong, Shoujun Zhou* \
[12th Aug., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2309.05929)]

**A Recycling Training Strategy for Medical Image Segmentation with Diffusion Denoising Models** \
*Yunguan Fu, Yiwen Li, Shaheer U Saeed, Matthew J Clarkson, Yipeng Hu* \
[30th Aug., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2308.16355)] [[Github](https://github.com/mathpluscode/ImgX-DiffSeg)]

**Masked Diffusion as Self-supervised Representation Learner** \
*Zixuan Pan, Jianxu Chen, Yiyu Shi* \
[10th Aug., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2308.05695)]

**DermoSegDiff: A Boundary-aware Segmentation Diffusion Model for Skin Lesion Delineation** \
*Afshin Bozorgpour, Yousef Sadegheih, Amirhossein Kazerouni, Reza Azad, Dorit Merhof* \
[5th Aug., 2023] [MICCAI Workshop, 2023] \
[[Paper](https://arxiv.org/abs/2308.02959)] [[Github](https://github.com/mindflow-institue/DermoSegDiff)]

**C-DARL: Contrastive diffusion adversarial representation learning for label-free blood vessel segmentation** \
*Boah Kim, Yujin Oh, Bradford J. Wood, Ronald M. Summers, Jong Chul Ye* \
[31st Jul., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2308.00193)]

**Pre-Training with Diffusion models for Dental Radiography Segmentation** \
*Jérémy Rousseau, Christian Alaka, Emma Covili, Hippolyte Mayard, Laura Misrachi, Willy Au* \
[26th Jul., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2307.14066)]

**FEDD -- Fair, Efficient, and Diverse Diffusion-based Lesion Segmentation and Malignancy Classification** \
*Héctor Carrión, Narges Norouzi* \
[21st Jul., 2023] [MICCAI, 2023] \
[[Paper](https://arxiv.org/abs/2307.11654)] [[Github](https://github.com/hectorcarrion/fedd)]

**Annotator Consensus Prediction for Medical Image Segmentation with Diffusion Models** \
*Tomer Amit, Shmuel Shichrur, Tal Shaharbany, and Lior Wolf* \
[15th Jun., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.09004)] [[Github](https://github.com/tomeramit/annotator-consensus-prediction)]

**Conditional Diffusion Models for Weakly Supervised Medical Image Segmentation** \
*Xinrong Hu, Yu-Jen Chen, Tsung-Yi Ho, Yiyu Shi* \
[6th Jun., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.03878)] [[Github](https://github.com/xhu248/cond_ddpm_wsss)]

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
[10th Apr., 2023] [CVPR, 2023] \
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
[15th Mar., 2023] [ICCV, 2023] \
[[Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Zbinden_Stochastic_Segmentation_with_Conditional_Categorical_Diffusion_Models_ICCV_2023_paper.html)] [[Github](https://github.com/LarsDoorenbos/ccdm-stochastic-segmentation)]

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
[11th Nov., 2022] [ISBI, 2023] \
[[Paper](https://arxiv.org/abs/2211.06150)]

**MedSegDiff: Medical Image Segmentation with Diffusion Probabilistic Model** \
*Junde Wu, Huihui Fang, Yu Zhang, Yehui Yang, Yanwu Xu* \
[1st Nov., 2022] [MIDL, 2023] \
[[Paper](https://arxiv.org/abs/2211.00611)] [[Github](https://github.com/WuJunde/MedSegDiff)]

**Accelerating Diffusion Models via Pre-segmentation Diffusion Sampling for Medical Image Segmentation** \
*Xutao Guo, Yanwu Yang, Chenfei Ye, Shang Lu, Yang Xiang, Ting Ma* \
[27th Oct., 2022] [ISBI, 2023] \
[[Paper](https://arxiv.org/abs/2210.17408)]

**Diffusion Adversarial Representation Learning for Self-supervised Vessel Segmentation** \
*Boah Kim, Yujin Oh, Jong Chul Ye* \
[19th Sep., 2022] [ICLR, 2023] \
[[Paper](https://arxiv.org/abs/2209.14566)]

**Can segmentation models be trained with fully synthetically generated data?** \
*Virginia Fernandez, Walter Hugo Lopez Pinaya, Pedro Borges, Petru-Daniel Tudosiu, Mark S Graham, Tom Vercauteren, M Jorge Cardoso* \
[17th Sep., 2022] [MICCAI Workshop, 2022] \
[[Paper](https://arxiv.org/abs/2209.08256)]

**Diffusion Models for Implicit Image Segmentation Ensembles** \
*Julia Wolleb, Robin Sandkühler, Florentin Bieder, Philippe Valmaggia, Philippe C. Cattin* \
[6th Dec., 2021] [MIDL, 2022] \
[[Paper](https://arxiv.org/abs/2112.03145)] [[Github](https://github.com/juliawolleb/diffusion-based-segmentation)]

---

### Image-to-Image Translation

**Benchmarking GANs, Diffusion Models, and Flow Matching for T1w-to-T2w MRI Translation** \
*Andrea Moschetto, Lemuel Puglisi, Alec Sargood, Pierluigi Dell'Acqua, Francesco Guarnera, Sebastiano Battiato, Daniele Ravì* \
[19th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.14575v1)] [[Github](https://github.com/AndreaMoschetto/medical-I2I-benchmark)] 

**Human-Guided Shade Artifact Suppression in CBCT-to-MDCT Translation via Schrödinger Bridge with Conditional Diffusion** \
*Sung Ho Kang, Hyun-Cheol Park* \
[15th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.11025v1)]

**Regression is all you need for medical image translation** \
*Sebastian Rassmann, David Kügler, Christian Ewert, Martin Reuter* \
[04th May, 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2505.02048v2)]

**Diffusion Bridge Models for 3D Medical Image Translation** \
*Shaorong Zhang, Tamoghna Chattopadhyay, Sophia I. Thomopoulos, Jose-Luis Ambite, Paul M. Thompson, Greg Ver Steeg* \
[21st Apr., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.15267v1)]

**Structure-Accurate Medical Image Translation via Dynamic Frequency Balance and Knowledge Guidance** \
*Jiahua Xu, Dawei Zhou, Lei Hu, Zaiyi Liu, Nannan Wang, Xinbo Gao* \
[13th Apr., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.09441v2)]

**seg2med: a bridge from artificial anatomy to multimodal medical images** \
*Zeyu Yang, Zhilin Chen, Yipeng Sun, Anika Strittmatter, Anish Raj, Ahmad Allababidi, Johann S. Rink, Frank G. Zöllner* \
[12th Apr., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.09182v2)]

**Translation of Fetal Brain Ultrasound Images into Pseudo-MRI Images using Artificial Intelligence** \
*Naomi Silverstein, Efrat Leibowitz, Ron Beloosesky, Haim Azhari* \
[03rd Apr., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.02408v1)]

**Deterministic Medical Image Translation via High-fidelity Brownian Bridges** \
*Qisheng He, Nicholas Summerfield, Peiyong Wang, Carri Glide-Hurst, Ming Dong* \
[28th Mar., 2025] [CVPR, 2025] \
[[Paper](http://arxiv.org/abs/2503.22531v1)]

**VasTSD: Learning 3D Vascular Tree-state Space Diffusion Model for Angiography Synthesis** \
*Zhifeng Wang, Renjiao Yi, Xin Wen, Chenyang Zhu, Kai Xu* \
[17th Mar., 2025] [CVPR, 2025] \
[[Paper](http://arxiv.org/abs/2503.12758v1)] [[GitHub](https://jefferyzhifeng.github.io/projects/VasTSD/)] 

**Geodesic Diffusion Models for Medical Image-to-Image Generation** \
*Teng Zhang, Hongxu Jiang, Kuang Gong, Wei Shao* \
[2nd Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.00745v1)]

**3D Shape-to-Image Brownian Bridge Diffusion for Brain MRI Synthesis from Cortical Surfaces** \
*Fabian Bongratz, Yitong Li, Sama Elbaroudy, Christian Wachinger* \
[18th Feb., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2502.12742v1)] [[GitHub](https://github.com/ai-med/Cor2Vox)] 

**Trustworthy image-to-image translation: evaluating uncertainty calibration in unpaired training scenarios** \
*Ciaran Bench, Emir Ahmed, Spencer A. Thomas* \
[29th Jan., 2025] [IPMI, 2025] \
[[Paper](http://arxiv.org/abs/2501.17570v1)]

**Introducing 3D Representation for Medical Image Volume-to-Volume Translation via Score Fusion** \
*Xiyue Zhu, Dou Hoon Kwark, Ruike Zhu, Kaiwen Hong, Yiqi Tao, Shirui Luo, Yudu Li, Zhi-Pei Liang, Volodymyr Kindratenko* \
[13th Jan., 2025] [ICML, 2025] \
[[Paper](http://arxiv.org/abs/2501.07430v2)] [[Project Page](https://score-fusion.github.io/)] 

**Multi-Subject Image Synthesis as a Generative Prior for Single-Subject PET Image Reconstruction** \
*George Webber, Yuya Mizuno, Oliver D. Howes, Alexander Hammers, Andrew P. King, Andrew J. Reader* \
[05th Dec., 2024] [IEEE Symposium on Nuclear Science (NSS/MIC), 2024] \
[[Paper](http://arxiv.org/abs/2412.04324v1)]

**Cross-conditioned Diffusion Model for Medical Image to Image Translation** 
*Zhaohu Xing, Sicheng Yang, Sixiang Chen, Tian Ye, Yijun Yang, Jing Qin, Lei Zhu* 
[12th Sep., 2024] [MICCAI, 2024] 
[[Paper](https://arxiv.org/abs/2409.08500)]

**Bi-modality medical images synthesis by a bi-directional discrete process matching method** \
*Zhe Xiong, Qiaoqiao Ding, Xiaoqun Zhang* \
[06th Sep., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2409.03977v3)]

**Slice-Consistent 3D Volumetric Brain CT-to-MRI Translation with 2D Brownian Bridge Diffusion Model** \
*Kyobin Choo, Youngjun Jun, Mijin Yun, Seong Jae Hwang* \
[6th Jul., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2407.05059)] [[GitHub](https://github.com/MICV-yonsei/CT2MRI)]

**Soft Masked Mamba Diffusion Model for CT to MRI Conversion** \
*Zhenbin Wang, Lei Zhang, Lituan Wang, Zhenwei Zhang* \
[22nd Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.15910)] [[GitHub](https://github.com/wongzbb/DiffMa-Diffusion-Mamba)]

**2.5D Multi-view Averaging Diffusion Model for 3D Medical Image Translation: Application to Low-count PET Reconstruction with CT-less Attenuation Correction** \
*Tianqi Chen, Jun Hou, Yinchi Zhou, Huidong Xie, Xiongchao Chen, Qiong Liu, Xueqi Guo, Menghua Xia, James S. Duncan, Chi Liu, Bo Zhou*  \
[12th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.08374)]

**Similarity-aware Syncretic Latent Diffusion Model for Medical Image Translation with Representation Learning** \
*Tingyi Lin, Pengju Lyu, Jie Zhang, Yuqing Wang, Cheng Wang, Jianjun Zhu* \
[19th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.13977)]

**Fast-DDPM: Fast Denoising Diffusion Probabilistic Models for Medical Image-to-Image Generation** \
*Hongxu Jiang, Muhammad Imran, Linhai Ma, Teng Zhang, Yuyin Zhou, Muxuan Liang, Kuang Gong, Wei Shao* \
[23rd May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.14802)] [[GitHub](https://github.com/mirthAI/Fast-DDPM)]

**Cascaded Multi-path Shortcut Diffusion Model for Medical Image Translation** \
*Yinchi Zhou, Tianqi Chen, Jun Hou, Huidong Xie, Nicha C. Dvornek, S. Kevin Zhou, David L. Wilson, James S. Duncan, Chi Liu, Bo Zhou* \
[5th Apr., 2024] [MedIA, 2024] \
[[Paper](https://arxiv.org/abs/2405.12223)]

**Diffusion based Zero-shot Medical Image-to-Image Translation for Cross Modality Segmentation** \
*Zihao Wang, Yingyu Yang, Yuzhou Chen, Tingting Yuan, Maxime Sermesant, Herve Delingette, Ona Wu* \
[1st Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.01102)]

**Self-Consistent Recursive Diffusion Bridge for Medical Image Translation** \
*Fuat Arslan, Bilal Kabas, Onat Dalmaz, Muzaffer Ozbey, Tolga Çukur* \
[10th May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.06789)] [[GitHub](https://github.com/icon-lab/SelfRDB)]

**Tackling Structural Hallucination in Image Translation with Local Diffusion** \
*Seunghoi Kim, Chen Jin, Tom Diethe, Matteo Figini, Henry F. J. Tregidgo, Asher Mullokandov, Philip Teare, Daniel C. Alexander* \
[9th Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.05980)]

**Mitigating analytical variability in fMRI results with style transfer** \
*Elodie Germani, Elisa Fromont, Camille Maumet* \
[4th Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.03703)]

**ContourDiff: Unpaired Image Translation with Contour-Guided Diffusion Models** \
*Yuwen Chen, Nicholas Konz, Hanxue Gu, Haoyu Dong, Yaqian Chen, Lin Li, Jisoo Lee, Maciej A. Mazurowski* \
[16th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.10786)]

**FDDM: Unsupervised Medical Image Translation with a Frequency-Decoupled Diffusion Model** \
*Yunxiang Li, Hua-Chieh Shao, Xiaoxue Qian, You Zhang* \
[19th Nov., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2311.12070)]

**Adaptive Latent Diffusion Model for 3D Medical Image to Image Translation: Multi-modal Magnetic Resonance Imaging Study** \
*Jonghun Kim, Hyunjin Park* \
[1st Nov., 2023] [WACV, 2024] \
[[Paper](https://arxiv.org/abs/2311.00265)] [[Github](https://github.com/jongdory/ALDM/)]

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
[14th Mar., 2023] [MIDL, 2023] \
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
[17th Jul., 2022] [IEEE TMI Journal, 2022] \
[[Paper](https://arxiv.org/abs/2207.08208)]

**A Novel Unified Conditional Score-based Generative Framework for Multi-modal Medical Image Completion** \
*Xiangxi Meng, Yuning Gu, Yongsheng Pan, Nizhuan Wang, Peng Xue, Mengkang Lu, Xuming He, Yiqiang Zhan, Dinggang Shen* \
[7th Jul., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2207.03430)]

---

### Reconstruction

**PET Image Reconstruction Using Deep Diffusion Image Prior** \
*Fumio Hashimoto, Kuang Gong* \
[20th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.15078v1)]

**Physics-informed guided diffusion for accelerated multi-parametric MRI reconstruction** \
*Perla Mayo, Carolin M. Pirkl, Alin Achim, Bjoern Menze, Mohammad Golbabaee* \
[29th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.23311v1)]

**Adaptive Mask-guided K-space Diffusion for Accelerated MRI Reconstruction** \
*Qinrong Cai, Yu Guan, Zhibo Chen, Dong Liang, Qiuyun Fan, Qiegen Liu* \
[23th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.18270v1)] [[Github](https://github.com/yqx7150/AMDM)]

**Personalized MR-Informed Diffusion Models for 3D PET Image Reconstruction** \
*George Webber, Alexander Hammers, Andrew P. King, Andrew J. Reader* \
[04th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.03804v1)]

**Pseudoinverse Diffusion Models for Generative CT Image Reconstruction from Low Dose Data** \
*Matthew Tivnan, Dufan Wu, Quanzheng Li* \
[20th Feb., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2502.15064v1)]

**When are Diffusion Priors Helpful in Sparse Reconstruction? A Study with Sparse-view CT** \
*Matt Y. Cheung, Sophia Zorek, Tucker J. Netherton, Laurence E. Court, Sadeer Al-Kindi, Ashok Veeraraghavan, Guha Balakrishnan* \
[04th Feb., 2025] [ISBI, 2025] \
[[Paper](http://arxiv.org/abs/2502.02771v1)]

**Solving Blind Inverse Problems: Adaptive Diffusion Models for Motion-corrected Sparse-view 4DCT** \
*Antoine De Paepe, Alexandre Bousse, Clémentine Phung-Ngoc, Dimitris Visvikis* \
[21st Jan., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2501.12249v4)]

**Bigger Isn't Always Better: Towards a General Prior for Medical Image Reconstruction** \
*Lukas Glaszner, Martin Zach* \
[13th Jan., 2025] [DAGM, 2024] \
[[Paper](http://arxiv.org/abs/2501.07376v1)]

**A Conditional Diffusion Model for Electrical Impedance Tomography Image Reconstruction** \
*Shuaikai Shi, Ruiyuan Kang, Panos Liatsis* \
[22th Dec., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2412.16979v1)]

**Likelihood-Scheduled Score-Based Generative Modeling for Fully 3D PET Image Reconstruction** \
*George Webber, Yuya Mizuno, Oliver D. Howes, Alexander Hammers, Andrew P. King, Andrew J. Reader* \
[05th Dec., 2024] [IEEE TMI, 2024] \
[[Paper](http://arxiv.org/abs/2412.04339v2)]

**RN-SDEs: Limited-Angle CT Reconstruction with Residual Null-Space Diffusion Stochastic Differential Equations** \
*Jiaqi Guo, Santiago Lopez-Tapia, Wing Shun Li, Yunnan Wu, Marcelo Carignano, Vadim Backman, Vinayak P. Dravid, Aggelos K. Katsaggelos* \ 
[20th Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.13930)] [[GitHub](https://github.com/GuoJiaqi-1020/RN-SDE)]

**DX2CT: Diffusion Model for 3D CT Reconstruction from Bi or Mono-planar 2D X-ray(s)** 
*Yun Su Jeong, Hye Bin Yoo, Il Yong Chun* \
[13th Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.08850)] [[GitHub] \ (https://www.github.com/intyeger/DX2CT)]

**DiffuX2CT: Diffusion Learning to Reconstruct CT Images from Biplanar X-Rays** \
*Xuhui Liu, Zhi Qiao, Runkun Liu, Hong Li, Juan Zhang, Xiantong Zhen, Zhen Qian, Baochang Zhang* \
[18th Jul., 2024] [ECCV, 2025] \
[[Paper](https://arxiv.org/abs/2407.13545)] 

**Adaptive Compressed Sensing with Diffusion-Based Posterior Sampling** \
*Noam Elata, Tomer Michaeli, Michael Elad* \
[11th Jul., 2024] [ECCV, 2024] \
[[Paper](https://arxiv.org/abs/2407.08256)] [[GitHub](https://github.com/noamelata/AdaSense)]

**Highly Accelerated MRI via Implicit Neural Representation Guided Posterior Sampling of Diffusion Models** \
*Jiayue Chu, Chenhe Du, Xiyue Lin, Yuyao Zhang, Hongjiang Wei* \
[2nd Jul., 2024] [MedIA, 2024] \
[[Paper](https://arxiv.org/abs/2407.02744)]

**Diffusion Transformer Model With Compact Prior for Low-dose PET Reconstruction** \
*Bin Huang, Xubiao Liu, Lei Fang, Qiegen Liu, Bingxuan Li*  \
[30 Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.00944)] [[GitHub](https://github.com/yqx7150/DTM)]

**DiffusionBlend: Learning 3D Image Prior through Position-aware Diffusion Score Blending for 3D Computed Tomography Reconstruction** \
*Bowen Song, Jason Hu, Zhaoxu Luo, Jeffrey A. Fessler, Liyue Shen* \
[14th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.10211)]

**Learning Image Priors through Patch-based Diffusion Models for Solving Inverse Problems** \
*Jason Hu, Bowen Song, Xiaojian Xu, Liyue Shen, Jeffrey A. Fessler* \
[4th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.02462)]

**DEFT: Efficient Finetuning of Conditional Diffusion Models by Learning the Generalised $h$-transform** \
*Alexander Denker, Francisco Vargas, Shreyas Padhy, Kieran Didi, Simon Mathis, Vincent Dutordoir, Riccardo Barbano, Emile Mathieu, Urszula Julia Komorowska, Pietro Lio* \
[3rd Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.01781)]

**Blaze3DM: Marry Triplane Representation with Diffusion for 3D Medical Inverse Problem Solving** \
*Jia He, Bonan Li, Ge Yang, Ziwen Liu* \
[24th May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.15241)]

**Reducing the cost of posterior sampling in linear inverse problems via task-dependent score learning** \
*Fabian Schneider, Duc-Lam Duong, Matti Lassas, Maarten V. de Hoop, Tapio Helin* \
[24th May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.15643)] [[GitHub](https://github.com/FabianSBD/SBD-task-dependent)]

**DP-MDM: Detail-Preserving MR Reconstruction via Multiple Diffusion Models** \
*Mengxiao Geng, Jiahao Zhu, Xiaolin Zhu, Qiqing Liu, Dong Liang, Qiegen Liu* \
[9th May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.05763)] [[GitHub](https://github.com/yqx7150/DP-MDM)]

**Data-driven approaches for electrical impedance tomography image segmentation from partial boundary data** 
*Alexander Denker, Zeljko Kereta, Imraj Singh, Tom Freudenberg, Tobias Kluth, Peter Maass, Simon Arridge* \
[6th May, 2024] [Applied Mathematics for Modern Challenges Journal, 2024] \
[[Paper](https://arxiv.org/abs/2407.01559)] [[GitHub] \ (https://github.com/alexdenker/eit_fenicsx)]

**Bi-level Guided Diffusion Models for Zero-Shot Medical Imaging Inverse Problems** \
*Hossein Askari, Fred Roosta, Hongfu Sun* \
[4th Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.03706)]

**Score-Based Diffusion Models for Photoacoustic Tomography Image Reconstruction** \
*Sreemanti Dey, Snigdha Saha, Berthy T. Feng, Manxiu Cui, Laure Delisle, Oscar Leong, Lihong V. Wang, Katherine L. Bouman* \
[30th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.00471)]

**U2MRPD: Unsupervised undersampled MRI reconstruction by prompting a large latent diffusion model** \
*Ziqi Gao, S. Kevin Zhou* \
[16th Feb., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2402.10609)] [[GitHub](https://github.com/Z7Gao/MRPD)]

**Hyper-Diffusion: Estimating Epistemic and Aleatoric Uncertainty with a Single Model** \
*Matthew A. Chan, Maria J. Molina, Christopher A. Metzler* \
[5th Feb., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2402.03478)]

**A Comparative Study of Variational Autoencoders, Normalizing Flows, and Score-based Diffusion Models for Electrical Impedance Tomography** \
*Huihui Wang, Guixian Xu, Qingping Zhou* \
[29th Nov., 2023] [Journal of Inverse and Ill-posed Problems, 2024] \
[[Paper](https://arxiv.org/abs/2310.15831)] [[Github](https://github.com/adahfbch/DGM-EIT)]

**Ultrasound image reconstruction with denoising diffusion restoration models** \
*Yuxin Zhang, Clément Huneau, Jérôme Idier, Diana Mateus* \
[8th Oct., 2023] [DGM4MICCAI, 2023] \
[[Paper](https://arxiv.org/pdf/2307.15990)] [[Github](https://github.com/Yuxin-Zhang-Jasmine/DRUS-v1)]

**Sequential Diffusion-Guided Deep Image Prior For Medical Image Reconstruction** \
*Shijun Liang, Ismail Alkhouri, Qing Qu, Rongrong Wang, Saiprasad Ravishankar* \
[06th Oct., 2024] [ICASSP, 2025] \
[[Paper](http://arxiv.org/abs/2410.04482v2)]

**Steerable Conditional Diffusion for Out-of-Distribution Adaptation in Medical Image Reconstruction** \
*Riccardo Barbano, Alexander Denker, Hyungjin Chung, Tae Hoon Roh, Simon Arridge, Peter Maass, Bangti Jin, Jong Chul Ye* \
[28th Aug., 2023] [IEEE TMI, 2023] \
[[Paper](http://arxiv.org/abs/2308.14409v3)]

**Learning Fourier-Constrained Diffusion Bridges for MRI Reconstruction** \
*Muhammad U. Mirza, Onat Dalmaz, Hasan A. Bedel, Gokberk Elmas, Yilmaz Korkmaz, Alper Gungor, Salman UH Dar, Tolga Çukur* \
[4th Aug., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2308.01096)] [[Github](https://github.com/icon-lab/FDB)]

**Fast and Stable Diffusion Inverse Solver with History Gradient Update** \
*Linchao He, Hongyu Yan, Mengting Luo, Hongjie Wu, Kunming Luo, Wang Wang, Wenchao Du, Hu Chen, Hongyu Yang, Yi Zhang, Jiancheng Lv* \
[22th Jul., 2023] [arXiv, 2023] \
[[Paper](http://arxiv.org/abs/2307.12070v2)]

**Solving Inverse Problems with Latent Diffusion Models via Hard Data Consistency** \
*Bowen Song, Soo Min Kwon, Zecheng Zhang, Xinyu Hu, Qing Qu, Liyue Shen* \
[16th Jul., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2307.08123)]

**DiffuseIR: Diffusion Models For Isotropic Reconstruction of 3D Microscopic Images** \
*Mingjie Pan, Yulu Gan, Fangxu Zhou, Jiaming Liu, Aimin Wang, Shanghang Zhang, Dawei Li* \
[21st Jun., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.12109)]

**Optimizing Sampling Patterns for Compressed Sensing MRI with Diffusion Generative Models** \
*Sriram Ravula, Brett Levac, Ajil Jalal, Jonathan I. Tamir, Alexandros G. Dimakis* \
[5th Jun., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.03284)] [[Github](https://github.com/Sriram-Ravula/MRI_Sampling_Diffusion)]

**Solving Inverse Problems with Score-Based Generative Priors learned from Noisy Data** \
*Asad Aali, Marius Arvinte, Sidharth Kumar, Jonathan I. Tamir* \
[2nd May, 2023] [arXiv, 2023] \
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

**Lung-DDPM+: Efficient Thoracic CT Image Synthesis using Diffusion Probabilistic Model** \
*Yifan Jiang, Ahmad Shariftabrizi, Venkata SK. Manem* \
[12th Aug., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2508.09327v1)]

**Perceptual Evaluation of GANs and Diffusion Models for Generating X-rays** \
*Gregory Schuit, Denis Parra, Cecilia Besa* \
[10th Aug., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2508.07128v1)] [[GitHub](https://github.com/gregschuit/radiologist-perceptual-eval-xrays)]   

**MAISI-v2: Accelerated 3D High-Resolution Medical Image Synthesis with Rectified Flow and Region-specific Contrastive Loss** \
*Can Zhao, Pengfei Guo, Dong Yang, Yucheng Tang, Yufan He, Benjamin Simon, Mason Belue, Stephanie Harmon, Baris Turkbey, Daguang Xu* \
[07th Aug., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2508.05772v1)] [[GitHub](https://github.com/Project-MONAI/tutorials/tree/main/generation/maisi)] [[Demo](https://build.nvidia.com/nvidia/maisi)]  

**Adaptively Distilled ControlNet: Accelerated Training and Superior Sampling for Medical Image Synthesis** \
*Kunpeng Qiu, Zhiying Zhou, Yongxin Guo* \
[31th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.23652v1)] [[GitHub](https://github.com/Qiukunpeng/ADC)]  

**LesionGen: A Concept-Guided Diffusion Model for Dermatology Image Synthesis** \
*Jamil Fayyad, Nourhan Bayasi, Ziyang Yu, Homayoun Najjaran* \
[30th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.23001v1)] [[GitHub](https://github.com/jfayyad/LesionGen)]  

**Pyramid Hierarchical Masked Diffusion Model for Imaging Synthesis** \
*Xiaojiao Xiao, Qinmin Vivian Hu, Guanghui Wang* \
[22th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.16579v1)] [[GitHub](https://github.com/xiaojiao929/PHMDiff)]  

**AI-Driven Cytomorphology Image Synthesis for Medical Diagnostics** \
*Jan Carreras Boada, Rao Muhammad Umer, Carsten Marr* \
[07th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.05063v1)]

**MedDiff-FT: Data-Efficient Diffusion Model Fine-tuning with Structural Guidance for Controllable Medical Image Synthesis** \
*Jianhao Xie, Ziang Zhang, Zhenyu Weng, Yuesheng Zhu, Guibo Luo* \
[01st Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.00377v1)] [[GitHub](https://github.com/JianhaoXie1/MedDiff-FT)]  

**TRACE: Temporally Reliable Anatomically-Conditioned 3D CT Generation with Enhanced Efficiency** \
*Minye Shao, Xingyu Miao, Haoran Duan, Zeyu Wang, Jingkun Chen, Yawen Huang, Xian Wu, Jingjing Deng, Yang Long, Yefeng Zheng* \
[01st Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.00802v1)] [[GitHub](https://github.com/VinyehShaw/TRACE.git)]  

**Towards 3D Semantic Image Synthesis for Medical Imaging** \
*Wenwu Tang, Khaled Seyam, Bin Yang* \
[30th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.00206v1)]

**Angio-Diff: Learning a Self-Supervised Adversarial Diffusion Model for Angiographic Geometry Generation** \
*Zhifeng Wang, Renjiao Yi, Xin Wen, Chenyang Zhu, Kai Xu, Kunlun He* \
[24th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.19455v1)] [[GitHub](https://github.com/zfw-cv/AngioDiff)]  

**Doctor Approved: Generating Medically Accurate Skin Disease Images through AI-Expert Feedback** \
*Janet Wang, Yunbei Zhang, Zhengming Ding, Jihun Hamm* \
[14th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.12323v1)] [[GitHub](https://github.com/janet-sw/MAGIC.git)]  

**Prompt-Guided Latent Diffusion with Predictive Class Conditioning for 3D Prostate MRI Generation** \
*Emerson P. Grabke, Masoom A. Haider, Babak Taati* \
[11th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.10230v2)] [[GitHub](https://github.com/grabkeem/CCELLA)]  

**Skeleton-Guided Diffusion Model for Accurate Foot X-ray Synthesis in Hallux Valgus Diagnosis** \
*Midi Wan, Pengfei Li, Yizhuo Liang, Di Wu, Yushan Pan, Guangzhen Zhu, Hao Wang* \
[13th May, 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2505.08247v1)] https://github.com/midisec/SCCDM

**Noise-Consistent Siamese-Diffusion for Medical Image Synthesis and Segmentation** \
*Kunpeng Qiu, Zhiqiang Gao, Zhiying Zhou, Mingjie Sun, Yongxin Guo* \
[09th May, 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2505.06068v1)] [[GitHub](https://github.com/Qiukunpeng/Siamese-Diffusion)]  

**ViCTr: Vital Consistency Transfer for Pathology Aware Image Synthesis** \
*Onkar Susladkar, Gayatri Deshmukh, Yalcin Tur, Gorkhem Durak, Ulas Bagci* \
[08th May, 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2505.04963v3)] [[GitHub](https://github.com/Onkarsus13/ViCTr-2D)] 

**Bringing together invertible UNets with invertible attention modules for memory-efficient diffusion models** \
*Karan Jain, Mohammad Nayeem Teli* \
[15th Apr., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.10883v1)]

**MedSegFactory: Text-Guided Generation of Medical Image-Mask Pairs** \
*Jiawei Mao, Yuhan Wang, Yucheng Tang, Daguang Xu, Kang Wang, Yang Yang, Zongwei Zhou, Yuyin Zhou* \
[09th Apr., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.06897v2)] [[GitHub](https://github.com/jwmao1/MedSegFactory)] [[Project Page](https://jwmao1.github.io/MedSegFactory_web/)] 

**Few-Shot Generation of Brain Tumors for Secure and Fair Data Sharing** \
*Yongyi Shi, Ge Wang* \
[31st Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.00150v1)]

**Language-Guided Trajectory Traversal in Disentangled Stable Diffusion Latent Space for Factorized Medical Image Generation** \
*Zahra TehraniNasab, Amar Kumar, Tal Arbel* \
[30th Mar., 2025] [MIV-CVPR Workshop, 2025] \
[[Paper](http://arxiv.org/abs/2503.23623v1)] [[GitHub](https://github.com/tehraninasab/sd-latent-traversal)] [[Project Page](https://tehraninasab.github.io/sd-latent-traversal/)]   

**CoSimGen: Controllable Diffusion Model for Simultaneous Image and Mask Generation** \
*Rupak Bose, Chinedu Innocent Nwoye, Aditya Bhat, Nicolas Padoy* \
[25th Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.19661v1)] [[Project Page](https://camma-public.github.io/endogen/cosimgen)]  

**ZECO: ZeroFusion Guided 3D MRI Conditional Generation** \
*Feiran Wang, Bin Duan, Jiachen Tao, Nikhil Sharma, Dawen Cai, Yan Yan* \
[24th Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.18246v1)] [[GitHub](https://github.com/Brack-Wang/ZECO)] [[Project Page](https://brack-wang.github.io/ZECO_web/)] 

**MedLoRD: A Medical Low-Resource Diffusion Model for High-Resolution 3D CT Image Synthesis** \
*Marvin Seyfarth, Salman Ul Hassan Dar, Isabelle Ayx, Matthias Alexander Fink, Stefan O. Schoenberg, Hans-Ulrich Kauczor, Sandy Engelhardt* \
[17th Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.13211v1)]

**FCaS: Fine-grained Cardiac Image Synthesis based on 3D Template Conditional Diffusion Model** \
*Jiahao Xia, Yutao Hu, Yaolei Qi, Zhenliang Li, Wenqi Shao, Junjun He, Ying Fu, Longjiang Zhang, Guanyu Yang* \
[12th Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.09560v1)]

**Synthetic Lung X-ray Generation through Cross-Attention and Affinity Transformation** \
*Ruochen Pi, Lianlei Shan* \
[10th Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.07209v1)]

**Task-Specific Knowledge Distillation from the Vision Foundation Model for Enhanced Medical Image Segmentation** \
*Pengchen Liang, Haishan Huang, Bin Pu, Jianguo Chen, Xiang Hua, Jing Zhang, Weibo Ma, Zhuangzhuang Chen, Yiwei Li, Qing Chang* \
[10th Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.06976v1)]

**CQ CNN: A Hybrid Classical Quantum Convolutional Neural Network for Alzheimer's Disease Detection Using Diffusion Generated and U Net Segmented 3D MRI** \
*Mominul Islam, Mohammad Junayed Hasan, M. R. C. Mahdy* \
[04th Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.02345v1)] [[GitHub](https://github.com/mominul-ssv/alz-cq-cnn)]  

**Flow Matching for Medical Image Synthesis: Bridging the Gap Between Speed and Quality** \
*Milad Yazdani, Yasamin Medghalchi, Pooria Ashrafian, Ilker Hacihaliloglu, Dena Shahriari* \
[01st Mar., 2025] [MICCAI, 2025] \
[[Paper](http://arxiv.org/abs/2503.00266v1)] [[GitHub](https://github.com/milad1378yz/MOTFM)] 

**Advancing AI-Powered Medical Image Synthesis: Insights from MedVQA-GI Challenge Using CLIP, Fine-Tuned Stable Diffusion, and Dream-Booth + LoRA** \
*Ojonugwa Oluwafemi Ejiga Peter, Md Mahmudur Rahman, Fahmi Khalifa* \
[28th Feb., 2025] [CEUR workshop, 2025] \
[[Paper](http://arxiv.org/abs/2502.20667v2)]

**Robust Polyp Detection and Diagnosis through Compositional Prompt-Guided Diffusion Models** \
*Jia Yu, Yan Zhu, Peiyao Fu, Tianyi Chen, Junbo Huang, Quanlin Li, Pinghong Zhou, Zhihua Wang, Fei Wu, Shuo Wang, Xian Yang* \
[25th Feb., 2025] [IEEE TMI, 2025] \
[[Paper](http://arxiv.org/abs/2502.17951v1)] [[GitHub](https://github.com/Jia7878/compositional-prompt-diffusion-for-polyp-generation)]   

**Lung-DDPM: Semantic Layout-guided Diffusion Models for Thoracic CT Image Synthesis** \
*Yifan Jiang, Yannick Lemaréchal, Sophie Plante, Josée Bafaro, Jessica Abi-Rjeile, Philippe Joubert, Philippe Després, Venkata Manem* \
[21st Feb., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2502.15204v2)] [[GitHub](https://github.com/Manem-Lab/Lung-DDPM/)] 

**Ultrasound Image Generation using Latent Diffusion Models** \
*Benoit Freiche, Anthony El-Khoury, Ali Nasiri-Sarvi, Mahdi S. Hosseini, Damien Garcia, Adrian Basarab, Mathieu Boily, Hassan Rivaz* \
[12th Feb., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2502.08580v1)] https://github.com/Toterino/US-image-generation

**Ambient Denoising Diffusion Generative Adversarial Networks for Establishing Stochastic Object Models from Noisy Image Data** \
*Xichen Xu, Wentao Chen, Weimin Zhou* \
[31th Jan., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2501.19094v2)]

**Addressing Small and Imbalanced Medical Image Datasets Using Generative Models: A Comparative Study of DDPM and PGGANs with Random and Greedy K Sampling** \
*Iman Khazrak, Shakhnoza Takhirova, Mostafa M. Rezaee, Mehrdad Yadollahi, Robert C. Green II, Shuteng Niu* \
[17th Dec., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2412.12532v1)]

**3D MedDiffusion: A 3D Medical Diffusion Model for Controllable and High-quality Medical Image Generation** \
*Haoshen Wang, Zhentao Liu, Kaicong Sun, Xiaodong Wang, Dinggang Shen, Zhiming Cui* \
[17th Dec., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2412.13059v1)]

**MRGen: Segmentation Data Engine for Underrepresented MRI Modalities** \
*Haoning Wu, Ziheng Zhao, Ya Zhang, Yanfeng Wang, Weidi Xie* \
[04th Dec., 2024] [ICCV, 2025] \
[[Paper](http://arxiv.org/abs/2412.04106v3)] [[GitHub](https://github.com/haoningwu3639/MRGen/)] [[Project Page](https://haoningwu3639.github.io/MRGen/)]  

**Volumetric Conditioning Module to Control Pretrained Diffusion Models for 3D Medical Images** \
*Suhyun Ahn, Wonjung Park, Jihoon Cho, Seunghyuck Park, Jinah Park* \
[29th Oct., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2410.21826v1)] [[GitHub](https://github.com/Ahn-Ssu/VCM)]

**Evaluating and Improving the Effectiveness of Synthetic Chest X-Rays for Medical Image Analysis** \
*Eva Prakash, Jeya Maria Jose Valanarasu, Zhihong Chen, Eduardo Pontes Reis, Andrew Johnston, Anuj Pareek, Christian Bluethgen, Sergios Gatidis, Cameron Olsen, Akshay Chaudhari, Andrew Ng, Curtis Langlotz* \
[27th Nov., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2411.18602v1)]

**cWDM: Conditional Wavelet Diffusion Models for Cross-Modality 3D Medical Image Synthesis** \
*Paul Friedrich, Alicia Durrer, Julia Wolleb, Philippe C. Cattin* \
[26th Nov., 2024] [BraTS, 2024] \
[[Paper](http://arxiv.org/abs/2411.17203v1)] [[GitHub](https://github.com/pfriedri/cwdm)] 

**Counterfactual MRI Data Augmentation using Conditional Denoising Diffusion Generative Models** \
*Pedro Morão, Joao Santinha, Yasna Forghani, Nuno Loução, Pedro Gouveia, Mario A. T. Figueiredo* \
[31th Oct., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2410.23835v1)] [[GitHub](https://github.com/pedromorao/Counterfactual-MRI-Data-Augmentation)]

**Deep Generative Models for 3D Medical Image Synthesis** \
*Paul Friedrich, Yannik Frisch, Philippe C. Cattin* \
[23th Oct., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2410.17664v1)]

**Synthetic Augmentation for Anatomical Landmark Localization using DDPMs** \
*Arnela Hadzic, Lea Bogensperger, Simon Johannes Joham, Martin Urschler* \
[16th Oct., 2024] [SASHIMI, 2024] \
[[Paper](http://arxiv.org/abs/2410.12489v2)]

**Evaluating Utility of Memory Efficient Medical Image Generation: A Study on Lung Nodule Segmentation** \
*Kathrin Khadra, Utku Türkbey* \
[16th Oct., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2410.12542v1)]

**Multiscale Latent Diffusion Model for Enhanced Feature Extraction from Medical Images** \
*Rabeya Tus Sadia, Jie Zhang, Jin Chen* \
[05th Oct., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2410.04000v3)]

**Devil is in Details: Locality-Aware 3D Abdominal CT Volume Generation for Self-Supervised Organ Segmentation** \
*Yuran Wang, Zhijing Wan, Yansheng Qiu, Zheng Wang* \
[30th Sep., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2409.20332v2)]

**Ctrl-GenAug: Controllable Generative Augmentation for Medical Sequence Classification** \ 
*Xinrui Zhou, Yuhao Huang, Haoran Dou, Shijing Chen, Ao Chang, Jia Liu, Weiran Long, Jian Zheng, Erjiao Xu, Jie Ren, Ruobing Huang, Jun Cheng, Wufeng Xue, Dong Ni* \
[25th Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.17091)]

**Physics-Informed Latent Diffusion for Multimodal Brain MRI Synthesis** \
*Sven Lüpke, Yousef Yeganeh, Ehsan Adeli, Nassir Navab, Azade Farshad* \
[20th Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.13532)]

**MAISI: Medical AI for Synthetic Imaging** \
*Pengfei Guo, Can Zhao, Dong Yang, Ziyue Xu, Vishwesh Nath, Yucheng Tang, Benjamin Simon, Mason Belue, Stephanie Harmon, Baris Turkbey, Daguang Xu* \
[13th Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.11169)]

**Towards Predicting Temporal Changes in a Patient's Chest X-ray Images based on Electronic Health Records** \
*Daeun Kyung, Junu Kim, Tackeun Kim, Edward Choi* \
[11th Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.07012)] 

**Exploring Foundation Models for Synthetic Medical Imaging: A Study on Chest X-Rays and Fine-Tuning Techniques** \
*Davide Clode da Silva, Marina Musse Bernardes, Nathalia Giacomini Ceretta, Gabriel Vaz de Souza, Gabriel Fonseca Silva, Rafael Heitor Bordini, Soraia Raupp Musse* \
[6th Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.04424)]

**Multi-Conditioned Denoising Diffusion Probabilistic Model (mDDPM) for Medical Image Synthesis** \
*Arjun Krishna, Ge Wang, Klaus Mueller* \
[6th Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.04670)] 

**LPUWF-LDM: Enhanced Latent Diffusion Model for Precise Late-phase UWF-FA Generation on Limited Dataset** \
*Zhaojie Fang, Xiao Yu, Guanyu Zhou, Ke Zhuang, Yifei Chen, Ruiquan Ge, Changmiao Wang, Gangyong Jia, Qing Wu, Juan Ye, Maimaiti Nuliqiman, Peifang Xu, Ahmed Elazab* \
[1st Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.00726)] [[GitHub](https://github.com/Tinysqua/LPUWF-LDM)]

**Training-Free Condition Video Diffusion Models for single frame Spatial-Semantic Echocardiogram Synthesis** \
*Van Phi Nguyen, Tri Nhan Luong Ha, Huy Hieu Pham, Quoc Long Tran* \
[6th Aug., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2408.03035)] [[GitHub](https://github.com/gungui98/echo-free)]

**Mpox Detection Advanced: Rapid Epidemic Response Through Synthetic Data** \
*Yudara Kularathne, Prathapa Janitha, Sithira Ambepitiya, Prarththanan Sothyrajah, Thanveer Ahamed, Dinuka Wijesundara* \
[25th Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.17762)]

**URCDM: Ultra-Resolution Image Synthesis in Histopathology** \
*Sarah Cechnicka, James Ball, Matthew Baugh, Hadrien Reynaud, Naomi Simmonds, Andrew P. T. Smith, Catherine Horsfield, Candice Roufosse, Bernhard Kainz* \
[18th Jul., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2407.13277)] [[GitHub](https://github.com/scechnicka/URCDM)]

**CATD: Unified Representation Learning for EEG-to-fMRI Cross-Modal Generation** \
*Weiheng Yao, Shuqiang Wang* \
[16th Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2408.00777)]

**Bora: Biomedical Generalist Video Generation Model** \
*Weixiang Sun, Xiaocao You, Ruizhe Zheng, Zhengqing Yuan, Xiang Li, Lifang He, Quanzheng Li, Lichao Sun* \
[11th Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.08944)] [[GitHub](https://weixiang-sun.github.io/Bora/)]

**Data Augmentation with Diffusion Models for Colon Polyp Localization on the Low Data Regime: How much real data is enough?** 
*Adrian Tormos, Blanca Llauradó, Fernando Núñez, Axel Romero, Dario Garcia-Gasulla, Javier Béjar* 
[28th Nov., 2024] [arXiv, 2024] 
[[Paper](https://arxiv.org/abs/2411.18926)]

**Enhancing Spatiotemporal Disease Progression Models via Latent Diffusion and Prior Knowledge** \
*Lemuel Puglisi, Daniel C. Alexander, Daniele Ravì* \
[22th Aug., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2405.03328)] [[GitHub](https://github.com/LemuelPuglisi/BrLP)]

**SeLoRA: Self-Expanding Low-Rank Adaptation of Latent Diffusion Model for Medical Image Synthesis** \
*Yuchen Mao, Hongwei Li, Wei Pang, Giorgos Papanastasiou, Guang Yang, Chengjia Wang* \
[13th Aug., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2408.07196)]

**Temporal Evolution of Knee Osteoarthritis: A Diffusion-based Morphing Model for X-ray Medical Image Synthesis** \
*Zhe Wang, Aladine Chetouani, Rachid Jennane, Yuhua Ru, Wasim Issa, Mohamed Jarraya* \
[1st Aug., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2408.00891)]

**On Differentially Private 3D Medical Image Synthesis with Controllable Latent Diffusion Models** \
*Deniz Daum, Richard Osuala, Anneliese Riess, Georgios Kaissis, Julia A. Schnabel, Maxime Di Folco* \
[23rd Jul., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2407.16405)] [[GitHub](https://github.com/compai-lab/2024-miccai-dgm-daum)]

**Non-Reference Quality Assessment for Medical Imaging: Application to Synthetic Brain MRIs** \
*Karl Van Eeden Risager, Torkan Gholamalizadeh, Mostafa Mehdipour Ghazi* \
[20th Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.14994)]

**DiNO-Diffusion. Scaling Medical Diffusion via Self-Supervised Pre-Training** \
*Guillermo Jimenez-Perez, Pedro Osorio, Josef Cersovsky, Javier Montalt-Tordera, Jens Hooge, Steffen Vogler, Sadegh Mohammadi* \
[16th Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.11594)]

**Deformation-Recovery Diffusion Model (DRDM): Instance Deformation for Image Manipulation and Synthesis** \
*Jian-Qing Zheng, Yuanhan Mo, Yang Sun, Jiahua Li, Fuping Wu, Ziyang Wang, Tonia Vincent, Bartłomiej W. Papież* \
[9th Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.07295)] [[GitHub](https://jianqingzheng.github.io/def_diff_rec/)]

**RadiomicsFill-Mammo: Synthetic Mammogram Mass Manipulation with Radiomics Features** \
*Inye Na, Jonghun Kim, Eun Sook Ko, Hyunjin Park* \
[8th, Jul., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2407.05683)] [[GitHub](https://github.com/nainye/RadiomicsFill)]

**Diffusion as Sound Propagation: Physics-inspired Model for Ultrasound Image Generation** \
*Marina Domínguez, Yordanka Velikova, Nassir Navab, Mohammad Farid Azampour* \
[7th Jul., 2024] [IEEE Transactions on Ultrasonics, Ferroelectrics, and Frequency Control Journal, 2024] \
[[Paper](https://arxiv.org/abs/2407.05428)] [[GitHub](https://github.com/yuan-12138/Synomaly)]

**Deep learning for automated detection of breast cancer in deep ultraviolet fluorescence images with diffusion probabilistic model** \
*Sepehr Salem Ghahfarokhi, Tyrell To, Julie Jorns, Tina Yen, Bing Yu, Dong Hye Ye* \
[1st Jul., 2024] [ISBI, 2024] \
[[Paper](https://arxiv.org/abs/2407.00967)]

**From Majority to Minority: A Diffusion-based Augmentation for Underrepresented Groups in Skin Lesion Analysis** \
*Janet Wang, Yunsung Chung, Zhengming Ding, Jihun Hamm* \
[26th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.18375)]

**Towards Synchronous Memorizability and Generalizability with Site-Modulated Diffusion Replay for Cross-Site Continual Segmentation** \
*Dunyuan Xu, Xi Wang, Jingyang Zhang, Pheng-Ann Heng* \
[25th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.18037)] [[GitHub](https://github.com/dyxu-cuhkcse/SMG-Learning)]

**Test-Time Generative Augmentation for Medical Image Segmentation** \
*Xiao Ma, Yuhui Tao, Yuhan Zhang, Zexuan Ji, Yizhe Zhang, Qiang Chen* \
[25th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.17608)] [[GitHub](https://github.com/maxiao0234/TTGA)]

**X-ray2CTPA: Generating 3D CTPA scans from 2D X-ray conditioning** \
*Noa Cahan, Eyal Klang, Galit Aviram, Yiftach Barash, Eli Konen, Raja Giryes, Hayit Greenspan* \
[23rd Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.16109)] [[GitHub](https://github.com/NoaCahan/X-ray2CTPA)]

**Image Distillation for Safe Data Sharing in Histopathology** \
*Zhe Li, Bernhard Kainz* \
[19th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.13536)] [[GitHub](https://github.com/ZheLi2020/InfoDist)]

**3D MRI Synthesis with Slice-Based Latent Diffusion Models: Improving Tumor Segmentation Tasks in Data-Scarce Regimes** \
*Aghiles Kebaili, Jérôme Lapuyade-Lahorgue, Pierre Vera, Su Ruan* \
[8th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.05421)] [[GitHub](https://github.com/Arksyd96/synthesis-with-slice-based-ldm)]

**U-KAN Makes Strong Backbone for Medical Image Segmentation and Generation** \
*Chenxin Li, Xinyu Liu, Wuyang Li, Cheng Wang, Hengyu Liu, Yixuan Yuan* \
[5th Jun, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.02918)] [[GitHub](https://github.com/CUHK-AIM-Group/U-KAN)] [[Website](https://yes-ukan.github.io/)]

**EchoNet-Synthetic: Privacy-preserving Video Generation for Safe Medical Data Sharing** \
*Hadrien Reynaud, Qingjie Meng, Mischa Dombrowski, Arijit Ghosh, Thomas Day, Alberto Gomez, Paul Leeson, Bernhard Kainz* \
[2nd Jun, 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2406.00808)] [[GitHub](https://github.com/HReynaud/EchoNet-Synthetic)]

**Unsupervised Contrastive Analysis for Salient Pattern Detection using Conditional Diffusion Models** \
*Cristiano Patrício, Carlo Alberto Barbano, Attilio Fiandrotti, Riccardo Renzulli, Marco Grangetto, Luis F. Teixeira, João C. Neves* \
[2nd Jun, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.00772)] [[GitHub](https://github.com/CristianoPatricio/unsupervised-contrastive-cond-diff)]

**GenMix: Combining Generative and Mixture Data Augmentation for Medical Image Classification** \
*Hansang Lee, Haeil Lee, Helen Hong* \
[31st May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.20650)]

**Memory-efficient High-resolution OCT Volume Synthesis with Cascaded Amortized Latent Diffusion Models** \
*Kun Huang, Xiao Ma, Yuhan Zhang, Na Su, Songtao Yuan, Yong Liu, Qiang Chen, Huazhu Fu* \
[26th May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.16516)] [[GitHub](https://github.com/nicetomeetu21/ca-ldm)]

**MediSyn: Text-Guided Diffusion Models for Broad Medical 2D and 3D Image Synthesis** \
*Joseph Cho, Cyril Zakka, Rohan Shad, Ross Wightman, Akshay Chaudhari, William Hiesinger* \
[16th May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.09806)]

**VM-DDPM: Vision Mamba Diffusion for Medical Image Synthesis** \
*Zhihan Ju, Wanting Zhou* \
[09th May, 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2405.05667v1)]

**Long Tail Image Generation Through Feature Space Augmentation and Iterated Learning** \
*Rafael Elberg, Denis Parra, Mircea Petrache* \
[2nd May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.01705)] [[GitHub](https://github.com/SugarFreeManatee/Feature-Space-Augmentation-and-Iterated-Learning)]

**Generating Counterfactual Trajectories with Latent Diffusion Models for Concept Discovery** \
*Payal Varshney, Adriano Lucieri, Christoph Balada, Andreas Dengel, Sheraz Ahmed* \
[16th Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.10356)]

**MaSkel: A Model for Human Whole-body X-rays Generation from Human Masking Images** \
*Yingjie Xi, Boyuan Cheng, Jingyao Cai, Jian Jun Zhang, Xiaosong Yang* \
[13th Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.09000)] [[GitHub](https://github.com/2022yingjie/MaSkel)]

**Segmentation-Guided Knee Radiograph Generation using Conditional Diffusion Models** \
*Siyuan Mei, Fuxin Fan, Fabian Wagner, Mareike Thies, Mingxuan Gu, Yipeng Sun, Andreas Maier* \
[4th Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.03541)]

**Debiasing Cardiac Imaging with Controlled Latent Diffusion Models** \
*Grzegorz Skorupko, Richard Osuala, Zuzanna Szafranowska, Kaisar Kushibar, Nay Aung, Steffen E Petersen, Karim Lekadir, Polyxeni Gkontra* \
[28th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.19508)] [[Github](https://github.com/faildeny/debiasing-cardiac-mri)]

**Vision-Language Synthetic Data Enhances Echocardiography Downstream Tasks** \
*Pooria Ashrafian, Milad Yazdani, Moein Heidari, Dena Shahriari, Ilker Hacihaliloglu* \
[28th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.19880)] [[Github](https://github.com/Pooria90/DiffEcho)]

**CT Synthesis with Conditional Diffusion Models for Abdominal Lymph Node Segmentation** \
*Yongrui Yu, Hanyu Chen, Zitian Zhang, Qiong Xiao, Wenhui Lei, Linrui Dai, Yu Fu, Hui Tan, Guan Wang, Peng Gao, Xiaofan Zhang* \
[26th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.17770)]

**Paired Diffusion: Generation of related, synthetic PET-CT-Segmentation scans using Linked Denoising Diffusion Probabilistic Models** \
*Rowan Bradbury, Katherine A. Vallis, Bartlomiej W. Papiez* \
[26th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.17734)]

**MEDDAP: Medical Dataset Enhancement via Diversified Augmentation Pipeline** \
*Yasamin Medghalchi, Niloufar Zakariaei, Arman Rahmim, Ilker Hacihaliloglu* \
[25th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.16335)] [[Github](https://github.com/yasamin-med/MEDDAP)]

**LeFusion: Synthesizing Myocardial Pathology on Cardiac MRI via Lesion-Focus Diffusion Models** \
*Hantao Zhang, Jiancheng Yang, Shouhong Wan, Pascal Fua* \
[21st Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.14066)] [[Github](https://github.com/M3DV/LeFusion)]

**Generative Enhancement for 3D Medical Images** \
*Lingting Zhu, Noel Codella, Dongdong Chen, Zhenchao Jin, Lu Yuan, Lequan Yu* \
[14th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.12852)] [[Github](https://github.com/HKU-MedAI/GEM-3D)]

**XReal: Realistic Anatomy and Pathology-Aware X-ray Generation via Controllable Diffusion Model** \
*Anees Ur Rehman Hashmi, Ibrahim Almakky, Mohammad Areeb Qazi, Santosh Sanjeev, Vijay Ram Papineni, Dwarikanath Mahapatra, Mohammad Yaqub* \
[14th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.09240)] [[Github](https://github.com/BioMedIA-MBZUAI/XReal)]

**TrIND: Representing Anatomical Trees by Denoising Diffusion of Implicit Neural Fields** \
*Ashish Sinha, Ghassan Hamarneh* \
[13th Mar., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2403.08974)] [[Github](https://github.com/sinashish/TreeDiffusion)]

**Representing Anatomical Trees by Denoising Diffusion of Implicit Neural Fields** \
*Ashish Sinha, Ghassan Hamarneh* \
[13th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.08974)] [[Github](https://github.com/sinashish/TreeDiffusion)]

**Federated Data Model** \
*Xiao Chen, Shunan Zhang, Eric Z. Chen, Yikang Liu, Lin Zhao, Terrence Chen, Shanhui Sun* \
[13th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.08887)]

**GuideGen: A Text-Guided Framework for Full-torso Anatomy and CT Volume Generation** \
*Linrui Dai, Rongzhao Zhang, Yongrui Yu, Xiaofan Zhang* \
[12th Mar., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2403.07247v2)]

**A Domain Translation Framework with an Adversarial Denoising Diffusion Model to Generate Synthetic Datasets of Echocardiography Images** \
*Cristiana Tiago, Sten Roar Snare, Jurica Sprem, Kristin McLeod* \
[7th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.04612)]

**MedM2G: Unifying Medical Multi-Modal Generation via Cross-Guided Diffusion with Visual Invariant** \
*Chenlu Zhan, Yu Lin, Gaoang Wang, Hongwei Wang, Jian Wu* \
[7th Mar., 2024] [CVPR, 2024] \
[[Paper](https://arxiv.org/abs/2403.04290)]

**An Ordinal Diffusion Model for Generating Medical Images with Different Severity Levels** \
*Shumpei Takezaki, Seiichi Uchida* \
[1st Mar., 2024] [ISBI, 2024] \
[[Paper](https://arxiv.org/abs/2403.00452)]

**Structure Preserving Diffusion Models** \
*Haoye Lu, Spencer Szabados, Yaoliang Yu* \
[29th Feb., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2402.19369v2)]

**Towards Generalizable Tumor Synthesis** \
*Qi Chen, Xiaoxi Chen, Haorui Song, Zhiwei Xiong, Alan Yuille, Chen Wei, Zongwei Zhou* \
[29th Feb., 2024] [CVPR, 2024] \
[[Paper](https://arxiv.org/abs/2402.19470)] [[Github](https://github.com/MrGiovanni/DiffTumor)]

**WDM: 3D Wavelet Diffusion Models for High-Resolution Medical Image Synthesis** \
*Paul Friedrich, Julia Wolleb, Florentin Bieder, Alicia Durrer, Philippe C. Cattin* \
[29th Feb., 2024] [DGM4MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2402.19043)] [[Github](https://github.com/pfriedri/wdm-3d)] [[Project Page](https://pfriedri.github.io/wdm-3d-io/)]

**Anatomically-Controllable Medical Image Generation with Segmentation-Guided Diffusion Models** \
*Nicholas Konz, Yuwen Chen, Haoyu Dong, Maciej A. Mazurowski* \
[7th Feb., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2402.05210)]

**SynthVision -- Harnessing Minimal Input for Maximal Output in Computer Vision Models using Synthetic Image data** \
*Yudara Kularathne, Prathapa Janitha, Sithira Ambepitiya, Thanveer Ahamed, Dinuka Wijesundara, Prarththanan Sothyrajah* \
[5th Jan., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2402.02826)]

**DDPM based X-ray Image Synthesizer** \
*Praveen Mahaulpatha, Thulana Abeywardane, Tomson George* \
[3rd Jan., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2401.01539)]

**Fast Diffusion-Based Counterfactuals for Shortcut Removal and Generation** \
*Nina Weng, Paraskevas Pegios, Aasa Feragen, Eike Petersen, Siavash Bigdeli* \
[21st Dec., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2312.14223)]

**On the existence of optimal multi-valued decoders and their accuracy bounds for undersampled inverse problems** \
*Fangxin Shang, Jie Fu, Yehui Yang, Haifeng Huang, Junwei Liu, Lei Ma* \
[1st Dec., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2312.00377)] [[Github](https://github.com/parap1uie-s/SynFundus-1M)]

**Federated Learning with Diffusion Models for Privacy-Sensitive Vision Tasks** \
*Ye Lin Tun, Chu Myaet Thwal, Ji Su Yoon, Sun Moo Kang, Chaoning Zhang, Choong Seon Hong* \
[28th Nov., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2311.16538)]

**Overcoming Pathology Image Data Deficiency: Generating Images from Pathological Transformation Process** \
*Zeyu Liu, Yufang He, Yu Zhao, Yunlu Feng, Guanglei Zhang* \
[21st Nov., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2311.12316)] [[Github](https://github.com/Rowerliu/ADBD)]

**MAM-E: Mammographic synthetic image generation with diffusion models** \
*Ricardo Montoya-del-Angel, Karla Sam-Millan, Joan C Vilanova, Robert Martí* \
[16th Nov., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2311.09822)] [[Github](https://github.com/Likalto4/diffusion-models)]

**Synthetically Enhanced: Unveiling Synthetic Data's Potential in Medical Imaging Research** \
*Bardia Khosravi, Frank Li, Theo Dapamede, Pouria Rouzrokh, Cooper U. Gamble, Hari M. Trivedi, Cody C. Wyles, Andrew B. Sellergren, Saptarshi Purkayastha, Bradley J. Erickson, Judy W. Gichoya* \
[15th Nov., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2311.09402)] [[Github](https://github.com/BardiaKh/SyntheticallyEnhanced)]

**Synthesizing Diabetic Foot Ulcer Images with Diffusion Model** \
*Reza Basiri, Karim Manji, Francois Harton, Alisha Poonja, Milos R. Popovic, Shehroz S. Khan* \
[31st Oct., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.20140)]

**MCRAGE: Synthetic Healthcare Data for Fairness** \
*Keira Behal, Jiayi Chen, Caleb Fikes, Sophia Xiao* \
[27th Oct., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.18430)]

**Using Diffusion Models to Generate Synthetic Labelled Data for Medical Image Segmentation** \
*Daniel Saragih, Pascal Tyrrell* \
[25th Oct., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.16794)] [[Github](https://github.com/dsaragih/diffuse-gen)]

**EMIT-Diff: Enhancing Medical Image Segmentation via Text-Guided Diffusion Model** \
*Zheyuan Zhang, Lanhong Yao, Bin Wang, Debesh Jha, Elif Keles, Alpay Medetalibeyoglu, Ulas Bagci* \
[19th Oct., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.12868)]

**Echocardiography video synthesis from end diastolic semantic map via diffusion model** \
*Phi Nguyen Van, Duc Tran Minh, Hieu Pham Huy, Long Tran Quoc* \
[11th Oct., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.07131)]

**MedDiffusion: Boosting Health Risk Prediction via Diffusion-based Data Augmentation** \
*Yuan Zhong, Suhan Cui, Jiaqi Wang, Xiaochen Wang, Ziyi Yin, Yaqing Wang, Houping Xiao, Mengdi Huai, Ting Wang, Fenglong Ma* \
[4th Oct., 2023] [SIAM, 2024] \
[[Paper](https://arxiv.org/abs/2310.02520)]

**M3Dsynth: A dataset of medical 3D images with AI-generated local manipulations** \
*Giada Zingarini, Davide Cozzolino, Riccardo Corvi, Giovanni Poggi, Luisa Verdoliva* \
[3rd Sep., 2023] [MICCAI, 2023] \
[[Paper](https://arxiv.org/abs/2309.07973)] [[GitHub](https://grip-unina.github.io/M3Dsynth/)]

**ArSDM: Colonoscopy Images Synthesis with Adaptive Refinement Semantic Diffusion Models** \
*Yuhao Du, Yuncheng Jiang, Shuangyi Tan, Xusheng Wu, Qi Dou, Zhen Li, Guanbin Li, Xiang Wan* \
[3rd Sep., 2023] [MICCAI, 2023] \
[[Paper](https://arxiv.org/abs/2309.01111)] [[GitHub](https://github.com/DuYooho/ArSDM)]

**Augmenting medical image classifiers with synthetic data from latent diffusion models** \
*Luke W. Sagers, James A. Diao, Luke Melas-Kyriazi, Matthew Groh, Pranav Rajpurkar, Adewole S. Adamson, Veronica Rotemberg, Roxana Daneshjou, Arjun K. Manrai* \
[23rd Aug., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2308.12453)]

**Synthetic Augmentation with Large-scale Unconditional Pre-training** \
*Jiarong Ye, Haomiao Ni, Peng Jin, Sharon X. Huang, Yuan Xue* \
[8th Aug., 2023] [MICCAI, 2023] \
[[Paper](https://arxiv.org/abs/2308.04020)] [[GitHub](https://github.com/karenyyy/HistoDiffAug)]

**Make-A-Volume: Leveraging Latent Diffusion Models for Cross-Modality 3D Brain MRI Synthesis** \
*Lingting Zhu, Zeyue Xue, Zhenchao Jin, Xian Liu, Jingzhen He, Ziwei Liu, Lequan Yu* \
[19th Jul., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2307.10094)]

**DreaMR: Diffusion-driven Counterfactual Explanation for Functional MRI** \
*Hasan A. Bedel, Tolga C¸ ukur* \
[18th Jul., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2307.09547)] [[Github](https://github.com/icon-lab/DreaMR)]

**Hybrid Neural Diffeomorphic Flow for Shape Representation and Generation via Triplane** \
*Kun Han, Shanlin Sun, Xiaohui Xie* \
[4th July. 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2307.01957)]

**Investigating Data Memorization in 3D Latent Diffusion Models for Medical Image Synthesis** \
*Salman Ul Hassan Dar, Arman Ghanaat, Jannik Kahmann, Isabelle Ayx, Theano Papavassiliu, Stefan O. Schoenberg, Sandy Engelhardt* \
[3rd July. 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2307.01148)]

**DiffMix: Diffusion Model-based Data Synthesis for Nuclei Segmentation and Classification in Imbalanced Pathology Image Datasets** \
*Hyun-Jic Oh, Won-Ki Jeong* \
[25th Jun. 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.14132)]

**DiffInfinite: Large Mask-Image Synthesis via Parallel Random Patch Diffusion in Histopathology** \
*Marco Aversa, Gabriel Nobis, Miriam Hägele, Kai Standvoss, Mihaela Chirica, Roderick Murray-Smith, Ahmed Alaa, Lukas Ruff, Daniela Ivanova, Wojciech Samek, Frederick Klauschen, Bruno Sanguinetti, Luis Oala* \
[23th Jun. 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.13384)]

**Aligning Synthetic Medical Images with Clinical Knowledge using Human Feedback** \
*Shenghuan Sun, Gregory M. Goldgof, Atul Butte, Ahmed M. Alaa* \
[16th Jun., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.12438)]

**Diffusion Models for Realistic CT Image Generation** \
*Maialen Stephens Txurio, Karen López-Linares Román, Andrés Marcos-Carrión, Pilar Castellote-Huguet, José M. Santabárbara-Gómez, Iván Macía Oliver, Miguel A. González Ballester* \
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

**Don't Play Favorites: Minority Guidance for Diffusion Models** \
*Soobin Um, Suhyeon Lee, Jong Chul Ye* \
[29th Jan., 2023] [ICLR, 2024] \
[[Paper](http://arxiv.org/abs/2301.12334v2)]

**Conversion of the Mayo LDCT Data to Synthetic Equivalent through the Diffusion Model for Training Denoising Networks with a Theoretically Perfect Privacy** \
*Yongyi Shi, Ge Wang* \
[16th Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.06604)]

**Denoising Diffusion Probabilistic Models for Generation of Realistic Fully-Annotated Microscopy Image Data Sets** \
*Dennis Eschweiler, Johannes Stegmaier* \
[2nd Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.10227)] [[Github](https://github.com/stegmaierj/DiffusionModelsForImageSynthesis)] [[Synthetic Dataset](https://osf.io/dnp65/)]

**Generating Realistic 3D Brain MRIs Using a Conditional Diffusion Probabilistic Model** \
*Wei Peng, Ehsan Adeli, Qingyu Zhao, Kilian M Pohl* \
[15th Dec., 2022] [MICCAI, 2023] \
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
[[Paper](https://openreview.net/pdf?id=Oz7lKWVh45H)] [[Github](https://github.com/DL-Circle/3D-DDPM)]

---

### Text-to-Image

**Aiding Medical Diagnosis through Image Synthesis and Classification** \
*Kanishk Choudhary* \
[01th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.00786v1)]

**Text-to-CT Generation via 3D Latent Diffusion Model with Contrastive Vision-Language Pretraining** \
*Daniele Molino, Camillo Maria Caruso, Filippo Ruffini, Paolo Soda, Valerio Guarrasi* \
[31st May, 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.00633v1)]

**Prompt to Polyp: Medical Text-Conditioned Image Synthesis with Diffusion Models** \
*Mikhail Chaichuk, Sushant Gautam, Steven Hicks, Elena Tutubalina* \
[08th May, 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2505.05573v2)] [[Github](https://github.com/THunderCondOR/ImageCLEFmed-MEDVQA-GI-2024-MMCP-Team)] 

**Pathology-Aware Adaptive Watermarking for Text-Driven Medical Image Synthesis** \
*Chanyoung Kim, Dayun Ju, Jinyeong Kim, Woojung Han, Roberto Alcover-Couso, Seong Jae Hwang* \
[11th Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.08346v1)]

**Can Medical Vision-Language Pre-training Succeed with Purely Synthetic Data?** \
*Che Liu, Zhongwei Wan, Haozhe Wang, Yinda Chen, Talha Qaiser, Chen Jin, Fariba Yousefi, Nikolay Burlutskiy, Rossella Arcucci* \
[17th Oct., 2024] [ACL, 2025] \
[[Paper](http://arxiv.org/abs/2410.13523v2)]

**MedDiT: A Knowledge-Controlled Diffusion Transformer Framework for Dynamic Medical Image Generation in Virtual Simulated Patient** \
*Yanzeng Li, Cheng Zeng, Jinchao Zhang, Jie Zhou, Lei Zou* \
[22nd Aug., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2408.12236)]

**Chest-Diffusion: A Light-Weight Text-to-Image Model for Report-to-CXR Generation** \
*Peng Huang, Xue Gao, Lihong Huang, Jing Jiao, Xiaokang Li, Yuanyuan Wang, Yi Guo* \
[30 Jun., 2024] [ISBI, 2024] \
[[Paper](https://arxiv.org/abs/2407.00752)]

**Fair Text to Medical Image Diffusion Model with Subgroup Distribution Aligned Tuning** \
*Xu Han, Fangfang Fan, Jingzhao Rong, Xiaofeng Liu* \
[20th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.14847)]

**Advancing Text-Driven Chest X-Ray Generation with Policy-Based Reinforcement Learning** \
*Woojung Han, Chanyoung Kim, Dayun Ju, Yumin Shim, Seong Jae Hwang* \
[11th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.06516)]

**Synthesizing CTA Image Data for Type-B Aortic Dissection using Stable Diffusion Models** \
*Ayman Abaid, Muhammad Ali Farooq, Niamh Hynes, Peter Corcoran, Ihsan Ullah* \
[10th Feb., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2402.06969)]

**Navigating the Synthetic Realm: Harnessing Diffusion-based Models for Laparoscopic Text-to-Image Generation** \
*Simeon Allmendinger, Patrick Hemmer, Moritz Queisner, Igor Sauer, Leopold Müller, Johannes Jakubik, Michael Vössing, Niklas Kühl* \
[5th Dec., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2312.03043)] [[Github](https://github.com/SimeonAllmendinger/SyntheticImageGeneration)]

**MedXChat: Bridging CXR Modalities with a Unified Multimodal Large Model** \
*Ling Yang, Zhanyu Wang, Luping Zhou* \
[4th Dec., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2312.02233)]

**BiomedJourney: Counterfactual Biomedical Image Generation by Instruction-Learning from Multimodal Patient Journeys** \
*Yu Gu, Jianwei Yang, Naoto Usuyama, Chunyuan Li, Sheng Zhang, Matthew P. Lungren, Jianfeng Gao, Hoifung Poon* \
[16th Oct., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.10765)]

**MedSyn: Text-guided Anatomy-aware Synthesis of High-Fidelity 3D CT Images** \
*Yanwu Xu, Li Sun, Wei Peng, Shyam Visweswaran, Kayhan Batmanghelich* \
[5th Oct., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.03559)] [[Github](https://github.com/batmanlab/MedSyn)]

**Boosting Dermatoscopic Lesion Segmentation via Diffusion Models with Visual and Textual Prompts** \
*Shiyi Du, Xiaosong Wang, Yongyi Lu, Yuyin Zhou, Shaoting Zhang, Alan Yuille, Kang Li, Zongwei Zhou* \
[4th Oct., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.02906)]

**TauPETGen: Text-Conditional Tau PET Image Synthesis Based on Latent Diffusion Models** \
*Se-In Jang, Cristina Lois, Emma Thibault, J. Alex Becker, Yafei Dong, Marc D. Normandin, Julie C. Price, Keith A. Johnson, Georges El Fakhri, Kuang Gong* \
[21st Jun., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.11984)]

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


**DiffuseReg: Denoising Diffusion Model for Obtaining Deformation Fields in Unsupervised Deformable Image Registration** \
*Yongtai Zhuo, Yiqing Shen* \
[07th Oct., 2024] [MICCAI, 2024] \
[[Paper](http://arxiv.org/abs/2410.05234v1)]

**Learning Diffeomorphism for Image Registration with Time-Continuous Networks using Semigroup Regularization** \
*Mohammadjavad Matinkia, Nilanjan Ray* \
[28th May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.18684)] [[GitHub](https://github.com/mattkia/SGDIR)]

**FSDiffReg: Feature-wise and Score-wise Diffusion-guided Unsupervised Deformable Image Registration for Cardiac Images** \
*Yi Qin, Xiaomeng Li* \
[22nd Jul., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2307.12035)] [[Github](https://github.com/xmed-lab/FSDiffReg.git)]

**DiffuseMorph: Unsupervised Deformable Image Registration Along Continuous Trajectory Using Diffusion Models** \
*Boah Kim, Inhwa Han, Jong Chul Ye* \
[9th Dec., 2021] [ECCV, 2022] \
[[Paper](https://arxiv.org/abs/2112.05149)]

---

### Classification

**DAug: Diffusion-based Channel Augmentation for Radiology Image Retrieval and Classification** \
*Ying Jin, Zhuoran Zhou, Haoquan Fang, Jenq-Neng Hwang* \
[06th Dec., 2024] [NeurIPS Workshop, 2024] \
[[Paper](http://arxiv.org/abs/2412.04828v1)]

**Ctrl-GenAug: Controllable Generative Augmentation for Medical Sequence Classification** \ 
*Xinrui Zhou, Yuhao Huang, Haoran Dou, Shijing Chen, Ao Chang, Jia Liu, Weiran Long, Jian Zheng, Erjiao Xu, Jie Ren, Ruobing Huang, Jun Cheng, Wufeng Xue, Dong Ni* \
[25th Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.17091)]

**Anisotropic Diffusion Probabilistic Model for Imbalanced Image Classification** \
*Jingyu Kong, Yuan Guo, Yu Wang, Yuping Duan* \
[22nd Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.14313)]

**Deep Generative Classification of Blood Cell Morphology** \
*Simon Deltadahl, Julian Gilbey, Christine Van Laer, Nancy Boeckx, Mathie Leers, Tanya Freeman, Laura Aiken, Timothy Farren, Matthew Smith, Mohamad Zeina, BloodCounts! consortium, Concetta Piazzese, Joseph Taylor, Nicholas Gleadall, Carola-Bibiane Schönlieb, Suthesh Sivapalaratnam, Michael Roberts, Parashkev Nachev* \
[16th Aug., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2408.08982)][[GitHub](https://github.com/Deltadahl/CytoDiffusion)]

**Counterfactual Explanations for Medical Image Classification and Regression using Diffusion Autoencoder** \
*Matan Atad, David Schinz, Hendrik Moeller, Robert Graf, Benedikt Wiestler, Daniel Rueckert, Nassir Navab, Jan S. Kirschke, Matthias Keicher* \
[2nd Aug., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2408.01571)] [[GitHub](https://github.com/matanat/dae_counterfactual)]

**Diff3Dformer: Leveraging Slice Sequence Diffusion for Enhanced 3D CT Classification with Transformer Networks** \
*Zihao Jin, Yingying Fang, Jiahao Huang, Caiwen Xu, Simon Walsh, Guang Yang* \
[24th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.17173)] [[GitHub](https://github.com/ayanglab/Diff3Dformer)]

**Guided Conditional Diffusion Classifier (ConDiff) for Enhanced Prediction of Infection in Diabetic Foot Ulcers** \
*Palawat Busaranuvong, Emmanuel Agu, Deepak Kumar, Shefalika Gautam, Reza Saadati Fard, Bengisu Tulu, Diane Strong* \
[1st May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.00858)]

**Improving Robustness and Reliability in Medical Image Classification with Latent-Guided Diffusion and Nested-Ensembles** \
*Xing Shen, Hengguan Huang, Brennan Nichyporuk, Tal Arbel* \
[10th Nov., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.15952)]

**Improving Nonalcoholic Fatty Liver Disease Classification Performance With Latent Diffusion Models** \
*Romain Hardy, Cornelia Ilin, Joe Klepich, Ryan Mitchell, Steve Hall, Jericho Villareal* \
[13th Jul., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2307.06507)]

**Interpretable Alzheimer's Disease Classification Via a Contrastive Diffusion Autoencoder** \
*Ayodeji Ijishakin, Ahmed Abdulaal, Adamos Hadjivasiliou, Sophie Martin, James Cole* \
[5th Jun., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.03022)]

**DiffMIC: Dual-Guidance Diffusion Network for Medical Image Classification** \
*Yijun Yang, Huazhu Fu, Angelica I. Aviles-Rivero, Carola-Bibiane Schönlieb, Lei Zhu* \
[19th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.10610)] [[Github](https://github.com/scott-yjyang/DiffMIC)]

---

### Object Detection

**LoGex: Improved tail detection of extremely rare histopathology classes via guided diffusion** \
*Maximilian Mueller, Matthias Hein* \
[2nd Sep., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.01317)] [[GitHub](https://github.com/mueller-mp/logex)]

**Diffusion-Based Hierarchical Multi-Label Object Detection to Analyze Panoramic Dental X-rays** \
*Ibrahim Ethem Hamamci, Sezgin Er, Enis Simsar, Anjany Sekuboyina, Mustafa Gundogar, Bernd Stadlinger, Albert Mehl, Bjoern Menze* \
[11th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.06500)] [[Github](https://github.com/ibrahimethemhamamci/HierarchicalDet)]

---
### Image Restoration
#### Inpainting

**MaskMedPaint: Masked Medical Image Inpainting with Diffusion Models for Mitigation of Spurious Correlations** \
*Qixuan Jin, Walter Gerych, Marzyeh Ghassemi* \
[16th Nov., 2024] [ML4H, 2024] \
[[Paper](http://arxiv.org/abs/2411.10686v1)] [[GitHub](https://github.com/QixuanJin99/generative_validation)] 

**Investigating the Role of Bilateral Symmetry for Inpainting Brain MRI** \
*Sergey Kuznetsov, Sanduni Pinnawala, Peter A. Wijeratne, Ivor J. A. Simpson* \
[14th Apr., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.10039v1)]

**FCDM: Sparse-view Sinogram Inpainting with Frequency Domain Convolution Enhanced Diffusion Models** \
*Jiaze E, Srutarshi Banerjee, Tekin Bicer, Guannan Wang, Yanfu Zhang, Bin Ren* \
[26th Aug., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2409.06714)]

**Inpainting Pathology in Lumbar Spine MRI with Latent Diffusion** \
*Colin Hansen, Simas Glinskis, Ashwin Raju, Micha Kornreich, JinHyeong Park, Jayashri Pawar, Richard Herzog, Li Zhang, Benjamin Odry* \
[4th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.02477)]

**Multitask Brain Tumor Inpainting with Diffusion Models: A Methodological Report** \
*Pouria Rouzrokh, Bardia Khosravi, Shahriar Faghani, Mana Moassefi, Sanaz Vahdati, Bradley J. Erickson* \
[21st Oct., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2210.12113)] [[GitHub](https://github.com/Mayo-Radiology-Informatics-Lab/MBTI)] [[Online Tool](https://1f1f559d51c361e2.gradio.app/)]

---

#### Super Resolution

**Quaternion Wavelet-Conditioned Diffusion Models for Image Super-Resolution** \
*Luigi Sigillo, Christian Bianchi, Aurelio Uncini, Danilo Comminiello* \
[1st May, 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2505.00334v2)]

**MRI super-resolution reconstruction using efficient diffusion probabilistic model with residual shifting** \
*Mojtaba Safari, Shansong Wang, Zach Eidex, Qiang Li, Erik H. Middlebrooks, David S. Yu, Xiaofeng Yang* \
[3rd Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.01576v2)] [[GitHub](https://github.com/mosaf/Res-SRDiff)] 

**Temporal and Spatial Super Resolution with Latent Diffusion Model in Medical MRI images** \
*Vishal Dubey* \
[29th Oct., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2410.23898v1)] [[GitHub](https://github.com/vishal-dubey-0026/TemporalSpatialSR_LDM)]
 
**Simultaneous Tri-Modal Medical Image Fusion and Super-Resolution using Conditional Diffusion Model** \
*Yushen Xu, Xiaosong Li, Yuchan Jie, Haishu Tan* \
[26th Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.17357)]

**Implicit Image-to-Image Schrodinger Bridge for CT Super-Resolution and Denoising** \
*Yuang Wang, Siyeop Yoon, Pengfei Jin, Matthew Tivnan, Zhennong Chen, Rui Hu, Li Zhang, Zhiqiang Chen, Quanzheng Li, Dufan Wu* \
[10th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.06069)]

**Cas-DiffCom: Cascaded diffusion model for infant longitudinal super-resolution 3D medical image completion** \
*Lianghu Guo, Tianli Tao, Xinyi Cai, Zihao Zhu, Jiawei Huang, Lixuan Zhu, Zhuoyang Gu, Haifeng Tang, Rui Zhou, Siyan Han, Yan Liang, Qing Yang, Dinggang Shen, Han Zhang* \
[21st Feb., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2402.13776)]

**Image Compression and Decompression Framework Based on Latent Diffusion Model for Breast Mammography** \
*InChan Hwang, MinJae Woo* \
[8th Oct, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.05299)]

**InverseSR: 3D Brain MRI Super-Resolution Using a Latent Diffusion Model** \
*Jueqi Wang, Jacob Levman, Walter Hugo Lopez Pinaya, Petru-Daniel Tudosiu, M. Jorge Cardoso, Razvan Marinescu* \
[23rd Aug, 2023] [MICCAI, 2023] \
[[Paper](https://arxiv.org/abs/2308.12465)] [[GitHub](https://github.com/BioMedAI-UCSC/InverseSR)]

**Self-similarity-based super-resolution of photoacoustic angiography from hand-drawn doodles** \
*Yuanzheng Ma, Wangting Zhou, Rui Ma, Sihua Yang, Yansong Tang, Xun Guan* \
[2nd May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.01165)] [[GitHub](https://github.com/yuanzhengthu/handDrawnPAAImages)]

**DisC-Diff: Disentangled Conditional Diffusion Model for Multi-Contrast MRI Super-Resolution** \
*Ye Mao, Lan Jiang, Xi Chen, Chao Li* \
[24th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.13933)]

---

#### Enhancement

**All-in-One Medical Image Restoration with Latent Diffusion-Enhanced Vector-Quantized Codebook Prior** \
*Haowei Chen, Zhiwen Yang, Haotian Hou, Hui Zhang, Bingzheng Wei, Gang Zhou, Yan Xu* \
[26th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.19874v1)]

**Investigating the Feasibility of Patch-based Inference for Generalized Diffusion Priors in Inverse Problems for Medical Images** \
*Saikat Roy, Mahmoud Mostapha, Radu Miron, Matt Holbrook, Mariappan Nadar* \
[25th Jan., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2501.15309v2)]

**Lightening Anything in Medical Images** \
*Ben Fei, Yixuan Li, Weidong Yang, Hengjun Gao, Jingyi Xu, Lipeng Ma, Yatian Yang, Pinghong Zhou* \
[1st Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.10236)] [[GitHub](https://github.com/Fayeben/UniMIE)]

**LighTDiff: Surgical Endoscopic Image Low-Light Enhancement with T-Diffusion** \
*Tong Chen, Qingcheng Lyu, Long Bai, Erjian Guo, Huxin Gao, Xiaoxiao Yang, Hongliang Ren, Luping Zhou* \
[17th May, 2024] [MICCAI, 2024]
[[Paper](https://arxiv.org/abs/2405.10550)] [[GitHub](https://github.com/DavisMeee/LighTDiff)]

**Towards Learning Contrast Kinetics with Multi-Condition Latent Diffusion Models** \
*Richard Osuala, Daniel Lang, Preeti Verma, Smriti Joshi, Apostolia Tsirikoglou, Grzegorz Skorupko, Kaisar Kushibar, Lidia Garrucho, Walter H. L. Pinaya, Oliver Diaz, Julia Schnabel, Karim Lekadir* \
[20th Mar, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.13890)] [[GitHub](https://github.com/RichardObi/ccnet)]

**Step-Calibrated Diffusion for Biomedical Optical Image Restoration** \
*Yiwei Lyu, Sung Jik Cha, Cheng Jiang, Asadur Chowdury, Xinhai Hou, Edward Harake, Akhil Kondepudi, Christian Freudiger, Honglak Lee, Todd C. Hollon* \
[20th Mar, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.13680)] [[GitHub](https://github.com/MLNeurosurg/restorative_step-calibrated_diffusion)]

**LLCaps: Learning to Illuminate Low-Light Capsule Endoscopy with Curved Wavelet Attention and Reverse Diffusion** \
*Long Bai, Tong Chen, Yanan Wu, An Wang, Mobarakol Islam, Hongliang Ren* \
[5th July, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2307.02452)] [[GitHub](https://github.com/longbai1006/LLCaps)]

---

### Editing

**Interactive Tumor Progression Modeling via Sketch-Based Image Editing** \
*Gexin Huang, Ruinan Jin, Yucheng Tang, Can Zhao, Tatsuya Harada, Xiaoxiao Li, Gu Lin* \
[10th Mar., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2503.06809v1)]

**Latent Drifting in Diffusion Models for Counterfactual Medical Image Synthesis** \
*Yousef Yeganeh, Azade Farshad, Ioannis Charisiadis, Marta Hasny, Martin Hartenberger, Björn Ommer, Nassir Navab, Ehsan Adeli* \
[30th Dec., 2024] [CVPR, 2025] \
[[Paper](http://arxiv.org/abs/2412.20651v2)] [[Project Page](https://latentdrifting.github.io/)] 

**MedEdit: Counterfactual Diffusion-based Image Editing on Brain MRI** \
*Malek Ben Alaya, Daniel M. Lang, Benedikt Wiestler, Julia A. Schnabel, Cosmin I. Bercea* \
[21st Jul., 2024] [SASHIMI, 2024] \
[[Paper](https://arxiv.org/abs/2407.15270)] 

**PIE: Simulating Disease Progression via Progressive Image Editing** \
*Kaizhao Liang, Xu Cao, Kuei-Da Liao, Tianren Gao, Wenqian Ye, Zhengyu Chen, Jianguo Cao, Tejas Nama, Jimeng Sun* \
[21st Sep., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2309.11745)]

---

### Adversarial Attacks

**Prompt2Perturb (P2P): Text-Guided Diffusion-Based Adversarial Attacks on Breast Ultrasound Images** \
*Yasamin Medghalchi, Moein Heidari, Clayton Allard, Leonid Sigal, Ilker Hacihaliloglu* \
[13th December, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2412.09910)] [[GitHub](https://github.com/yasamin-med/P2P)]

**On enhancing the robustness of Vision Transformers: Defensive Diffusion** \
*Raza Imam, Muhammad Huzaifa, Mohammed El-Amine Azz* \
[14th May, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2305.08031)] [[GitHub](https://github.com/Muhammad-Huzaifaa/Defensive_Diffusion)]

**Fight Fire With Fire: Reversing Skin Adversarial Examples by Multiscale Diffusive and Denoising Aggregation Mechanism** \
*Yongwei Wang, Yuan Li, Zhiqi Shen* \
[22nd Aug., 2022] [arXiv, 2022] \
[[Paper](https://arxiv.org/abs/2208.10373)]

---

### Fairness

**AI Alignment in Medical Imaging: Unveiling Hidden Biases Through Counterfactual Analysis** \
*Haroui Ma, Francesco Quinzan, Theresa Willem, Stefan Bauer* \
[28th Apr., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2504.19621v1)] [[GitHub](https://github.com/Neferpitou3871/AI-Alignment-Medical-Imaging)] 

**FairDiffusion: Enhancing Equity in Latent Diffusion Models via Fair Bayesian Perturbation** \
*Yan Luo, Muhammad Osama Khan, Congcong Wen, Muhammad Muneeb Afzal, Titus Fidelis Wuermeling, Min Shi, Yu Tian, Yi Fang, Mengyu Wang* \
[29th Dec., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2412.20374v2)] [[GitHub](https://github.com/Harvard-Ophthalmology-AI-Lab/FairDiffusion)] 

**FairDiff: Fair Segmentation with Point-Image Diffusion** \
*Wenyi Li, Haoran Xu, Guiyu Zhang, Huan-ang Gao, Mingju Gao, Mengyu Wang, Hao Zhao* \
[8th Jul., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2407.06250)] [[GitHub](https://github.com/wenyi-li/FairDiff)]

**From Majority to Minority: A Diffusion-based Augmentation for Underrepresented Groups in Skin Lesion Analysis** \
*Janet Wang, Yunsung Chung, Zhengming Ding, Jihun Hamm* \
[26th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.18375)]

**Fair Text to Medical Image Diffusion Model with Subgroup Distribution Aligned Tuning** \
*Xu Han, Fangfang Fan, Jingzhao Rong, Xiaofeng Liu* \
[20th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.14847)]

**Debiasing Cardiac Imaging with Controlled Latent Diffusion Models** \
*Grzegorz Skorupko, Richard Osuala, Zuzanna Szafranowska, Kaisar Kushibar, Nay Aung, Steffen E Petersen, Karim Lekadir, Polyxeni Gkontra* \
[28th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.19508)] [[Github](https://github.com/faildeny/debiasing-cardiac-mri)]

**MCRAGE: Synthetic Healthcare Data for Fairness** \
*Keira Behal, Jiayi Chen, Caleb Fikes, Sophia Xiao* \
[27th Oct., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.18430)]

**FEDD -- Fair, Efficient, and Diverse Diffusion-based Lesion Segmentation and Malignancy Classification** \
*Héctor Carrión, Narges Norouzi* \
[21st Jul., 2023] [MICCAI, 2023] \
[[Paper](https://arxiv.org/abs/2307.11654)] [[Github](https://github.com/hectorcarrion/fedd)]

---

### Time Series

**Diffusion-driven SpatioTemporal Graph KANsformer for Medical Examination Recommendation** \
*Jianan Li, Yangtao Zhou, Zhifu Zhao, Qinglan Huang, Jian Qi, Xiao He, Hua Chu, Fu Li* \
[12th May, 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2505.07431v1)]

**Improving EEG Classification Through Randomly Reassembling Original and Generated Data with Transformer-based Diffusion Models** \
*Mingzhi Chen, Yiyu Gui, Yuqi Su, Yuesheng Zhu, Guibo Luo, Yuchao Yang* \
[20th Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.20253)]

**NODER: Image Sequence Regression Based on Neural Ordinary Differential Equations** \
*Hao Bai, Yi Hong* \
[18th Jul., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2407.13241v1)] [[GitHub](https://github.com/ZedKing12138/NODER-pytorch)]

**SSSD-ECG-nle: New Label Embeddings with Structured State-Space Models for ECG generation** \
*Sergey Skorik, Aram Avetisyan* \
[15th Jul., 2024] [IEEE IVMEM Workshop, 2024] \
[[Paper](https://arxiv.org/abs/2407.11108)] [[GitHub](https://github.com/ispras/EcgLib)]

**Stochastic Diffusion: A Diffusion Probabilistic Model for Stochastic Time Series Forecasting** \
*Yuansan Liu, Sudanthi Wijewickrema, Dongting Hu, Christofer Bester, Stephen O'Leary, James Bailey* \
[4th Jun., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2406.02827)]

**Time Weaver: A Conditional Time Series Generation Model** \
*Sai Shankar Narasimhan, Shubhankar Agarwal, Oguzhan Akcin, Sujay Sanghavi, Sandeep Chinchali* \
[5th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.02682)]

**Risk-Sensitive Diffusion: Learning the Underlying Distribution from Noisy Samples** \
*Yangming Li, Max Ruiz Luyten, Mihaela van der Schaar* \
[3rd Feb., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2402.02081)]

**Reliable Generation of EHR Time Series via Diffusion Models** \
*Muhang Tian, Bernie Chen, Allan Guo, Shiyi Jiang, Anru R. Zhang* \
[23rd Oct., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2310.15290)]

**A Comprehensive Survey on Generative Diffusion Models for Structured Data** \
*Heejoon Koo, To Eun Kim* \
[7th Jun., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.04139)]

**Restoration of Time-Series Medical Data with Diffusion Model** \
*Jiwoon Lee, Cheolsoo Park* \
[6th Oct., 2022] [ICCE-Asia, 2022] \
[[Paper](https://www.researchgate.net/profile/Jiwoon-Lee-3/publication/363520751_Restoration_of_Time-Series_Medical_Data_with_Diffusion_Model/links/63210895071ea12e362ee672/Restoration-of-Time-Series-Medical-Data-with-Diffusion-Model.pdf)]

---

### Audio

**Adversarial Fine-tuning using Generated Respiratory Sound to Address Class Imbalance** \
*June-Woo Kim, Chihyeon Yoon, Miika Toikkanen, Sangmin Bae, Ho-Young Jung* \
[11th Nov., 2023] [NeurIPS Workshop, 2023] \
[[Paper](https://openreview.net/forum?id=z1AVG5LDQ7)] [[GitHub](https://github.com/kaen2891/adversarial_fine-tuning_using_generated_respiratory_sound)]

---

### Multi-task

**MedDiff-FM: A Diffusion-based Foundation Model for Versatile Medical Image Applications** \
*Yongrui Yu, Yannian Gu, Shaoting Zhang, Xiaofan Zhang* \
[20th Oct., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2410.15432v2)]

**Simultaneous Tri-Modal Medical Image Fusion and Super-Resolution using Conditional Diffusion Model** \
*Yushen Xu, Xiaosong Li, Yuchan Jie, Haishu Tan* \
[26th Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.17357)]

**Implicit Image-to-Image Schrodinger Bridge for CT Super-Resolution and Denoising** \
*Yuang Wang, Siyeop Yoon, Pengfei Jin, Matthew Tivnan, Zhennong Chen, Rui Hu, Li Zhang, Zhiqiang Chen, Quanzheng Li, Dufan Wu* \
[10th Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.06069)]

**DDPET-3D: Dose-aware Diffusion Model for 3D Ultra Low-dose PET Imaging** \
*Huidong Xie, Weijie Gan, Bo Zhou, Xiongchao Chen, Qiong Liu, Xueqi Guo, Liang Guo, Hongyu An, Ulugbek S. Kamilov, Ge Wang, Chi Liu* \
[7th Nov., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2311.04248)]

**Application-driven Validation of Posteriors in Inverse Problems** \
*Tim J. Adler, Jan-Hinrich Nölke, Annika Reinke, Minu Dietlinde Tizabi, Sebastian Gruber, Dasha Trofimova, Lynton Ardizzone, Paul F. Jaeger, Florian Buettner, Ullrich Köthe, Lena Maier-Hein* \
[18th Sep., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2309.09764)]

**Content-Preserving Diffusion Model for Unsupervised AS-OCT image Despeckling** \
*Li Sanqian, Higashita Risa, Fu Huazhu, Li Heng, Niu Jingxuan, Liu Jiang* \
[30th June, 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.17717)]

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

**MInDI-3D: Iterative Deep Learning in 3D for Sparse-view Cone Beam Computed Tomography** \
*Daniel Barco, Marc Stadelmann, Martin Oswald, Ivo Herzig, Lukas Lichtensteiger, Pascal Paysan, Igor Peterlik, Michal Walczak, Bjoern Menze, Frank-Peter Schilling* \
[13th Aug., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2508.09616v1)]

**Out-of-Distribution Detection in Medical Imaging via Diffusion Trajectories** \
*Lemar Abdi, Francisco Caetano, Amaan Valiuddin, Christiaan Viviers, Hamdi Joudeh, Fons van der Sommen* \
[31th Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2507.23411v1)]

**DiSC-Med: Diffusion-based Semantic Communications for Robust Medical Image Transmission** \
*Fupei Guo, Hao Zheng, Xiang Zhang, Li Chen, Yue Wang, Songyang Zhang* \
[31st Jul., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2508.00172v1)]

**DM-FNet: Unified multimodal medical image fusion via diffusion process-trained encoder-decoder** \
*Dan He, Weisheng Li, Guofen Wang, Yuping Huang, Shiqiang Liu* \
[18th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.15218v1)]

**GM-LDM: Latent Diffusion Model for Brain Biomarker Identification through Functional Data-Driven Gray Matter Synthesis** \
*Hu Xu, Yang Jingling, Jia Sihan, Bi Yuda, Calhoun Vince* \
[15th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.12719v1)]

**Anatomy-Grounded Weakly Supervised Prompt Tuning for Chest X-ray Latent Diffusion Models** \
*Konstantinos Vilouras, Ilias Stogiannidis, Junyu Yan, Alison Q. O'Neil, Sotirios A. Tsaftaris* \
[12th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.10633v1)]

**Stable Vision Concept Transformers for Medical Diagnosis** \
*Lijie Hu, Songning Lai, Yuan Hua, Shu Yang, Jingfeng Zhang, Di Wang* \
[05th Jun., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2506.05286v1)]

**The Devil is in the Prompts: De-Identification Traces Enhance Memorization Risks in Synthetic Chest X-Ray Generation** \
*Raman Dutt* \
[11th Feb., 2025] [arXiv, 2025] \
[[Paper](http://arxiv.org/abs/2502.07516v2)]

**Deep Generative Models Unveil Patterns in Medical Images Through Vision-Language Conditioning** \
*Xiaodan Xing, Junzhi Ning, Yang Nan, Guang Yang* \
[17th Oct., 2024] [arXiv, 2024] \
[[Paper](http://arxiv.org/abs/2410.13823v1)] [[GitHub](https://github.com/junzhin/DGM-VLC)] 

**Self-supervised pre-training with diffusion model for few-shot landmark detection in x-ray images** \ 
*Roberto Di Via, Francesca Odone, Vito Paolo Pastore* \
[25th Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.18125)]

**A discontinuous Galerkin method for the three-dimensional heterodimer model with application to prion-like proteins' dynamics** \
*Paola F. Antonietti, Mattia Corti, Giacomo Lorenzon* \
[22nd Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.16065)]

**Assessing Sample Quality via the Latent Space of Generative Models** \
*Jingyi Xu, Hieu Le, Dimitris Samaras* \
[21st Jul., 2024] [ECCV, 2025] \
[[Paper](https://arxiv.org/abs/2407.15171)] [[GitHub](https://github.com/cvlab-stonybrook/LS-sample-quality)]

**Back-in-Time Diffusion: Unsupervised Detection of Medical Deepfakes** \
*Fred Grabovski, Lior Yasur, Guy Amit, Yuval Elovici, Yisroel Mirsky* \
[21st Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.15169)]

**Latent Pollution Model: The Hidden Carbon Footprint in 3D Image Synthesis** \
*Marvin Seyfarth, Salman Ul Hassan Dar, Sandy Engelhardt* \
[20th Jul., 2024] [SASHIMI, 2024] \
[[Paper](https://arxiv.org/abs/2407.14892)]

**Hallucination Index: An Image Quality Metric for Generative Reconstruction Models** \
*Matthew Tivnan, Siyeop Yoon, Zhennong Chen, Xiang Li, Dufan Wu, Quanzheng Li* \
[17th Jul., 2024] [MICCAI, 2024] \
[[Paper](https://arxiv.org/abs/2407.12780)] 

**Salt & Pepper Heatmaps: Diffusion-informed Landmark Detection Strategy** \
*Julian Wyatt, Irina Voiculescu* \
[12th Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.09192)]

**Hybrid RAG-empowered Multi-modal LLM for Secure Healthcare Data Management: A Diffusion-based Contract Theory Approach** \
*Cheng Su, Jinbo Wen, Jiawen Kang, Yonghua Wang, Hudan Pan, M. Shamim Hossain* \
[1st Jul., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2407.00978)]

**MemControl: Mitigating Memorization in Medical Diffusion Models via Automated Parameter Selection** \
*Raman Dutt, Pedro Sanchez, Ondrej Bohdal, Sotirios A. Tsaftaris, Timothy Hospedales* \
[29th May, 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2405.19458)]

**RadRotator: 3D Rotation of Radiographs with Diffusion Models** \
*Pouria Rouzrokh, Bardia Khosravi, Shahriar Faghani, Kellen L. Mulford, Michael J. Taunton, Bradley J. Erickson, Cody C. Wyles* \
[19th Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.13000)] [[Project Page](https://pouriarouzrokh.github.io/RadRotator/)] [[Huggingface](https://huggingface.co/spaces/Pouriarouzrokh/RadRotator)]

**Zero-Shot Medical Phrase Grounding with Off-the-shelf Diffusion Models** \
*Konstantinos Vilouras, Pedro Sanchez, Alison Q. O'Neil, Sotirios A. Tsaftaris* \
[19th Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.12920)]

**Guided Discrete Diffusion for Electronic Health Record Generation** \
*Jun Han, Zixiang Chen, Yongqian Li, Yiwen Kou, Eran Halperin, Robert E. Tillman, Quanquan Gu* \
[18th Apr., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2404.12314)]

**QSMDiff: Unsupervised 3D Diffusion Models for Quantitative Susceptibility Mapping** \
*Zhuang Xiong, Wei Jiang, Yang Gao, Feng Liu, Hongfu Sun* \
[21st Mar., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.14070)]

**DUE: Dynamic Uncertainty-Aware Explanation Supervision via 3D Imputation** \
*Qilong Zhao, Yifei Zhang, Mengdan Zhu, Siyi Gu, Yuyang Gao, Xiaofeng Yang, Liang Zhao* \
[16th Feb., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2403.10831)] [[GitHub](https://github.com/AlexQilong/DUE)]

**Statistical Test for Generated Hypotheses by Diffusion Models** \
*Teruyuki Katsuoka, Tomohiro Shiraishi, Daiki Miwa, Vo Nguyen Le Duy, Ichiro Takeuchi* \
[19th Feb., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2402.11789)] [[GitHub](https://github.com/teruyukikatsuoka/DMAD-test)]

**On the Standardization of Behavioral Use Clauses and Their Adoption for Responsible Licensing of AI** \
*Daniel McDuff, Tim Korjakow, Scott Cambo, Jesse Josua Benjamin, Jenny Lee, Yacine Jernite, Carlos Muñoz Ferrandis, Aaron Gokaslan, Alek Tarkowski, Joseph Lindley, A. Feder Cooper, Danish Contractor* \
[7th Feb., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2402.05979)]

**Unconditional Latent Diffusion Models Memorize Patient Imaging Data** \
*Salman Ul Hassan Dar, Marvin Seyfarth, Jannik Kahmann, Isabelle Ayx, Theano Papavassiliu, Stefan O. Schoenberg, Sandy Engelhardt* \
[1st Feb., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2402.01054)] [[GitHub](https://github.com/Warvito/generative_chestxray)]

**FedTabDiff: Federated Learning of Diffusion Probabilistic Models for Synthetic Mixed-Type Tabular Data Generation** \
*Timur Sattarov, Marco Schreyer, Damian Borth* \
[11th Jan., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2401.06263)] [[GitHub](https://github.com/sattarov/FedTabDiff)]

**VALD-MD: Visual Attribution via Latent Diffusion for Medical Diagnostics** \
*Ammar A. Siddiqui, Santosh Tirunagari, Tehseen Zia, David Windridge* \
[2nd Jan., 2024] [arXiv, 2024] \
[[Paper](https://arxiv.org/abs/2401.01414)]

**On the notion of Hallucinations from the lens of Bias and Validity in Synthetic CXR Images** \
*Gauri Bhardwaj, Yuvaraj Govindarajulu, Sundaraparipurnan Narayanan, Pavan Kulkarni, Manojkumar Parmar* \
[12th Dec., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2312.06979)]

**Reconstruction of Patient-Specific Confounders in AI-based Radiologic Image Interpretation using Generative Pretraining** \
*Tianyu Han, Laura Žigutytė, Luisa Huck, Marc Huppertz, Robert Siepmann, Yossi Gandelsman, Christian Blüthgen, Firas Khader, Christiane Kuhl, Sven Nebelung, Jakob Kather, Daniel Truhn* \
[29th Sep., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2309.17123)] [[GitHub](https://github.com/peterhan91/diffchest)] [[Demo](https://colab.research.google.com/drive/1gHWCQxreE1Olo2uQiXfSFSVInmiX85Nn?usp=sharing)]

**Assessing the capacity of a denoising diffusion probabilistic model to reproduce spatial context** \
*Rucha Deshpande, Muzaffer Özbey, Hua Li, Mark A. Anastasio, Frank J. Brooks* \
[19th Sep., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2309.10817)]

**Beta quantile regression for robust estimation of uncertainty in the presence of outliers** \
*Haleh Akrami, Omar Zamzam, Anand Joshi, Sergul Aydore, Richard Leahy* \
[14th Sep., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2309.07374)]

**Unsupervised 3D out-of-distribution detection with latent diffusion models** \
*Mark S. Graham, Walter Hugo Lopez Pinaya, Paul Wright, Petru-Daniel Tudosiu, Yee H. Mah, James T. Teo, H. Rolf Jäger, David Werring, Parashkev Nachev, Sebastien Ourselin, M. Jorge Cardoso* \
[7th Jul., 2023] [MICCAI, 2023] \
[[Paper](https://arxiv.org/abs/2307.03777)] [[GitHub](https://github.com/marksgraham/ddpm-ood)]

**DoseDiff: Distance-aware Diffusion Model for Dose Prediction in Radiotherapy** \
*Yiwen Zhang, Chuanpu Li, Liming Zhong, Zeli Chen, Wei Yang, Xuetao Wang* \
[28th Jun., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2306.16324)]

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
[8th Mar., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2303.04603)]

**DiffusionCT: Latent Diffusion Model for CT Image Standardization** \
*Md Selim, Jie Zhang, Michael A. Brooks, Ge Wang, Jin Chen* \
[20th Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.08815)]

**Diffusion Model based Semi-supervised Learning on Brain Hemorrhage Images for Efficient Midline Shift Quantification** \
*Shizhan Gong, Cheng Chen, Yuqi Gong, Nga Yan Chan, Wenao Ma, Calvin Hoi-Kwan Mak, Jill Abrigo, Qi Dou* \
[1st Jan., 2023] [arXiv, 2023] \
[[Paper](https://arxiv.org/abs/2301.00409)]
