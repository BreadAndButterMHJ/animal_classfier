# 🦊动物品种分类器（Animal Classifier）

这个项目的功能是动物品种的识别，采用了**ResNet18**作为预训练模型，能够识别**10**种类型，该项目是本人对于torch使用的练习，数据集采用如下[Animals-10](https://www.kaggle.com/datasets/alessiocorrado99/animals10)

## 环境配置主要使用了如下包
- torch，torchvision用作模型的建立
- matplotlib用作结果可视化
- sklearn用作训练集测试集验证集的拆分
- python版本为3.9。

## 💻环境配置
conda配置指令如下
### 1.创建环境
```bash
conda create -n torch python = 3.9
conda activate torch
```
### 2.下载torch
有**cuda**的可以采用以下指令安装torch。
```bash
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```
没有cuda的则采用torch的cpu版本。
```bash
pip3 install torch torchvision torchaudio
```
### 3.安装其他依赖库
之后安装matplotlib和sklearn以及jupyter notebook
```bash
conda install matplotlib scikit-learn notebook
```
即可完成环境配置。
