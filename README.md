# awesome-AutoML-and-Lightweight-Models with stars

A list of high-quality (newest) AutoML works and lightweight models including **1.) Neural Architecture Search**, **2.) Lightweight Structures**, **3.) Model Compression, Quantization and Acceleration**, **4.) Hyperparameter Optimization**, **5.) Automated Feature Engineering**.

This repo is aimed to provide the info for AutoML research (especially for the lightweight models). Welcome to PR the works (papers, repositories) that are missed by the repo.

## 1.) Neural Architecture Search

### **\[Papers]**

**Gradient:**

* [When NAS Meets Robustness: In Search of Robust Architectures against Adversarial Attacks](https://arxiv.org/abs/1911.10695) | \[**CVPR 2020**]
  * [gmh14/RobNets](https://github.com/gmh14/RobNets) ⭐ 126 | 🐛 10 | 🌐 Python | 📅 2020-10-21 | \[Pytorch]

* [Searching for A Robust Neural Architecture in Four GPU Hours](https://xuanyidong.com/publication/cvpr-2019-gradient-based-diff-sampler/) | \[**CVPR 2019**]
  * [D-X-Y/GDAS](https://github.com/D-X-Y/GDAS) ⭐ 1,582 | 🐛 15 | 🌐 Python | 📅 2022-04-24 | \[Pytorch]

* [ASAP: Architecture Search, Anneal and Prune](https://arxiv.org/abs/1904.04123) | \[2019/04]

* [Single-Path NAS: Designing Hardware-Efficient ConvNets in less than 4 Hours](https://arxiv.org/abs/1904.02877#) | \[2019/04]
  * [dstamoulis/single-path-nas](https://github.com/dstamoulis/single-path-nas) ⭐ 394 | 🐛 16 | 🌐 Python | 📅 2020-12-14 | \[Tensorflow]

* [Automatic Convolutional Neural Architecture Search for Image Classification Under Different Scenes](https://ieeexplore.ieee.org/document/8676019) | \[**IEEE Access 2019**]

* [sharpDARTS: Faster and More Accurate Differentiable Architecture Search](https://arxiv.org/abs/1903.09900) | \[2019/03]

* [Learning Implicitly Recurrent CNNs Through Parameter Sharing](https://arxiv.org/abs/1902.09701) | \[**ICLR 2019**]
  * [lolemacs/soft-sharing](https://github.com/lolemacs/soft-sharing) ⭐ 70 | 🐛 2 | 🌐 Python | 📅 2020-12-15 | \[Pytorch]

* [Probabilistic Neural Architecture Search](https://arxiv.org/abs/1902.05116) | \[2019/02]

* [Auto-DeepLab: Hierarchical Neural Architecture Search for Semantic Image Segmentation](https://arxiv.org/abs/1901.02985) | \[2019/01]

* [SNAS: Stochastic Neural Architecture Search](https://arxiv.org/abs/1812.09926) | \[**ICLR 2019**]

* [FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search](https://arxiv.org/abs/1812.03443) | \[2018/12]

* [Neural Architecture Optimization](http://papers.nips.cc/paper/8007-neural-architecture-optimization) | \[**NIPS 2018**]
  * [renqianluo/NAO](https://github.com/renqianluo/NAO) ⭐ 285 | 🐛 11 | 🌐 Python | 📅 2021-01-11 | \[Tensorflow]

* [DARTS: Differentiable Architecture Search](https://arxiv.org/abs/1806.09055) | \[2018/06]
  * [quark0/darts](https://github.com/quark0/darts) ⭐ 3,996 | 🐛 95 | 🌐 Python | 📅 2021-01-03 | \[Pytorch]
  * [khanrc/pt.darts](https://github.com/khanrc/pt.darts) ⭐ 451 | 🐛 33 | 🌐 Python | 📅 2022-07-19 | \[Pytorch]
  * [dragen1860/DARTS-PyTorch](https://github.com/dragen1860/DARTS-PyTorch) ⭐ 80 | 🐛 4 | 🌐 Python | 📅 2019-03-01 | \[Pytorch]

**Reinforcement Learning:**

* [Template-Based Automatic Search of Compact Semantic Segmentation Architectures](https://arxiv.org/abs/1904.02365) | \[2019/04]

* [Understanding Neural Architecture Search Techniques](https://arxiv.org/abs/1904.00438) | \[2019/03]

* [Fast, Accurate and Lightweight Super-Resolution with Neural Architecture Search](https://arxiv.org/abs/1901.07261) | \[2019/01]
  * [falsr/FALSR](https://github.com/falsr/FALSR) ⭐ 681 | 🐛 6 | 🌐 Python | 📅 2022-11-21 | \[Tensorflow]

* [Multi-Objective Reinforced Evolution in Mobile Neural Architecture Search](https://arxiv.org/abs/1901.01074) | \[2019/01]
  * [moremnas/MoreMNAS](https://github.com/moremnas/MoreMNAS) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2020-07-06 | \[Tensorflow]

* [ProxylessNAS: Direct Neural Architecture Search on Target Task and Hardware](https://arxiv.org/abs/1812.00332) | \[**ICLR 2019**]
  * [MIT-HAN-LAB/ProxylessNAS](https://github.com/MIT-HAN-LAB/ProxylessNAS) ⭐ 1,448 | 🐛 2 | 🌐 C++ | 📅 2024-08-30 | \[Pytorch, Tensorflow]

* [Transfer Learning with Neural AutoML](http://papers.nips.cc/paper/8056-transfer-learning-with-neural-automl) | \[**NIPS 2018**]

* [Learning Transferable Architectures for Scalable Image Recognition](https://arxiv.org/abs/1707.07012) | \[2018/07]
  * [tensorflow/models/research/slim/nets/nasnet](https://github.com/tensorflow/models/tree/master/research/slim/nets/nasnet) ⭐ 77,658 | 🐛 1,274 | 🌐 Python | 📅 2026-09-09 | \[Tensorflow]
  * [wandering007/nasnet-pytorch](https://github.com/wandering007/nasnet-pytorch) ⭐ 75 | 🐛 2 | 🌐 Python | 📅 2020-12-05 | \[Pytorch]

* [MnasNet: Platform-Aware Neural Architecture Search for Mobile](https://arxiv.org/abs/1807.11626) | \[2018/07]
  * [AnjieZheng/MnasNet-PyTorch](https://github.com/AnjieZheng/MnasNet-PyTorch) ⭐ 275 | 🐛 4 | 🌐 Python | 📅 2018-08-15 | \[Pytorch]

* [Practical Block-wise Neural Network Architecture Generation](https://arxiv.org/abs/1708.05552) | \[**CVPR 2018**]

* [Efficient Neural Architecture Search via Parameter Sharing](https://arxiv.org/abs/1802.03268) | \[**ICML 2018**]
  * [carpedm20/ENAS-pytorch](https://github.com/carpedm20/ENAS-pytorch) ⭐ 2,718 | 🐛 40 | 🌐 Python | 📅 2023-07-06 | \[Pytorch]
  * [melodyguan/enas](https://github.com/melodyguan/enas) ⭐ 1,578 | 🐛 84 | 🌐 Python | 📅 2019-06-18 | \[Tensorflow]

* [Efficient Architecture Search by Network Transformation](https://arxiv.org/abs/1707.04873) | \[**AAAI 2018**]

**Evolutionary Algorithm:**

* [Single Path One-Shot Neural Architecture Search with Uniform Sampling](https://arxiv.org/abs/1904.00420) | \[2019/04]

* [DetNAS: Neural Architecture Search on Object Detection](https://arxiv.org/abs/1903.10979) | \[2019/03]

* [The Evolved Transformer](https://arxiv.org/abs/1901.11117) | \[2019/01]

* [Designing neural networks through neuroevolution](https://www.nature.com/articles/s42256-018-0006-z) | \[**Nature Machine Intelligence 2019**]

* [EAT-NAS: Elastic Architecture Transfer for Accelerating Large-scale Neural Architecture Search](https://arxiv.org/abs/1901.05884) | \[2019/01]

* [Efficient Multi-objective Neural Architecture Search via Lamarckian Evolution](https://arxiv.org/abs/1804.09081) | \[**ICLR 2019**]

**SMBO:**

* [MFAS: Multimodal Fusion Architecture Search](https://arxiv.org/abs/1903.06496) | \[**CVPR 2019**]

* [DPP-Net: Device-aware Progressive Search for Pareto-optimal Neural Architectures](https://arxiv.org/abs/1806.08198) | \[**ECCV 2018**]

* [Progressive Neural Architecture Search](https://arxiv.org/abs/1712.00559) | \[**ECCV 2018**]
  * [chenxi116/PNASNet.pytorch](https://github.com/chenxi116/PNASNet.pytorch) ⭐ 321 | 🐛 3 | 🌐 Python | 📅 2022-08-04 | \[Pytorch]
  * [titu1994/progressive-neural-architecture-search](https://github.com/titu1994/progressive-neural-architecture-search) ⭐ 118 | 🐛 1 | 🌐 Python | 📅 2019-02-11 | \[Keras, Tensorflow]

**Random Search:**

* [Exploring Randomly Wired Neural Networks for Image Recognition](https://arxiv.org/abs/1904.01569) | \[2019/04]

* [Searching for Efficient Multi-Scale Architectures for Dense Image Prediction](http://papers.nips.cc/paper/8087-searching-for-efficient-multi-scale-architectures-for-dense-image-prediction) | \[**NIPS 2018**]

**Hypernetwork:**

* [Graph HyperNetworks for Neural Architecture Search](https://arxiv.org/abs/1810.05749) | \[**ICLR 2019**]

**Bayesian Optimization:**

* [Inductive Transfer for Neural Architecture Optimization](https://arxiv.org/abs/1903.03536) | \[2019/03]

**Partial Order Pruning**

* [Partial Order Pruning: for Best Speed/Accuracy Trade-off in Neural Architecture Search](https://arxiv.org/abs/1903.03777) | \[**CVPR 2019**]
  * [lixincn2015/Partial-Order-Pruning](https://github.com/lixincn2015/Partial-Order-Pruning) ⭐ 147 | 🐛 1 | 🌐 Cuda | 📅 2020-09-23 | \[Caffe]

**Knowledge Distillation**

* [Improving Neural Architecture Search Image Classifiers via Ensemble Learning](https://arxiv.org/abs/1903.06236) | \[2019/03]

### **\[Projects]**

* [MindsDB](https://github.com/mindsdb/mindsdb) ⭐ 39,720 | 🐛 7 | 🌐 Makefile | 📅 2026-09-09 | \[Python]
* [Microsoft/nni](https://github.com/Microsoft/nni) ⚠️ Archived | \[Python]

## 2.) Lightweight Structures

### **\[Papers]**

**Image Classification:**

* [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks](http://proceedings.mlr.press/v97/tan19a.html) | \[**ICML 2019**]
  * [lukemelas/EfficientNet-PyTorch](https://github.com/lukemelas/EfficientNet-PyTorch) ⭐ 8,217 | 🐛 167 | 🌐 Python | 📅 2022-04-08 | \[Pytorch]
  * [tensorflow/tpu/models/official/efficientnet/](https://github.com/tensorflow/tpu/tree/master/models/official/efficientnet) ⭐ 5,276 | 🐛 320 | 🌐 Jupyter Notebook | 📅 2026-06-22 | \[Tensorflow]

* [Searching for MobileNetV3](https://arxiv.org/abs/1905.02244) | \[2019/05]
  * [kuan-wang/pytorch-mobilenet-v3](https://github.com/kuan-wang/pytorch-mobilenet-v3) ⭐ 807 | 🐛 9 | 🌐 Python | 📅 2019-06-23 | \[Pytorch]
  * [leaderj1001/MobileNetV3-Pytorch](https://github.com/leaderj1001/MobileNetV3-Pytorch) ⭐ 299 | 🐛 7 | 🌐 Python | 📅 2019-07-04 | \[Pytorch]

**Semantic Segmentation:**

* [CGNet: A Light-weight Context Guided Network for Semantic Segmentation](https://arxiv.org/abs/1811.08201) | \[2019/04]
  * [wutianyiRosun/CGNet](https://github.com/wutianyiRosun/CGNet) ⭐ 278 | 🐛 7 | 🌐 Python | 📅 2022-02-16 | \[Pytorch]

* [ESPNetv2: A Light-weight, Power Efficient, and General Purpose Convolutional Neural Network](https://arxiv.org/abs/1811.11431) | \[2018/11]
  * [sacmehta/ESPNetv2](https://github.com/sacmehta/ESPNetv2) ⭐ 455 | 🐛 2 | 🌐 Python | 📅 2021-01-29 | \[Pytorch]

* [ESPNet: Efficient Spatial Pyramid of Dilated Convolutions for Semantic Segmentation](https://sacmehta.github.io/ESPNet/) | \[**ECCV 2018**]
  * [sacmehta/ESPNet](https://github.com/sacmehta/ESPNet/) ⭐ 542 | 🐛 9 | 🌐 Python | 📅 2023-06-30 | \[Pytorch]

* [BiSeNet: Bilateral Segmentation Network for Real-time Semantic Segmentation](https://arxiv.org/abs/1808.00897) | \[**ECCV 2018**]
  * [ycszen/TorchSeg](https://github.com/ycszen/TorchSeg) ⭐ 1,409 | 🐛 41 | 🌐 Python | 📅 2020-03-11 | \[Pytorch]
  * [ooooverflow/BiSeNet](https://github.com/ooooverflow/BiSeNet) ⭐ 409 | 🐛 23 | 🌐 Python | 📅 2020-03-13 | \[Pytorch]

* [ERFNet: Efficient Residual Factorized ConvNet for Real-time Semantic Segmentation](http://www.robesafe.uah.es/personal/eduardo.romera/pdfs/Romera17tits.pdf) | \[**T-ITS 2017**]
  * [Eromera/erfnet\_pytorch](https://github.com/Eromera/erfnet_pytorch) ⭐ 445 | 🐛 14 | 🌐 Python | 📅 2019-12-05 | \[Pytorch]

**Object Detection:**

* [ThunderNet: Towards Real-time Generic Object Detection](https://arxiv.org/abs/1903.11752) | \[2019/03]

* [Pooling Pyramid Network for Object Detection](https://arxiv.org/abs/1807.03284) | \[2018/09]
  * [tensorflow/models](https://github.com/tensorflow/models/tree/master/research/object_detection/models) ⭐ 77,658 | 🐛 1,274 | 🌐 Python | 📅 2026-09-09 | \[Tensorflow]

* [Tiny-DSOD: Lightweight Object Detection for Resource-Restricted Usages](https://arxiv.org/abs/1807.11013) | \[**BMVC 2018**]
  * [lyxok1/Tiny-DSOD](https://github.com/lyxok1/Tiny-DSOD) ⭐ 231 | 🐛 20 | 🌐 C++ | 📅 2019-06-07 | \[Caffe]

* [Pelee: A Real-Time Object Detection System on Mobile Devices](https://arxiv.org/abs/1804.06882) | \[**NeurIPS 2018**]
  * [Robert-JunWang/Pelee](https://github.com/Robert-JunWang/Pelee) ⭐ 884 | 🐛 54 | 🌐 Jupyter Notebook | 📅 2019-01-04 | \[Caffe]
  * [Robert-JunWang/PeleeNet](https://github.com/Robert-JunWang/PeleeNet) ⭐ 154 | 🐛 8 | 🌐 Python | 📅 2019-02-26 | \[Pytorch]

* [Receptive Field Block Net for Accurate and Fast Object Detection](https://eccv2018.org/openaccess/content_ECCV_2018/papers/Songtao_Liu_Receptive_Field_Block_ECCV_2018_paper.pdf) | \[**ECCV 2018**]
  * [ruinmessi/RFBNet](https://github.com/ruinmessi/RFBNet) ⭐ 1,418 | 🐛 58 | 🌐 Python | 📅 2021-11-02 | \[Pytorch]
  * [lzx1413/PytorchSSD](https://github.com/lzx1413/PytorchSSD) ⭐ 704 | 🐛 44 | 🌐 Python | 📅 2020-03-27 | \[Pytorch]
  * [ShuangXieIrene/ssds.pytorch](https://github.com/ShuangXieIrene/ssds.pytorch) ⭐ 566 | 🐛 40 | 🌐 Python | 📅 2020-08-18 | \[Pytorch]

* [FSSD: Feature Fusion Single Shot Multibox Detector](https://arxiv.org/abs/1712.00960) | \[2017/12]
  * [lzx1413/PytorchSSD](https://github.com/lzx1413/PytorchSSD) ⭐ 704 | 🐛 44 | 🌐 Python | 📅 2020-03-27 | \[Pytorch]
  * [ShuangXieIrene/ssds.pytorch](https://github.com/ShuangXieIrene/ssds.pytorch) ⭐ 566 | 🐛 40 | 🌐 Python | 📅 2020-08-18 | \[Pytorch]
  * [dlyldxwl/fssd.pytorch](https://github.com/dlyldxwl/fssd.pytorch) ⭐ 68 | 🐛 9 | 🌐 Python | 📅 2019-03-19 | \[Pytorch]

* [Feature Pyramid Networks for Object Detection](https://arxiv.org/abs/1612.03144) | \[**CVPR 2017**]
  * [tensorflow/models](https://github.com/tensorflow/models/tree/master/research/object_detection/models) ⭐ 77,658 | 🐛 1,274 | 🌐 Python | 📅 2026-09-09 | \[Tensorflow]

## 3.) Model Compression & Acceleration

### **\[Papers]**

**Pruning:**

* [The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks](https://arxiv.org/abs/1803.03635) | \[**ICLR 2019**]
  * [google-research/lottery-ticket-hypothesis](https://github.com/google-research/lottery-ticket-hypothesis) ⚠️ Archived | \[Tensorflow]

* [Rethinking the Value of Network Pruning](https://arxiv.org/abs/1810.05270) | \[**ICLR 2019**]

* [Slimmable Neural Networks](https://openreview.net/pdf?id=H1gMCsAqY7) | \[**ICLR 2019**]
  * [JiahuiYu/slimmable\_networks](https://github.com/JiahuiYu/slimmable_networks) ⭐ 928 | 🐛 13 | 🌐 Python | 📅 2023-03-09 | \[Pytorch]

* [AMC: AutoML for Model Compression and Acceleration on Mobile Devices](https://arxiv.org/abs/1802.03494) | \[**ECCV 2018**]
  * [AutoML for Model Compression (AMC): Trials and Tribulations](https://github.com/NervanaSystems/distiller/wiki/AutoML-for-Model-Compression-\(AMC\):-Trials-and-Tribulations) | \[Pytorch]

* [Learning Efficient Convolutional Networks through Network Slimming](https://arxiv.org/abs/1708.06519) | \[**ICCV 2017**]
  * [foolwood/pytorch-slimming](https://github.com/foolwood/pytorch-slimming) ⭐ 573 | 🐛 16 | 🌐 Python | 📅 2019-05-13 | \[Pytorch]

* [Channel Pruning for Accelerating Very Deep Neural Networks](https://arxiv.org/abs/1707.06168) | \[**ICCV 2017**]
  * [yihui-he/channel-pruning](https://github.com/yihui-he/channel-pruning) ⭐ 1,086 | 🐛 21 | 🌐 Python | 📅 2024-05-02 | \[Caffe]

* [Pruning Convolutional Neural Networks for Resource Efficient Inference](https://arxiv.org/abs/1611.06440) | \[**ICLR 2017**]
  * [jacobgil/pytorch-pruning](https://github.com/jacobgil/pytorch-pruning) ⭐ 884 | 🐛 31 | 🌐 Python | 📅 2019-07-12 | \[Pytorch]

* [Pruning Filters for Efficient ConvNets](https://arxiv.org/abs/1608.08710) | \[**ICLR 2017**]

**Quantization:**

* [Understanding Straight-Through Estimator in Training Activation Quantized Neural Nets](https://arxiv.org/abs/1903.05662) | \[**ICLR 2019**]

* [Quantization and Training of Neural Networks for Efficient Integer-Arithmetic-Only Inference](http://openaccess.thecvf.com/content_cvpr_2018/html/Jacob_Quantization_and_Training_CVPR_2018_paper.html) | \[**CVPR 2018**]

* [Quantizing deep convolutional networks for efficient inference: A whitepaper](https://arxiv.org/abs/1806.08342) | \[2018/06]

* [PACT: Parameterized Clipping Activation for Quantized Neural Networks](https://arxiv.org/abs/1805.06085) | \[2018/05]

* [Post-training 4-bit quantization of convolution networks for rapid-deployment](https://arxiv.org/abs/1810.05723) | \[**ICML 2018**]

* [WRPN: Wide Reduced-Precision Networks](https://arxiv.org/abs/1709.01134) | \[**ICLR 2018**]

* [Incremental Network Quantization: Towards Lossless CNNs with Low-Precision Weights](https://arxiv.org/abs/1702.03044) | \[**ICLR 2017**]

* [DoReFa-Net: Training Low Bitwidth Convolutional Neural Networks with Low Bitwidth Gradients](https://arxiv.org/abs/1606.06160) | \[2016/06]

* [Estimating or Propagating Gradients Through Stochastic Neurons for Conditional Computation](https://arxiv.org/abs/1308.3432) | \[2013/08]

**Knowledge Distillation**

* [Apprentice: Using Knowledge Distillation Techniques To Improve Low-Precision Network Accuracy](https://arxiv.org/abs/1711.05852) | \[**ICLR 2018**]

* [Model compression via distillation and quantization](https://arxiv.org/abs/1802.05668) | \[**ICLR 2018**]

**Acceleration:**

* [Fast Algorithms for Convolutional Neural Networks](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Lavin_Fast_Algorithms_for_CVPR_2016_paper.pdf) | \[**CVPR 2016**]
  * [andravin/wincnn](https://github.com/andravin/wincnn) ⭐ 628 | 🐛 6 | 🌐 Python | 📅 2026-02-09 | \[Python]

### **\[Projects]**

* [Tencent/PocketFlow](https://github.com/Tencent/PocketFlow) ⭐ 2,908 | 🐛 75 | 🌐 Python | 📅 2023-03-31 | \[Tensorflow]
* [aaron-xichen/pytorch-playground](https://github.com/aaron-xichen/pytorch-playground) ⭐ 2,719 | 🐛 11 | 🌐 Python | 📅 2022-11-22 | \[Pytorch]
* [NervanaSystems/distiller](https://github.com/NervanaSystems/distiller/) | \[Pytorch]

### **\[Tutorials/Blogs]**

* [Introducing the CVPR 2018 On-Device Visual Intelligence Challenge](https://research.googleblog.com/search/label/On-device%20Learning)

## 4.) Hyperparameter Optimization

### **\[Papers]**

* [Tuning Hyperparameters without Grad Students: Scalable and Robust Bayesian Optimisation with Dragonfly](https://arxiv.org/abs/1903.06694) | \[2019/03]
  * [dragonfly/dragonfly](https://github.com/dragonfly/dragonfly) ⭐ 894 | 🐛 43 | 🌐 Python | 📅 2023-06-19

* [Efficient High Dimensional Bayesian Optimization with Additivity and Quadrature Fourier Features](https://papers.nips.cc/paper/8115-efficient-high-dimensional-bayesian-optimization-with-additivity-and-quadrature-fourier-features) | \[**NeurIPS 2018**]

* [Google vizier: A service for black-box optimization](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/46180.pdf) | \[**SIGKDD 2017**]

* [On Hyperparameter Optimization of Machine Learning Algorithms: Theory and Practice](https://arxiv.org/abs/2007.15745) | \[**Neurocomputing 2020**]
  * [LiYangHart/Hyperparameter-Optimization-of-Machine-Learning-Algorithms](https://github.com/LiYangHart/Hyperparameter-Optimization-of-Machine-Learning-Algorithms) ⭐ 1,343 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-09-22

### **\[Projects]**

* [Microsoft/nni](https://github.com/Microsoft/nni) ⚠️ Archived | \[Python]
* [LiYangHart/Hyperparameter-Optimization-of-Machine-Learning-Algorithms](https://github.com/LiYangHart/Hyperparameter-Optimization-of-Machine-Learning-Algorithms) ⭐ 1,343 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-09-22 | \[Python]
* [dragonfly/dragonfly](https://github.com/dragonfly/dragonfly) ⭐ 894 | 🐛 43 | 🌐 Python | 📅 2023-06-19 | \[Python]
* [BoTorch](https://botorch.org/) | \[PyTorch]
* [Ax (Adaptive Experimentation Platform)](https://ax.dev/) | \[PyTorch]

### **\[Tutorials/Blogs]**

* [Hyperparameter tuning in Cloud Machine Learning Engine using Bayesian Optimization](https://cloud.google.com/blog/products/gcp/hyperparameter-tuning-cloud-machine-learning-engine-using-bayesian-optimization)

* [Overview of Bayesian Optimization](https://soubhikbarari.github.io/blog/2016/09/14/overview-of-bayesian-optimization)

* [Bayesian optimization](http://krasserm.github.io/2018/03/21/bayesian-optimization/)
  * [krasserm/bayesian-machine-learning](https://github.com/krasserm/bayesian-machine-learning) ⭐ 1,917 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2026-07-12 | \[Python]

## 5.) Automated Feature Engineering

## Model Analyzer

* [Lyken17/pytorch-OpCounter](https://github.com/Lyken17/pytorch-OpCounter) ⭐ 5,077 | 🐛 84 | 🌐 Python | 📅 2024-07-08 | \[Pytorch]

* [sksq96/pytorch-summary](https://github.com/sksq96/pytorch-summary) ⭐ 4,052 | 🐛 141 | 🌐 Python | 📅 2024-03-02 | \[Pytorch]

* [sovrasov/flops-counter.pytorch](https://github.com/sovrasov/flops-counter.pytorch) ⭐ 2,982 | 🐛 29 | 🌐 Python | 📅 2025-08-20 | \[Pytorch]

* [Netscope CNN Analyzer](https://chakkritte.github.io/netscope/quickstart.html) | \[Caffe]

## References

* [mrgloom/awesome-semantic-segmentation](https://github.com/mrgloom/awesome-semantic-segmentation) ⭐ 10,846 | 🐛 17 | 📅 2021-05-08
* [amusi/awesome-object-detection](https://github.com/amusi/awesome-object-detection) ⭐ 7,502 | 🐛 7 | 📅 2022-12-17
* [hibayesian/awesome-automl-papers](https://github.com/hibayesian/awesome-automl-papers) ⭐ 4,157 | 🐛 2 | 📅 2024-06-11
* [handong1587/handong1587.github.io](https://github.com/handong1587/handong1587.github.io/tree/master/_posts/deep_learning) ⭐ 3,138 | 🐛 3 | 🌐 CSS | 📅 2023-11-22
* [LITERATURE ON NEURAL ARCHITECTURE SEARCH](https://www.ml4aad.org/automl/literature-on-neural-architecture-search/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-09._
