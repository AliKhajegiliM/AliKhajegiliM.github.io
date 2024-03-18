---
title: "GRASP: GRAph-Structured Pyramidal Whole Slide Image Representation"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is about represnting WSIs in a multi-magnification setting.'
date: 2024-02-17
venue: 'Arxiv; Submitted to ECCV 2024'
paperurl: 'https://arxiv.org/abs/2402.03592'
citation: 'Mirabadi AK, Archibald G, Darbandsari A, Contreras-Sanz A, Nakhli RE, Asadi M, Zhang A, Gilks CB, Black P, Wang G, Farahani H. GRASP: GRAph-Structured Pyramidal Whole Slide Image Representation. arXiv preprint arXiv:2402.03592. 2024 Feb 6.'
---

Abstract: Cancer subtyping is one of the most challenging tasks in digital pathology, where Multiple Instance Learning (MIL) by processing gigapixel whole slide images (WSIs) has been in the spotlight of recent research. However, MIL approaches do not take advantage of inter- and intra-magnification information contained in WSIs. In this work, we present GRASP, a novel graph-structured multi-magnification framework for processing WSIs in digital pathology. Our approach is designed to dynamically emulate the pathologist's behavior in handling WSIs and benefits from the hierarchical structure of WSIs. GRASP, which introduces a convergence-based node aggregation instead of traditional pooling mechanisms, outperforms state-of-the-art methods over two distinct cancer datasets by a margin of up to 10% balanced accuracy, while being 7 times smaller than the closest-performing state-of-the-art model in terms of the number of parameters. Our results show that GRASP is dynamic in finding and consulting with different magnifications for subtyping cancers and is reliable and stable across different hyperparameters. The model's behavior has been evaluated by two expert pathologists confirming the interpretability of the model's dynamic. We also provide a theoretical foundation, along with empirical evidence, for our work, explaining how GRASP interacts with different magnifications and nodes in the graph to make predictions. We believe that the strong characteristics yet simple structure of GRASP will encourage the development of interpretable, structure-based designs for WSI representation in digital pathology. Furthermore, we publish two large graph datasets of rare Ovarian and Bladder cancers to contribute to the field.
