# Problem 8 — First-order differential equation

The equation is

dy/dt = −k y

---

# 1. Solve the equation

Separate variables:

dy/y = −k dt

Integrate both sides:

∫ (1/y) dy = ∫ −k dt

ln|y| = −k t + C

Exponentiate:

y(t) = C e^(−k t)

---

# 2. Initial condition

If the initial value is

y(0) = y₀

then

C = y₀

Therefore the solution becomes

y(t) = y₀ e^(−k t)

---

# Interpretation

The solution describes **exponential decay**.

For k > 0 the value decreases over time.
