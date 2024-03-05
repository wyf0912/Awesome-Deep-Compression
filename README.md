# Awesome-Deep-Compression
Collection of recent deep learning based compression works, e.g., image/video compression. Questions and discussions are most welcome! Upcoming works will be updated on a regular basis, feel free to contact me to add... :thumbsup:

## Image Compression
### Survey
* `Signal Processing 2022` Deep Architectures for Image Compression: A Critical Review [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0165168421003832)]
* `TPAMI 2021` Learning end-to-end lossy image compression: A benchmark [[Paper](https://arxiv.org/pdf/2002.03711.pdf)]

### Methods
* `CVPR 2023` Raw Image Reconstruction with Learned Compact Metadata [[Paper](https://arxiv.org/pdf/2302.12995.pdf)]
* `CVPR 2023` Multi-Realism Image Compression with a Conditional Generator [[Paper](https://arxiv.org/pdf/2212.13824.pdf)]
* `CVPR 2023` AccelIR: Task-aware Image Compression for Accelerating Neural Restoration [[Paper](https://arxiv.org/pdf/2304.12319.pdf)]
* `CVPR 2023` Context-Based Trit-Plane Coding for Progressive Image Compression [[Paper](https://arxiv.org/pdf/2303.05715.pdf)]
* `CVPR 2023` LVQAC: Lattice Vector Quantization Coupled with Spatially Adaptive Companding for Efficient Learned Image Compression [[Paper]()]
* `CVPR 2023` Learned Image Compression with Mixed Transformer-CNN Architectures  [[Paper](https://arxiv.org/pdf/2303.14978.pdf)]
* `ICLR 2023` Multi-Rate VAE: Train Once, Get the Full Rate-Distortion Curve [[Paper](https://openreview.net/forum?id=OJ8aSjCaMNK)]
* `CVPR 2022` LC-FDNet: Learned Lossless Image Compression with Frequency Decomposition Network [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Rhee_LC-FDNet_Learned_Lossless_Image_Compression_With_Frequency_Decomposition_Network_CVPR_2022_paper.pdf)]
* `CVPR 2022` The Devil Is in the Details: Window-Based Attention for Image Compression [[Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Zou_The_Devil_Is_in_the_Details_Window-Based_Attention_for_Image_CVPR_2022_paper.html)]
* `CVPR 2022` ELIC: Efficient Learned Image Compression With Unevenly Grouped Space-Channel Contextual Adaptive Coding [[Paper](https://openaccess.thecvf.com/content/CVPR2022/html/He_ELIC_Efficient_Learned_Image_Compression_With_Unevenly_Grouped_Space-Channel_Contextual_CVPR_2022_paper.html#:~:text=ELIC%3A%20Efficient%20Learned%20Image%20Compression%20With%20Unevenly%20Grouped%20Space%2DChannel%20Contextual%20Adaptive%20Coding)]
* `ECCV 2022` Optimizing Image Compression via Joint Learning with Denoising [[Paper](https://arxiv.org/pdf/2207.10869.pdf)]
* `ECCV 2022` Content Adaptive Latents and Decoder for Neural Image Compression [[Paper](https://arxiv.org/pdf/2212.10132.pdf)]
* `ACMMM 2022` High-Fidelity Variable-Rate Image Compression via Invertible Activation Transformation [[Paper]](https://dl.acm.org.remotexs.ntu.edu.sg/doi/pdf/10.1145/3503161.3547880)
* `NIPS 2022` High-fidelity generative image compression [[Paper]](https://proceedings.neurips.cc/paper/2020/file/8a50bae297807da9e97722a0b3fd8f27-Paper.pdf) [[Code](https://hific.github.io/)]
* `CVPR 2022` DPICT: Deep Progressive Image Compression Using Trit-Planes [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Lee_DPICT_Deep_Progressive_Image_Compression_Using_Trit-Planes_CVPR_2022_paper.pdf)]
* `CVPR 2022` Neural data-dependent transform for learned image compression [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Neural_Data-Dependent_Transform_for_Learned_Image_Compression_CVPR_2022_paper.pdf)]
* `NIPS 2021` Lossy compression for lossless prediction [[Paper]](https://proceedings.neurips.cc/paper/2021/hash/7535bbb91c8fde347ad861f293126633-Abstract.html) [[Code](github.com/YannDubs/lossyless)]
* `ICCV 2021` Variable-Rate Deep Image Compression through Spatially-Adaptive Feature Transform [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Song_Variable-Rate_Deep_Image_Compression_Through_Spatially-Adaptive_Feature_Transform_ICCV_2021_paper.pdf)
* `CVPR 2021` Asymmetric Gained Deep Image Compression With Continuous Rate Adaptation [[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Cui_Asymmetric_Gained_Deep_Image_Compression_With_Continuous_Rate_Adaptation_CVPR_2021_paper.pdf)]
* `CVPR 2021` Slimmable Compressive Autoencoders for Practical Neural Image Compression [[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Slimmable_Compressive_Autoencoders_for_Practical_Neural_Image_Compression_CVPR_2021_paper.pdf)]
* `CVPR 2021` Checkerboard Context Model for Efficient Learned Image Compression [[Paper]](https://ieeexplore.ieee.org/document/9577406) [[Code]](https://github.com/JiangWeibeta/Checkerboard-Context-Model-for-Efficient-Learned-Image-Compression)
* `CVPR 2020` Learned Image Compression With Discretized Gaussian Mixture Likelihoods and Attention Modules [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cheng_Learned_Image_Compression_With_Discretized_Gaussian_Mixture_Likelihoods_and_Attention_CVPR_2020_paper.pdf)] [[code](https://github.com/JooyoungLeeETRI/CA_Entropy_Model)]
* `SPL 2020` Variable rate deep image compression with modulated autoencoder [[Paper]](https://arxiv.org/pdf/1912.05526.pdf)
* `CVPR 2019` Practical Full Resolution Learned Lossless Image Compression [[Paper](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/385576/1/Mentzer_Practical_Full_Resolution_Learned_Lossless_Image_Compression_CVPR_2019_paper.pdf)]
* `ICCV 2019` Variable Rate Deep Image Compression With a Conditional Autoencoder [[Paper]](https://openaccess.thecvf.com/content_ICCV_2019/html/Choi_Variable_Rate_Deep_Image_Compression_With_a_Conditional_Autoencoder_ICCV_2019_paper.html)
* `NIPS 2018` Joint Autoregressive and Hierarchical Priors for Learned Image Compression [[Paper](https://proceedings.neurips.cc/paper/2018/file/53edebc543333dfbf7c5933af792c9c4-Paper.pdf)]
* `ICLR 2018` Variational image compression with a scale hyperprior [[Paper]](https://openreview.net/forum?id=rkcQFMZRb) [[Code]](https://paperswithcode.com/paper/variational-image-compression-with-a-scale)

## Video Compression
* `CVPR 2023` Hierarchical B-frame Video Compression Using Two-Layer CANF without Motion Coding [[Paper]()]
* `CVPR 2023` Motion Information Propagation for Neural Video Compression [[Paper]()]
* `CVPR 2023` Neural Video Compression with Diverse Contexts [[Paper]()]
* `CVPR 2023` Video Compression with Entropy-Constrained Neural Representations [[Paper]()]
* `ECCV 2022` CANF-VC: Conditional Augmented Normalizing Flows for Video Compression[[Paper](https://arxiv.org/pdf/2207.05315.pdf)]
* `ECCV 2022` Neural video compression using gans for detail synthesis and propagation [[Paper](https://arxiv.org/pdf/2107.12038.pdf)]
* `CVPR 2022` LSVC: a learning-based stereo video compression framework [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_LSVC_A_Learning-Based_Stereo_Video_Compression_Framework_CVPR_2022_paper.pdf)]
* `CVPR 2021` FVC: A new framework towards deep video compression in feature space [[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Hu_FVC_A_New_Framework_Towards_Deep_Video_Compression_in_Feature_CVPR_2021_paper.pdf)]
* `ECCV 2020` Improving Deep Video Compression by Resolution-adaptive Flow Coding [[Paper](https://arxiv.org/pdf/2009.05982.pdf)]
* `ECCV 2020` Content Adaptive and Error Propagation Aware Deep Video Compression [[Paper](https://arxiv.org/pdf/2003.11282.pdf)]
* `CVPR 2020` Scale-space flow for end-to-end optimized video compression [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Agustsson_Scale-Space_Flow_for_End-to-End_Optimized_Video_Compression_CVPR_2020_paper.pdf)]
* `CVPR 2020` Learning for Video Compression with Hierarchical Quality and Recurrent Enhancement [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_Learning_for_Video_Compression_With_Hierarchical_Quality_and_Recurrent_Enhancement_CVPR_2020_paper.pdf)]
* `CVPR 2020` M-LVC: Multiple Frames Prediction for Learned Video Compression [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lin_M-LVC_Multiple_Frames_Prediction_for_Learned_Video_Compression_CVPR_2020_paper.pdf)]
* `ICCV 2019` Learned video compression [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Rippel_Learned_Video_Compression_ICCV_2019_paper.pdf)]
* `ICCV 2019` Video Compression With Rate-Distortion Autoencoders [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Habibian_Video_Compression_With_Rate-Distortion_Autoencoders_ICCV_2019_paper.pdf)]
* `ICCV 2019` Non-Local ConvLSTM for Video Compression Artifact Reduction [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Non-Local_ConvLSTM_for_Video_Compression_Artifact_Reduction_ICCV_2019_paper.pdf)]
* `ICCV 2019` Neural Inter-Frame Compression for Video Coding [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Djelouah_Neural_Inter-Frame_Compression_for_Video_Coding_ICCV_2019_paper.pdf)]
* `CVPR 2019` Dvc: An end-to-end deep video compression framework [[Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Lu_DVC_An_End-To-End_Deep_Video_Compression_Framework_CVPR_2019_paper.pdf)]
* `CVPR 2019` Learning Image and Video Compression through Spatial-Temporal Energy Compaction [[Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Cheng_Learning_Image_and_Video_Compression_Through_Spatial-Temporal_Energy_Compaction_CVPR_2019_paper.pdf)]
* `IJCV 2019` Video Enhancement with Task-Oriented Flow [[Paper](https://arxiv.org/pdf/1711.09078.pdf)]
### Based on Super Resolution
* `CPVR 2022` Super-Resolution Based Video Coding Scheme [[Paper](https://openaccess.thecvf.com/content/CVPR2022W/CLIC/html/Cho_Super-Resolution_Based_Video_Coding_Scheme_CVPRW_2022_paper.html)]
## Security
* `CVPR 2023` Backdoor Attacks Against Deep Image Compression via Adaptive Frequency Trigger [[Paper](https://arxiv.org/pdf/2302.14677.pdf)]
* `Arxiv` Towards Robust Neural Image Compression: Adversarial Attack and Model Finetuning [[Paper](https://arxiv.org/pdf/2112.08691.pdf)]

## Awesome Library
* `CompressAI` [[Page/Code](https://github.com/InterDigitalInc/CompressAI)]

## Previous Paper List
* `Image and Video Coding` [[github](https://github.com/flyywh/Image-compression-and-video-coding)], last updation 2018-Aug
