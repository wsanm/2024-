# 2024 review of depth estimates
## Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data  
Abstract 概要
作者认为Depth Anything是一种用于稳健单目深度估计的非常实用的解决方案。在不追求新颖的技术模块的情况下，作者目标建立一个简单而强大的基础模型（而且是Zero-shot）。为此，作者通过设计一个数据引擎来收集并自动标注大规模未标记数据（∼62M），从而扩大数据覆盖范围，来能够减少泛化误差。（训练的数据量很多）  
作者研究了两种简单而有效的策略，这些策略使数据扩展很有希望。  
首先，通过利用数据增强工具创建更具挑战性的优化目标。它迫使模型积极寻求额外的视觉知识并获得强大的表示。  
其次，开发了一种辅助监督来强制模型从预训练的编码器（encoder是特征语义分割的encoder）继承丰富的语义分割先验。  
概要结尾总结起来三点：  
1 使用大量的未标注图像信息  
2 采用优化策略—数据增强工具(作用在未标注图像)  
3 进行辅助监督—继承语义分割知识（作用在未标注图像）  
## Depth Anything v2
Depth Anything v2放出了演示[Demo](https://huggingface.co/spaces/depth-anything/Depth-Anything-V2"上传照片显示深度估计")
