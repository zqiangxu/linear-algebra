# 矩阵的乘法

## 1、矩阵乘法


```math
c
\begin{pmatrix}
x_{11} & \cdots & x_{1n} \\
\vdots & & \vdots \\
x_{m1} & \cdots & x_{mn}
\end{pmatrix}
=
\begin{pmatrix}
cx_{11} & \cdots & cx_{1n} \\
\vdots & & \vdots \\
cx_{m1} & \cdots & cx_{mn}
\end{pmatrix}
```

```math
\begin{pmatrix}
a_{11} & \cdots & a_{1n} \\
\vdots & & \vdots \\
a_{m1} & \cdots & a_{mn}
\end{pmatrix}
\begin{pmatrix}
x_{1}\\
\vdots\\
x_{n}
\end{pmatrix}
=
\begin{pmatrix}
a_{11}x_1 + \cdots + a_{1n}x_n \\
\vdots\\
a_{m1}x_1 + \cdots a_{mn}x_n
\end{pmatrix}
```

例如：

```math
\begin{pmatrix}
2 & 7 \\
9 & 3 \\
4 & 3
\end{pmatrix}
\begin{pmatrix}
1\\
2
\end{pmatrix}
=
\begin{pmatrix}
2*1 + 7*2 \\
9*1 + 3*2 \\
4*1 + 3*2
\end{pmatrix}
=
\begin{pmatrix}
16 \\
19 \\
10
\end{pmatrix}
```