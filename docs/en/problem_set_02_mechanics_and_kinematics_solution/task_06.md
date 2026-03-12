# Problem 6 — Cycloid: trajectory of a point on a rolling circle

A circle of radius \(R\) rolls without slipping along the x-axis.  
A point on the rim of the circle traces a cycloid with parametric equations:

\[
x(t) = R(\omega t - \sin(\omega t))
\]

\[
y(t) = R(1 - \cos(\omega t))
\]

---

## 1. Velocity

Velocity components are the derivatives of position:

\[
v_x(t) = \frac{dx}{dt} = R\omega(1 - \cos(\omega t))
\]

\[
v_y(t) = \frac{dy}{dt} = R\omega \sin(\omega t)
\]

Velocity vector:

\[
\vec{v}(t) = (R\omega(1-\cos(\omega t)), \; R\omega\sin(\omega t))
\]

Magnitude of velocity:

\[
|\vec{v}(t)| = \sqrt{[R\omega(1-\cos(\omega t))]^2 + [R\omega\sin(\omega t)]^2}
\]

---

## 2. When does the point stop?

The point temporarily stops when the velocity is zero:

\[
v_x = 0
\]

\[
v_y = 0
\]

This occurs when:

\[
\omega t = 2\pi n
\]

where \(n\) is an integer.

At these moments the point touches the ground.

---

## 3. Acceleration

Acceleration components are derivatives of velocity:

\[
a_x(t) = \frac{dv_x}{dt} = R\omega^2\sin(\omega t)
\]

\[
a_y(t) = \frac{dv_y}{dt} = R\omega^2\cos(\omega t)
\]

Acceleration vector:

\[
\vec{a}(t) = (R\omega^2\sin(\omega t), \; R\omega^2\cos(\omega t))
\]

---

## 4. Maximum values

The maximum velocity magnitude occurs when the sine and cosine terms produce the largest result.

The approximate maximum velocity is:

\[
|\vec{v}|_{max} = 2R\omega
\]

The maximum acceleration magnitude is:

\[
|\vec{a}|_{max} = R\omega^2
\]

---

## 5. Interpretation

The cycloid is the trajectory of a point on the rim of a rolling wheel.

Important properties:

- the point periodically stops when touching the ground,
- the path consists of repeating arches,
- the motion combines rotation and translation.
