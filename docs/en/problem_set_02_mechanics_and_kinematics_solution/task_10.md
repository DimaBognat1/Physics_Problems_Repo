# Problem 10 — Analysis of motion from numerical data

The position of the body is given by:

x(t) = t + (1/20)t²

The time interval is:

t ∈ [0, 10]

with time step:

Δt = 0.1

---

## 1. Velocity using the finite difference method

Velocity can be approximated using the finite difference formula:

v(t) ≈ (x(t + Δt) − x(t)) / Δt

This method estimates the derivative of position numerically.

---

## 2. Acceleration using the finite difference method

Acceleration can be approximated as the derivative of velocity:

a(t) ≈ (v(t + Δt) − v(t)) / Δt

This gives a numerical approximation of acceleration.

---

## 3. Analytical solution

Given:

x(t) = t + (1/20)t²

Velocity is the derivative:

v(t) = dx/dt = 1 + (1/10)t

Acceleration is the derivative of velocity:

a(t) = dv/dt = 1/10

So the acceleration is constant.

---

## 4. Effect of the time step

The accuracy of numerical differentiation depends on the time step Δt.

- Smaller Δt → higher accuracy
- Larger Δt → lower accuracy

Therefore reducing the time step improves the approximation of velocity and acceleration.
