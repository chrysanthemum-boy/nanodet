[<img src="https://img.shields.io/badge/Language-English-blue.svg">](README_en.md) | [<img src="https://img.shields.io/badge/Language-简体中文-red.svg">](README.md)

# nanodet
##### 轻量级手势识别自学项目  

## 简介
本仓库改编自nanodet，原仓库地址为：[RangiLyu/nanodet](https://github.com/RangiLyu/nanodet) ，部分版权属于原仓库作者所有，请参见原仓库[License](https://github.com/RangiLyu/nanodet/blob/main/LICENSE)（侵权会删）

## 训练集
本人制作的`数据集`在[hand](https://github.com/chrysanthemum-boy/nanodet/tree/main/hand)文件夹中。  
如需自己制作训练数据集和图片，请在百度网盘上下载：

#### 手势训练图片（可自行制作训练集）
链接：https://pan.baidu.com/s/1ZiCOc5yqE0pbZu2QsNxhSA 
提取码：y9jj

#### 手势训练集（自制）
链接：https://pan.baidu.com/s/1fhu8FIFWBu4fbGyRQk9nKg 
提取码：iyzr

## 权重文件
[model_best.ckpt](https://github.com/chrysanthemum-boy/nanodet/blob/main/model_best.ckpt)为部分手势训练完成的权重文件，可直接使用  
[nanodet_sim.bin](https://github.com/chrysanthemum-boy/nanodet/blob/main/nanodet_sim.bin)和[nanodet_sim.param](https://github.com/chrysanthemum-boy/nanodet/blob/main/nanodet_sim.param)为将`ckpt格式` -> `onnx格式` -> `ncnn格式` 后的`Android demo`，可直接使用

## 问题及建议
本人比较菜，也走了许多弯路，有问题欢迎联系我。  
请反馈至邮箱fannc@qq.com，谢谢。
