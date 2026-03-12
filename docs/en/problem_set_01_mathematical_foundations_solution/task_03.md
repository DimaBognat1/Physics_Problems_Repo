# Problem 3 — Integration of motion

## A) For a given velocity

The velocity is given as:

v(t) = (2t, 3, -e^{-t})

Initial position:

r(0) = (0, 1, 2)

---

# 1. Position vector

Position is obtained by integrating velocity:

r(t) = r(0) + ∫₀ᵗ v(τ) dτ

Integrate each component.

First component:

∫ 2τ dτ = τ²

Second component:

∫ 3 dτ = 3τ

Third component:

∫ -e^{-τ} dτ = e^{-τ}

So

r(t) =
(
t²,
1 + 3t,
2 + e^{-t} - 1
)

Simplify:

r(t) =
(
t²,
1 + 3t,
1 + e^{-t}
)

---

# 2. Acceleration

Acceleration is the derivative of velocity:

a(t) = dv/dt

Differentiate each component:

2t → 2  
3 → 0  
−e^{-t} → e^{-t}

Therefore

a(t) = (2, 0, e^{-t})

---

# B) For a given acceleration

Acceleration:

a(t) = (4, −sin(t), 0)

Initial conditions:

v(0) = (1, 0, 2)

r(0) = (0, 0, 0)

---

# 1. Velocity

Velocity is the integral of acceleration:

v(t) = v(0) + ∫₀ᵗ a(τ) dτ

Integrate components.

First:

∫ 4 dτ = 4t

Second:

∫ −sin(τ) dτ = cos(τ)

Third:

∫ 0 dτ = 0

Thus

v(t) =
(
1 + 4t,
cos(t),
2
)

---

# 2. Position

Position is the integral of velocity:

r(t) = r(0) + ∫₀ᵗ v(τ) dτ

Integrate components.

First:

∫ (1 + 4τ) dτ = t + 2t²

Second:

∫ cos(τ) dτ = sin(t)

Third:

∫ 2 dτ = 2t

Therefore

r(t) =
(
t + 2t²,
sin(t),
2t
)
