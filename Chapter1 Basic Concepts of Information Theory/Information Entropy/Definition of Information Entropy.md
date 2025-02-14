﻿# 信息熵的定义

## 信息熵

1. 每一个随机事件都有自信息$I(a_{i})$

2. 针对系统，取各随机事件自信息的统计平均：
   $$
   E_{p}I(a_{i})=\sum_{i}^{}p(a_{i})I(a_{i})=-\sum_{i}^{}p(a_{i})logp(a_{i})
   $$

## 离散随机变量的信息熵

离散随机变量$X$的信息熵$H(X)$定义为：
$$
H(X)=-\sum_{x∈X}^{}p(x)logp(x)
$$

- $H(.)$的综量是随机变量的分布，而非取值
- $0log0=0$（$x→0$时，$xlogx→0$），概率为0的事件不影响信息熵

## 信息熵的唯一性定理

- 香农给出了信息熵函数满足的三个条件

  1. 连续性：当随机系统的概率分布发生了微小的变化，信息量不应该发生显著的变化，二者应该是连续的。
  2. 等概时的单调增函数特性：当随机系统是在一个集合上等概率分布的，那么随着集合中元素的个数的增加，信息熵的函数应该具有单调增的特性。
  3. 可加性：一个随机系统的信息熵应该具有可加的性质。

  定理1.1：满足上述三个条件的随机变量不确定性度量函数为：
  $$
  f(p_{1},p_{2},...p_{N})=-C\sum_{n=1}^{N}p(n)logp_{n}
  $$
  
