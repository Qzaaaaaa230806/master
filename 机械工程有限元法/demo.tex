\documentclass{article}
\usepackage{amsmath}
\usepackage{amsfonts}
\usepackage{amssymb}

\begin{document}

要计算系统刚度矩阵 \(\mathbf{K}\) 的具体过程，我们需要将每个三节点三角形单元的刚度矩阵 \(\mathbf{K}^e\) 组装到整个系统的刚度矩阵中。这里给出的 \(\mathbf{K}^e\) 是：

\[
\mathbf{K}^e = \begin{bmatrix} 
6 & -3 & 0 \\ 
-3 & 4 & -2 \\ 
0 & -2 & 3 
\end{bmatrix}
\]

图3中的节点编号为 1, 2, 3, 4, 5。每个三节点单元对应节点的编号如下：

\begin{itemize}
    \item 单元 1：节点 1, 2, 3
    \item 单元 2：节点 3, 5, 1
    \item 单元 3：节点 3, 4, 2
\end{itemize}

我们假设这些单元的刚度矩阵均为上面的 \(\mathbf{K}^e\)，并将这些刚度矩阵组装到全局刚度矩阵中。

### 步骤1: 初始化全局刚度矩阵

假设系统中每个节点有一个自由度，因此全局刚度矩阵的维度是 \(5 \times 5\)。初始化全局刚度矩阵 \(\mathbf{K}\)：

\[
\mathbf{K} = \begin{bmatrix}
0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 \\
\end{bmatrix}
\]

### 步骤2: 组装单元刚度矩阵到全局刚度矩阵

#### 单元 1 (节点 1, 2, 3)

将 \(\mathbf{K}^e\) 组装到全局刚度矩阵 \(\mathbf{K}\) 的位置 (1,1), (1,2), (1,3), (2,1), (2,2), (2,3), (3,1), (3,2), (3,3):

\[ 
\begin{aligned}
&\mathbf{K}(1,1) += 6, \quad \mathbf{K}(1,2) += -3, \quad \mathbf{K}(1,3) += 0 \\
&\mathbf{K}(2,1) += -3, \quad \mathbf{K}(2,2) += 4, \quad \mathbf{K}(2,3) += -2 \\
&\mathbf{K}(3,1) += 0, \quad \mathbf{K}(3,2) += -2, \quad \mathbf{K}(3,3) += 3 \\
\end{aligned}
\]

结果是：

\[
\mathbf{K} = \begin{bmatrix}
6 & -3 & 0 & 0 & 0 \\
-3 & 4 & -2 & 0 & 0 \\
0 & -2 & 3 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 \\
\end{bmatrix}
\]

#### 单元 2 (节点 3, 5, 1)

将 \(\mathbf{K}^e\) 组装到全局刚度矩阵 \(\mathbf{K}\) 的位置 (3,3), (3,5), (3,1), (5,3), (5,5), (5,1), (1,3), (1,5), (1,1):

\[ 
\begin{aligned}
&\mathbf{K}(3,3) += 6, \quad \mathbf{K}(3,5) += -3, \quad \mathbf{K}(3,1) += 0 \\
&\mathbf{K}(5,3) += -3, \quad \mathbf{K}(5,5) += 4, \quad \mathbf{K}(5,1) += -2 \\
&\mathbf{K}(1,3) += 0, \quad \mathbf{K}(1,5) += -2, \quad \mathbf{K}(1,1) += 3 \\
\end{aligned}
\]

结果是：

\[
\mathbf{K} = \begin{bmatrix}
9 & -3 & 0 & 0 & -2 \\
-3 & 4 & -2 & 0 & 0 \\
0 & -2 & 9 & 0 & -3 \\
0 & 0 & 0 & 0 & 0 \\
-2 & 0 & -3 & 0 & 4 \\
\end{bmatrix}
\]

#### 单元 3 (节点 3, 4, 2)

将 \(\mathbf{K}^e\) 组装到全局刚度矩阵 \(\mathbf{K}\) 的位置 (3,3), (3,4), (3,2), (4,3), (4,4), (4,2), (2,3), (2,4), (2,2):

\[ 
\begin{aligned}
&\mathbf{K}(3,3) += 6, \quad \mathbf{K}(3,4) += -3, \quad \mathbf{K}(3,2) += 0 \\
&\mathbf{K}(4,3) += -3, \quad \mathbf{K}(4,4) += 4, \quad \mathbf{K}(4,2) += -2 \\
&\mathbf{K}(2,3) += 0, \quad \mathbf{K}(2,4) += -2, \quad \mathbf{K}(2,2) += 3 \\
\end{aligned}
\]

结果是：

\[
\mathbf{K} = \begin{bmatrix}
9 & -3 & 0 & 0 & -2 \\
-3 & 7 & -2 & -2 & 0 \\
0 & -2 & 15 & -3 & -3 \\
0 & -2 & -3 & 4 & 0 \\
-2 & 0 & -3 & 0 & 4 \\
\end{bmatrix}
\]

因此，系统刚度矩阵 \(\mathbf{K}\) 为：

\[
\mathbf{K} = \begin{bmatrix}
9 & -3 & 0 & 0 & -2 \\
-3 & 7 & -2 & -2 & 0 \\
0 & -2 & 15 & -3 & -3 \\
0 & -2 & -3 & 4 & 0 \\
-2 & 0 & -3 & 0 & 4 \\
\end{bmatrix}
\]

\end{document}
