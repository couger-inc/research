# Couger research paper


## [2023.08.23 : End-to-End Depth-Guided Relighting Using Lightweight Deep Learning-Based Method](https://www.mdpi.com/2313-433X/9/9/175)

Image relighting, which involves modifying the lighting conditions while preserving the visual content, is fundamental to computer vision. This study introduced a bi-modal lightweight deep learning model for depth-guided relighting. The model utilizes the Res2Net Squeezed block’s ability to capture long-range dependencies and to enhance feature representation for both the input image and its corresponding depth map. The proposed model adopts an encoder–decoder structure with Res2Net Squeezed blocks integrated at each stage of encoding and decoding. The model was trained and evaluated on the VIDIT dataset, which consists of 300 triplets of images. Each triplet contains the input image, its corresponding depth map, and the relit image under diverse lighting conditions, such as different illuminant angles and color temperatures. The enhanced feature representation and improved information flow within the Res2Net Squeezed blocks enable the model to handle complex lighting variations and generate realistic relit images. The experimental results demonstrated the proposed approach’s effectiveness in relighting accuracy, measured by metrics such as the PSNR, SSIM, and visual quality.

## [2023.01.23 : Insta Net: Recurrent Residual Network for Instagram Filter Removal](https://couger.co.jp/paper/InstaNetRecurrentResidualNetworkforInstagramFilterRemoval.pdf)
Social media filters cause various manipulations in the original image. While these manipulations make the images visibly pleasant, they can affect their authenticity and the performance of further image-processing tasks. Therefore, removing these social media filters is a crucial pre-processing step for the data pipeline of any image-processing task. In this paper, a recurrent residual UNetbased model is proposed to remove the filters. The recurrent residual block allows the units of each layer to evolve over discrete time steps so that the activity of each unit is modulated by the activities of its neighboring units. Because of this characteristic, the networks learn contextual information more efficiently and effectively. Assuming that a filter can be noise, the proposed model learns the feature representation of the filter, and then the original, unfiltered image is retrieved by taking the residuals of the input image and the filter representation. The experimental results show that the proposed model outperforms both supervised and unsupervised methods by a considerable margin in the IFFI dataset.

## [2021.11.24 : SkeletonNetV2: A Dense Channel Attention Blocks for Skeleton Extraction](https://openaccess.thecvf.com/content/ICCV2021W/DLGC/papers/Nathan_SkeletonNetV2_A_Dense_Channel_Attention_Blocks_for_Skeleton_Extraction_ICCVW_2021_paper.pdf)
Geometrical analysis of a shape through skeletonization has some of very important high- and low-level application which includes tracking, manipulation, retrieval, representation, registration, recognition, and compression. The task of skeletonization is defined as the generation of the medial axis of the shape while preserving its original topology and geometry. While the earlier approaches are mainly based on extracting the skeleton and then pruning the unwanted branches, the present study proposes a novel convolutional neural network based method to perform this task. The proposed architecture is an encoder-decoder network that leverages the benefits of the coordinated convolutional layer and multi-level supervision to prevent the loss of information between the extracted skeleton and the ground truth. The dense attention block is used as the backbone block in the encoder and decoder block. This architecture is performing better than the state of art on not only skeletonization of image tasks but also skeletonization from the point cloud. This method achieved an F1 score of 0.7961 on the Pixel Skeleton dataset and a Chamfer Distance (CD) score of 1.9561 on the Point skeleton dataset.

## [2021.06.18 : Leveraging Multi scale Backbone with Multilevel supervision for Thermal Image Super Resolution](https://couger.co.jp/paper/couger_CVPRW_2021_paper.pdf)
This paper proposes an attention-based multi-level model with a multi-scale backbone for thermal image superresolution. The model leverages the multi-scale backbone as well. The thermal image dataset is provided by PBVS 2020 in their thermal image super-resolution challenge. This dataset contains the images with three different resolution scales(low, medium, high). However, only the medium and high-resolution images are used to train the proposed architecture to generate the super-resolution images in x2, x4 scales. The proposed architecture is based on the Res2net blocks as the backbone of the network. Along with this, the coordinate convolution layer and dual attention are also used in the architecture. Further, multi-level supervision is implemented to supervise the output image resolution similarity with the real image at each block during training. To test the robustness of the proposed model, we evaluated our model on the Thermal-6 dataset. The results show that our model is efficient to achieve state-ofthe-art results on the PBVS dataset. Further the results on the Thermal-6 dataset show that the model has a decent generalization capacity.

