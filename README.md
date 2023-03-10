# Bi3D: Bi-domain Active Learning for Cross-domain 3D Object Detection
This repo is for our CVPR2023 paper.

**Paper**: [[arxiv]]() &nbsp;

**Code**: Code is avaiable in [[3DTrans]](). 

**Authors**: Jiakang Yuan, Bo Zhang, Xiangchao Yan, Tao Chen, Botian Shi, Yikang Li, Yu Qiao.



## Abstract
Unsupervised Domain Adaptation (UDA) technique has been explored in 3D cross-domain tasks recently. Though preliminary progress has been made, the performance gap between the UDA-based 3D model and the supervised one trained with fully annotated target domain is still large. This motivates us to consider selecting partial-yetimportant target data and labeling them at a minimum cost, to achieve a good trade-off between high performance and low annotation cost. To this end, we propose a Bi-domain active learning approach, namely Bi3D, to solve the crossdomain 3D object detection task. The Bi3D first develops a domainness-aware source sampling strategy, which identifies target-domain-like samples from the source domain to avoid the model being interfered by irrelevant source data. Then a diversity-based target sampling strategy is developed, which selects the most informative subset of target domain to improve the model adaptability to the target domain using as little annotation budget as possible. Experiments are conducted on typical cross-domain adaptation scenarios including cross-LiDAR-beam, cross-country, and crosssensor, where Bi3D achieves a promising target-domain detection accuracy (89.63% on KITTI) compared with UDAbased work (84.29%), even surpassing the detector trained on the full set of the labeled target domain (88.98%).

![teaser](https://sshaoshuai.github.io/content/images/PVRCNN_min.png)

## Code 
Bi3D codes have been released to [[3DTrans]]().


## Citation
If you find this work useful in your research, please consider cite:
```

```
If you encounter any issues or have questions, please feel free to contact us via jkyuan22@m.fudan.edu.cn.
