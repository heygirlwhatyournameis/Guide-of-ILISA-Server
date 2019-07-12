# 使用 Anaconda 中的 Python 环境 

## Anaconda

Anaconda 是一个基于 Python 或 R 语言的集成环境，它提供了超过 1500 个数据科学相关的包和库。通过内置的 Conda，用户得以方便地进行环境管理与包管理。无需手动安装和编译所需模块，以及耗费时间解决模块间的版本冲突。ILISA 上已经安装了 Anaconda，当用户使用 python3 命令时，即使用了 Anaconda 默认环境中的 Python。

## 使用 Conda 管理包

使用下面的命令可以查看当前环境中安装的包：

``` bash
conda list
```

使用下面的命令在当前环境安装新的包，如：

```
conda install numpy
```



## ILISA 的 Anaconda 默认环境

| Python 版本  | 更新时间 |
| ------------ | ----- |
| 3.7.3 |   2019-07-10    |

默认环境已安装了以下常用包（截至 19/07/12）：

| 包名           | 模块名     | 版本   | 描述                    |
| -------------- | ---------- | ------ | ----------------------- |
| NumPy          | numpy      | 1.16.2 | 数组和矩阵计算库        |
| SciPy          | scipy      | 1.2.1  | 科学计算库和数学工具包  |
| scikit-learn   | sklearn    | 0.20.3 | 基于 SciPy 的机器学习库 |
| Pandas         | pandas     | 0.24.2 | 数据操作和数据分析      |
| TensorFlow GPU | tensorflow | 1.13.1 | 深度学习库              |
| PyTorch        | torch      | 1.1.0  | 深度学习库              |
| Keras          | keras      | 2.2.4  | 深度学习库              |



## 配置自定义环境

Anaconda 允许用户建立多个环境，每个环境之间相互独立。在新的环境中，用户可以安装不同版本的 Python 以及模块，如果用户需要使用自定义环境，可参考 [Conda 文档](https://conda.io/en/latest/)。