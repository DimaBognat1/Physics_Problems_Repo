# Problem 1 — Vectors and Linear Transformations

## Given vectors

\[
\vec a = (2, -1, 3)
\]

\[
\vec b = (1, 4, -2)
\]

---

# 1. Length of the vectors

The length of a vector is defined as:

\[
|\vec v| = \sqrt{x^2 + y^2 + z^2}
\]

### Length of vector **a**

\[
|\vec a| =
\sqrt{2^2 + (-1)^2 + 3^2}
\]

\[
|\vec a| =
\sqrt{4 + 1 + 9}
\]

\[
|\vec a| =
\sqrt{14}
\]

---

### Length of vector **b**

\[
|\vec b| =
\sqrt{1^2 + 4^2 + (-2)^2}
\]

\[
|\vec b| =
\sqrt{1 + 16 + 4}
\]

\[
|\vec b| =
\sqrt{21}
\]

---

# 2. Normalized vector

The normalized vector is:

\[
\hat a = \frac{\vec a}{|\vec a|}
\]

\[
\hat a =
\left(
\frac{2}{\sqrt{14}},
\frac{-1}{\sqrt{14}},
\frac{3}{\sqrt{14}}
\right)
\]

---

# 3. Dot product

The dot product is defined as:

\[
\vec a \cdot \vec b =
a_x b_x + a_y b_y + a_z b_z
\]

Substituting the values:

\[
= 2·1 + (-1)·4 + 3·(-2)
\]

\[
= 2 - 4 - 6
\]

\[
= -8
\]

---

# Angle between vectors

\[
\cos\theta =
\frac{\vec a \cdot \vec b}{|\vec a||\vec b|}
\]

\[
\cos\theta =
\frac{-8}{\sqrt{14}\sqrt{21}}
\]

\[
\cos\theta =
\frac{-8}{\sqrt{294}}
\]

---

# 4. Cross product

\[
\vec a \times \vec b =
\begin{vmatrix}
i & j & k \\
2 & -1 & 3 \\
1 & 4 & -2
\end{vmatrix}
\]

Result:

\[
\vec a \times \vec b =
(-10, 7, 9)
\]

---

# Area of parallelogram

The area equals the magnitude of the cross product:

\[
|\vec a \times \vec b|
\]

\[
=
\sqrt{(-10)^2 + 7^2 + 9^2}
\]

\[
=
\sqrt{100 + 49 + 81}
\]

\[
=
\sqrt{230}
\]

---

# 5. Matrix transformation

Matrix:

\[
A =
\begin{pmatrix}
2 & 1 & 0 \\
0 & 1 & -1 \\
1 & 0 & 1
\end{pmatrix}
\]

Vector:

\[
\vec a = (2,-1,3)
\]

---

## Multiplication \(A\vec a\)

\[
A\vec a =
\begin{pmatrix}
2·2 + 1·(-1) + 0·3 \\
0·2 + 1·(-1) + (-1)·3 \\
1·2 + 0·(-1) + 1·3
\end{pmatrix}
\]

\[
=
\begin{pmatrix}
3 \\
-4 \\
5
\end{pmatrix}
\]

---

# Determinant of the matrix

\[
det(A)
=
\begin{vmatrix}
2 & 1 & 0 \\
0 & 1 & -1 \\
1 & 0 & 1
\end{vmatrix}
\]

\[
= 2(1·1 - (-1)·0) - 1(0·1 - (-1)·1)
\]

\[
= 2 - 1
\]

\[
= 1
\]

---

# Orientation of space

If

```
det(A) > 0
```

then the transformation preserves the orientation.

Since

```
det(A) = 1 > 0
```

the orientation of space **is preserved**.
