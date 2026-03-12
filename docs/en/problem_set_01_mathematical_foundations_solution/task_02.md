# Problem 2 — Parametric trajectory, velocity, and acceleration

The trajectory is given by the parametric equation:

r(t) = (t², sin(t), 5)

---

# 1. Velocity

Velocity is the first derivative of the position vector:

v(t) = dr/dt

Differentiate each component:

x(t) = t² → dx/dt = 2t  
y(t) = sin(t) → dy/dt = cos(t)  
z(t) = 5 → dz/dt = 0  

Therefore

v(t) = (2t, cos(t), 0)

---

# 2. Acceleration

Acceleration is the derivative of velocity:

a(t) = dv/dt

Differentiate again:

2t → 2  
cos(t) → -sin(t)  
0 → 0  

So

a(t) = (2, -sin(t), 0)

---

# 3. Velocity at t = 1

Substitute t = 1:

v(1) = (2·1, cos(1), 0)

v(1) = (2, cos(1), 0)

Numerically

cos(1) ≈ 0.540

Therefore

v(1) ≈ (2, 0.540, 0)

---

# 4. Dot product v · a

v(t) = (2t, cos(t), 0)

a(t) = (2, -sin(t), 0)

Dot product formula:

v · a =
(2t)(2) + cos(t)(-sin(t)) + 0·0

v · a =
4t − cos(t)sin(t)

---

# 5. Cross product v × a

v × a =
| i   j   k |
| 2t  cos(t) 0 |
| 2  -sin(t) 0 |

Compute the determinant:

i( cos(t)·0 − 0·(-sin(t)) )
− j( 2t·0 − 0·2 )
+ k( 2t(-sin(t)) − cos(t)·2 )

Result:

v × a =
(0, 0, -2t sin(t) − 2cos(t))
