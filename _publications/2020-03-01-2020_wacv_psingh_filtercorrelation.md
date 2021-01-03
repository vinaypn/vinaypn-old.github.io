---
title: "Leveraging Filter Correlations for Deep Model Compression"
collection: publications
permalink: /publication/2020-03-01-2020_wacv_psingh_filtercorrelation
excerpt: 'We present a filter correlation based model compression approach for deep convolutional neural networks. Our approach iteratively identifies pairs of filters with the largest pairwise correlations and drops one of the filters from each such pair. However, instead of discarding one of the filters from each such pair naïvely, the model is re-optimized to make the filters in these pairs maximally correlated, so that discarding one of the filters from the pair results in minimal information loss. Moreover, after discarding the filters in each round, we further finetune the model to recover from the potential small loss incurred by the compression. We evaluate our proposed approach using a comprehensive set of experiments and ablation studies. Our compression method yields state-of-the-art FLOPs compression rates on various benchmarks, such as LeNet-5, VGG-16, and ResNet-50,56, while still achieving excellent predictive performance for tasks such as object detection on benchmark datasets.'
date: 2020-03-01
venue: 'Winter Conference on Applications of Computer Vision (WACV ’20)'
paperurl: 'https://arxiv.org/abs/1811.10559'
citation: 'P. Singh, V.K. Verma, P. Rai, V.P. Namboodiri, &quot;Leveraging Filter Correlations for Deep Model Compression&quot;, <i> IEEE Winter Conference on Applications of Computer Vision (WACV ’20) </i> pages 824-833, 2020'
---

<a href='https://arxiv.org/abs/1811.10559'>Download paper here</a>

We present a filter correlation based model compression approach for deep convolutional neural networks. Our approach iteratively identifies pairs of filters with the largest pairwise correlations and drops one of the filters from each such pair. However, instead of discarding one of the filters from each such pair naïvely, the model is re-optimized to make the filters in these pairs maximally correlated, so that discarding one of the filters from the pair results in minimal information loss. Moreover, after discarding the filters in each round, we further finetune the model to recover from the potential small loss incurred by the compression. We evaluate our proposed approach using a comprehensive set of experiments and ablation studies. Our compression method yields state-of-the-art FLOPs compression rates on various benchmarks, such as LeNet-5, VGG-16, and ResNet-50,56, while still achieving excellent predictive performance for tasks such as object detection on benchmark datasets.

Recommended citation: P. Singh, V.K. Verma, P. Rai, V.P. Namboodiri, "Leveraging Filter Correlations for Deep Model Compression", <i> IEEE Winter Conference on Applications of Computer Vision (WACV ’20) </i> pages 824-833, 2020