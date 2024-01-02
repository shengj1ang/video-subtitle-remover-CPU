简体中文 | No English Version, Use browser to translate this README.


视频介绍：
[https://www.youtube.com/watch?v=31PfkCSR5_8](https://www.youtube.com/watch?v=31PfkCSR5_8)<br>
[https://www.bilibili.com/video/BV1xi4y1r7gP](https://www.bilibili.com/video/BV1xi4y1r7gP)


## 项目简介

![License](https://img.shields.io/badge/License-Apache%202-red.svg)
![python version](https://img.shields.io/badge/Python-3.8+-blue.svg)
![support os](https://img.shields.io/badge/OS-Windows/macOS/Linux-green.svg)  

Video-subtitle-remover (VSR) 是一款基于AI技术，将视频中的硬字幕去除的软件。
主要实现了以下功能：
- **无损分辨率**将视频中的硬字幕去除，生成去除字幕后的文件
- 通过超强AI算法模型，对去除字幕文本的区域进行填充（非相邻像素填充与马赛克去除）
- 支持自定义字幕位置，仅去除定义位置中的字幕（传入位置）
- 支持全视频自动去除所有文本（不传入位置）
- 支持多选图片批量去除水印文本

<p style="text-align:center;"><img src="https://github.com/YaoFANGUK/video-subtitle-remover/raw/main/design/demo.png" alt="demo.png"/></p>

**下载地址：**

Windows GPU版本v1.1.0（GPU）：

- 百度网盘:  <a href="https://pan.baidu.com/s/1zR6CjRztmOGBbOkqK8R1Ng?pwd=vsr1">vsr_windows_gpu_v1.1.0.zip</a> 提取码：**vsr1**

- Google Drive:  <a href="https://drive.google.com/drive/folders/1NRgLNoHHOmdO4GxLhkPbHsYfMOB_3Elr?usp=sharing">vsr_windows_gpu_v1.1.0.zip</a> 

> 这个仓库是CPU版本的，旨在让这个程序能在所有的设备上运行，虽然速度慢，但是对设备没有高要求。

> 并且我修复了一些BUG。

> 你只需要在上面的下载地址下载原作者提供的版本，然后使用本仓库中的backend文件夹替换。



## 演示

- GUI版：

<p style="text-align:center;"><img src="https://github.com/YaoFANGUK/video-subtitle-remover/raw/main/design/demo2.gif" alt="demo2.gif"/></p>

- <a href="https://b23.tv/guEbl9C">点击查看演示视频👇</a>

<p style="text-align:center;"><a href="https://b23.tv/guEbl9C"><img src="https://github.com/YaoFANGUK/video-subtitle-remover/raw/main/design/demo.gif" alt="demo.gif"/></a></p>

## 源码使用说明

> **CPU版本，不需要显卡！！！**，最低配置：
> 内存小可能会有问题，可以在源码里改改，16G的内存是可以的。
> 
> CPU: 支持AVX指令集


## 后面的可以去看原仓库

## 赞助（这个是给原作者的）
<img src="https://i.imgur.com/EMCP5Lv.jpeg" width="600">

| 捐赠者                       | 累计捐赠金额     | 赞助席位 |
|---------------------------|------------| --- |
| 坤V                        | 400.00 RMB | 金牌赞助席位 |
| Jenkit                        | 200.00 RMB | 金牌赞助席位 |
| 麦格                        | 100.00 RMB | 金牌赞助席位 |
| wr                        | 100.00 RMB | 金牌赞助席位 |
| 陈凯                        | 50.00 RMB  | 银牌赞助席位 |
| Tshuang                   | 20.00 RMB  | 银牌赞助席位 |
| 很奇异                       | 15.00 RMB  | 银牌赞助席位 |
| 何斐                        | 10.00 RMB  | 铜牌赞助席位 |
| [老猫](http://lanmaoba.com) | 8.80 RMB   | 铜牌赞助席位 |
| 长缨在手                      | 6.00 RMB   | 铜牌赞助席位 |
| Stephen                   | 2.00 RMB   | 铜牌赞助席位 |
| Leo                       | 1.00 RMB   | 铜牌赞助席位 |
