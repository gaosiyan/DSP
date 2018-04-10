
# 信号的表达
&emsp;&emsp;随时间变化的模拟信号f(t),经过Ts采样后,得到一组数字序列,比如对f(t)进行N点采样后,得到一个N点的采样序列 f = (f1,f2,...,fN),每个点是一个数,那么f就可以表示成一个N维向量.若将N无限增大,那么函数f的所有信息都被包含在序列中.

&emsp;&emsp;二维空间向量(x,y)是二维空间R^2中的一个点;三维空间中的一个向量(x,y,z)对应三维空间R^3中的一个点.N维空间的向量仍然是N维空间中的一个点,不过没有办法直观的用图形方式表达;随着N的不断增大,可以认为是一个无限大维数的空间,连续函数f(t)就是此空间中的一个点,因此无限维的空间也称为函数空间.

## 二维空间向量的距离和内积
&emsp;&emsp;通过距离和内积可以计算出两个信号的关系强弱.为了简化问题这里只考虑2维的信号.

&emsp;&emsp;设对某个连续信号f(t)和g(t)进行采样得到两个值(f1,f2)和(g1,g2);那么f(t)和g(t)可以表示成二维向量形式f = (f1,f2)和g = (g1,g2)
&emsp;&emsp;