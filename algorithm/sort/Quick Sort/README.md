# 快速排序 <Quick Sort>

## 定义

快速排序使用分治法（Divide and conquer）策略来把一个序列（list）分为两个子序列（sub-lists）

## 过程

![Quick Sort](https://camo.githubusercontent.com/253b22840353c9759694d63839fe7565d48f9df6/687474703a2f2f696d672e626c6f672e6373646e2e6e65742f3230313630393137303033303034393036)

1.  在数据集之中，选择一个元素作为"基准"（pivot）
1.  所有小于"基准"的元素，都移到"基准"的左边；所有大于"基准"的元素，都移到"基准"的右边
1.  对"基准"左边和右边的两个子集，不断重复第一步和第二步，直到所有子集只剩下一个元素为止

## 时间复杂度

* 最坏时间复杂度 O(n²)
* 最优时间复杂度 O(n log n)
* 平均时间复杂度 O(n log n)