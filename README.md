# Awesome-CVPR2020-Low-Level-Vision[![Awesome](https://camo.githubusercontent.com/13c4e50d88df7178ae1882a203ed57b641674f94/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f643733303566333864323966656437386661383536353265336136336531353464643865383832392f6d656469612f62616467652e737667)](https://github.com/sindresorhus/awesome)
A Collection of Papers and Codes for CVPR2020 Low Level Vision or Image Reconstruction

整理汇总了下今年CVPR图像重建(Image Reconstruction)/底层视觉(Low-Level Vision)相关的一些论文，包括超分辨率，图像恢复，去雨，去雾，去模糊，去噪等方向。大家如果觉得有帮助，欢迎star~~
- CVPR2020的所有论文：[http://openaccess.thecvf.com/CVPR2020.py](http://openaccess.thecvf.com/CVPR2020.py)
- CVPR2020Workshops：[http://openaccess.thecvf.com/CVPR2020_workshops/menu.py](http://openaccess.thecvf.com/CVPR2020_workshops/menu.py)

**【Contents】**
- [1.超分辨率（Super-Resolution）](#1.超分辨率)
- [2.图像去雨（Image Deraining）](#2.图像去雨)
- [3.图像去雾（Image Dehazing）](#3.图像去雾)
- [4.去模糊（Deblurring）](#4.去模糊)
- [5.去噪（Denoising）](#5.去噪)
- [6.图像恢复（Image Restoration）](#6.图像恢复)
- [7.图像增强（Image Enhancement）](#7.图像增强)
- [8.图像去摩尔纹（Image Demoireing）](#8.图像去摩尔纹)
- [9.图像修复（Inpainting）](#9.图像修复)
- [10.图像质量评价（Image Quality Assessment）](#10.图像质量评价)
- [11.其他](#11.其他)

<a name="1.超分辨率"></a>
# 1.超分辨率（Super-Resolution）
## 图像超分辨率
### PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models
- Paper：[https://arxiv.org/abs/2003.03808](https://arxiv.org/abs/2003.03808)
- Code：[https://github.com/adamian98/pulse](https://github.com/adamian98/pulse)
- Analysis：[杜克大学提出 AI 算法，拯救渣画质马赛克秒变高清](https://mp.weixin.qq.com/s?__biz=MzU3NTQ2NDIyOQ==&mid=2247493978&idx=1&sn=48a3a6c775ae490b2d6f90bcc607b075&chksm=fd201f10ca5796062a968040ed7e6bfebe8085b183b4ea0e1117c38ce6ec66c6d728ca483fba&mpshare=1&scene=23&srcid=&sharer_sharetime=1592366037552&sharer_shareid=e2c873c63ba339b9a32a1bfa460a6ebf#rd)
### Closed-Loop Matters: Dual Regression Networks for Single Image Super-Resolution
- Paper：[https://arxiv.org/abs/2003.07018](https://arxiv.org/abs/2003.07018)
- Code：[https://github.com/guoyongcs/DRN](https://github.com/guoyongcs/DRN)
- Analysis：[CVPR2020丨DRN：用于单图像超分辨率的对偶回归网络](https://zhuanlan.zhihu.com/p/115498523)
### EventSR: From Asynchronous Events to Image Reconstruction, Restoration, and Super-Resolution via End-to-End Adversarial Learning
- Paper：[http://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_EventSR_From_Asynchronous_Events_to_Image_Reconstruction_Restoration_and_Super-Resolution_CVPR_2020_paper.pdf](http://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_EventSR_From_Asynchronous_Events_to_Image_Reconstruction_Restoration_and_Super-Resolution_CVPR_2020_paper.pdf)
- Video ：[https://www.youtube.com/watch?v=OShS_MwHecs](https://www.youtube.com/watch?v=OShS_MwHecs)
- Dataset： [https://github.com/wl082013/ESIM_dataset](https://github.com/wl082013/ESIM_dataset)
### Unpaired Image Super-Resolution Using Pseudo-Supervision
- Paper：[https://arxiv.org/abs/2002.11397?context=eess](https://arxiv.org/abs/2002.11397?context=eess)
- Analysis：[#每日五分钟一读#Image Super-Resolution](https://zhuanlan.zhihu.com/p/147171955)
### Correction Filter for Single Image Super-Resolution: Robustifying Off-the-Shelf Deep Super-Resolvers
- Paper：[https://arxiv.org/abs/1912.00157](https://arxiv.org/abs/1912.00157)
- Code：[https://github.com/shadyabh/Correction-Filter](https://github.com/shadyabh/Correction-Filter)
- Analysis：[Correction Filter for Single Image Super-Resolution阅读笔记（CVPR2020）](https://blog.csdn.net/weixin_45828771/article/details/107601560)
### Residual Feature Aggregation Network for Image Super-Resolution
- Paper：[http://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Residual_Feature_Aggregation_Network_for_Image_Super-Resolution_CVPR_2020_paper.pdf](http://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Residual_Feature_Aggregation_Network_for_Image_Super-Resolution_CVPR_2020_paper.pdf)
- Code：[https://github.com/njulj/RFANet](https://github.com/njulj/RFANet)
- Analysis：[超越RCAN，图像超分又一峰：RFANet](https://mp.weixin.qq.com/s/laZ_LH8tQ4PQaQXIyr38Bg)
### Deep Unfolding Network for Image Super-Resolution
- Paper：[https://arxiv.org/abs/2003.10428](https://arxiv.org/abs/2003.10428)
- Code：[https://github.com/cszn/USRNet](https://github.com/cszn/USRNet)
- Analysis：[CVPR2020：USRNet](https://mp.weixin.qq.com/s/0-Kjfi8RBuPb_KuB5-Khkg)
### Image Super-Resolution With Cross-Scale Non-Local Attention and Exhaustive Self-Exemplars Mining
- Paper：[https://arxiv.org/abs/2006.01424](https://arxiv.org/abs/2006.01424)
- Code：[https://github.com/SHI-Labs/Cross-Scale-Non-Local-Attention](https://github.com/SHI-Labs/Cross-Scale-Non-Local-Attention)
- Analysis：[CVPR2020|跨尺度非局部注意力模型改进图像超分辨率，Code开源](https://zhuanlan.zhihu.com/p/145514672)
### Learning Texture Transformer Network for Image Super-Resolution
- Paper：[https://arxiv.org/abs/2006.04139](https://arxiv.org/abs/2006.04139)
- Code：[https://github.com/FuzhiYang/TTSR](https://github.com/FuzhiYang/TTSR)
- Analysis：[CVPR 2020丨图像超清化+老照片修复技术，拯救你所有的模糊、破损照片](https://blog.csdn.net/moxibingdao/article/details/106726668)
### Robust Reference-Based Super-Resolution With Similarity-Aware Deformable Convolution
- Paper：[http://openaccess.thecvf.com/content_CVPR_2020/html/Shim_Robust_Reference-Based_Super-Resolution_With_Similarity-Aware_Deformable_Convolution_CVPR_2020_paper.html](http://openaccess.thecvf.com/content_CVPR_2020/html/Shim_Robust_Reference-Based_Super-Resolution_With_Similarity-Aware_Deformable_Convolution_CVPR_2020_paper.html)
- Analysis：[8/19 (CVPR2020) Robust Reference-based Super-Resolution with Similarity-Aware Deformable Convolution](https://blog.csdn.net/qq_40723205/article/details/108103295)
### Structure-Preserving Super Resolution with Gradient Guidance
- Paper：[https://arxiv.org/abs/2003.13063](https://arxiv.org/abs/2003.13063)
- Code：[https://github.com/Maclory/Deep-Iterative-Collaboration](https://github.com/Maclory/Deep-Iterative-Collaboration)
- Analysis：[CVPR2020丨SPSR：基于梯度指导的结构保留超分辨率方法](https://zhuanlan.zhihu.com/p/121721537)
### Unified Dynamic Convolutional Network for Super-Resolution With Variational Degradations
- Paper：[https://arxiv.org/abs/2004.06965](https://arxiv.org/abs/2004.06965)
- Analysis：[UDVD：适用于可变降质类型的通用图像超分，附参考Code](https://mp.weixin.qq.com/s?__biz=MzI5MDUyMDIxNA%3D%3D&mid=2247494694&idx=1&sn=ed29071f700b129534beb649a04b3b97&scene=45#wechat_redirect)
### Perceptual Extreme Super Resolution Network with Receptive Field Block
- Paper：[https://arxiv.org/abs/2005.12597](https://arxiv.org/abs/2005.12597)
- Analysis：[NTIRE2020冠军方案RFB-ESRGAN：带感受野模块的超分网络](https://mp.weixin.qq.com/s/nj_C_LXFpWQZASc4ITJmmA)
- Remarks：NTIRE2020极限超分冠军方案RFB-ESRGAN；Workshops
### Real-World Super-Resolution via Kernel Estimation and Noise Injection
- Paper：[http://openaccess.thecvf.com/content_CVPRW_2020/html/w31/Ji_Real-World_Super-Resolution_via_Kernel_Estimation_and_Noise_Injection_CVPRW_2020_paper.html](http://openaccess.thecvf.com/content_CVPRW_2020/html/w31/Ji_Real-World_Super-Resolution_via_Kernel_Estimation_and_Noise_Injection_CVPRW_2020_paper.html)
- Code：[https://github.com/jixiaozhong/RealSR](https://github.com/jixiaozhong/RealSR)
- Remarks：NTIRE2020-RWSR超分双赛道冠军方案；Workshops
### Investigating Loss Functions for Extreme Super-Resolution
- Paper：[http://openaccess.thecvf.com/content_CVPRW_2020/papers/w31/Jo_Investigating_Loss_Functions_for_Extreme_Super-Resolution_CVPRW_2020_paper.pdf](http://openaccess.thecvf.com/content_CVPRW_2020/papers/w31/Jo_Investigating_Loss_Functions_for_Extreme_Super-Resolution_CVPRW_2020_paper.pdf)
- Code：[https://github.com/kingsj0405/ciplab-NTIRE-2020](https://github.com/kingsj0405/ciplab-NTIRE-2020)
- Remarks：NTIRE2020极限超分亚军方案CIPLab；Workshops
### Nested Scale-Editing for Conditional Image Synthesis
- Paper：[http://arxiv.org/abs/2006.02038](http://arxiv.org/abs/2006.02038)
### MSG-GAN: Multi-Scale Gradients for Generative Adversarial Networks
- Paper：[https://arxiv.org/abs/1903.06048v3](https://arxiv.org/abs/1903.06048v3)
- Code：[https://github.com/akanimax/msg-stylegan-tf](https://github.com/akanimax/msg-stylegan-tf)
- Analysis：[CVPR2020之MSG-GAN：简单有效的SOTA](https://mp.weixin.qq.com/s?__biz=MzU5MTgzNzE0MA==&mid=2247484246&idx=1&sn=3af777e066a3d4b6dcf1c4cf4856a671&chksm=fe29a1edc95e28fb85299ccf87a1819755f80243ff17f0057c425f3c4077e7e3b4d4a2035329&scene=21#wechat_redirect)
- Remarks：NTIRE2020极限超分亚军方案CIPLab；Workshops
## 视频超分辨率
### TDAN: Temporally-Deformable Alignment Network for Video Super-Resolution
- Paper：[https://arxiv.org/abs/1812.02898](https://arxiv.org/abs/1812.02898)
- Code：[https://github.com/YapengTian/TDAN-VSR-CVPR-2020](https://github.com/YapengTian/TDAN-VSR-CVPR-2020)
- Video：[https://www.youtube.com/watch?v=eZExENE50I0](https://www.youtube.com/watch?v=eZExENE50I0)
### Zooming Slow-Mo: Fast and Accurate One-Stage Space-Time Video Super-Resolution
- Paper：[https://arxiv.org/abs/2002.11616](https://arxiv.org/abs/2002.11616)
- Code：[https://github.com/Mukosame/Zooming-Slow-Mo-CVPR-2020](https://github.com/Mukosame/Zooming-Slow-Mo-CVPR-2020)
- Analysis：[慢镜头变焦：视频超分辨率：CVPR2020Paper解析](https://zhuanlan.zhihu.com/p/117341018)
### Video Super-Resolution With Temporal Group Attention
- Paper：[http://openaccess.thecvf.com/content_CVPR_2020/papers/Isobe_Video_Super-Resolution_With_Temporal_Group_Attention_CVPR_2020_paper.pdf](http://openaccess.thecvf.com/content_CVPR_2020/papers/Isobe_Video_Super-Resolution_With_Temporal_Group_Attention_CVPR_2020_paper.pdf)
### Space-Time-Aware Multi-Resolution Video Enhancement
- 主页：[https://alterzero.github.io/projects/STAR.html](https://alterzero.github.io/projects/STAR.html)
- Paper：[http://arxiv.org/abs/2003.13170](http://arxiv.org/abs/2003.13170)
- Code：[https://github.com/alterzero/STARnet](https://github.com/alterzero/STARnet)
## 人脸超分辨率
### Learning to Have an Ear for Face Super-Resolution
- Paper：[https://arxiv.org/abs/1909.12780](https://arxiv.org/abs/1909.12780)
- Code：[https://github.com/gmeishvili/ear_for_face_super_resolution](https://github.com/gmeishvili/ear_for_face_super_resolution)
### Deep Face Super-Resolution With Iterative Collaboration Between Attentive Recovery and Landmark Estimation
- Paper：[https://arxiv.org/abs/1812.02898](https://arxiv.org/abs/1812.02898)
- Code：[https://github.com/YapengTian/TDAN-VSR-CVPR-2020](https://github.com/YapengTian/TDAN-VSR-CVPR-2020)
## 深度图超分辨率
### Channel Attention Based Iterative Residual Learning for Depth Map Super-Resolution
- Paper：[https://arxiv.org/abs/2006.01469](https://arxiv.org/abs/2006.01469)
## 光场图像超分辨率
### Light Field Spatial Super-Resolution via Deep Combinatorial Geometry Embedding and Structural Consistency Regularization
- Paper：[https://arxiv.org/abs/2004.02215](https://arxiv.org/abs/2004.02215)
- Code：[https://github.com/jingjin25/LFSSR-ATO](https://github.com/jingjin25/LFSSR-ATO)
## 高光谱图像超分辨率
### Unsupervised Adaptation Learning for Hyperspectral Imagery Super-Resolution
- Paper：[http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Unsupervised_Adaptation_Learning_for_Hyperspectral_Imagery_Super-Resolution_CVPR_2020_paper.pdf](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Unsupervised_Adaptation_Learning_for_Hyperspectral_Imagery_Super-Resolution_CVPR_2020_paper.pdf)
- Code：[https://github.com/JiangtaoNie/UAL](https://github.com/JiangtaoNie/UAL)
## 零样本超分辨率
### Meta-Transfer Learning for Zero-Shot Super-Resolution
- Paper：[https://arxiv.org/abs/2002.12213](https://arxiv.org/abs/2002.12213)
- Code：[https://github.com/JWSoh/MZSR](https://github.com/JWSoh/MZSR)
## 用于超分辨率的数据增广
### Rethinking Data Augmentation for Image Super-resolution: A Comprehensive Analysis and a New Strategy
- Paper：[http://openaccess.thecvf.com/content_CVPR_2020/html/Yoo_Rethinking_Data_Augmentation_for_Image_Super-resolution_A_Comprehensive_Analysis_and_CVPR_2020_paper.html](http://openaccess.thecvf.com/content_CVPR_2020/html/Yoo_Rethinking_Data_Augmentation_for_Image_Super-resolution_A_Comprehensive_Analysis_and_CVPR_2020_paper.html)
- Code：[https://github.com/clovaai/cutblur](https://github.com/clovaai/cutblur)
## 超分辨率用于语义分割
### Dual Super-Resolution Learning for Semantic Segmentation
- Paper：[http://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Dual_Super-Resolution_Learning_for_Semantic_Segmentation_CVPR_2020_paper.html](http://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Dual_Super-Resolution_Learning_for_Semantic_Segmentation_CVPR_2020_paper.html)
- Code：[https://github.com/wanglixilinx/DSRL](https://github.com/wanglixilinx/DSRL)
## 其他超分
### Explorable Super Resolution
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Bahat_Explorable_Super_Resolution_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Bahat_Explorable_Super_Resolution_CVPR_2020_paper.pdf)

<a name="2.图像去雨"></a>
# 2.图像去雨（Image Deraining）
### Deep Adversarial Decomposition: A Unified Framework for Separating Superimposed Images
- Paper：[http://openaccess.thecvf.com/content_CVPR_2020/html/Zou_Deep_Adversarial_Decomposition_A_Unified_Framework_for_Separating_Superimposed_Images_CVPR_2020_paper.html](http://openaccess.thecvf.com/content_CVPR_2020/html/Zou_Deep_Adversarial_Decomposition_A_Unified_Framework_for_Separating_Superimposed_Images_CVPR_2020_paper.html)
- Code：[https://github.com/jiupinjia/Deep-adversarial-decomposition](https://github.com/jiupinjia/Deep-adversarial-decomposition)
- Demo:[http://www-personal.umich.edu/~zzhengxi/zzx_gallery/5946-1min.mp4](http://www-personal.umich.edu/~zzhengxi/zzx_gallery/5946-1min.mp4)
### Multi-Scale Progressive Fusion Network for Single Image Deraining
- Paper：[https://arxiv.org/abs/2003.10985](https://arxiv.org/abs/2003.10985)
- Code：[https://github.com/kuihua/MSPFN](https://github.com/kuihua/MSPFN)
### Syn2Real Transfer Learning for Image Deraining Using Gaussian Processes
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Yasarla_Syn2Real_Transfer_Learning_for_Image_Deraining_Using_Gaussian_Processes_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yasarla_Syn2Real_Transfer_Learning_for_Image_Deraining_Using_Gaussian_Processes_CVPR_2020_paper.pdf)
### Detail-recovery Image Deraining via Context Aggregation Networks
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Deng_Detail-recovery_Image_Deraining_via_Context_Aggregation_Networks_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Deng_Detail-recovery_Image_Deraining_via_Context_Aggregation_Networks_CVPR_2020_paper.pdf)

<a name="3.图像去雾"></a>
# 3.图像去雾（Image Dehazing）
### Domain Adaptation for Image Dehazing
- Paper：[https://arxiv.org/abs/2005.04668](https://arxiv.org/abs/2005.04668)
- Code：[https://github.com/shawnchen63/DA_dahazing](https://github.com/shawnchen63/DA_dahazing)
### Multi-Scale Boosted Dehazing Network with Dense Feature Fusion
- Paper：[https://arxiv.org/abs/2004.13388](https://arxiv.org/abs/2004.13388)
- Code：[https://github.com/BookerDeWitt/MSBDN-DFF](https://github.com/BookerDeWitt/MSBDN-DFF)
### BidNet: Binocular Image Dehazing Without Explicit Disparity Estimation
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Pang_BidNet_Binocular_Image_Dehazing_Without_Explicit_Disparity_Estimation_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Pang_BidNet_Binocular_Image_Dehazing_Without_Explicit_Disparity_Estimation_CVPR_2020_paper.pdf)
### Distilling Image Dehazing With Heterogeneous Task Imitation
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Hong_Distilling_Image_Dehazing_With_Heterogeneous_Task_Imitation_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Hong_Distilling_Image_Dehazing_With_Heterogeneous_Task_Imitation_CVPR_2020_paper.pdf)
- Code：[https://github.com/FadeoN/Distilling-Image-Dehazing-With-Heterogeneous-Task-Imitation](https://github.com/FadeoN/Distilling-Image-Dehazing-With-Heterogeneous-Task-Imitation)

<a name="4.去模糊"></a>
# 4.去模糊（Deblurring）
## 视频去模糊
### Cascaded Deep Video Deblurring Using Temporal Sharpness Prior
- Paper：[https://arxiv.org/abs/2004.02501](https://arxiv.org/abs/2004.02501)
- Code：[https://github.com/csbhr/CDVD-TSP](https://github.com/csbhr/CDVD-TSP)
- Homepage：[https://csbhr.github.io/projects/cdvd-tsp/index.html](https://csbhr.github.io/projects/cdvd-tsp/index.html)
### Learning Event-Based Motion Deblurring
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Jiang_Learning_Event-Based_Motion_Deblurring_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Jiang_Learning_Event-Based_Motion_Deblurring_CVPR_2020_paper.pdf)
### Variational-EM-Based Deep Learning for Noise-Blind Image Deblurring
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Nan_Variational-EM-Based_Deep_Learning_for_Noise-Blind_Image_Deblurring_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Nan_Variational-EM-Based_Deep_Learning_for_Noise-Blind_Image_Deblurring_CVPR_2020_paper.pdf)
### Efficient Dynamic Scene Deblurring Using Spatially Variant Deconvolution Network With Optical Flow Guided Training
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Yuan_Efficient_Dynamic_Scene_Deblurring_Using_Spatially_Variant_Deconvolution_Network_With_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yuan_Efficient_Dynamic_Scene_Deblurring_Using_Spatially_Variant_Deconvolution_Network_With_CVPR_2020_paper.pdf)
### Deblurring by Realistic Blurring
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Deblurring_by_Realistic_Blurring_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Deblurring_by_Realistic_Blurring_CVPR_2020_paper.pdf)
### Spatially-Attentive Patch-Hierarchical Network for Adaptive Motion Deblurring
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Suin_Spatially-Attentive_Patch-Hierarchical_Network_for_Adaptive_Motion_Deblurring_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Suin_Spatially-Attentive_Patch-Hierarchical_Network_for_Adaptive_Motion_Deblurring_CVPR_2020_paper.pdf)
### Deblurring Using Analysis-Synthesis Networks Pair
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Kaufman_Deblurring_Using_Analysis-Synthesis_Networks_Pair_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kaufman_Deblurring_Using_Analysis-Synthesis_Networks_Pair_CVPR_2020_paper.pdf)

<a name="5.去噪"></a>
# 5.去噪（Denoising）
### A Physics-based Noise Formation Model for Extreme Low-light Raw Denoising
- Paper：[https://arxiv.org/abs/2003.12751](https://arxiv.org/abs/2003.12751)
- Code：[https://github.com/Vandermode/NoiseModel](https://github.com/Vandermode/NoiseModel)
### CycleISP: Real Image Restoration via Improved Data Synthesis
- Paper：[https://arxiv.org/abs/2003.07761](https://arxiv.org/abs/2003.07761)
- Code：[https://github.com/swz30/CycleISP](https://github.com/swz30/CycleISP)

<a name="6.图像恢复"></a>
# 6.图像恢复（Image Restoration）
### Learning Invariant Representation for Unsupervised Image Restoration
- Paper：[https://arxiv.org/pdf/2003.12769.pdf](https://arxiv.org/pdf/2003.12769.pdf)
- Code：[https://github.com/Wenchao-Du/LIR-for-Unsupervised-IR](https://github.com/Wenchao-Du/LIR-for-Unsupervised-IR)
### Attentive Normalization for Conditional Image Generation
- Paper：[https://arxiv.org/abs/2004.03828](https://arxiv.org/abs/2004.03828)
- Code：[https://github.com/shepnerd/AttenNorm](https://github.com/shepnerd/AttenNorm)
### Bringing Old Photos Back to Life
- Paper：[https://arxiv.org/abs/2004.09484](https://arxiv.org/abs/2004.09484)
- Code：[https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life)
- Homepage：[http://raywzy.com/Old_Photo/](http://raywzy.com/Old_Photo/)
### CycleISP: Real Image Restoration via Improved Data Synthesis
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Zamir_CycleISP_Real_Image_Restoration_via_Improved_Data_Synthesis_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zamir_CycleISP_Real_Image_Restoration_via_Improved_Data_Synthesis_CVPR_2020_paper.pdf)
- Code：[https://github.com/swz30/CycleISP](https://github.com/swz30/CycleISP)
### Enhanced Blind Face Restoration With Multi-Exemplar Images and Adaptive Spatial Feature Fusion
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Blind_Face_Restoration_With_Multi-Exemplar_Images_and_Adaptive_Spatial_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Blind_Face_Restoration_With_Multi-Exemplar_Images_and_Adaptive_Spatial_CVPR_2020_paper.pdf)
- Code：[https://github.com/csxmli2016/ASFFNet](https://github.com/csxmli2016/ASFFNet)
### Disparity-Aware Domain Adaptation in Stereo Image Restoration
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Yan_Disparity-Aware_Domain_Adaptation_in_Stereo_Image_Restoration_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yan_Disparity-Aware_Domain_Adaptation_in_Stereo_Image_Restoration_CVPR_2020_paper.pdf)

<a name="7.图像增强"></a>
# 7.图像增强（Image Enhancement）
### DeepLPF: Deep Local Parametric Filters for Image Enhancement
- Paper：[https://arxiv.org/abs/2003.13985](https://arxiv.org/abs/2003.13985)
- Code：[https://github.com/sjmoran/deep_local_parametric_filters](https://github.com/sjmoran/deep_local_parametric_filters)
### Learning for Video Compression With Hierarchical Quality and Recurrent Enhancement
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_Learning_for_Video_Compression_With_Hierarchical_Quality_and_Recurrent_Enhancement_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_Learning_for_Video_Compression_With_Hierarchical_Quality_and_Recurrent_Enhancement_CVPR_2020_paper.pdf)
- Code：[https://github.com/RenYang-home/HLVC](https://github.com/RenYang-home/HLVC)
### Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Guo_Zero-Reference_Deep_Curve_Estimation_for_Low-Light_Image_Enhancement_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Guo_Zero-Reference_Deep_Curve_Estimation_for_Low-Light_Image_Enhancement_CVPR_2020_paper.pdf)
- Code：[https://github.com/Li-Chongyi/Zero-DCE](https://github.com/Li-Chongyi/Zero-DCE)
### From Fidelity to Perceptual Quality: A Semi-Supervised Approach for Low-Light Image Enhancement
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_From_Fidelity_to_Perceptual_Quality_A_Semi-Supervised_Approach_for_Low-Light_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_From_Fidelity_to_Perceptual_Quality_A_Semi-Supervised_Approach_for_Low-Light_CVPR_2020_paper.pdf)
- Code：[https://github.com/flyywh/CVPR-2020-Semi-Low-Light](https://github.com/flyywh/CVPR-2020-Semi-Low-Light)
### Space-Time-Aware Multi-Resolution Video Enhancement
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Haris_Space-Time-Aware_Multi-Resolution_Video_Enhancement_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Haris_Space-Time-Aware_Multi-Resolution_Video_Enhancement_CVPR_2020_paper.pdf)
- Code：[https://github.com/alterzero/STARnet](https://github.com/alterzero/STARnet)
### Learning to Restore Low-Light Images via Decomposition-and-Enhancement
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Learning_to_Restore_Low-Light_Images_via_Decomposition-and-Enhancement_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_Learning_to_Restore_Low-Light_Images_via_Decomposition-and-Enhancement_CVPR_2020_paper.pdf)

<a name="8.图像去摩尔纹"></a>
# 8.图像去摩尔纹（Image Demoireing）
### Image Demoireing with Learnable Bandpass Filters
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Zheng_Image_Demoireing_with_Learnable_Bandpass_Filters_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zheng_Image_Demoireing_with_Learnable_Bandpass_Filters_CVPR_2020_paper.pdf)
- Code：[https://github.com/zhenngbolun/Learnbale_Bandpass_Filter](https://github.com/zhenngbolun/Learnbale_Bandpass_Filter)

<a name="9.图像修复"></a>
# 9.图像修复（Inpainting）
### Contextual Residual Aggregation for Ultra High-Resolution Image Inpainting
- Paper：[https://arxiv.org/abs/2005.09704](https://arxiv.org/abs/2005.09704)
- Code：[https://github.com/phillips96/CRA-Inpainting](https://github.com/phillips96/CRA-Inpainting)
### UCTGAN: Diverse Image Inpainting based on Unsupervised Cross-Space
- Paper：[http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_UCTGAN_Diverse_Image_Inpainting_Based_on_Unsupervised_Cross-Space_Translation_CVPR_2020_paper.pdf](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_UCTGAN_Diverse_Image_Inpainting_Based_on_Unsupervised_Cross-Space_Translation_CVPR_2020_paper.pdf)
### Recurrent Feature Reasoning for Image Inpainting
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Recurrent_Feature_Reasoning_for_Image_Inpainting_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Recurrent_Feature_Reasoning_for_Image_Inpainting_CVPR_2020_paper.pdf)
- Code：[https://github.com/jingyuanli001/RFR-Inpainting](https://github.com/jingyuanli001/RFR-Inpainting)
### Prior Guided GAN Based Semantic Inpainting
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Lahiri_Prior_Guided_GAN_Based_Semantic_Inpainting_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lahiri_Prior_Guided_GAN_Based_Semantic_Inpainting_CVPR_2020_paper.pdf)
### 3D Photography Using Context-Aware Layered Depth Inpainting
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Shih_3D_Photography_Using_Context-Aware_Layered_Depth_Inpainting_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Shih_3D_Photography_Using_Context-Aware_Layered_Depth_Inpainting_CVPR_2020_paper.pdf)
- Code：[https://github.com/vt-vl-lab/3d-photo-inpainting](https://github.com/vt-vl-lab/3d-photo-inpainting)

<a name="10.图像质量评价"></a>
# 10.图像质量评价（Image Quality Assessment）
### MetaIQA: Deep Meta-Learning for No-Reference Image Quality Assessment
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhu_MetaIQA_Deep_Meta-Learning_for_No-Reference_Image_Quality_Assessment_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhu_MetaIQA_Deep_Meta-Learning_for_No-Reference_Image_Quality_Assessment_CVPR_2020_paper.pdf)
- Code：[https://github.com/zhuhancheng/MetaIQA](https://github.com/zhuhancheng/MetaIQA)
### Uncertainty-Aware Score Distribution Learning for Action Quality Assessment
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Tang_Uncertainty-Aware_Score_Distribution_Learning_for_Action_Quality_Assessment_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tang_Uncertainty-Aware_Score_Distribution_Learning_for_Action_Quality_Assessment_CVPR_2020_paper.pdf)
- Code：[https://github.com/nzl-thu/MUSDL](https://github.com/nzl-thu/MUSDL)
### Perceptual Quality Assessment of Smartphone Photography
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_Perceptual_Quality_Assessment_of_Smartphone_Photography_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_Perceptual_Quality_Assessment_of_Smartphone_Photography_CVPR_2020_paper.pdf)
- Code：[https://github.com/h4nwei/SPAQ](https://github.com/h4nwei/SPAQ)
### Adaptive Fractional Dilated Convolution Network for Image Aesthetics Assessment
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Chen_Adaptive_Fractional_Dilated_Convolution_Network_for_Image_Aesthetics_Assessment_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Chen_Adaptive_Fractional_Dilated_Convolution_Network_for_Image_Aesthetics_Assessment_CVPR_2020_paper.pdf)
### Deep Metric Learning via Adaptive Learnable Assessment
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/papers/Zheng_Deep_Metric_Learning_via_Adaptive_Learnable_Assessment_CVPR_2020_paper.pdf](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zheng_Deep_Metric_Learning_via_Adaptive_Learnable_Assessment_CVPR_2020_paper.pdf)

<a name="11.其他"></a>
# 11.其他多任务
### Image Processing Using Multi-Code GAN Prior
- Paper：[https://openaccess.thecvf.com/content_CVPR_2020/html/Gu_Image_Processing_Using_Multi-Code_GAN_Prior_CVPR_2020_paper.html](https://openaccess.thecvf.com/content_CVPR_2020/html/Gu_Image_Processing_Using_Multi-Code_GAN_Prior_CVPR_2020_paper.html)
- Code：[https://github.com/genforce/mganprior](https://github.com/genforce/mganprior)
### EventSR: From Asynchronous Events to Image Reconstruction, Restoration, and Super-Resolution via End-to-End Adversarial Learning
- Paper：[http://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_EventSR_From_Asynchronous_Events_to_Image_Reconstruction_Restoration_and_Super-Resolution_CVPR_2020_paper.pdf](http://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_EventSR_From_Asynchronous_Events_to_Image_Reconstruction_Restoration_and_Super-Resolution_CVPR_2020_paper.pdf)
- Video ：[https://www.youtube.com/watch?v=OShS_MwHecs](https://www.youtube.com/watch?v=OShS_MwHecs)
- Dataset： [https://github.com/wl082013/ESIM_dataset](https://github.com/wl082013/ESIM_dataset)

<font color=red size=5>待续更新~</font>
<div class="output_wrapper" id="output_wrapper_id" style="font-size: 16px; color: rgb(62, 62, 62); line-height: 1.6; word-spacing: 0px; letter-spacing: 0px; font-family: 'Helvetica Neue', Helvetica, 'Hiragino Sans GB', 'Microsoft YaHei', Arial, sans-serif;"><h1 id="h" style="color: inherit; line-height: inherit; padding: 0px; margin: 1.5em 0px; font-weight: bold; font-size: 1.6em;"><span style="font-size: inherit; color: inherit; line-height: inherit; margin: 0px; padding: 0px;">参考</span></h1>
<p style="font-size: inherit; color: inherit; line-height: inherit; padding: 0px; margin: 1.5em 0px;"><a href="https://mp.weixin.qq.com/s?__biz=MzU3NTQ2NDIyOQ==&amp;mid=2247493978&amp;idx=1&amp;sn=48a3a6c775ae490b2d6f90bcc607b075&amp;chksm=fd201f10ca5796062a968040ed7e6bfebe8085b183b4ea0e1117c38ce6ec66c6d728ca483fba&amp;mpshare=1&amp;scene=23&amp;srcid=&amp;sharer_sharetime=1592366037552&amp;sharer_shareid=e2c873c63ba339b9a32a1bfa460a6ebf#rd" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[1] 杜克大学提出 AI 算法，拯救渣画质马赛克秒变高清</a><br><a href="https://blog.csdn.net/moxibingdao/article/details/106726667" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[2] CVPR 2020 论文大盘点-超分辨率篇</a><br><a href="https://zhuanlan.zhihu.com/p/121721537" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[3] CVPR2020丨SPSR：基于梯度指导的结构保留超分辨率方法</a><br><a href="https://mp.weixin.qq.com/s/0-Kjfi8RBuPb_KuB5-Khkg" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[4] CVPR2020：USRNet</a><br><a href="https://mp.weixin.qq.com/s?__biz=MzI5MDUyMDIxNA%3D%3D&amp;mid=2247494694&amp;idx=1&amp;sn=ed29071f700b129534beb649a04b3b97&amp;scene=45#wechat_redirect" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[5] UDVD：适用于可变降质类型的通用图像超分，附参考代码</a><br><a href="https://mp.weixin.qq.com/s/nj_C_LXFpWQZASc4ITJmmA" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[6] NTIRE2020冠军方案RFB-ESRGAN：带感受野模块的超分网络</a><br><a href="https://mp.weixin.qq.com/s/laZ_LH8tQ4PQaQXIyr38Bg" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[7] 超越RCAN，图像超分又一峰：RFANet</a><br><a href="https://zhuanlan.zhihu.com/p/147171955" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[8] #每日五分钟一读#Image Super-Resolution</a><br><a href="https://zhuanlan.zhihu.com/p/148965379" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[9] CVPR 2020 | 几篇GAN在low-level vision中的应用论文</a><br><a href="https://mp.weixin.qq.com/s?__biz=MzU5MTgzNzE0MA==&amp;mid=2247486455&amp;idx=1&amp;sn=94156f53845cdf07e859e343862be745&amp;chksm=fe29a94cc95e205ae880cb9518cb16a54c0abde69e5a8654f7fedf70a0cc990775265bf28a1c&amp;mpshare=1&amp;scene=23&amp;srcid=&amp;sharer_sharetime=1592478384281&amp;sharer_shareid=e2c873c63ba339b9a32a1bfa460a6ebf#rd" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[10] 超100篇！CVPR 2020最全GAN论文梳理汇总！</a><br><a href="https://mp.weixin.qq.com/s?__biz=MzU5MTgzNzE0MA==&amp;mid=2247484246&amp;idx=1&amp;sn=3af777e066a3d4b6dcf1c4cf4856a671&amp;chksm=fe29a1edc95e28fb85299ccf87a1819755f80243ff17f0057c425f3c4077e7e3b4d4a2035329&amp;scene=21#wechat_redirect" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[11] CVPR2020之MSG-GAN：简单有效的SOTA</a><br><a href="https://github.com/amusi/CVPR2020-Code" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[12] CVPR2020-Code</a><br><a href="https://zhuanlan.zhihu.com/p/117341018" style="font-size: inherit; line-height: inherit; margin: 0px; padding: 0px; text-decoration: none; color: rgb(30, 107, 184); overflow-wrap: break-word;">[13] 慢镜头变焦：视频超分辨率：CVPR2020论文解析</a></p></div>

# 相关Low-Level-Vision整理
- [Awesome-ECCV2020-Low-Level-Vision](https://github.com/Kobaayyy/Awesome-ECCV2020-Low-Level-Vision)
