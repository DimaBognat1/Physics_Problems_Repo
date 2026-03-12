# Problem 7 — 2D motion with a given acceleration

Given acceleration:

a = (2, -3)

Initial conditions:

v(0) = (1, 0)  
r(0) = (0, 0)

---

## 1. Velocity

Acceleration is the derivative of velocity:

a = dv/dt

Integrating:

v(t) = v(0) + a t

Substitute the values:

v(t) = (1,0) + (2,-3)t

Velocity components:

vx(t) = 1 + 2t  
vy(t) = -3t

Velocity vector:

v(t) = (1 + 2t, -3t)

---

## 2. Position

Position is the integral of velocity:

r(t) = r(0) + ∫ v(t) dt

Integrate each component.

x(t):

x(t) = ∫(1 + 2t) dt

x(t) = t + t²

y(t):

y(t) = ∫(-3t) dt

y(t) = -3/2 t²

Therefore:

r(t) = (t + t², -3/2 t²)

---

## 3. Trajectory

The trajectory is defined by the parametric equations:

x(t) = t + t²  
y(t) = -3/2 t²

This describes a curved trajectory determined by constant acceleration.
