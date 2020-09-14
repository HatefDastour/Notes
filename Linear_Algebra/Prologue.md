# Prologue
Throughout Chapter 1 of the textbook, A First Course in Linear Algebra by K. Kuttler, there are a number of notations and terminologies that are introduced from Chapter 2 onwards. Therefore, in this prologue, we set the stage by briefly discussing some points of notation and terminology that will be used throughout this semester.

## Equation

An equation is a mathematical statement that two things are equal. A mathematical equation is an expression containing at least one variable (an unknown value) and an "equals sign" ( = ) with a mathematical expression on each side of it.

For example,
\begin{equation*}
x+2=3
\end{equation*}
is a mathematical equation where $x$ is a variable (unknown value).

## Plane

Plane is a flat surface that is infinitely large and with \underline{zero thickness}. For two planes in space we can have either **parallel planes** or **intersecting planes**.

### Parallel planes:

Parallel planes are the same distance apart everywhere, and so they never touch.

<img src='Figures/fig0_01.png' width='500' align="center"/>


### Intersecting planes:
If two planes are not parallel, then they will intersect (cross over) each other somewhere. Two planes always intersect at a line (This is similar to the way two lines intersect at a point.).

<img src='Figures/fig0_02.png' width='300' align="center"/>

## Hyperplane
In geometry, a **hyperplane** is a subspace whose dimension is one less than that of its ambient space. For example, if a space is 3-dimensional, then its hyperplanes are the 2-dimensional planes. Moreover, if the space is 2-dimensional, its hyperplanes are the 1-dimensional lines.

## Matrix

A matrix is a set of numbers laid out in tabular form (in rows and
columns). Usually the numbers are real numbers (real number such as $1$,
$5$, $\sqrt{2}$, $\frac{2}{3}$,...,\...). In general, matrices can
contain complex numbers[^1]. The rows of a matrix are each left-to-right
(horizontal) lines, and the columns of a matrix go top-to-bottom
(vertical).

Here is an example of a matrix with four rows and three columns:

<img src='Figures/fig0_03.png' width='600' align="center"/>

<div class="alert alert-block alert-info">
<font size="+2"><b>
    Remarks
</b></font>
</div>

1.  Each number that makes up a matrix is called an **element** or an
    **entry** of the matrix. The elements (entries) in a matrix have
    specific locations.

    For example, the upper left corner of the matrix is the first row
    (or simply, **row 1**) and the first column (or simply, **column
    1**). The entry at row 1 and column 1 is 1. Similarly, the entry at
    row 4 and column 4 is 11.

2.  A matrix with $m$ rows and $n$ columns is referred to as an
    $m\times n$ matrix or as having size $m\times n$.

    For example,
    $A=\begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 &9 \\ 10 & 11 & 12 \end{bmatrix}$
    is a $4\times 3$ matrix (it has four rows and three columns).

3.  $A$ matrix of size $1\times n$ is called a **row matrix** (it just
    has a row), whereas one of size $m\times1$ is called a **column
    matrix** (it has only a column).

    For example, $\begin{bmatrix} 1 & 2 & 3\end{bmatrix}$ is a row
    matrix and $\begin{bmatrix} 1 \\ 2 \\ 3\end{bmatrix}$ is a column
    matrix.

4.  $A$ is a **square matrix** if it has the same number of rows and
    columns.

    For example, $\begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$ and
    $\begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 &9\end{bmatrix}$
    are $2\times 2$ and $3\times 3$ square matrices, respectively.

5.  **Scalar multiplication of matrices**: If $A$ is a matrix and $k$ is
    a scalar (scalar is just a number, such as $2$, $3$,
    $\frac{5}{2}$,...), then $kA$ is another matrix which consists of
    elements of $A$ multiplied by $k$. See the following examples:
    $$\begin{aligned}
    2\begin{bmatrix} 1 \\ 2 \\ 3\end{bmatrix}=\begin{bmatrix} (2)(1) \\ (2)(2) \\ (2)(3)\end{bmatrix}
    =\begin{bmatrix} 2 \\ 4 \\ 6\end{bmatrix}
    \quad \text{ and } \quad
    2\begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}=\begin{bmatrix} (2)(1) & (2)(2) \\ (2)(3) & (2)(4) \end{bmatrix}
    =\begin{bmatrix} 2 & 4 \\ 6 & 8\end{bmatrix}.\end{aligned}$$

***
