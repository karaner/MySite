---
title: 变换
description: 这是Games101的学习记录
date: 2021-06-21
categories:
  - Games101
tags:
---
## 1.1 线性变换

#### 1.1.1 缩放变换
![](attachments/pasted-img-2023-10-15-19-26-02.png)

#### 1.1.2 反射变换
![](attachments/pasted-img-2023-10-15-19-32-41.png)

#### 1.1.3  切变变换
![](attachments/pasted-img-2023-10-15-19-33-21.png)

#### 1.1.4  旋转变换
![](attachments/pasted-img-2023-10-15-19-34-14.png)

>**<span style="background:#d3f8b6">推导对应矩阵，就是用特殊点代入去推导</span>**

## 1.2 齐次坐标

#### 1.2.1 平移变换
![](attachments/pasted-img-2023-10-15-19-41-43.png)

![](attachments/pasted-img-2023-10-15-20-00-06.png)
>**<span style="background:#d3f8b6">平移变换，不是线性变换，我们不想特殊用一种表示去处理平移变换，所以我们引入齐次坐标的概念</span>**

#### 1.2.2 引入齐次坐标

我们通过在n维坐标上，向上引入多一维的坐标，来重新表示点和向量

![](attachments/pasted-img-2023-10-15-20-05-20.png)

![](attachments/pasted-img-2023-10-15-20-12-42.png)

这时候，平移变换就可以这样表示
![](attachments/pasted-img-2023-10-15-20-05-53.png)

这时候，线性变换+平移变换 ，引入齐次坐标后的表示改变，如下

![](attachments/pasted-img-2023-10-15-20-14-22.png)

这时候，所有的2D变换，分别可以这样表示，如下

![](attachments/pasted-img-2023-10-15-20-17-51.png)

## 1.3 逆变换
在几何上，变换的逆变换，有这样的效果，几何进行了一次变换，再进行一次逆变换，会回到原来的位置

![](attachments/pasted-img-2023-10-15-20-19-40.png)

## 1.4 组合变换

#### 1.4.1 组合变换中，变换的顺序很重要
![](attachments/pasted-img-2023-10-15-20-26-16.png)
可以用结合律，将很多次的变换，通过结合律，算出最后一个变换
![](attachments/pasted-img-2023-10-15-20-27-53.png)

## 1.5分解复杂的变换

#### 1.5.1 思考如果绕着一个点做旋转

![](attachments/pasted-img-2023-10-15-20-31-10.png)

先平移的逆变换到原点，做旋转变换，再通过做平移变换，得出最后想要的结果

## 1.5 3D坐标中的变换

可以类比2D,得出相同的结论

![](attachments/pasted-img-2023-10-15-20-33-56.png)

![](attachments/pasted-img-2023-10-15-20-34-11.png)

