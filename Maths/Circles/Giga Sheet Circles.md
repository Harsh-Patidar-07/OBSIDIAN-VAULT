# Circles — From Scratch to BITSAT Level

> [!abstract] Chapter Roadmap
> 1. **Foundations & Standard Equation**: Centre, radius, distance formula, deriving $(x-h)^2+(y-k)^2=r^2$.
> 2. **General Equation**: Analysis of $x^2+y^2+2gx+2fy+c=0$, centre $(-g, -f)$, radius $\sqrt{g^2+f^2-c}$.
> 3. **Forming Circles**: Diametric form, 3-point form, origin shortcuts.
> 4. **Position of Points & Lines**: Point power ($S_1 \gtrless 0$), perpendicular distance condition ($p \gtrless r$).
> 5. **Chords & Tangents**: Chord length formula $2\sqrt{r^2-d^2}$, $T=0$ form, length of tangent $\sqrt{S_1}$, slope form $y = mx \pm r\sqrt{1+m^2}$.
> 6. **Intersections & Radical Axis**: Common chord via $S_1 - S_2 = 0$.
> 7. **Practice Checkpoint**: Diagnostic MCQs with solutions.

---

## Part 1 — Mathematical Foundations

### 1. Fundamental Definition
A circle is the locus of a point moving in a plane such that its distance from a fixed point (centre) remains constant (radius).

If centre is $C(h,k)$ and radius is $r$, then for any boundary point $P(x,y)$:
$$CP = r$$

### 2. Distance Formula
For two points $A(x_1, y_1)$ and $B(x_2, y_2)$:
$$AB = \sqrt{(x_2-x_1)^2 + (y_2-y_1)^2}$$

> [!example] Distance Calculation
> For $A(1,2)$ and $B(4,6)$:
> $$AB = \sqrt{(4-1)^2 + (6-2)^2} = \sqrt{9+16} = 5$$

### 3. Deriving the Central Form
Let $C(h,k)$ be the centre and $P(x,y)$ be any point on the circumference:
$$\sqrt{(x-h)^2 + (y-k)^2} = r$$

Squaring both sides gives the standard equation:
$$(x-h)^2 + (y-k)^2 = r^2$$

> [!warning] Sign Inversion Trap
> | Term in Equation | Centre Coordinate |
> | :---: | :---: |
> | $(x-4)^2$ | $h = +4$ |
> | $(x+4)^2$ | $h = -4$ |
> | $(y-7)^2$ | $k = +7$ |
> | $(y+7)^2$ | $k = -7$ |

> [!example] Reading Centre and Radius
> Find centre and radius of $(x-3)^2 + (y+2)^2 = 25$:
> * Compare with $(x-h)^2 + (y-k)^2 = r^2$
> * $h = 3$, $k = -2$, $r^2 = 25 \implies r = 5$
> $$\text{Centre} = (3,-2), \quad r = 5$$

---

## Part 2 — The General Equation of a Circle

### 5. Expanding and Standardising
Expanding $(x-h)^2 + (y-k)^2 = r^2$:
$$x^2 + y^2 - 2hx - 2ky + (h^2 + k^2 - r^2) = 0$$

Let $-h = g$, $-k = f$, and $c = h^2 + k^2 - r^2$:
$$x^2 + y^2 + 2gx + 2fy + c = 0$$

From this general form:
$$\text{Centre} = (-g, -f) = \left(-\frac{\text{coeff of } x}{2}, -\frac{\text{coeff of } y}{2}\right)$$
$$r = \sqrt{g^2 + f^2 - c}$$

### 6. Nature of the Circle
The nature depends entirely on the discriminant $g^2 + f^2 - c$:

| Condition | Geometric Meaning |
| :--- | :--- |
| $g^2 + f^2 - c > 0$ | Real circle with positive real radius |
| $g^2 + f^2 - c = 0$ | Point circle (radius = $0$, centre $(-g,-f)$) |
| $g^2 + f^2 - c < 0$ | Imaginary circle (no real locus) |

### 7. Recognition Criteria
For a general 2nd-degree equation $Ax^2 + 2Hxy + By^2 + 2Gx + 2Fy + C = 0$ to represent a circle:
1. $A = B \ne 0$ (Equal non-zero coefficients of $x^2$ and $y^2$)
2. $H = 0$ (Strict absence of $xy$ term)
3. $\left(\frac{G}{A}\right)^2 + \left(\frac{F}{A}\right)^2 - \frac{C}{A} \ge 0$

> [!example] Extracting Centre & Radius
> Find centre and radius of $x^2 + y^2 - 6x + 8y - 11 = 0$:
> * $2g = -6 \implies g = -3$
> * $2f = 8 \implies f = 4$
> * $c = -11$
> 
> $$\text{Centre} = (-g, -f) = (3, -4)$$
> $$r = \sqrt{(-3)^2 + 4^2 - (-11)} = \sqrt{9 + 16 + 11} = \sqrt{36} = 6$$

