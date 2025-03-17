
# 概述
本代码由 ChatGPT 生成，作为个人学习卷积神经网络（CNN）的示例。使用卷积神经网络（CNN）对 CIFAR-10 数据集进行图像分类。CIFAR-10 数据集包含 10 个类别的彩色图像，每个类别有 6000 张图像。我们使用 PyTorch 框架实现了一个基于 ResNet-18 的图像分类模型，并进行了训练、验证和推理。

# 数据
请从以下链接下载 CIFAR-10 数据集：
[https://www.kaggle.com/c/cifar-10/data](https://www.kaggle.com/c/cifar-10/data)

下载后，将 `train` 目录和 `test` 目录解压并覆盖到项目的 `data/cifar-10/train` 和 `data/cifar-10/test` 目录中。

# 环境
- 操作系统：Windows 11 64位
- GPU：NVIDIA GeForce RTX 4060 Ti 16GB
- Python 版本：3.9.21
- 依赖库：详见 `requirements.txt`

# 使用方法
1. 确保已正确导入数据。
2. 安装依赖库：
   ```sh
   pip install -r requirements.txt
   ```
3. 进入 `src/Cifar_10.ipynb` 并运行代码。

# 运行时间
预计运行时间为 43 分钟。