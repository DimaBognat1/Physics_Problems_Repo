# Problem 5 — Trajectory curvature and normal acceleration

For an ellipse:

x = a cos(t)  
y = b sin(t)

---

# 1. Velocity

Velocity is the derivative of the position vector.

x'(t) = -a sin(t)  
y'(t) = b cos(t)

v(t) = (-a sin(t), b cos(t))

Magnitude of velocity:

|v| = √(a² sin²t + b² cos²t)

---

# 2. Acceleration

Acceleration is the derivative of velocity.

x''(t) = -a cos(t)  
y''(t) = -b sin(t)

a(t) = (-a cos(t), -b sin(t))

---

# 3. Unit tangent vector

The unit tangent vector is

T(t) = v(t) / |v(t)|

Therefore

T(t) = (-a sin(t), b cos(t)) / √(a² sin²t + b² cos²t)

---

# 4. Normal acceleration

Acceleration can be decomposed into tangential and normal components:

a = a_t + a_n

The magnitude of the normal acceleration is related to curvature:

a_n = v² / R

where R is the radius of curvature.

---

# 5. Radius of curvature at t = 0

At t = 0:

sin(0) = 0  
cos(0) = 1

Velocity:

v(0) = (0, b)

|v(0)| = b

Acceleration:

a(0) = (-a, 0)

Magnitude:

|a(0)| = a

Using

a_n = v² / R

we obtain

a = b² / R

Therefore

R = b² / a

---

# 6. Special case: circle

If

a = b

the ellipse becomes a circle.

In this case the radius of curvature equals the radius of the circle and the motion becomes uniform circular motion.
