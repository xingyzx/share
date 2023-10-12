# 人流密度监测

>关键词：
app, AI,大数据, 踩踏, 车流量

## 目标
1. 踩踏
2. 自然灾害逃生
3. 野生珍贵动植物保护等人为监测

## 方案
1. FCN
~~~
(Fully Convolutional Network)
传统的深度卷积神经网络（CNN）通常用于图像分类任务，其输出是一个固定大小的特征向量，表示输入图像中的不同对象类别的概率分布。然而，对于图像分割任务，我们需要为图像中的每个像素分配一个类别标签，而不仅仅是整个图像的分类标签。
FCN架构的关键思想是将传统的全连接层替换为全卷积层，从而允许输入和输出具有不同的空间分辨率。这允许网络输出一个与输入图像相同大小的特征图，其中每个像素对应于输入图像中的相应区域。然后，通过对这个特征图进行上采样，可以获得与输入图像相同大小的分割结果。
~~~
2. BIM
~~~
Building information modeling, or BIM, is a building design technology that starts with creating an intelligent 3D model.

The most advanced BIM software systems include a database of all related building information and intelligent data - including construction sequencing, cost, and lifecycle management information - that allows for document management, collaboration, and simulation throughout the lifecycle of a project.

The idea here is simple — if everyone involved can see exactly what a site is going to look like and have all relevant information available in one centralized, actionable repository, it can help the team...
(https://www.accruent.com/resources/blog-posts/what-building-information-modeling)
~~~
>BIM逃生规划模型
https://patents.google.com/patent/CN112288985A/zh
https://patents.google.com/patent/CN108961626A/zh
https://patents.google.com/patent/CN112367617A/zh
等专利

3. app



## 案例
### 1. 获取人流密度 （政府监控

1. [PaddleDetection](https://zhuanlan.zhihu.com/p/433652735)
   ✨[github](https://github.com/PaddlePaddle/paddledetection)

![许可](<截屏2023-10-12 23.29.05.png>)

2. [CCTrans(github)](https://github.com/wfs123456/CCTrans)   
    
   [📑paper](https://arxiv.org/pdf/2109.14483.pdf)

   [知乎](https://zhuanlan.zhihu.com/p/542590841)
    
    目前最佳算法，但需要很多精力部署代码，1中算法文档较全

    
3. [yolo](https://yolov8.com/)

   [🌟github](https://github.com/ultralytics/ultralytics)
   >The YOLOv8 model contains out-of-the-box support for object detection, classification, and segmentation tasks, accessible through a Python package as well as a command line interface.
    开源模型，可识别很多东西

![Alt text](<截屏2023-10-12 23.41.58.png>)

### 2. app
#### 大尺度：百度地图热力图？微信宜出行？
[商场车站实时人流量一搜便知 百度地图教你“错峰出行”(中国日报)](http://ex.chinadaily.com.cn/exchange/partners/82/rss/channel/cn/columns/snl9a7/stories/WS5e6efd57a3107bb6b57a6bc1.html)
#### 小尺度（商场、车站内部）：无用户可查询
~~（问的bing ai）~~



# 开发方向

## 1. 部署算法
选定算法，学习python、pytorch等

## 2. 开发app

注重UX(user experience)！！！

重体验🐶

## 3. 数据库建立（若真要做出来一个平台
