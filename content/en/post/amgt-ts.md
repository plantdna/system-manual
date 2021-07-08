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

AMGT-TS User Manual

<!--more-->

# AMGT-TS User manual

## Create a new project

### Step 1: 

Launch this function by select the menu item "New Project" on the left, then fill the following information: 

- Project name
- Project description
- Upload the targeted sequencing files of each sample

  we can upload more than one samples data files and there is no limit.
- Reference files
  Use the default if you are not familiar with the details.
- Remark

Then use the `Next` button to continue.

![step1](/img/amgt/step1.png)

### Step 2: 
- After creating the project, we use the `Start` button to launch the AMGT-TS tool.

- Then, we use the `Next` button to go to the result tab page.

![step2](/img/amgt/step2.png)

### Step 3: 

- This page show the analysis result of AMGT-TS tool. 

We can select the `View Analysis Results` of a sample, to view all the loci result information of this sample.

![step3](/img/amgt/step3.png)

![sites](/img/amgt/sites.png)

- We can show the reads alignment graph by select a locus. In the graph, the first read is the reference read of the locus，others is from the targeted sequencing data.

![alignment](/img/amgt/alignment.gif)

## Project List

![projectList](/img/amgt/projectList.png)

We can view all the projects information by select the second menu item on the left. By select the `View` button to check the details of each project. There are information of each project as following:

- Basic information
  Such as project name, description, the result path, etc.

- Samples list：
  Same as the step 3 of "Create a new project".

![viewProject](/img/amgt/viewProject.png)
