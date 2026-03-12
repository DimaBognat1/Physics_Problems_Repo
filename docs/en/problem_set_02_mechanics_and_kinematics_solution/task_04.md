# Problem 4 — Circular motion

A body moves in a circle of radius \(R\) with angular velocity \(\omega\).

---

## 1. Position vector \( \vec{r}(t) \)

For circular motion the position vector is:

\[
\vec{r}(t) =
\begin{pmatrix}
R\cos(\omega t) \\
R\sin(\omega t)
\end{pmatrix}
\]

Magnitude of the position vector:

\[
|\vec{r}(t)| = R
\]

The magnitude is constant because the motion occurs on a circle of radius \(R\).

---

## 2. Velocity vector \( \vec{v}(t) \)

Velocity is the derivative of the position vector:

\[
\vec{v}(t) = \frac{d\vec{r}}{dt}
\]

\[
\vec{v}(t) =
\begin{pmatrix}
- R\omega \sin(\omega t) \\
R\omega \cos(\omega t)
\end{pmatrix}
\]

Magnitude of velocity:

\[
|\vec{v}(t)| = R\omega
\]

Velocity is tangent to the circular trajectory.

---

## 3. Acceleration vector \( \vec{a}(t) \)

Acceleration is the derivative of velocity:

\[
\vec{a}(t) = \frac{d\vec{v}}{dt}
\]

\[
\vec{a}(t) =
\begin{pmatrix}
- R\omega^2 \cos(\omega t) \\
- R\omega^2 \sin(\omega t)
\end{pmatrix}
\]

Magnitude of acceleration:

\[
|\vec{a}(t)| = R\omega^2
\]

---

## 4. Centripetal acceleration

Acceleration is directed toward the center of the circle.

This can be written as:

\[
\vec{a}(t) = -\omega^2 \vec{r}(t)
\]

Therefore the acceleration is **centripetal**.

---

## 5. Interpretation

- The position vector describes circular motion.
- Velocity is always tangent to the circle.
- Acceleration always points toward the center.
- The magnitude of velocity is constant but the direction changes.
