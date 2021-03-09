# Deepside
About our previous Neurocomputing paper "Deepside: A general deep framework for salient object detection".
## Introduction
  In this paper, we review and draw underlying connections between existing architectures ((a)-(d)), and show that they actually could be unified into a general framework, which simply just has side structures with different depths. Based on the idea of designing deeper side structures for better detection accuracy, we propose a unified framework called Deepside that can be deeply supervised to incorporate hierarchical CNN features.  
  ![alt text](ExistingScheme.png)  
  
  The reason to have deeper side structures ((a) and (b)), especially for low-level features, is that side structure activation should contain information of finer boundary details of salient objects, and it indicates where salient object boundaries locate. In this sense, such information is a kind of “high-level”information and therefore may require relatively deeper structure to capture it. More details please see the paper.  
  ![alt text](Deepside.png)  

## Results
![alt text](Examples.png)  
Saliency maps of Deepside on 7 benchmark datasets (ASD, DUT-OMRON, DUTS, ECSSD, HKU-IS, PASCAL-S, SOC) can be found below:  
链接: https://pan.baidu.com/s/1UOmBfjQiNyp1FkfKJ5bovQ 提取码: xcjw  

References of datasets:  
[STERE] Leveraging stereopsis for saliency analysis. In CVPR 2012.  
[NJU2K] Depth saliency based on anisotropic centersurround difference. In ICIP 2014.  
[NLPR] Rgbd salient object detection: A benchmark and algorithms. In ECCV 2014.  
[RGBD135] Depth enhanced saliency detection method. In International Conference on Internet Multimedia Computing and Service. ACM, 2014.  
[LFSD] Saliency detection on light field. In CVPR 2014.  
[DUT-RGBD] Depth-induced multi-scale recurrent attention network for saliency detection. In ICCV 2019.  
[SIP] Rethinking RGB-D salient object detection: Models, datasets, and large-scale benchmarks. IEEE TNNLS, 2020.  

## Citation
    @article{Fu2019deepside,
      title={Deepside: A general deep framework for salient object detection},
      author={Fu, Keren and Zhao, Qijun and Gu, Irene Yu-Hua and Yang, Jie},
      journal={Neurocomputing},
      volume={356},
      pages={69--82},
      year={2019}
    }
