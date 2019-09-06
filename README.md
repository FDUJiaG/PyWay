# PyWay
基于Python 3.7，对于常用算法、包以及在实际问题中可能遇到的工具进行简单的整理

[传送门](https://github.com/FDUJiaG/PyWay)

# 基本算法

## [Base](https://github.com/FDUJiaG/PyWay/tree/master/Base)

### 排序

【[PySort.py](https://github.com/FDUJiaG/PyWay/blob/master/Base/PySort.py)】

### 搜索

- 对有序序列的搜索：【[PyOrderSearch.py](https://github.com/FDUJiaG/PyWay/blob/master/Base/PyOrderSearch.py)】

- 对无序序列的搜索：【[PySearch.py](https://github.com/FDUJiaG/PyWay/blob/master/Base/PySearch.py)】

### 二叉树

【[PyBinaryTree.py](https://github.com/FDUJiaG/PyWay/blob/master/Base/PyBinaryTree.py)】

### 红黑树

【[PyRedBlackTree.py](https://github.com/FDUJiaG/PyWay/blob/master/Base/PyRedBlackTree.py)】

## [Graph](https://github.com/FDUJiaG/PyWay/tree/master/Graph)

基于networkx包，基本可以完成常规的图论任务

```shell
$ conda activate {env_name}
$ pip3 install networkx
# or
$ conda install networkx
```

**文件说明**

| 文件名                 | 说明                                                         |
| ---------------------- | ------------------------------------------------------------ |
| PyGraph.py             | 代码，networkx的基本使用                                     |
| PyGraphDraw.py         | 代码，networkx的对Graph的呈现                                |
| PyPrim.py              | 代码，Prim算法实现最小生成树                                 |
| PyGraphCPA.py          | 代码，获取关键路径算法                                       |
| PyMaxConSubgraph.py    | 代码，获取最大连通成分                                       |
| Matrix_of_Graph.ipynb  | jupyter文档，与图论相关的矩阵，主要包括：邻接矩阵，关联矩阵，拉普拉斯矩阵，相关特征值，连通性等 |
| Graph相关算法.ipynb    | jupyter文档，networkx中内置算法的实例，主要包括，最短路径，最小/大生成树，拓扑排序，最大流，最小费用最大流，广度优先与深度优先 |
| networkx_reference.pdf | pdf文档，networkx官方参考                                    |

# 科学计算

## Numpy

基于numpy包

```shell
$ pip3 install numpy
```

整理为一个markdown。

原示例为python 2.x，目前已经全部更新，并在python 3.7版本试验过，基于Ipython

```shell
$ pip3 install ipython
```

**主要内容包括**：

- ndrray对象
- ufunc运算
- 矩阵运算
- 文件存取

## Scipy

基于scipy包

```shell
$ pip3 install scipy
```

整理为一个markdown。

**主要内容包括**：

- 最小二乘拟合
- 非线性方程组求解
- B-Spline样条曲线
- 数值积分
- 解常微分方程组
- 滤波器设计
- 符号运算
- 球体体积

**代码文件说明**

| 文件名        | 说明               |
| ------------- | ------------------ |
| PySciTest1.py | 最小二乘拟合       |
| PySciTest2.py | 返回各种拟合的误差 |
| PySciTest3.py | 非线性方程组求解   |
| PySciTest4.py | B-Spline样条差值   |
| PySciTest5.py | 洛伦兹吸引子绘制   |