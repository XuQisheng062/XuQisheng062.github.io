---
layout: single
title: "高等代数"
permalink: /notes/advanced-algebra/
author_profile: true
modified: 2026-09-28
---
## 1. 行列式

### 1.1 基本知识

$$
A =
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}
$$

$M_{ij}$ 是划去 $A$ 的第 $i$ 行、第 $j$ 列后得到的行列式。

递归定义：

$$
\det(A) = \sum_{i=1}^{n}(-1)^{i+1}a_{i1}M_{i1}
= a_{11}M_{11}-a_{21}M_{21}+\cdots+(-1)^{n+1}a_{n1}M_{n1}.
$$

代数余子式

$\det(A)$ 的第 $(i,j)$ 个元素的代数余子式为 $A_{ij}=(-1)^{i+j}M_{ij}$。

代入上式得（ $i$ 与 $j$ 对称）

$$
\det(A) = a_{1j}A_{1j} + \cdots + a_{ij}A_{ij} + \cdots + a_{nj}A_{nj}
$$

$$
\det(A) = \sum_{(k_1,\ldots,k_n)\in S_n}(-1)^{N(k_1\cdots k_n)}
a_{k_1 1}a_{k_2 2}\cdots a_{k_n n}
$$

性质：

① 上（下）三角行列式的值等于其主对角线之积；

②若行列式的某一行/列为 $0$，则 $\det(A)=0$；

③行列式的某一行（列）乘以 $c$，行列式的值也乘以 $c$；特别地，$\det(cA)=c^n\det(A)$。

④对换行列式的两行或两列，行列式变号；

⑤若存在两行两列成比例，行列式的值为零；

⑥

$$
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
\vdots & \vdots & \ddots & \vdots \\
b_{i1} +c_{i1} & b_{i2} +c_{i2} & \cdots & b_{in} +c_{in} \\
\vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}
=
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
\vdots & \vdots & \ddots & \vdots \\
b_{i1} & b_{i2} & \cdots & b_{in}  \\
\vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}
+
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
\vdots & \vdots & \ddots & \vdots \\
c_{i1} & c_{i2} & \cdots & c_{in}  \\
\vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}
$$

⑦行/列 $\times c$ 加减到另一行/列上，$\det(A)$ 不变

⑧$\det(A^T)=\det(A)$

Cramer 性质：

$$
\begin{cases}
a_{11}x_{1}+a_{21}x_{2}+\cdots +a_{n1}x_{n}=b_{1}\\
a_{12}x_{1}+a_{22}x_{2}+\cdots +a_{n2}x_{n}=b_{2}\\
\cdots \cdots\\
a_{1n}x_{1}+a_{2n}x_{2}+\cdots +a_{nn}x_{n}=b_{n}\\
\end{cases}
$$

$$
\det(A) =
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}
,
\det(A_i)=\begin{vmatrix}
a_{11} & a_{12} & \cdots & b_{1} &\cdots  & a_{1n} \\
a_{21} & a_{22} & \cdots& b_{2} & \cdots & a_{2n} \\
\vdots & \vdots & \vdots &\vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & \cdots& a_{12} & \cdots & a_{nn}
\end{vmatrix}
$$

$$
x_i=\frac{\det(A_i)}{\det(A)}
$$

Vandermonde 行列式

$$
\det(V_n) =
\begin{vmatrix}
1 & x_{1} & \cdots & x_{1}^{n-1} \\
1 & x_{2} & \cdots & x_{2}^{n-1} \\
\vdots & \vdots & \ddots & \vdots \\
1 & x_{n} & \cdots & x_{n}^{n-1} \\
\end{vmatrix}
=
\prod_{1\leq i < j \leq n}(x_j-x_i)
$$

分块上下三角：

$$
\begin{vmatrix}
A &M \\
O &B
\end{vmatrix}
=\det(A)\det(B),\qquad
\begin{vmatrix}
A &O \\
M &B
\end{vmatrix}
=\det(A)\det(B)
$$

Laplace 定理：

在 $\det(A)$ 中取任意 $k$ 行，含于这 $k$ 行的全部 $k$ 阶子式与所对应的代数余子式的乘积之和等于行列式 $A$ 的值，即：

$$
\det(A)=\sum_{1 \leq j_1 \leq j_2 < \cdots < j_k \leq n} A
\begin{pmatrix}
i_1,i_2,\cdots,i_k\\
j_1,j_2,\cdots,j_k\\
\end{pmatrix}
\widehat{A}
\begin{pmatrix}
i_1,i_2,\cdots,i_k\\
j_1,j_2,\cdots,j_k\\
\end{pmatrix}
$$


## 2. 矩阵
### 2.1 基本性质
$$
A=
\begin{pmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{pmatrix}
$$

矩阵计算

$$
\begin{aligned}
A+B &= B+A, \\
(A+B)+C &= A+(B+C), \\
O+A &= A+O=A, \\
A+(-A) &= O, \\
1\cdot A &= A, \\
k(A+B) &= kA+kB, \\
(k+l)A &= kA+lA, \\
(kl)A &= k(lA).
\end{aligned}
$$
