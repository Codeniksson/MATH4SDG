---
title: "Chapter 2"
---

# Chapter 2: Intro

# Lagrange Multipliers Method

Lagrange multipliers help find extrema (maxima/minima) of a function subject to constraints.

## Concept

Given:
- A function to optimize: \( f(x, y, \dots) \)
- A constraint: \( g(x, y, \dots) = 0 \)

Introduce a **Lagrange multiplier** \( \lambda \) and define the **Lagrangian**:

\[
\mathcal{L}(x, y, \dots, \lambda) = f(x, y, \dots) - \lambda g(x, y, \dots)
\]

## Steps

1. Compute partial derivatives:
   \[
   \nabla \mathcal{L} = 0
   \]
   This leads to the system:
   \[
   \nabla f = \lambda \nabla g
   \]
   \[
   g(x, y, \dots) = 0
   \]
2. Solve for \( x, y, \dots \) and \( \lambda \).

## Interpretation

- The constraint surface and the level curves of \( f \) are **tangent** at optimal points.
- The method ensures we stay within the constraint while optimizing.

## Example

Maximize \( f(x, y) = x + y \) subject to \( x^2 + y^2 = 1 \):

1. Define the Lagrangian:
   \[
   \mathcal{L} = x + y - \lambda (x^2 + y^2 - 1)
   \]
2. Compute gradients:
   \[
   \frac{\partial \mathcal{L}}{\partial x} = 1 - 2\lambda x = 0
   \]
   \[
   \frac{\partial \mathcal{L}}{\partial y} = 1 - 2\lambda y = 0
   \]
   \[
   x^2 + y^2 - 1 = 0
   \]
3. Solve the system to find optimal \( (x, y) \).

Lagrange multipliers are widely used in physics, economics, and engineering for constrained optimization.


