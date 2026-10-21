# 第 05 课：PyTorch 作业

## 作业 01：学习参数 w

打开 `01_learn_w_pytorch.ipynb`，学习如何用 PyTorch 最小化损失：

$$L = |y - xw^2|.$$

Notebook 包含中文讲解、可运行示例、初始化与学习率对比，以及需要填写的实验题。只需要 CPU 和 PyTorch，不需要下载数据。

## 作业 02：独立训练三个参数

打开 `02_train_three_parameters.ipynb`。题目只提供预测函数、绝对值损失的定义，以及 `x`、`y` 两个数据张量。请参考作业 01，自行完成三个参数的训练，保存结果并填写实验说明。

## 从 GitHub 获取作业

1. 在教师提供的 GitHub 仓库页面点击 **Fork**，创建自己的副本。
2. 在自己仓库的 **Code** 按钮中复制 HTTPS 地址。
3. 打开终端（Windows 使用 Miniforge Prompt），输入 `git clone` 加上复制的地址。例如 `git clone https://github.com/你的用户名/仓库名.git`，请替换为真实地址。
4. 进入克隆后的仓库，再进入本作业所在文件夹。若教师发布整个课程仓库，文件夹为 `lectures/05/hw`；若单独发布本文件夹，则在仓库根目录打开即可。

## 打开 Notebook

沿用上一份环境配置作业的 **torch-class** 环境。在终端进入本文件夹后运行：

```bash
conda activate torch-class
python -m notebook
```

在浏览器中打开 `01_learn_w_pytorch.ipynb`，选择 **Python (torch-class)** 内核。保持终端开启，按 **Shift + Enter** 逐格运行。

完成作业 01 后，可在同一界面打开 `02_train_three_parameters.ipynb`。如果你已安装好 PyTorch 和 Notebook 的环境叫 `cv-learning`，则激活该环境，并在 Notebook 中选择对应的 **Python (cv-learning)** 内核。

若尚未配置环境，请先完成上一份“从零搭建 PyTorch 学习环境”作业。若内核列表没有课程环境，在已激活环境的终端执行一次：

```bash
python -m ipykernel install --user --name torch-class --display-name "Python (torch-class)"
```

## 保存和提交

填写 Notebook 中的实验回答，重启内核并运行全部单元格，确认没有报错，再保存文件。按之前 Git 作业中的流程，将修改提交并推送到自己的 GitHub 仓库。不要上传本地 Conda 环境。

关闭时先保存，再在启动 Notebook 的终端按 **Ctrl + C**，按提示确认。
