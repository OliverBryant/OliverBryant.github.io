---
title: Advanced_Mathematics
abbrlink: 6688
date: 2021-01-16 19:56:37
updated: 2021-01-16 19:56:37
categories:
	- 考研
tags:
	- 数学
permalink:
mathjax: true
---

# 高等数学

## 第一章 函数、极限与连续性

### 一、函数

1. 概念：

    - 定义：设x，y是两个变量，D是实数集的某个子集，若对于D中的每个值x，按照一定的法则有唯一确定的值y与之对应，则称变量y为变量x的函数，记作y=f(x)，数集D称为函数的定义域，由函数对应法则或实际问题的要求来确定，相应的函数值的集合称为函数的值域。

    - 函数的两要素：

        - 定义域
            $$
            \frac1{f\left(x\right)},f\left(x\right)\neq0;\sqrt[2n]{f\left(x\right)},f(x)\geq0;\ln f(x),\log_af(x),f(x)>0;arc\sin f(s),arc\cos f(x),\left|f(x)\right|\leq1
            $$

        - 对应法则

2. 几何特性：

    1. 奇偶性：

        - 定义：

            - 奇函数：
                $$
                f(-x)=-f(x)
                $$

            - 偶函数：
                $$
                f(-x)=f(x)
                $$

        - 常见的奇偶函数：

            - 奇函数：
                $$
                x^{2n},\left|x\right|,\cos(x),sec(x),e^x+e^{-x}
                $$

            - 偶函数：
                $$
                x^{2n+1},\sin x,\tan x,arc\sin x,arc\tan x,e^x-e^{-x},\ln(x+\sqrt{1+x^2})
                $$

        - 注：

            - 奇函数+奇函数=奇函数；奇函数+偶函数=不一定；偶函数+偶函数=偶函数
            - 偶函数关于y轴对称。
            - 奇函数关于原点对称；若在原点有定义，f(0)=0.

    2. 周期性：

        - 定义：
            $$
            f(x+T)=f(x)
            $$

        - 常见函数：
            $$
            \sin x,\cos x,\tan x,cotx,secx,cscx,C(\mathrm{常数函数})
            $$

    3. 单调性：

        - 定义：

            - 单调递增：
                $$
                \forall x_1<x_2\in I,f(x_1)<f(x_2)
                $$

            - 单调递减：
                $$
                \forall x_1<x_2\in I,f(x_1)>f(x_2)
                $$

        - 判定：

            - 若f'(x)>0，则f(x)单调递增，反之递减。
            - f'(x)>=0且等号仅在有限个点成立，则f(x)单调递增，反之递减。

    4. 有界性：

        - 定义：
            $$
            \forall x\in I,\exists M>0,使\left|f(x)\right|\leq M,则I上f(x)\mathrm{有界}
            $$

        - 常见函数：
            $$
            sinx,cosx,arctanx,C
            $$

        - 判定：

            - f(x)在

