# 1. Awesome Domain Adaptation For Semantic Segmentation Papers

- [1. Awesome Domain Adaptation For Semantic Segmentation Papers](#1-awesome-domain-adaptation-for-semantic-segmentation-papers)
	- [1.1.General Domain Adaptation](#11general-domain-adaptation)
		- [1.1.1. Traditional Methods](#111-traditional-methods)
		- [1.1.2. Deep / Adversarial Methods](#112-deep--adversarial-methods)
	- [1.2. Domain Generalization](#12-domain-generalization)
	- [1.3. Multi-source Domain Adaptation](#13-multi-source-domain-adaptation)
	- [1.4. Multi-target Domain Adaptation](#14-multi-target-domain-adaptation)
	- [1.5. OpenSet Domain Adaptation](#15-openset-domain-adaptation)
	- [1.6. Zero-shot / Few-shot Domain Adaptation](#16-zero-shot--few-shot-domain-adaptation)

---

## 1.1.General Domain Adaptation

- 2018/12/14 ICCV-17 [Curriculum Domain Adaptation for Semantic Segmentation of Urban Scenes](https://arxiv.org/abs/1707.09465) [code](https://github.com/YangZhang4065/AdaptationSeg)
    - **Curriculum DA**

### 1.1.1. Traditional Methods

- 2019/08/26 arxiv [Constructing Self-motivated Pyramid Curriculums for Cross-Domain Semantic Segmentation: A Non-Adversarial Approach](https://arxiv.org/abs/1908.09547) [code]
    - Pyramid Curriculums

### 1.1.2. Deep / Adversarial Methods

- 2020/07/07 MICCAI-20 [Scribble-based Domain Adaptation via Co-segmentation](https://arxiv.org/abs/2007.03632)

- 2020/07/05 ISPRS [Weakly Supervised Domain Adaptation for Built-up Region Segmentation in Aerial and Satellite Imagery](https://arxiv.org/abs/2007.02277)

- :satr: 2020/07/05 ECCV-20 [Contextual-Relation Consistent Domain Adaptation for Semantic Segmentation](https://arxiv.org/abs/2007.02424)

- 2020/06/28 WACV-20 [Uncertainty-aware multi-view co-training for semi-supervised medical image segmentation and domain adaptation](https://arxiv.org/abs/2006.16806)

- 2020/04/29 MIDL-20 [An Auto-Encoder Strategy for Adaptive Image Segmentation](https://arxiv.org/abs/2004.13903)

- 2020/04/24 CVPR-20 [What Can Be Transferred: Unsupervised Domain Adaptation for Endoscopic Lesions Segmentation](https://arxiv.org/abs/2004.11500)

- 2020/04/19 arxiv [Uncertainty-Aware Consistency Regularization for Cross-Domain Semantic Segmentation](https://arxiv.org/abs/2004.08878)
	- TODO; Uncertainty; tearcher-student model

- 2020/04/17 arxiv [IDDA: a large-scale multi-domain dataset for autonomous driving](https://arxiv.org/abs/2004.08298)
	- dataset; multi-domain DA;

- 2020/04/16 arxiv [Unsupervised Learning of Landmarks based on Inter-Intra Subject Consistencies](https://arxiv.org/abs/2004.07936)
	- inter-intra subkect consistencies; unsupervised learning

- 2020/04/16 CVPR Oral [Unsupervised Intra-domain Adaptation for Semantic Segmentation through Self-Supervision](https://arxiv.org/abs/2004.07703)
	- Inter-DA; Entropy-based Ranking; Intra-DA
	- Previous works have considered directly adapting models from the source data to the unlabeled target data (to reduce the inter-domain gap). Nonetheless, these techniques do not consider the large distribution gap among the target data itself (intra-domain gap).
	- Baseline为ADVENT, stage 1 用ADVENT得到target domain 所有图片的Entropy img, 然后根据entropy img 对target img 排序，然后split成Hard, Easy sample, 在进一步针对Hard, Easy samples之间存在的domain gap再用一次ADVENT，其中easy split作为source, 并生成pesudo labels.

- 2020/04/14 arxiv [Rectifying Pseudo Label Learning via Uncertainty Estimation for Domain Adaptive Semantic Segmentation](https://arxiv.org/abs/2003.03773)
	- Focus on obtaining and selecting high-quality proxy labels by incorporating both the confidence of the class predictor and that from the adversarial discriminators. Discriminators not only work as a regularizer to encourage feature alignment but also provide an alternative confidence measure for generating proxy labels.

- 2020/04/11  CVPR-20 [Inter-Region Affinity Distillation for Road Marking Segmentation](https://arxiv.org/abs/2004.05304)
	- important; inter-Region

- 2020/04/11 arxiv [FDA: Fourier Domain Adaptation for Semantic Segmentation](https://arxiv.org/abs/2004.05498)
	- TODO

- 2020/04/10 arxiv [Phase Consistent Ecological Domain Adaptation](https://arxiv.org/abs/2004.04923)
	-TODO

- 2020/04/09 CVPR-20 [Instance-aware, Context-focused, and Memory-efficient Weakly Supervised Object Detection](https://arxiv.org/abs/2004.04725)
	- Object Ddetection

- 2020/04/05 arxiv [ADVERSARIAL-PREDICTION GUIDED MULTI-TASK ADAPTATION FOR SEMANTIC SEGMENTATION OF ELECTRON MICROSCOPY IMAGES](https://arxiv.org/abs/2004.02134) [code]
    - Electron microscopy (EM) image analysis;

- 2020/04/02 arxiv [Alleviating Semantic-level Shift: A Semi-supervised Domain Adaptation Method for Semantic Segmentation](https://arxiv.org/abs/2004.00794)
	- semi-supervised;


- 2020/03/29 arxiv [Spatial Attention Pyramid Network for Unsupervised Domain Adaptation](https://arxiv.org/abs/2003.12979)

- 2020/03/31 arxiv [Graph Domain Adaptation for Alignment-Invariant Brain Surface Segmentation](https://arxiv.org/abs/2004.00074)

- 2020/03/30 arxiv [PANDA: Prototypical Unsupervised Domain Adaptation](https://arxiv.org/abs/2003.13274)

- 2020/03/29 arxiv [Self-Supervised Learning for Domain Adaptation on Point-Clouds](https://arxiv.org/abs/2003.12641)
	- SSL; DA; Point-Clouds

- 2020/03/27 arxiv [Generalizable Semantic Segmentation via Model-agnostic Learning and Target-specific Normalization](https://arxiv.org/abs/2003.12296)

- 2020/03/18 CVPR-20 [Differential Treatment for Stuff and Things: A Simple Unsupervised Domain Adaptation Method for Semantic Segmentation](https://arxiv.org/abs/2003.08040) [code]()
	- Based on the observation that stuff categories usually share similar appearances across images of different domains while things (i.e. object instances) have much larger differences, we propose to improve the semantic-level alignment with different strategies for stuff regions and for things.

- 2020/02/06 WACVW [Impact of ImageNet Model Selection on Domain Adaptation](https://arxiv.org/abs/2002.02559)

- 2020/01/09 CVPR-2019 [CrDoCo: Pixel-level Domain Transfer with Cross-Domain Consistency](https://arxiv.org/abs/2001.03182) [code](https://github.com/YunChunChen/CrDoCo-pytorch)
	- Image translation(src-2-trg + trg-2-src), Cross-Domain Consistency 
	- By leveraging image-toimage translation methods for data augmentation, our key insight is that while the translated images between domains may differ in styles, their predictions for the task should be consistent.

- 2019/12/05 NIPS-19 [Category Anchor-Guided Unsupervised Domain Adaptation for Semantic Segmentation](https://arxiv.org/abs/1910.13049) [code](https://github.com/RogerZhangzz/CAG_UDA)
    - **CAG-UDA**; TODO

- 2019/11/28 arxiv [Class-Conditional Domain Adaptation on Semantic Segmentation](https://arxiv.org/abs/1911.11981) [code]
    - **CCDA**; TODO

- 2019/09/30 ICCV-19 [Domain Adaptation for Semantic Segmentation with Maximum Squares Loss](https://arxiv.org/abs/1909.13589) [code](https://github.com/ZJULearning/MaxSquareLoss)
    - **MaxSquareLoss**; TODO

- 2019/08-27 ICCV-19 oral [Confidence Regularized Self-Training](https://arxiv.org/abs/1908.09822) [code](https://github.com/yzou2/CRST)
    - **CRST**; TODO  

- 2019/08/19 ICCV-19 [DADA: Depth-aware Domain Adaptation in Semantic Segmentation](https://arxiv.org/abs/1904.01886) [code](https://github.com/valeoai/DADA)
    - **DADA**; Depth information;

- 2019/08/08 MICCAI-19 [Constrained domain adaptation for segmentation](https://arxiv.org/abs/1908.02996)
	- **TODO** Medical image Segmentation

- 2019/07/29 arxiv [Regularizing Proxies with Multi-Adversarial Training for Unsupervised Domain-Adaptive Semantic Segmentation](https://arxiv.org/abs/1907.12282) [code]
    - **TODO**

- 2019/05/13 CVPR-19 [DLOW: Domain Flow for Adaptation and Generalization](https://arxiv.org/abs/1812.05418) [code](https://github.com/ETHRuiGong/DLOW)
	- **DLOW**; generating a continuous sequence of intermediate domains
	- DLOW model is able to produce a sequence of intermediate domains shifting from the source domain to the target domain.

- 2019/04/24 CVPR-19 [Bidirectional Learning for Domain Adaptation of Semantic Segmentation](https://arxiv.org/abs/1904.10620) [code](https://github.com/liyunsheng13/BDL)
	- **BDL**;
	- Using the bidirectional learning, the image translation model and the segmentation adaptation model can be learned alternatively and promote to each other.

- 2019/04/17 CVPR-19 [ADVENT: Adversarial Entropy Minimization for Domain Adaptation in Semantic Segmentation](https://arxiv.org/abs/1811.12833) [code](https://github.com/valeoai/ADVENT)
	- **ADVENT**; Entropy
	- In this work, we address the task of unsupervised domain adaptation in semantic segmentation with losses based on the **entropy** of the pixel-wise predictions.

- 2019/04/01 CVPR-19 Oral [Taking A Closer Look at Domain Shift: Category-level Adversaries for Semantics Consistent Domain Adaptation](https://arxiv.org/abs/1809.09478) [code](https://github.com/RoyalVane/CLAN)
	- **CLAN**; Category-level joint distribution, adaptive adversarial loss
	- we introduce a category-level adversarial network, aiming to enforce local semantic consistency during the trend of global alignment

- 2019/04/01 ICCV-19 [Significance-aware Information Bottleneck for Domain Adaptive Semantic Segmentation](https://arxiv.org/abs/1904.00876) [code]
    - TODO

- 2019/03/26 CVPR-19 [All about Structure: Adapting Structural Information across Domains for Boosting Semantic Segmentation](https://arxiv.org/abs/1903.12212) [code](https://github.com/a514514772/DISE-Domain-Invariant-Structure-Extraction)
	- **DISE**; Domain Invariant Structure Extraction; disentangle structure and texture;
	- we propose a Domain Invariant Structure Extraction (DISE) framework to disentangle images into domain-invariant structure and domain-specific texture representations, which can further realize imagetranslation across domains and enable label transfer to improve segmentation performance

- 2019/02/18 ICLR-19 [SPIGAN: Privileged Adversarial Learning from Simulation]() [code]
	- **TODO**

- 2019/01/13 CVPR-19 [Learning Semantic Segmentation from Synthetic Data: A Geometrically Guided Input-Output Adaptation Approach](https://arxiv.org/abs/1812.05040) [code](https://github.com/yuhuayc/gio-ada)
	- **GIO-Ada**; geometric information
	- we propose an approach to cross domain semantic segmentation with the auxiliary geometric information, which can also be easily obtained from virtual environments

- 2018/02/28 CVPR-18 [Learning to Adapt Structured Output Space for Semantic Segmentation](https://arxiv.org/abs/1802.10349) [code](https://github.com/wasidennis/AdaptSegNet)
	- **AdaptSegnet**; Adversarial training

- 2018/10/25 ECCV-18 [Domain Adaptation for Semantic Segmentation via Class-Balanced Self-Training](https://arxiv.org/abs/1810.07911) [code](https://github.com/yzou2/CBST)
	- **CBST**; self-training; class-balanced 
	- 

- 2017/12/29 ICML-18 [CyCADA: Cycle-Consistent Adversarial Domain Adaptation](https://arxiv.org/abs/1711.03213) [code](https://github.com/jhoffman/cycada_release)
	- **CyCADA**; Image-translation + Adversarial training
	- CyCADA adapts representations at both the pixel-level and feature-level, enforces cycle-consistency while leveraging a task loss, and does not require aligned pairs.

## 1.2. Domain Generalization

- 2020/07/05 ECCV-20 Oral [Self-Challenging Improves Cross-Domain Generalization](https://arxiv.org/abs/2007.02454)

- 2020/04/03 arxiv [Sequential Learning for Domain Generalization](https://arxiv.org/abs/2004.01377)
	- Domain Gneralization

- 2019/09/02 arxiv [Domain Randomization and Pyramid Consistency: Simulation-to-Real Generalization without Accessing Target Domain Data](https://arxiv.org/abs/1909.00889)
    - **DRPC** Generalization, No target data, GAN, data augmentation

## 1.3. Multi-source Domain Adaptation


- 2020/04/22 arxiv [Representation Bayesian Risk Decompositions and Multi-Source Domain Adaptation](https://arxiv.org/abs/2004.10390)

- 2020/04/19 arxiv [TriGAN: Image-to-Image Translation for Multi-Source Domain Adaptation](https://arxiv.org/abs/2004.08769)
	- TODO; Multi-Source DA; 

- 2020/03/29 arxiv [Mutual Learning Network for Multi-Source Domain Adaptation](https://arxiv.org/abs/2003.12944)
	- Multi-Source 

- 2020/04/14 CVPR 2020 workshop [StandardGAN: Multi-source Domain Adaptation for Semantic Segmentation of Very High Resolution Satellite Images by Data Standardization](https://arxiv.org/abs/2004.06402)
	- TODO

- 2019/10/27 NIPS-19 [Multi-source Domain Adaptation for Semantic Segmentation](https://arxiv.org/abs/1910.12181) [code](https://github.com/Luodian/MADAN)
    - **MADAN** TODO
    - Extension [MADAN: Multi-source Adversarial Domain Aggregation Network for Domain Adaptation](https://arxiv.org/abs/2003.00820)

## 1.4. Multi-target Domain Adaptation

- 2019/04/12 ICCV-19 [ACE: Adapting to Changing Environments for Semantic Segmentation](https://arxiv.org/abs/1904.06268) [code](https://github.com/JarvisLL/ACE)
	- **ACE**; Life-long; style-transfer
	- We present ACE, a framework for semantic segmentation that dynamically adapts to changing environments over the time.

- 2018/02/24 ICRA-18 [Incremental Adversarial Domain Adaptation for Continually Changing Environments](https://arxiv.org/abs/1712.07436) [code](https://github.com/yamad07/IADA)
    - **IADA**; Continually learning

## 1.5. OpenSet Domain Adaptation

## 1.6. Zero-shot / Few-shot Domain Adaptation

- 2020/03/28 CVPR-20 [One-Shot Domain Adaptation For Face Generation](https://arxiv.org/abs/2003.12869)

- 2019/10/07 CVPR-19 [Adaptive Confidence Smoothing for Generalized Zero-Shot Learning](https://arxiv.org/abs/1812.09903) [code]
	- TODO 