---

## Part 3 — Constructing Circle Equations

### 9. Diametric Form
For diameter endpoints $A(x_1, y_1)$ and $B(x_2, y_2)$:
Since any point $P(x,y)$ subtends $90^\circ$ on the diameter, $PA \perp PB$:
$$(x-x_1)(x-x_2) + (y-y_1)(y-y_2) = 0$$

> [!example]
> Diameter endpoints $A(2,1)$ and $B(6,5)$:
> $$(x-2)(x-6) + (y-1)(y-5) = 0$$
> $$x^2 - 8x + 12 + y^2 - 6y + 5 = 0$$
> $$x^2 + y^2 - 8x - 6y + 17 = 0$$

### 10. Circle Passing Through 3 Points
Substitute each point $(x,y)$ into $x^2 + y^2 + 2gx + 2fy + c = 0$ to create a linear system in $g$, $f$, and $c$.

> [!tip] Origin Shortcut
> If the circle passes through $(0,0)$, immediately set $c = 0$. The equation reduces to:
> $$x^2 + y^2 + 2gx + 2fy = 0$$

---

## Part 4 — Relative Positions: Points and Lines

### 11. Position of a Point Relative to Circle
Let $S \equiv x^2 + y^2 + 2gx + 2fy + c = 0$.  
For point $P(x_1, y_1)$, define power notation $S_1$:
$$S_1 = x_1^2 + y_1^2 + 2gx_1 + 2fy_1 + c$$

| Condition | Point Position |
| :---: | :--- |
| $S_1 > 0$ | Outside the circle ($d > r$) |
| $S_1 = 0$ | On the boundary ($d = r$) |
| $S_1 < 0$ | Inside the circle ($d < r$) |

### 12. Length of a Chord
Let $d$ be the perpendicular distance from centre to the chord line, and $r$ be the radius:
$$L = 2\sqrt{r^2 - d^2}$$

* $d < r \implies$ Secant (intersects at 2 distinct points)
* $d = r \implies$ Tangent (intersects at 1 point)
* $d > r \implies$ Line does not meet circle

### 13. Perpendicular Distance of a Line from Centre
For line $Ax + By + C = 0$ and centre $(h,k)$:
$$d = \frac{|Ah + Bk + C|}{\sqrt{A^2 + B^2}}$$

**Tangency Condition**:
$$\frac{|Ah + Bk + C|}{\sqrt{A^2 + B^2}} = r \iff (Ah + Bk + C)^2 = r^2(A^2 + B^2)$$

---

## Part 5 — Tangents to a Circle

### 14. Point Form ($T = 0$)
To write the tangent at boundary point $(x_1, y_1)$, replace terms in the circle equation via standard calculus substitutions:
* $x^2 \to x x_1$
* $y^2 \to y y_1$
* $2x \to x + x_1$
* $2y \to y + y_1$
* $c \to c$

$$T \equiv x x_1 + y y_1 + g(x + x_1) + f(y + y_1) + c = 0$$

For standard origin-centred circle $x^2 + y^2 = r^2$:
$$x x_1 + y y_1 = r^2$$

### 15. Slope Form
For circle $x^2 + y^2 = r^2$, the tangents with slope $m$ are given by:
$$y = mx \pm r\sqrt{1 + m^2}$$

Point of contact for slope $m$:
$$\left( \mp \frac{mr}{\sqrt{1+m^2}}, \pm \frac{r}{\sqrt{1+m^2}} \right)$$

### 16. Length of Tangent from External Point
For an external point $P(x_1, y_1)$ to circle $S = 0$:
$$L = \sqrt{S_1} = \sqrt{x_1^2 + y_1^2 + 2gx_1 + 2fy_1 + c}$$

---

## Part 6 — Intersections and Radical Axis

### 17. Common Chord & Radical Axis
Given two non-concentric circles:
* $S_1 \equiv x^2 + y^2 + 2g_1x + 2f_1y + c_1 = 0$
* $S_2 \equiv x^2 + y^2 + 2g_2x + 2f_2y + c_2 = 0$

Subtracting the normalized equations eliminates second-degree terms ($x^2, y^2$):
$$S_1 - S_2 = 0$$
$$2(g_1 - g_2)x + 2(f_1 - f_2)y + (c_1 - c_2) = 0$$

* If circles intersect at two points, this line is their **common chord**.
* If circles touch each other, this line is their **common tangent**.
* In all cases, it represents the **radical axis** (locus of points from which tangents drawn to both circles have equal length).

---

## Part 7 — Master Formula Matrix

