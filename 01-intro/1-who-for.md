---
title: "Chapter 1"
---

# Chapter 1: Who is this for


## Simple Pendulum Modeling

A **simple pendulum** consists of:
- A **mass** \(m\) (the bob)
- A **string** of length \(L\)
- A **pivot point** (where the string is fixed)

When displaced, the pendulum swings under the influence of **gravity**, following the equation:

\[
\frac{d^2\theta}{dt^2} + \frac{g}{L} \sin\theta = 0
\]

Where:
- \( \theta \) = Angular displacement (radians)
- \( g \) = Acceleration due to gravity (\(9.81 m/s^2\))
- \( L \) = Length of the pendulum
- \( t \) = Time

## Small Angle Approximation
For **small angles** (\(\theta \approx 0\)), we use **\(\sin\theta \approx \theta\)**, simplifying the equation:

\[
\frac{d^2\theta}{dt^2} + \frac{g}{L} \theta = 0
\]

This is a **second-order linear differential equation**, representing **simple harmonic motion (SHM)** with the solution:

\[
\theta(t) = \theta_0 \cos(\omega t + \phi)
\]

where \( \omega = \sqrt{\frac{g}{L}} \) is the **natural frequency**.

