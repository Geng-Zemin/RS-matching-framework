@[TOC](FRIM : A Framework for Satellite - Borne Remote Sensing Image Matching)

# 简介

FRIM 是一个遥感图像匹配框架，旨在提供高效的遥感图像匹配方法，适用于卫星遥感影像的处理与分析。此框架支持多种图像匹配算法，并提供灵活的分块方式，用于处理大规模遥感影像数据。

# 使用方法


RIM 通过命令行工具运行。使用前需要解压opencv_world460.zip文件。使用时，可以通过 CMD 命令行输入以下命令

> RSFM.exe task.xml

## task.xml 配置文件说明

task.xml 是 FRIM 配置的核心文件，它包含了程序运行所需的各种参数。以下是 task.xml 文件的主要配置项及其说明：

>MatchType: 匹配方法，支持以下几种算法：SIFT、RIFT、ORB、Affine、BRISK、Phase

>BlockMode: 分块方式，支持两种选择：image: 按图像进行分块处理、object: 按物体进行分块处理

>GridNumX 和 GridNumY: 分块的行列数，分别表示图像在 X 和 Y 方向上分块的数量。

>Source: 原始影像文件的路径。

>Reference: 参考影像文件的路径。

>DEM: 数字高程模型（DEM）文件的路径。

>OutputDir: 结果输出文件夹的路径（不要包含文件名），程序将在此目录下输出处理结果。
# 注意

本软件仅可用于学术研究，禁止用于商业用途。

# 联系方式

如有问题或建议，欢迎通过以下方式与我们联系：
>作者：Geng Zemin
>联系邮箱：gengzemin@whu.edu.cn
