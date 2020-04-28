# Domain Adaptation 


A curated list of domain adaptation papers, tutorials, datasets and other resources.


- [Domain adaptation]()
	- [0.Latest Publications](#0latest-publications)
	- [1.Introduction and Tutorials](#1introduction-and-tutorials)
	- [2.Domain Adaptation Areas and Papers](#2domain-adaptation-areas-and-papers)
	- [7.Datasets and Benchmarks](#7datasets-and-benchmarks)
- - -

## 0.Latest Publications

**A good website to see the latest arXiv preprints by search: [Domain adaptation](http://arxitics.com/search?q=domain%20adaptation&sort=updated)**

- **Weekly latest papers**

- 2020/04/24 IROS-20 [Explicit Domain Adaptation with Loosely Coupled Samples](https://arxiv.org/abs/2004.11995)

- 2020/04/15 arxiv [Defining Benchmarks for Continual Few-Shot Learning](https://arxiv.org/abs/2004.11967)

- 2020/04/15 arxiv [Extreme Consistency: Overcoming Annotation Scarcity and Domain Shifts](https://arxiv.org/abs/2004.11966)

- 2020/04/24 arxiv [Extending and Analyzing Self-Supervised Learning Across Domains](https://arxiv.org/abs/2004.11992)

- 2020/04/25 CVPR-20 WorkShop [StRDAN: Synthetic-to-Real Domain Adaptation Network for Vehicle Re-Identification](https://arxiv.org/abs/2004.12032)

- 2020/04/26 arxiv [Cross-Domain Structure Preserving Projection for Heterogeneous Domain Adaptation](https://arxiv.org/abs/2004.12427)

- 2020/04/27 IJCAI-20 [Towards Accurate and Robust Domain Adaptation under Noisy Environments](https://arxiv.org/abs/2004.12529) 

- *\** 2020/04/27 TPAMI [Maximum Density Divergence for Domain Adaptation](https://arxiv.org/abs/2004.12615)

- 2020/04/24 CVPR-20 [What Can Be Transferred: Unsupervised Domain Adaptation for Endoscopic Lesions Segmentation](https://arxiv.org/abs/2004.11500)

- 2020/04/23 arxiv [Supervised Domain Adaptation: Were we doing Graph Embedding all along?](https://arxiv.org/abs/2004.11262)

- 2020/04/23 arxiv [Metric-Learning-Assisted Domain Adaptation](https://arxiv.org/abs/2004.10963)

- 2020/04/22 arxiv [Representation Bayesian Risk Decompositions and Multi-Source Domain Adaptation](https://arxiv.org/abs/2004.10390)

- 2020/04/22 ICLR-20 Workshop [Deeply Uncertain: Comparing Methods of Uncertainty Quantification in Deep Learning Algorithms](https://arxiv.org/abs/2004.10710)

- 2020/04/19 arxiv [TriGAN: Image-to-Image Translation for Multi-Source Domain Adaptation](https://arxiv.org/abs/2004.08769)
	- TODO; Multi-Source DA; 

- 2020/04/19 CVPR-20 [AD-Cluster: Augmented Discriminative Clustering for Domain Adaptive Person Re-identification](https://arxiv.org/abs/2004.08787)
	- TODO; clustring; DA for RE-ID
	
- 2020/04/19 arxiv [Uncertainty-Aware Consistency Regularization for Cross-Domain Semantic Segmentation](https://arxiv.org/abs/2004.08878)
	- TODO; Uncertainty; tearcher-student model

- 2020/04/19 arxiv [ResNeSt: Split-Attention Networks](https://arxiv.org/abs/2004.08955)
	- TODO;

- 2020/04/16 arxiv [Unsupervised Learning of Landmarks based on Inter-Intra Subject Consistencies](https://arxiv.org/abs/2004.07936)
	- inter-intra subkect consistencies; unsupervised learning
	
- 2020/04/17 AAAI 2020 [Generative Adversarial Networks for Video-to-Video Domain Adaptation](https://arxiv.org/abs/2004.08058)	
	- TODO; DA for Video
	
- 2020/04/17 arxiv [Meta-Meta-Classification for One-Shot Learning](https://arxiv.org/abs/2004.08083)
	- TODO; One-Shot Learning
	
- 2020/04/17 IJCNN-20 [Triplet Loss for Knowledge Distillation](https://arxiv.org/abs/2004.08116)
	- TODO; Triplet Loss;
	
- 2020/04/17 arxiv [Learning to Predict Context-adaptive Convolution for Semantic Segmentation](https://arxiv.org/abs/2004.08222)
	- context-adaptive conv; segmentaiton

- 2020/04/17 arxiv [IDDA: a large-scale multi-domain dataset for autonomous driving](https://arxiv.org/abs/2004.08298)
	- dataset; multi-domain DA;

- 2020/04/11  CVPR-20 [Inter-Region Affinity Distillation for Road Marking Segmentation](https://arxiv.org/abs/2004.05304)
	- important; inter-Region
	
- 2020/04/12 arxiv [Efficient Deep Representation Learning by Adaptive Latent Space Sampling](https://arxiv.org/abs/2004.02757)
	- Representation Learning;

- 2020/04/09 CVPR-20 [Instance-aware, Context-focused, and Memory-efficient Weakly Supervised Object Detection](https://arxiv.org/abs/2004.04725)
	- Object Ddetection

- 2020/04/05  arxiv [Deeply Aligned Adaptation for Cross-domain Object Detection](https://arxiv.org/abs/2004.02093)

- 2020/04/03 arxiv [Sequential Learning for Domain Generalization](https://arxiv.org/abs/2004.01377)
	- Domain Gneralization

- 2020/04/01 arxiv [Memory-Efficient Incremental Learning Through Feature Adaptation](https://arxiv.org/abs/2004.00713)

- 2020/04/02 arxiv [Alleviating Semantic-level Shift: A Semi-supervised Domain Adaptation Method for Semantic Segmentation](https://arxiv.org/abs/2004.00794)
	- semi-supervised;
	
- 2020/03/31 arxiv [Graph Domain Adaptation for Alignment-Invariant Brain Surface Segmentation](https://arxiv.org/abs/2004.00074)

- 2020/04/01 cvpr-20 [Knowledge as Priors: Cross-Modal Knowledge Generalization for Datasets without Superior Knowledge](https://arxiv.org/abs/2004.00176)

- 2020/04/01 arxiv [Self-Augmentation: Generalizing Deep Networks to Unseen Classes for Few-Shot Learning](https://arxiv.org/abs/2004.00251)

- 2020/03/30 CVPR-20 [Semi-supervised Learning for Few-shot Image-to-Image Translation](https://arxiv.org/abs/2003.13853)
	- semisupervised img-2-img translation

- 2020/03/31 CVPR-20 [FGN: Fully Guided Network for Few-Shot Instance Segmentation](https://arxiv.org/abs/2003.13954)
	- Few-Shot Instance Segmentation

- 2020/03/31 CVPR-20 Oral [BANet: Bidirectional Aggregation Network with Occlusion Handling for Panoptic Segmentation](https://arxiv.org/abs/2003.14031)
	- Panaoptic Segmentation

- 2020/03/31 CVPR-20 Oral [MTL-NAS: Task-Agnostic Neural Architecture Search towards General-Purpose Multi-Task Learning](https://arxiv.org/abs/2003.14058)
	- NAS;Multi-task

- 2020/03/31 arxiv [Learning Cross-domain Semantic-Visual Relation for Transductive Zero-Shot Learning](https://arxiv.org/abs/2003.14105)
	- DA + Zero-Shot

- 2020/03/29 arxiv [Self-Supervised Learning for Domain Adaptation on Point-Clouds](https://arxiv.org/abs/2003.12641)
	- SSL; DA; Point-Clouds

- 2020/03/27 ICCV-19 [Deep CG2Real: Synthetic-to-Real Translation via Image Disentanglement](https://arxiv.org/abs/2003.12649)

- 2020/03/28 arxiv [Learning Invariant Representation for Unsupervised Image Restoration](https://arxiv.org/abs/2003.12769)

- 2020/03/28 CVPR-20 Oral [Cross-domain Detection via Graph-induced Prototype Alignment](https://arxiv.org/abs/2003.12849)

- 2020/03/28 CVPR-20 [One-Shot Domain Adaptation For Face Generation](https://arxiv.org/abs/2003.12869)

- 2020/03/29 arxiv [Mutual Learning Network for Multi-Source Domain Adaptation](https://arxiv.org/abs/2003.12944)
	- Multi-Source 

- 2020/03/29 arxiv [Spatial Attention Pyramid Network for Unsupervised Domain Adaptation](https://arxiv.org/abs/2003.12979)

- 2020/03/30 CVPR-20 [Gradually Vanishing Bridge for Adversarial Domain Adaptation](https://arxiv.org/abs/2003.13183)

- 2020/03/30 CVPR-20 [Domain-aware Visual Bias Eliminating for Generalized Zero-Shot Learning](https://arxiv.org/abs/2003.13261)

- 2020/03/30 arxiv [PANDA: Prototypical Unsupervised Domain Adaptation](https://arxiv.org/abs/2003.13274)

- 2020/03/27 arxiv [Dynamic Region-Aware Convolution](https://arxiv.org/abs/2003.12243)
	- important

- 2020/03/27 arxiv [Generalizable Semantic Segmentation via Model-agnostic Learning and Target-specific Normalization](https://arxiv.org/abs/2003.12296)

- 2020/03/25 CVPR-20 [iTAML: An Incremental Task-Agnostic Meta-learning Approach](https://arxiv.org/abs/2003.11652)

- 2020/03/29 CVPR-20 Oral [Towards Backward-Compatible Representation Learning](https://arxiv.org/abs/2003.11942)


- 2020/0

- - -

## 1.Introduction and Tutorials

- 2020/04/22 [Moment-Based Domain Adaptation: Learning Bounds and Algorithms](https://arxiv.org/abs/2004.10618)
	- Doctoral Thesis developed at the Department of Knowledge-Based Mathematical Systems at the Johannes Kepler University Linz under the supervision of Susanne Saminger-Platz and Bernhard Moser.

- 2019/07/22 ICML-19 [Bridging Theory and Algorithm for Domain Adaptation](https://arxiv.org/abs/1904.05801)

- 2019/03/12 arxiv [Transfer Adaptation Learning: A Decade Survey](https://arxiv.org/abs/1903.04687)


## 2.Domain Adaptation Areas and Papers

Related articles by research areas:
- [Classification](https://github.com/jarvisWang0903/Awesome-Domain-Adaptation/blob/master/doc/Classification.md)
- [Semantic Segmentation](https://github.com/jarvisWang0903/Awesome-Domain-Adaptation/blob/master/doc/Semantic%20Segmentation.md)
- [Detection](https://github.com/jarvisWang0903/Awesome-Domain-Adaptation/blob/master/doc/Detection.md)
- ...




## 3.Datasets and Benchmarks

Please see [HERE](https://github.com/jarvisWang0903/Awesome-Domain-Adaptation/blob/master/doc/Datasets%20and%20benchmarks.md) for the popular domain adaptation**datasets and certain benchmark** results.
