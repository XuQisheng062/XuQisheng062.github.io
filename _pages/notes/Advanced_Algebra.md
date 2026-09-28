---
layout: single
title: "高等代数"
permalink: /notes/advanced-algebra/
author_profile: true
---


# 高等代数

## 1.行列式

### 1.1.1 基本

\[
A =
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
a_{21} & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix}
\]

\(M_{ij}\) 是划去 \(A\) 的第 \(i\) 行、第 \(j\) 列后得到的行列式。

递归定义:

\[
|A| = a_{11}M_{11}-a_{21}M_{21}+ \cdots +(-1)^{i+1}a_{i1}M_{i1} + \cdots + (-1)^{n+1}a_{n1}M_{n1}
\]