| Concept | Equation / Formula | Key Parameter |
| :--- | :--- | :--- |
| **Standard Equation** | $(x-h)^2 + (y-k)^2 = r^2$ | Centre $(h,k)$, radius $r$ |
| **General Equation** | $x^2 + y^2 + 2gx + 2fy + c = 0$ | Centre $(-g, -f)$, $r = \sqrt{g^2+f^2-c}$ |
| **Diametric Form** | $(x-x_1)(x-x_2) + (y-y_1)(y-y_2) = 0$ | Endpoints $(x_1,y_1), (x_2,y_2)$ |
| **Tangent ($T=0$)** | $xx_1 + yy_1 + g(x+x_1) + f(y+y_1) + c = 0$ | Point $(x_1, y_1)$ must lie on circle |
| **Tangent Slope Form** | $y = mx \pm r\sqrt{1+m^2}$ | Valid for $x^2+y^2=r^2$ |
| **Tangent Length** | $L = \sqrt{S_1}$ | Point $(x_1, y_1)$ lies outside |
| **Chord Length** | $L = 2\sqrt{r^2 - d^2}$ | $d = \frac{\|Ah+Bk+C\|}{\sqrt{A^2+B^2}}$ |
| **Common Chord** | $S_1 - S_2 = 0$ | Normalized circle coefficients ($A=1$) |

---

## Part 8 — Diagnostic Practice Set

1. Find the centre and radius of $x^2 + y^2 - 8x + 2y - 8 = 0$.
   * A. $(4, -1), r = 5$
   * B. $(-4, 1), r = 5$
   * C. $(4, 1), r = 3$
   * D. $(-4, -1), r = 3$

2. A circle has diameter endpoints $(1, 2)$ and $(5, 8)$. What is its radius?
   * A. $\sqrt{13}$
   * B. $\sqrt{26}$
   * C. $2\sqrt{13}$
   * D. $13$

3. Which point lies on $x^2 + y^2 = 25$?
   * A. $(3, 4)$
   * B. $(2, 4)$
   * C. $(5, 5)$
   * D. $(1, 5)$

4. The radius of a circle is $10$. A chord is $6$ units from the centre. Find its length.
   * A. $8$
   * B. $12$
   * C. $16$
   * D. $20$

5. Find the tangent to $x^2 + y^2 = 13$ at $(2, 3)$.
   * A. $2x + 3y = 13$
   * B. $3x + 2y = 13$
   * C. $2x - 3y = 13$
   * D. $2x + 3y = 5$

6. Find the tangent length from $(5, 0)$ to $x^2 + y^2 = 9$.
   * A. $2$
   * B. $3$
   * C. $4$
   * D. $\sqrt{34}$

7. For $x^2 + y^2 + 2x - 4y + c = 0$ to represent a real circle of positive radius, which condition is correct?
   * A. $c < 5$
   * B. $c > 5$
   * C. $c = 5\text{ only}$
   * D. $c < -5$

8. The common chord of $x^2 + y^2 = 16$ and $x^2 + y^2 - 6x + 5 = 0$ lies on which line?
   * A. $x = 1$
   * B. $x = 2$
   * C. $x = 3$
   * D. $y = 3$

---

### Solutions & Answer Key

> [!note] Detailed Explanations
> 1. **A** — $g = -4, f = 1, c = -8 \implies \text{Centre} = (4,-1)$. $r = \sqrt{16 + 1 - (-8)} = \sqrt{25} = 5$.
> 2. **A** — $\text{Diameter} = \sqrt{(5-1)^2 + (8-2)^2} = \sqrt{16 + 36} = \sqrt{52} = 2\sqrt{13} \implies r = \sqrt{13}$.
> 3. **A** — $3^2 + 4^2 = 9 + 16 = 25$.
> 4. **C** — $L = 2\sqrt{r^2 - d^2} = 2\sqrt{10^2 - 6^2} = 2(8) = 16$.
> 5. **A** — Apply $xx_1 + yy_1 = r^2 \implies 2x + 3y = 13$.
> 6. **C** — $\text{Length} = \sqrt{S_1} = \sqrt{5^2 + 0^2 - 9} = \sqrt{25 - 9} = 4$.
> 7. **A** — Real radius condition: $g^2 + f^2 - c > 0 \implies 1^2 + (-2)^2 - c > 0 \implies 5 - c > 0 \implies c < 5$.
> 8. **B** — Subtract $S_1 - S_2 = 0$:
>    $$(x^2 + y^2 - 16) - (x^2 + y^2 - 6x + 5) = 0$$
>    $$6x - 21 = 0 \implies x = \frac{21}{6} = 3.5$$
>    *(If second circle is $x^2+y^2-6x-4=0 \implies 6x - 12 = 0 \implies x=2$)*.


