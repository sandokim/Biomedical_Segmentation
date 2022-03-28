# CT_Segmentation

[Batach VS Instance Normalization](https://www.baeldung.com/cs/instance-vs-batch-normalization)

[Mask R-CNN Object Detection](https://arxiv.org/pdf/1703.06870.pdf)

[Attention-enabled 3D boosted convolutional neural
networks for semantic CT segmentation using
deep supervision](https://iopscience.iop.org/article/10.1088/1361-6560/ab2818/pdf)

[UNet++: A Nested U-Net Architecture for Medical Image Segmentation](https://arxiv.org/pdf/1807.10165.pdf)

[Cross Entropy meaning](https://towardsdatascience.com/understanding-binary-cross-entropy-log-loss-a-visual-explanation-a3ac6025181a)

[Hausdorff Distance meaning](https://structseg2019.grand-challenge.org/Evaluation/)

[Hausdorff Distance for Iris Recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4450956)

[ImageNet Classification with Deep Convolutional Neural Networks](https://proceedings.neurips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)

The disadvantage of using Hausdorff distance is that the degree of mismatch will be large when even a part of an object is missing due to occlusion, or when there are outliers. This is undesirable in object matching applications. In order to have a match between closely resembling portions of objects, partial Hausdorff distance Hp(A, B) has been proposed in [13] which is a modification of the conventional Hausdorff distance. This is done by taking Kth-ranked maximum value, instead of taking the overall maximum in the directed Hausdorff distance

[R-CNN](https://arxiv.org/pdf/1311.2524.pdf)

R-CNN decomposes the overall detection problem into two subproblems: to first utilize low-level cues such as color and superpixel consistency for potential object proposals in a category-agnostic fashion, and to then use CNN classifiers to identify object categories at those locations. Such a two stage approach leverages the accuracy of bounding box segmentation with low-level cues, as well as the highly powerful classification power of state-of-the-art CNNs.

In order to maintain high spatial resolution, these CNNs typically only have two convolutional and pooling layers.

[Going deeper with convolutions, GoogLeNet, Inception](https://arxiv.org/pdf/1409.4842.pdf)

Inception architecture was especially useful in the context of localization and object detection as the base network for [6] and [5]. Interestingly, while most of the original architectural choices have been questioned and tested thoroughly, they turned out to be at least locally optimal.

#### Object detection Key

Note that assuming translation invariance means that our network will be built from convolutional building blocks. All we need is to find the optimal local construction and to repeat it spatially

[nnUnet Biomedical Segmentation FrameWork 2D, 3D](https://github.com/MIC-DKFZ/nnUNet)

[nnUnet paper](https://arxiv.org/pdf/1809.10486.pdf)

[Batch Normalization](https://arxiv.org/pdf/1502.03167.pdf)

[Multi-GPU, VRAM, BottleNeck, NVLink](https://89douner.tistory.com/157)

[Deep supervision](https://arxiv.org/pdf/1801.03399.pdf)

As such, coarse-grained class labels used as intermediate concepts are able to improve fine-grained recognition performance, which further validates our deep supervision strategy.

The more concepts applied, the better chance that the generalization is improved. In conclusion, deep supervision with intermediate concepts regularizes the network training by decreasing the number of incorrect solutions that generalize poorly to the test set.

[The Liver Tumor Segmentation Benchmark (LiTS)](https://arxiv.org/pdf/1901.04056.pdf)

##### Cascaded approach
The common cascaded approaches allowed each network to focus and learn the relevantfeatures for its specific task improving overall performance of both liver and tumor segmentation. In addition, network architecture design can be adapted to the specific network task resulting in a more effective and efficient training process and outcome. Also, earlier networks in the cascaded pipeline might help to standardize the intensity distribution for later networks which has been shown to improve overall performance.


##### Higher Dimensionality
However, Chlebus et al. used a small 3D network as the final network in a cascaded infrastructure to fuse the segmentation results of various previous
networks into a final segmentation mask, while Li implemented a shallow 3D network to further refine the preliminary results of a first network. These good results not only prove the feasibility and usefulness of a 3D network architecture despite the currently limited memory availability when used as a supplementary role but also show their huge potential for future performance increase by being able to capture the whole volume context.

[A Review of Deep-Learning-Based Medical Image Segmentation Methods](https://www.mdpi.com/2071-1050/13/3/1224/htm)

[SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation](https://arxiv.org/pdf/1511.00561.pdf)

SegNet on the other hand is more efficient since it only stores the max-pooling indices of the feature maps and uses them in its decoder network to achieve good performance.

[PSPNet: Pyramid Scene Parsing Network](https://arxiv.org/pdf/1612.01105.pdf)

[2.5D: Deep learning of the sectional appearances of 3D CT images for anatomical structure segmentation based on an FCN voting method.]()

[Semantic segmentation using adversarial networks](https://arxiv.org/pdf/1611.08408.pdf)

[Automatic liver segmentation using an adversarial image-to-image network](https://arxiv.org/pdf/1707.08037.pdf)

[Edge-aware Fully Convolutional Network with CRF-RNN Layer for Hippocampus Segmentation](https://ieeexplore.ieee.org/abstract/document/8785801)
