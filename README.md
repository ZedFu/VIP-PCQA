# VIP-PCQA: A Multi-Modal Framework for No-reference Point Cloud Quality Assessment

Kang Fu*, Zicheng Zhang*, Huiyu Duan, Xiaohong Liu, Xiongkuo Min, Jia Wang, and Guangtao Zhai $\dagger$

Point clouds often suffer from geometric and color noise, as well as compression artifacts, during their production, storage, and transmission. Therefore, accurately and automatically evaluating the quality of point clouds is crucial for optimizing storage and compression strategies. This paper introduces the VIP-PCQA, a novel framework that combines $\underline{V}$ ideo, $\underline{I}$ mage, and $\underline{P}$ oint cloud modalities for no-reference $\underline{P}$ oint $\underline{C}$ loud $\underline{Q}$ uality $\underline{A}$ ssessment. The framework begins by rendering projection videos and normal images from point clouds, followed by sampling patches and computing statistical features related to color and geometry. Subsequently, a video encoder, two image encoders, and a point cloud encoder are employed to extract modality-specific features. Finally, these features are fused to regress the quality score.

The code will be released soon.