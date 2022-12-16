# 挖坑:深度神经网络与去噪
## 传统去噪算法
基于概率模型：maximum likelihood estimation

* [通过最大似然估计将统计模型与观测数据进行匹配的Python模块。](https://github.com/Samurais/maxlike)
* [Collect resources for maximum by 王海良@chatopera](https://github.com/hailiang-wang/maxlike)
* [一些经典OpenCV经典传统方法的实现](https://github.com/adraper2/Noise_Reduction_Research-STS499),包含了Nonlocal-means,bilateral, and 3x3 mean filters)
* [Non-local means算法的另外一种实现](https://github.com/antimattercorrade/Image_Denoising)，尤其是对滑动窗口的实现，详细
* 有关混合地震去噪的项目，<span style="color: red">matlab代码</span>有比较详细的注释。[Wavelet Block-Thresholding Denoising
](https://github.com/smousavi05/Denoising-BTwavelet)
* 自适应曲线阈值算法([Adaptive Curvelet Thresholding](https://github.com/NEslahi/ACT)),针对白噪声和彩色噪声问题。<span style="color: red">in Matlab.</span>

## 基于统计学习的图像分类

* [Statistical-Learning---Image-Segmentation](https://github.com/RenXiangyuan/Statistical-Learning---Image-Segmentation)
* [girishbathala的统计学习模型网站](https://github.com/girishbathala/statistical-learning-image-classification)
* [Digital-Signal-Processing-labs](https://github.com/leonardopedroso/Digital-Signal-Processing-labs)
* [Maximum Likelihood Training for Score-Based Diffusion ODEs by High-Order Denoising Score Matching (ICML 2022)
](https://github.com/LuChengTHU/mle_score_ode)
* [Statistical-Learning---Image-Segmentation by RenXiangyuan](https://github.com/RenXiangyuan/Statistical-Learning---Image-Segmentation)
* [A modification of the Recurrent Inference Machine (RIM)](https://github.com/EmaadKhwaja/Deep-Learning-Denoising)
## 数据库大全
* 一个使用分布式种子存储的数据库大全网站，宣称拥有127.15TB的研究数据
[academictorrents](https://academictorrents.com/)
* 用来做denoise的一个puzzle图像数据库(数据隐写技术).[website](https://drive.google.com/drive/folders/1xOgnY6dBTahUjqykN9HWYeCO67h_ax8S)
* [Datasets for super-image](https://github.com/eugenesiow/super-image-data)

## TF Traing Tutroial For Beginners
* Resnet(tensorflow) for training ur own data，数据来源是天池赛的比赛数据。
[website](https://github.com/Perseus1996/resnet-for-ur-own-data)

## 深度学习网络去噪
RED-Net
* Image Restoration Using Very Deep Convolutional Encoder-Decoder Networks with Symmetric Skip Connections
    - [官方代码,Matlab](https://bitbucket.org/chhshen/image-denoising/src/master/) 
    - [Pytorch 版本](https://github.com/yjn870/REDNet-pytorch),但是没有给出详细的训练方法，作者也没有解释
    * [Opendenoising](https://github.com/opendenoising/opendenoising-benchmark)有和RED-Net对比Benchmark,里面有比较详细的载入数据、分割数据和转换格式与加噪的过程
    * [ConsensusNet](https://github.com/jhchoi0908/consensusNet),在对比REDNet时，有相关的实现方法。但是写得比较难懂。
* Raphael Couturier, Gilles Perrot, Michel Salomon. Image Denoising Using a Deep Encoder-Decoder
Network with Skip Connections. International Conference on Neural Information Processing, Dec
2018, Siem Reap, Cambodia. pp.554 - 565. ffhal-02182820f
    - [PDF WEBSITE](https://hal.archives-ouvertes.fr/hal-02182820/document)




