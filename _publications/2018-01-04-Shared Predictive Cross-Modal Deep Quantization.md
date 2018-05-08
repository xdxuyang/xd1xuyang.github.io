---
title: "2 . Shared Predictive Cross-Modal Deep Quantization [TNNLS'18]"
permalink: /publication/2018-01-04-Shared Predictive Cross-Modal Deep Quantization
excerpt: '[PDF](http://www.ee.columbia.edu/~wliu/TNNLS18_CrossQuant.pdf), [Project](/publication/2018-01-04-Shared Predictive Cross-Modal Deep Quantization)'
---

---
# Title
__Shared Predictive Cross-Modal Deep Quantization [TNNLS'2018]__  

---
# Abstract

With explosive growth of data volume and everincreasing diversity of data modalities, cross-modal similarity search, which conducts nearest neighbor search across different modalities, has been attracting increasing interest. This paper presents a deep compact code learning solution for efficient cross-modal similarity search. Many recent studies have proven that quantization-based approaches perform generally better than hashing-based approaches on single-modal similarity search. In this paper, we propose a deep quantization approach, which is among the early attempts of leveraging deep neural networks into quantization-based cross-modal similarity search. Our approach, dubbed shared predictive deep quantization (SPDQ), explicitly formulates a shared subspace across different modalities and two private subspaces for individual modalities, and representations in the shared subspace and the private subspaces are learned simultaneously by embedding them to a reproducing kernel Hilbert space, where the mean embedding of different modality distributions can be explicitly compared. In addition, in the shared subspace, a quantizer is learned to produce the semantics preserving compact codes with the help of label alignment. Thanks to this novel network architecture in cooperation with supervised quantization training, SPDQ can preserve intramodal and intermodal similarities as much as possible and greatly reduce quantization error. Experiments on two popular benchmarks corroborate that our approach outperforms stateof-the-art methods.

---
# Framework
![image](https://github.com/ChaoLi1991/ChaoLi1991.github.io/blob/master/files/SPDQ/SPDQ.png)

---
# Download
[Paper](http://www.ee.columbia.edu/~wliu/TNNLS18_CrossQuant.pdf)  
[MIRFLICKR-25K](http://press.liacs.nl/mirflickr/), [NUS-WIDE](http://lms.comp.nus.edu.sg/research/NUS-WIDE.htm)

---
# Citation
@article{yang2018shared,  
  title={Shared Predictive Cross-Modal Deep Quantization},  
  author={Yang, Erkun and Deng, Cheng and Li, Chao and Liu, Wei and Li, Jie and Tao, Dacheng},  
  journal={IEEE Transactions on Neural Networks and Learning Systems},  
  year={2018},  
  publisher={IEEE}  
}
