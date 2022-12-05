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
## Methods (work in progress!)
|Name|Task(s)|Paper|Code|
|--|--|--|--|
|VESPCN|Super-resolution|Real-time video super-resolution with spatio-temporal networks and motion compensation (CVPR 2017)|[[Pytorch](https://github.com/JuheonYi/VESPCN-PyTorch)]|
|DBN|Deblurring|Deep Video Deblurring for Hand-held Cameras (CVPR 2017)|[[Lua](https://github.com/shuochsu/DeepVideoDeblurring)]|
|STRCNN|Deblurring|Online video deblurring via dynamic temporal blending network (ICCV 2017)|:x:|
|DBLRGAN|Deblurring|Adversarial spatio-temporal learning for video deblurring (TIP 2018)|:x:|


## Datasets
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
