---
title: demo
author: happysimple
desc: 这是一款很棒的Markdown主题
---


[TOC]

# 一级标题

## 二级标题

### 三级标题

在全球总电子含量（Total Electron Content, TEC）经验模型中表达各种电离层异常是一项具有挑战性的研究。现有的经验模型通过构造模型分量来表达电离层异常。

在全球总电子含量（Total Electron Content, TEC）经验模型中表达各种电离层异常是一项具有挑战性的研究。现有的经验模型通过构造模型分量来表达电离层异常。

> 在全球总电子含量（Total Electron Content, TEC）经验模型中表达各种电离层异常是一项具有挑战性的研究。现有的经验模型一般通过构造模型分量来表达电离层异常。

<blockquote alt="info"><p>在全球总电子含量（Total Electron Content, TEC）经验模型中表达各种电离层异常是一项具有挑战性的研究。现有的经验模型一般通过构造模型分量来表达电离层异常。</p></blockquote>

<blockquote alt="warn"><p>在全球总电子含量（Total Electron Content, TEC）经验模型中表达各种电离层异常是一项具有挑战性的研究。现有的经验模型一般通过构造模型分量来表达电离层异常。</p></blockquote>

<blockquote alt="danger"><p>在全球总电子含量（Total Electron Content, TEC）经验模型中表达各种电离层异常是一项具有挑战性的研究。现有的经验模型一般通过构造模型分量来表达电离层异常。</p></blockquote>

<blockquote alt="success"><p>在全球总电子含量（Total Electron Content, TEC）经验模型中表达各种电离层异常是一项具有挑战性的研究。现有的经验模型一般通过构造模型分量来表达电离层异常。</p></blockquote>

<!-- 这是个注释 -->

如有问题请查询[百度](https://www.baidu.com)，相关数据在<https://www.baidu.com>下载。

<font>默认标签</font>、<font title="red">红色标签</font>、<font title="yellow">黄色标签</font>、<font title="green">绿色标签</font>、<font title="blue">蓝色标签</font>、<font title="gray">灰色标签</font>、<font style="background-color:#28af94">自定义颜色标签</font>

<span alt="solid">下划线</span>、<span alt="dotted">着重号</span>、<span alt="wavy">波浪线</span>、<span alt="delete">删除线</span>、<span alt="shadow">阴影效果</span>、<span alt="hollow">空心字</span>、<span alt="blink">字体闪烁</span>

==高亮==、<kbd>Enter</kbd>

<details>
    <summary>折叠标签</summary>
    <p>青青子衿，悠悠我心</p>
    <p>老骥伏枥，志在千里</p>
</details>
---

这里有一个脚注[^1]。哈哈哈！

$y=ax^2+bx+c$
$$
y=ax^2+bx+c
$$

`print('Hello World')`



```matlab
clear;clc;

% 加载数据
x = 1:100;
y = linspace(10,40,100) + 10*rand(1,100);

% 计算拟合曲线
p = polyfit(x,y,1);
a = p(1);
b = p(2);
x0 = [0,100];
y0 = [a*x0(1)+b,a*x0(2)+b];

% 计算相关系数
R = corrcoef(x,y);
R = sprintf('%.2f',R(1,2));
```

1. 有序列表
   1. 有序列表
   2. 有序列表
   


- 无序列表
  - 无序列表
  - 无序列表
  


- [ ] 事项1
- [ ] 事项2
- [ ] 事项3



<img src="./happysimple/assets/Typora_02.png" alt="Typora" style="width:30vw;" />



|  日期   |  金额  |  利息  |
| :-----: | :----: | :----: |
| 2012.03 | ￥2000 | ￥2000 |
| 2012.04 | ￥2000 | ￥2000 |
| 2012.05 | ￥2000 | ￥2000 |
| 2012.06 | ￥2000 | ￥2000 |



<center>
<div alt="fig">表1.三线表</div>
<div alt="three-table">
<table>
  <tr>
    <th alt="center">日期</th>
    <th alt="center">金额</th>
    <th alt="center">利息</th>
  </tr>
  <tr>
    <td alt="center">2012.01</td>
    <td alt="center">￥2000</td>
    <td alt="center">￥2000</td>
  </tr>
  <tr>
    <td alt="center">2012.02</td>
    <td alt="center">￥2000</td>
    <td alt="center">￥2000</td>
  </tr>
      <tr>
    <td alt="center">2012.03</td>
    <td alt="center">￥2000</td>
    <td alt="center">￥2000</td>
  </tr>
</table>
</div>
</center> 


[^1]:张亭,赵庆鑫,钟慧鑫,张一彬,朱云聪,冯建迪.国际参考电离层2016模型在陆海区域的精度分析J.测绘科学,2021,46(09):14-33.DOI:10.16251/j.cnki.1009-2307.2021.09.003.
