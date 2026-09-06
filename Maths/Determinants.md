# Cramer's Rule & Types of Solutions

Think of Cramer's Rule as basic division:

$$x = \frac{\Delta_x}{\Delta}, \quad y = \frac{\Delta_y}{\Delta}, \quad z = \frac{\Delta_z}{\Delta}$$

Treat it just like a simple fraction $\frac{\text{Numerator}}{\text{Denominator}}$:

---

## 1. Non-Homogeneous Equations ($AX = B$, where constants $\neq 0$)

| Condition | Fraction Analogy | Nature of Solution | System Status |
| :--- | :--- | :--- | :--- |
| **$\Delta \neq 0$** | $\frac{\text{Number}}{\text{Non-Zero}}$ | **Unique Solution** (Exactly one $(x, y, z)$) | Consistent |
| **$\Delta = 0$** and at least one $\Delta_x, \Delta_y, \Delta_z \neq 0$ | $\frac{\text{Non-Zero}}{0}$ (Math error) | **No Solution** | Inconsistent |
| **$\Delta = 0$** and **$\Delta_x = \Delta_y = \Delta_z = 0$** | $\frac{0}{0}$ (Indeterminate) | **Infinitely Many Solutions** *(or No Solution if planes are parallel)* | Consistent / Inconsistent |

> **Exam Shortcut:** A linear system can **never** have "two solutions" or "three solutions". The answer is always: $1$, $0$, or $\infty$.

---

## 2. Homogeneous Equations ($AX = 0$, all constants $= 0$)

Here, the constants are all zero, so $\Delta_x = \Delta_y = \Delta_z = 0$ is **always guaranteed**.

### What do "Trivial" and "Non-Trivial" mean?

* **Trivial Solution:** The obvious, boring zero-answer:
  $$(x, y, z) = (0, 0, 0)$$
  * Because $0 + 0 + 0 = 0$ always works, this solution **always exists**.

* **Non-Trivial Solution:** Any solution where **at least one variable is not zero**:
  $$(x, y, z) \neq (0, 0, 0)$$

---

### The Decision Rule for Homogeneous Systems

* **$\Delta \neq 0$ $\implies$ Only Trivial Solution (Unique)**
  * The only answer is $(0, 0, 0)$.

* **$\Delta = 0$ $\implies$ Non-Trivial Solutions (Infinitely Many)**
  * There are infinitely many non-zero solutions alongside the $(0, 0, 0)$ solution.


---

>You can never add 2 determinants first and then find the determinant of the summed one.
>
Always find the determinants individually then sum them.


---
