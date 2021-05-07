# Computer Vision Baseline Papers
> contributor: datamonday
> 
> githubrepo: https://github.com/datamonday/CV-Baseline-Papers

---
# 1. 基础论文（Foundation）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :----------- | :----------------------------------------------------------- | :--- | :---------------- | :----------------------------------------------------- | :------------------------------ | :------- | :------- |
| AlexNet      | [ImageNet Classification with Deep Convolutional Neural Networks](https://datac.blog.csdn.net/article/details/108118232) | 2012 | 67950(20/08/20)   | Alex Krizhevsky,Ilya Sutskever,Geoffrey E. Hinton      | Classification                  |          |          |
| ZFNet        | [Visualizing and Understanding Convolutional Networks](https://datac.blog.csdn.net/article/details/108127261) | 2013 | 9898(20/08/2020)  | Matthew D. Zeiler,Rob Fergus                           | Classification                  |          |          |
| VGGNet       | [VERY DEEP CONVOLUTIONAL NETWORKS FOR LARGE-SCALE IMAGE RECOGNITION](https://datac.blog.csdn.net/article/details/108130240) | 2014 | 42645(20/08/2020) | Karen Simonyan,Andrew Zisserman+                       | Classification                  |          |          |
| GoogLeNet    | [Going deeper with convolutions](https://datac.blog.csdn.net/article/details/108136641) | 2014 | 23544(20/08/2020) | Christian Szegedy,Wei Liu,Yangqing Jia,et.al           | Classification                  |          |          |
| Inception v2 | [Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://datac.blog.csdn.net/article/details/108136897) | 2015 | 20238(21/08/2020) | Sergey Ioffe,Christian Szegedy                         | BN                              |          |          |
| Inception v3 | [Rethinking the Inception Architecture for Computer Vision](https://datac.blog.csdn.net/article/details/108136942) | 2015 | 9190(21/08/2020)  | Christian Szegedy,Vincent Vanhoucke,Sergey Ioffe,et.al |                                 |          |          |
| Inception v4 | [Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning](https://datac.blog.csdn.net/article/details/108136973) | 2016 | 5227(21/08/2020)  | Christian Szegedy,Sergey Ioffe,Vincent Vanhoucke       |                                 |          |          |
| ResNet       | [Deep Residual Learning for Image Recognition](https://datac.blog.csdn.net/article/details/108172996) | 2015 | 52996(25/08/2020) | Kaiming He,Xiangyu Zhang,Shaoqing Ren,Jian Sun         | Classification,Object Detection |          |          |
| ResNeXt      | [Aggregated Residual Transformations for Deep Neural Networks](https://datac.blog.csdn.net/article/details/108262454) | 2017 | 2715(27/08/2020)  | Saining Xie,Ross Girshick,et.al                        | Classification,Object Detection |          |          |
| DenseNet     | [Densely Connected Convolutional Networks](https://datac.blog.csdn.net/article/details/108262312) | 2017 | 10699(27/08/2020) | Gao Huang*,Zhuang Liu*,et.al                           | Classification,Object Detection |          |          |
| SENet        | [Squeeze-and-Excitation Networks](https://datac.blog.csdn.net/article/details/108262435) | 2017 | 3667(27/08/2020)  | Jie Hu,Li Shen,et.al                                   | Classification,Object Detection |          |          |

---
# 2. 图像分类（Image Classification）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :------ | :----------------------------------------------------------- | :--- | :--------------- | :------------------------------------------------------ | :------- | :------- | :------- |
| Highway | [Highway Networks](https://datac.blog.csdn.net/article/details/108506640) | 2015 | 1280(10/09/2020) | Rupesh Kumar Srivastava,Klaus Greff,J¨urgen Schmidhuber |          |          |          |
| PReLU   | [Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification](https://datac.blog.csdn.net/article/details/108507704) | 2015 | 9108(10/09/2020) | Kaiming He,Xiangyu Zhang,Shaoqing Ren,Jian Sun          |          |          |          |

---
# 3. 目标检测（Object Detection）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :--------------- | :----------------------------------------------------------- | :--- | :---------------- | :----------------------------------------------------------- | :------- | :------- | :------- |
| Selective Search | [Selective Search for Object Recognition](https://datac.blog.csdn.net/article/details/108435575) | 2013 | 4498(07/09/2020)  | J.R.R. Uijlings,et.al                                        |          |          |          |
| OverFeat         | [OverFeat:Integrated Recognition, Localization and Detection using Convolutional Networks](https://datac.blog.csdn.net/article/details/108433747) | 2014 | 4061(06/09/2020)  | Pierre Sermanet,David Eigen,et.al                            |          |          |          |
| R-CNN            | [Rich feature hierarchies for accurate object detection and semantic segmentation](https://datac.blog.csdn.net/article/details/108435598) | 2014 | 14188(06/09/2020) | Ross Girshick,Jeff Donahue,et.al                             |          |          |          |
| SPPNet           | [Spatial Pyramid Pooling in Deep Convolutional Networks for Visual Recognition](https://datac.blog.csdn.net/article/details/108496655) | 2014 | 4740(09/09/2020)  | Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun            |          |          |          |
| Fast R-CNN       | [Fast R-CNN](https://datac.blog.csdn.net/article/details/108452399) | 2015 | 10839(08/09/2020) | Ross Girshick                                                |          |          |          |
| Faster R-CNN     | [Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks](https://datac.blog.csdn.net/article/details/108452303) | 2016 | 20864(08/09/2020) | Shaoqing Ren, Kaiming He, Ross Girshick, and Jian Sun        |          |          |          |
| YOLO v1          | [You Only Look Once: Unified, Real-Time Object Detection](https://datac.blog.csdn.net/article/details/108526049) | 2015 | 10906(11/09/2020) | Joseph Redmon, Santosh Divvalay, Ross Girshick, Ali Farhadiy |          |          |          |
| SSD              | [SSD: Single Shot MultiBox Detector](https://datac.blog.csdn.net/article/details/108526052) | 2015 | 10131(11/09/2020) | Wei Liu, Dragomir Anguelov,et.al                             |          |          |          |

---
# 4. 图像分割（Image Segmentation）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :---- | :----------------------------------------------------------- | :--- | :---------------- | :------------------------------------------------- | :------- | :------- | :------- |
| FCN   | [Fully Convolutional Networks for Semantic Segmentation](https://datac.blog.csdn.net/article/details/108427478) | 2014 | 14541(06/09/2020) | Jonathan Long*,Evan Shelhamer*,Trevor Darrell      |          |          |          |
| U-Net | [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://datac.blog.csdn.net/article/details/108428852) | 2015 | 12052(08/03/2020) | Olaf Ronneberger, Philipp Fischer, and Thomas Brox |          |          |          |

---
# 5. 生成式对抗网络（Generative Adversarial Network, GAN）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :--- | :------- | :--- | :--- | :--- | :------- | :------- |:------- |
|  |  |  |  |  |  |  |  |

---
# 6. 光学字符识别（Optical Character Recognition, OCR）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :--- | :------- | :--- | :--- | :--- | :------- | :------- | :------- |  |  |  |  |  |  |  |  |

---
# 7. 轻量化网络（Light Networks）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :--- | :------- | :--- | :--- | :--- | :------- | :------- |:------- |
| SqueezeNet | [SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and <0.5MB model size](https://arxiv.org/abs/1602.07360) | 2016 | 3862(05/07/2021) | Forrest N. Iandola, Song Han. et.al |  |  |  |
|MobileNet  | [MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications](https://arxiv.org/abs/1704.04861) | 2017 | 8124(05/07/2021) | Andrew G. Howard, Menglong Zhu. et.al |  |  | |
| ShuffleNet | [ShuffleNet: An Extremely Efficient Convolutional Neural Network for Mobile Devices](https://arxiv.org/abs/1707.01083) | 2017 | 2430(05/07/2021) | Xiangyu Zhang, Xinyu Zhou, Mengxiao Lin, Jian Sun |  |  |  |
| Xception | [Xception: Deep Learning with Depthwise Separable Convolutions](https://arxiv.org/abs/1610.02357) | 2016 | 5016(05/07/2021) | François Chollet |  |  |  |

---
# 8. 图神经网络（Graph Neural Networks）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :--- | :------- | :--- | :--- | :--- | :------- | :------- |:------- |
|  |  |  |  |  |  |  |  |

---
# 9. 人脸识别（Face Recognition）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :--- | :------- | :--- | :--- | :--- | :------- | :------- |:------- |
|  |  |  |  |  |  |  |  |

---
# 10. 目标跟踪（Object Tracking）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :--- | :------- | :--- | :--- | :--- | :------- | :------- |:------- |
|  |  |  |  |  |  |  |  |

---
# 11. 行人重识别（Person Re-identification, ReID）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :--- | :------- | :--- | :--- | :--- | :------- | :------- |:------- |
|  |  |  |  |  |  |  |  |

---
# 12. 雷达点云（Lidar Point Clouds）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :--- | :------- | :--- | :--- | :--- | :------- | :------- |:------- |
|  |  |  |  |  |  |  |  |

---
# 13. 3D重建（3D Reconstruction）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :--- | :------- | :--- | :--- | :--- | :------- | :------- |:------- |
|  |  |  |  |  |  |  |  |



---
# 14. 图像重建（Image reconstruction）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :--- | :------- | :--- | :--- | :--- | :------- | :------- |:------- |
|  |  |  |  |  |  |  |  |



---
# 15. 图像压缩（Image Compression）
| 模型(Model) | 论文名称(Paper)| 年份(Year) | 被引(cited)  | 作者(Author) | 所属类别(Type) | 官方代码(Code) | 个人代码(Practice) |
| :--- | :------- | :--- | :--- | :--- | :------- | :------- |:------- |
|  |  |  |  |  |  |  |  |