## [2020.07.10 : Expectation and Reaction as Intention for Conversation System](https://link.springer.com/chapter/10.1007/978-3-030-49062-1_19#:~:text=Expectation%20represents%20opponent's%20expected%20responses,model%20based%20on%20transformer%20model)
Intention plays an import role in human daily conversation. Conventionally, human intention exerts influence on conversation contents and atmosphere. Although dialogue systems that involve emotion awareness are popular, implementation of human intention on artificial intelligence does not draw much attention of researchers. The reason is that intention is usually not a spontaneous response of external stimulus, but a self-generated desire and expectation. Moreover, internal intentions are not subjected to external signals that can be observed by third parties. In this research, we experimentally used “reaction” and “expectation” factors to represent intention at a text level and created intentional conversation model based on transformer model. Preliminary results were given to show that applying intention is able to help the a dialogue system address a higher level of engagement in the conversation.

## [2020.06.16 : A Multi-Level Supervision Model: A novel approach for Thermal Image Super Resolution](https://couger.co.jp/paper/cvpr2020.pdf)
This paper proposes a novel architecture for thermal image super-resolution. The proposed architecture is based on the residual blocks as the base units of the network. Along with this, the coordinate convolution layer and the convolutional block attention Module (CBAM) are also used in the architecture. Further, the multi-level supervision is implemented to supervise the output image resolution similarity with the real image at each block during training. To test the robustness of the proposed model, we evaluated our model on the Thermal-6 dataset [13]. The results show that our model is efficient to achieve the state of art results on the PBVS’2020 dataset. Further the results on the Thermal-6 dataset show that the model has a decent generalization capacity.


## [2019.10.16 : Eyenet: Attention based Convolutional Encoder-Decoder Network for Eye Region Segmentation ](https://couger.co.jp/paper/facebook_ai.pdf)
With the immersive development in the field of augmented and virtual reality, accurate and speedy eye-tracking is required. Facebook Research has organized a challenge, named OpenEDS Semantic Segmentation challenge for per-pixel segmentation of the key eye regions: the sclera, the iris, the pupil, and everything else (background). Our model, named EyeNet, includes modified residual units as the backbone, two types of attention blocks and multi-scale supervision for segmenting the aforesaid four eye regions. Our proposed model achieved a total score of 0.974(EDS Evaluation metric) on test data, which demonstrates superior results compared to the baseline methods


## [2019.05.21 : SkeletonNet: Shape Pixel to Skeleton Pixel ](https://couger.co.jp/paper/cvpr2019.pdf)
Deep Learning for Geometric Shape Understating has organized a challenge for extracting different kinds of skeletons from the images of different objects. This competition is organized in association with CVPR 2019. In our proposed architecture, unlike the plain decoder in the traditional U net, we have designed the decoder in the format of HED architecture, wherein we have introduced 4 side layers and fused them to one dilation convolutional layer to connect the broken links of the skeleton. Our proposed architecture achieved the F1 score of 0.77 on test data. 


# Collaborative research paper

## [2022.05.22 : Rethinking Offensive Text Detection as a Multi-Hop Reasoning Problem ](https://couger.co.jp/paper/2022.findings-acl.307.pdf)
We introduce the task of implicit offensive text detection in dialogues, where a statement may have either an offensive or non-offensive interpretation, depending on the listener and context. We argue that reasoning is crucial for understanding this broader class of offensive utterances and release SLIGHT, a dataset to support research on this task. Experiments using the data show that state-of-the-art methods of offense detection perform poorly when asked to detect implicitly offensive statements, achieving only ∼11% accuracy. 
