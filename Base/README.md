# Base

## Sort

### 选择排序

选择排序是一种简单直观的排序算法，无论什么数据进去都是 O(n^2^) 的时间复杂度，所以用到它的时候，数据规模越小越好，唯一的好处可能就是不占用额外的内存空间了吧

- **算法步骤**
	- 首先在未排序序列中找到最小（大）元素，存放到排序序列的起始位置
	- 再从剩余未排序元素中继续寻找最小（大）元素，然后放到已排序序列的末尾
	- 重复第二步，直到所有元素均排序完毕

- **动图演示**

<img src='img/selectionSort.gif' width=600/>

- 插入排序
- 希尔排序
- 冒泡排序
- 快速排序
- 归并排序

【[PySort.py](https://github.com/FDUJiaG/PyWay/blob/master/Base/PySort.py)】

## 搜索

- 对有序序列的搜索：
  - 二分查找
  - 二分查找（递归版）
  - 插值查找

【[PyOrderSearch.py](https://github.com/FDUJiaG/PyWay/blob/master/Base/PyOrderSearch.py)】

- 对无序序列的搜索：
  -  顺序查找
  - 哈希查找

【[PySearch.py](https://github.com/FDUJiaG/PyWay/blob/master/Base/PySearch.py)】

## 二叉树

【[PyBinaryTree.py](https://github.com/FDUJiaG/PyWay/blob/master/Base/PyBinaryTree.py)】
