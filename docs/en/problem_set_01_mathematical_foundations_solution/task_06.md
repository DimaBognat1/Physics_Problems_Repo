# Problem 6 — Curve length and numerical integration

The trajectory is given parametrically:

x(t) = t  
y(t) = t²  

t ∈ [0,1]

---

# 1. Velocity

Velocity is the derivative of the position vector.

v(t) = (dx/dt, dy/dt)

dx/dt = 1  
dy/dt = 2t  

Therefore

v(t) = (1, 2t)

---

# 2. Magnitude of velocity

|v(t)| = √(1² + (2t)²)

|v(t)| = √(1 + 4t²)

---

# 3. Arc length

The arc length of a parametric curve is

s = ∫ |v(t)| dt

Therefore

s = ∫₀¹ √(1 + 4t²) dt

---

# 4. Analytical solution

The integral

∫ √(1 + 4t²) dt

can be solved using substitution.

Let

u = 2t

Then

du = 2 dt

The integral becomes

½ ∫ √(1 + u²) du

The result is

s = (1/4) [ u√(1 + u²) + ln(u + √(1 + u²)) ]

Substitute u = 2t and evaluate from 0 to 1.

---

# 5. Numerical method (trapezoidal rule)

The trapezoidal rule approximates an integral as

∫ₐᵇ f(t) dt ≈ (Δt/2) Σ [ f(t_i) + f(t_{i+1}) ]

where

Δt = (b - a) / N

and N is the number of divisions.

Increasing N improves the accuracy of the approximation.

---

# 6. Convergence

As N increases:

- the numerical solution approaches the analytical value
- the approximation error decreases

This demonstrates the convergence of the trapezoidal method.
