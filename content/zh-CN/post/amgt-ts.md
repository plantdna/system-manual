---
title: "AMGT-TS"
author: "zhangyunlong"
type: ""
date: 2020-07-15T22:39:10+08:00
subtitle: "An Accurate and Ultra-deep Coverage Method for Large-scale SSR Genotyping with SNPs in the SSR and Flanking Region Compatible"
image: ""
bigimg: [{src: "/img/path.jpg", desc: "Path"}]
tags: ["AMGT-TS"]
---

AMGT-TS 使用说明书

<!--more-->

# AMGT-TS 使用说明书

## 创建项目

### 步骤1: 填写创建项目表单包括以下内容

- 项目名称
- 项目描述
- 样品序列文件
- 参考序列文件

通过点击`Next`创建项目

![step1](/img/amgt/step1.png)

### 步骤2: 执行分析脚本

- 项目创建完毕后进入步骤2，通过点击`Start`按钮开始执行分析程序

- 分析结束后通过点击`Next` 进入步骤3，查看分析结果

![step2](/img/amgt/step2.png)

### 步骤3: 查看分析结果

- 该界面展示了参与分析程序的样品列表，通过点击某一项的`View Analysis Results` 查看该样品的全部位点信息

![step3](/img/amgt/step3.png)

![sites](/img/amgt/sites.png)

- 当点击某个位点下的SSR分型结果后，系统将展示该SSR分型的对齐图，该图以重复区为参照将左右剩余的序列进行对齐，第一行是该位点的参考序列，同时针对每种碱基配置不同的背景颜色进行区分。

![alignment](/img/amgt/alignment.gif)

## 项目列表

![projectList](/img/amgt/projectList.png)

该功能展示系统中已创建的项目列表，通过点击`View`进入项目详情页面，该页面包含以下两部分内容

- 基础信息：如项目名称；描述；分析结果路径等。

- 样品列表：与步骤3中的样品列表相同，具体功能请参照步骤3。

![viewProject](/img/amgt/viewProject.png)