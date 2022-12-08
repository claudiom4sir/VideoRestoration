# Video restoration based on deep learning: a comprehensive survey 
*[Claudio Rota](https://scholar.google.com/citations?user=HwPPoh4AAAAJ&hl=en), [Marco Buzzelli](https://scholar.google.com/citations?hl=en&user=kSFvKBoAAAAJ), [Simone Bianco](https://scholar.google.com/citations?hl=en&user=P08LSD0AAAAJ), [Raimondo Schettini](https://scholar.google.com/citations?hl=en&user=ue60cV0AAAAJ)*

*Artificial Intelligence Review, Springer Nature*, 2022

[[Open Access PDF](https://link.springer.com/article/10.1007/s10462-022-10302-5)]


## Abstract
Video restoration concerns the recovery of a clean video sequence starting from its degraded version. Diferent video restoration tasks exist, including denoising, deblurring, super-resolution, and reduction of compression artifacts. In this paper, we provide a comprehensive review of the main features of existing video restoration methods based on deep learning. We focus our attention on the main architectural components, strategies for motion handling, and loss functions. We analyze the standard benchmark datasets and use them to summarize the performance of video restoration methods, both in terms of efectiveness and efciency. In conclusion, the main challenges and future research directions in video restoration using deep learning are highlighted.

## Citation

```
@article{rota2022video,
author = {Rota, Claudio and Buzzelli, Marco and Bianco, Simone and Schettini, Raimondo},
year = {2022},
month = {10},
pages = {1-48},
title = {Video restoration based on deep learning: a comprehensive survey},
journal = {Artificial Intelligence Review},
doi = {10.1007/s10462-022-10302-5}
}
```
## Methods for video restoration
|Name|Task(s)|Paper|Code|
|--|--|--|--|
|VESPCN|Super-resolution|Real-time video super-resolution with spatio-temporal networks and motion compensation (CVPR 2017)|[[Pytorch](https://github.com/JuheonYi/VESPCN-PyTorch)]|
|DBN|Deblurring|Deep Video Deblurring for Hand-held Cameras (CVPR 2017)|[[Torch](https://github.com/shuochsu/DeepVideoDeblurring)]|
|STRCNN|Deblurring|Online video deblurring via dynamic temporal blending network (ICCV 2017)|:x:|
|DBLRGAN|Deblurring|Adversarial spatio-temporal learning for video deblurring (TIP 2018)|:x:|
|DUF|Super-resolution|Deep Video Super-Resolution Network Using Dynamic Upsampling FiltersWithout Explicit Motion Compensation (CVPR 2018)|[[TensorFlow](https://github.com/yhjo09/VSR-DUF)]|
|MFQE|Compression artifact reduction|Multi-Frame Quality Enhancement for Compressed Video (CVPR 2018)|[[TensorFlow](https://github.com/ryangBUAA/MFQE)]|
|ToFlow|Denoising, Super-resolution, Compression artifact reduction|Video Enhancement with Task-Oriented Flow (IJCV 2019)|[[Torch](https://github.com/anchen1011/toflow)]|
|DVDNet|Denoising|Dvdnet: A fast network for deep video denoising (ICIP 2019)|[[Pytorch](https://github.com/m-tassano/dvdnet)]|
|MFQE2.0|Compression artifact reduction|MFQE 2.0: A New Approach for Multi-frame Quality Enhancement on Compressed Video (TPAMI 2019)|[[TensorFlow](https://github.com/RyanXingQL/MFQEv2.0)]
|STFAN|Deblurring|Spatio-Temporal Filter Adaptive Network for Video Deblurring (ICCV 2019)|[[Pytorch](https://github.com/sczhou/STFAN)]
|EDVR|Deblurring, Super-resolution|Edvr: Video restoration with enhanced deformable convolutional networks (CVPR 2019)|[[Pytorch](https://github.com/open-mmlab/mmediting)]|
|PFNL|Super-resolution|Progressive Fusion Video Super-Resolution Network via Exploiting Non-Local Spatio-Temporal Correlations (ICCV 2019)|[[Pytorch/TensorFlow](https://github.com/psychopa4/PFNL)]|
|ViDeNN|Denoising|ViDeNN: Deep Blind Video Denoising (CVPR 2019)|[[TensorFlow](https://github.com/clausmichele/ViDeNN)]|
|IFI-RNN|Deblurring|Recurrent neural networks with intra-frame iterations for video deblurring (CVPR 2019)|:x:|
|FITVNet|Denoising|First image then video: A two-stage network for spatiotemporal video denoising (2019)|:x:|
|VNLNet|Denoising|A Non-Local CNN for Video Denoising (ICIP 2019)|:x:|
|NL-ConvLSTM|Compression artifact reduction|Non-local convlstm for video compression artifact reduction (ICCV 2019)|[[Pytorch](https://github.com/xyiyy/NL-ConvLSTM)]|
|MB2D|Deblurring|Blur more to deblur better: Multi-blur2deblur for efficient video deblurring (2020)|:x:|
|FastDVDNet|Denoising|Fastdvdnet: Towards real-time deep video denoising without flow estimation (CVPR 2020)|[[Pytorch](https://github.com/m-tassano/fastdvdnet)]|
|TDAN|Super-resolution|Tdan: Temporally-deformable alignment network for video super-resolution (CVPR 2020)|[[Pytorch](https://github.com/YapengTian/TDAN-VSR-CVPR-2020)]|
|ESTRNN|Deblurring|Efficient spatio-temporal recurrent neural network for video deblurring (ECCV 2020)|[[Pytorch](https://github.com/zzh-tech/ESTRNN)]|
|STDF|Compression artifact reduction|Spatio-temporal deformable convolution for compressed video quality enhancement (AAAI 2020)|[[Pytorch](https://github.com/RyanXingQL/STDF-PyTorch)]|
|MuCAN|Super-resolution|Mucan: Multi-correspondence aggregation network for video super-resolution (ECCV 2020)|[[Pytorch](https://github.com/dvlab-research/Simple-SR)]|
|RViDeNet|Denoising|Supervised raw video denoising with a benchmark dataset on dynamic scenes (CVPR 2020)|[[Pytorch](https://github.com/cao-cong/RViDeNet)]|
|RSDN|Super-resolution|Video super-resolution with recurrent structure-detail network (ECCV 2020)|[[Pytorch](https://github.com/junpan19/RSDN)]|
|CDVD-TSP|Deblurring|Cascaded deep video deblurring using temporal sharpness prior (CVPR 2020)|[[Pytorch](https://github.com/csbhr/CDVD-TSP)]|
|Evrnet|Denoising, Super-resolution, Compression artifact reduction|Evrnet: Efficient video restoration on edge devices (ICM 2021)|:x:|
|MMNet|Denoising|Multiframe-to-multiframe network for video denoising (TOM 2021)|:x:|
|RFDA|Compression artifact reduction|Recursive fusion and deformable spatiotemporal attention for video compression artifact reduction (ICM 2021)|[[Pytorch](https://github.com/zhaominyiz/RFDA-PyTorch)]|
|PVDNet|Deblurring|Recurrent video deblurring with blur-invariant motion estimation and pixel volumes (TOG 2021)|[[Pytorch](https://github.com/codeslake/PVDNet)]|
|MaskDNGAN|Denoising|Multi-Stage Raw Video Denoising with Adversarial Loss and Gradient Mask (ICCP 2021)|[[Pytorch](https://github.com/avinashpaliwal/MaskDnGAN)]|
|PaCNet|Denoising|Patch craft: Video denoising by deep modeling and patch matching (ICCV 2021)|[[Pytorch](https://github.com/grishavak/PaCNet-denoiser)]|
|BasicVSR|Super-resolution|BasicVSR: The search for essential components in video super-resolution and beyond (CVPR 2021)|[[Pytorch](https://github.com/open-mmlab/mmediting)]|
|BasicVSR++|Super-resolution|BasicVSR++: Improving video super-resolution with enhanced propagation and alignment (CVPR 2022)|[[Pytorch](https://github.com/open-mmlab/mmediting)]|




## Datasets for video restoration
|Name|Task(s)|Usage|Repository|
|--|--|--|--|
|GOPRO|Deblurring|Train/Test|[[Link](https://seungjunnah.github.io/Datasets/gopro)]|
|DVD|Deblurring|Train/Test|[[Link](https://www.cs.ubc.ca/labs/imager/tr/2017/DeepVideoDeblurring/)]|
|BSD|Deblurring|Train/Test|[[Link](https://github.com/zzh-tech/ESTRNN)]|
|REDS|Deblurring, Super-resolution|Train/Test|[[Link](https://seungjunnah.github.io/Datasets/reds.html)]|
|Vid4|Super-resolution|Test|[[Link](https://people.csail.mit.edu/celiu/CVPR2011/default.html)]|
|UDM10|Super-resolution|Test|[[Link](https://github.com/psychopa4/PFNL)]|
|SPMCS|Super-resolution|Test|[[Link](https://github.com/jiangsutx/SPMC_VideoSR)]|
|Vimeo90K|Denoising, Super-resolution, Compression artifact resolution|Train/Test|[[Link](http://toflow.csail.mit.edu/)]| 
|MFQEv2|Compression artifact reduction|Train/Test|[[Link](https://github.com/RyanXingQL/MFQEv2.0)]|
|CRVD|Denoising|Train/Test|[[Link](https://github.com/cao-cong/RViDeNet)]|
|Set8|Denoising|Test|[[Link](https://github.com/m-tassano/fastdvdnet)]|
|DAVIS 2017|Denoising|Train/Test|[[Link](https://davischallenge.org/davis2017/code.html)]|


## Contacts
If you have any question, please contact Claudio Rota at c.rota30@campus.unimib.it
