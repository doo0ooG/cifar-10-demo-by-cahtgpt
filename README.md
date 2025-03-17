
# 概述
本代码由 ChatGPT 生成，作为个人学习卷积神经网络（CNN）的demo。
使用卷积神经网络（CNN）对 CIFAR-10 数据集进行图像分类。CIFAR-10 数据集包含 10 个类别的彩色图像，每个类别有 6000 张图像。我们使用 PyTorch 框架实现了一个基于 ResNet-18 的图像分类模型，并进行了训练、验证和推理。

# Data
在https://www.kaggle.com/c/cifar-10/data将train目录和test目录下载解压后覆盖目录`data/cifar-10/train`与`data/cifar-10/test`

# 环境
- window11 64
- GPU： 4060Ti 16GB
- python 3.9.21
- 依赖于`requiements.txt`中

# Run（43min）
- 正确导入数据
- 安装`requiements.txt`
- 进入`src/Cifar_10.ipynb`运行