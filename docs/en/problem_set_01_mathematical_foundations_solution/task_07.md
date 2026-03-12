# Problem 7 — Work of a force along a trajectory

The force field is given by

F(x,y) = (y, 2x)

The trajectory is

x = t  
y = t²  

t ∈ [0,1]

---

# 1. Velocity

Velocity is the derivative of the position vector.

r(t) = (t, t²)

v(t) = dr/dt

dx/dt = 1  
dy/dt = 2t  

Therefore

v(t) = (1, 2t)

---

# 2. Work done by the force

Work is defined as the line integral

W = ∫ F · dr

Since

dr = v(t) dt

we compute

W = ∫₀¹ F(r(t)) · v(t) dt

---

# 3. Substitute the trajectory

F(x,y) = (y, 2x)

Substitute

x = t  
y = t²

F(t) = (t², 2t)

---

# 4. Dot product

F · v =
(t², 2t) · (1, 2t)

= t²·1 + 2t·2t

= t² + 4t²

= 5t²

---

# 5. Compute the integral

W = ∫₀¹ 5t² dt

W = 5 ∫₀¹ t² dt

W = 5 [ t³/3 ]₀¹

W = 5/3

---

# Result

The work done by the force along the trajectory is

W = 5/3
