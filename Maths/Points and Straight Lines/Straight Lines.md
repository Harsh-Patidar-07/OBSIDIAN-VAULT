# Summary of formulas

### Points: all formulas

| Concept           | Formula                                                      |
| ----------------- | ------------------------------------------------------------ |
| Distance          | $\sqrt{(x_2-x_1)^2+(y_2-y_1)^2}$                             |
| Midpoint          | $\left(\frac{x_1+x_2}{2},\frac{y_1+y_2}{2}\right)$           |
| Internal division | $\left(\frac{mx_2+nx_1}{m+n},\frac{my_2+ny_1}{m+n}\right)$   |
| External division | $\left(\frac{mx_2-nx_1}{m-n},\frac{my_2-ny_1}{m-n}\right)$   |
| Centroid          | $\left(\frac{x_1+x_2+x_3}{3},\frac{y_1+y_2+y_3}{3}\right)$   |
| Area of triangle  | $\frac12\lvert x_1(y_2-y_3)+x_2(y_3-y_1)+x_3(y_1-y_2)\rvert$ |
| Collinearity      | Area $=0$                                                    |

### Straight lines: all formulas

| Concept                       | Formula                                                            |
| ----------------------------- | ------------------------------------------------------------------ |
| Slope                         | $m=\frac{y_2-y_1}{x_2-x_1}$                                        |
| Slope-angle relation          | $m=\tan\theta$                                                     |
| Slope-intercept               | $y=mx+c$                                                           |
| Point-slope                   | $y-y_1=m(x-x_1)$                                                   |
| Two-point                     | $\frac{y-y_1}{y_2-y_1}=\frac{x-x_1}{x_2-x_1}$                      |
| Intercept                     | $\frac xa+\frac yb=1$                                              |
| General                       | $Ax+By+C=0$                                                        |
| Slope of general line         | $-A/B$                                                             |
| Parallel lines                | $m_1=m_2$                                                          |
| Perpendicular lines           | $m_1m_2=-1$                                                        |
| Angle between lines           | $\tan\theta=\left\lvert\frac{m_1-m_2}{1+m_1m_2}\right\rvert$       |
| Point-line distance           | $\frac{\lvert Ax_1+By_1+C\rvert}{\sqrt{A^2+B^2}}$                  |
| Parallel-line distance        | $\frac{\lvert C_1-C_2\rvert}{\sqrt{A^2+B^2}}$                      |
| Normal form                   | $x\cos\alpha+y\sin\alpha=p$                                        |
| Angle bisectors               | $\frac{L_1}{\sqrt{A_1^2+B_1^2}}=\pm\frac{L_2}{\sqrt{A_2^2+B_2^2}}$ |
| Family of lines               | $L_1+\lambda L_2=0$                                                |
| **Condition of Concurrency:** | The determinant of coefficients must equal 0.                      |

**Standard Formula for Area of a Parallelogram bounded by lines:** For the four lines:$L_1: a_1 x + b_1 y + c_1 = 0$$L_2: a_1 x + b_1 y + c_2 = 0$$L_3: a_2 x + b_2 y + d_1 = 0$$L_4: a_2 x + b_2 y + d_2 = 0$

$$\text{Area} = \left\vert{} \frac{(c_1 - c_2)(d_1 - d_2)}{a_1 b_2 - a_2 b_1} \right\vert{}$$

---

![[Pasted image 20261031222226.png]]
![[Pasted image 20261031222258.png]]
**![[Pasted image 20261031223811.png]]**


- **Acute vs. Obtuse Bisector Rule via Angle with a Line:** If $\theta$ is the angle between a line and one of its angle bisectors:
    
    - If $\vert{}\tan\theta\vert{} < 1 \implies \theta < 45^\circ$, the bisector is the **acute angle bisector**.
        
    - If $\vert{}\tan\theta\vert{} > 1 \implies \theta > 45^\circ$, the bisector is the **obtuse angle bisector**.

---


### Point-slope form

Suppose you know:

- A point $(x_1,y_1)$on the line.
    
- The slope $(m)$.

You can directly write:

$$\boxed{y-y_1=m(x-x_1)}$$


---

### Intercept form

Suppose a line cuts:

- X-axis at $(a,0)$.
    
- Y-axis at $(0,b)$.

Then its equation is:

$$\boxed{\frac{x}{a}+\frac{y}{b}=1}$$


---

### General form of a straight line

This is another very important representation.

$$\boxed{Ax+By+C=0}$$

Here A, B and C are constants, and A and B cannot both be zero.

Compare with:

$$y=mx+c$$

Therefore:

$$\boxed{m=-\frac AB}$$


- If \(A=0\), the line is horizontal provided $B\neq0$.
    
- If \(B=0\), the line is vertical  provided $A\neq0$.

---

| Form            | Equation                                        | Given information     |
| --------------- | ----------------------------------------------- | --------------------- |
| Slope-intercept | $y=mx+c$                                        | Slope and Y-intercept |
| Point-slope     | $y-y_1=m(x-x_1)$                                | Point and slope       |
| Two-point       | $(\frac{y-y_1}{y_2-y_1}=\frac{x-x_1}{x_2-x_1})$ | Two points            |
| Intercept       | $(\frac xa+\frac yb=1)$                         | Both intercepts       |
| General         | $(Ax+By+C=0)$                                   | General equation      |

---

## 2 lines perpendicular condition

For two lines:

$A_1x+B_1y+C_1=0$

$A_2x+B_2y+C_2=0$

The perpendicular condition is:

$$\boxed{A_1A_2+B_1B_2=0}$$


---

## 2 parallel lines

For:

$A_1x+B_1y+C_1=0$

$A_2x+B_2y+C_2=0$

Parallel lines satisfy:

$$\boxed{A_1B_2=A_2B_1}$$


---

## Angle between 2 straight lines

$$ \boxed{\tan\theta=\left|\frac{m_1-m_2}{1+m_1m_2}\right|} $$


---

## Important 

Two straight lines can have:

1. One intersection point: intersecting lines.
    
2. No intersection point: distinct parallel lines.
    
3. Infinitely many common points: coincident lines.

For general equations:

$A_1x+B_1y+C_1=0$

$A_2x+B_2y+C_2=0$

| Condition                                            | Result       |
| ---------------------------------------------------- | ------------ |
| $\frac{A_1}{A_2}\neq\frac{B_1}{B_2}$                 | Intersecting |
| $\frac{A_1}{A_2}=\frac{B_1}{B_2}\neq\frac{C_1}{C_2}$ | Parallel     |
| All three ratios equal                               | Coincident   |


---

## Distance of a point from a straight line

$$ \boxed{d=\frac{|Ax_1+By_1+C|}{\sqrt{A^2+B^2}}} $$


---

## Distance between two parallel lines

Suppose we have:

$L_1:Ax+By+C_1=0$

$L_2:Ax+By+C_2=0$

Notice that the coefficients of x and y are identical.

The lines are parallel.

Their perpendicular distance is:

$$\boxed{d=\frac{|C_1-C_2|}{\sqrt{A^2+B^2}}}$$


---

## Angle bisectors of two straight lines

Suppose two lines intersect:

$$
L_1:A_1x+B_1y+C_1=0
$$

$$
L_2:A_2x+B_2y+C_2=0
$$

They form four angles.

The lines that divide these angles into two equal parts are called angle bisectors.

The equations of the angle bisectors are:

$$
{
\frac{A_1x+B_1y+C_1}{\sqrt{A_1^2+B_1^2}}
=
\pm
\frac{A_2x+B_2y+C_2}{\sqrt{A_2^2+B_2^2}}
}
$$


---

## Family of straight lines

Suppose two lines intersect at a common point:

$$
L_1=0
$$

$$
L_2=0
$$

Then the family of all straight lines passing through their intersection is:

$$
\boxed{L_1+\lambda L_2=0}
$$

Here $\lambda$ is an arbitrary parameter.

Example
Find the family of lines passing through the intersection of:

$$
x+y-5=0
$$

$$
2x-y-1=0
$$

Using the family formula:

$$
(x+y-5)+\lambda(2x-y-1)=0
$$

That's the required family.

For example, if you want a particular line in this family to have slope 2, you can substitute its coefficients into the slope formula and determine $\lambda$.


---

## Normal form of a straight line

The normal form is:

$$
\boxed{x\cos\alpha+y\sin\alpha=p}
$$

Here:
- $p$ = perpendicular distance of the line from the origin.
- $\alpha$ = angle made by the perpendicular from the origin with the positive X-axis

---

# Important

Equation of a line parallel or perpendicular to a given line through a point
These questions are very common and combine several formulas.

### Case 1: Parallel line

Find the equation of a line passing through $(2,3)$ and parallel to:

$$
2x+3y-7=0
$$

Parallel lines have the same slope.

An easier observation: the coefficients of x and y remain the same.

Therefore, the required equation is:

$$
2x+3y+C=0
$$

Since it passes through $(2,3)$:

$$
2(2)+3(3)+C=0
$$

$$
4+9+C=0
$$

$$
C=-13
$$

Answer:

$$
\boxed{2x+3y-13=0}
$$

### Case 2: Perpendicular line

Find the equation of a line passing through $(2,3)$ and perpendicular to:

$$
2x+3y-7=0
$$

First find the given line's slope:

$$
m_1=-\frac23
$$

For a perpendicular line:

$$
m_1m_2=-1
$$

$$
-\frac23m_2=-1
$$

$$
m_2=\frac32
$$

Now use point-slope form:

$$
y-3=\frac32(x-2)
$$

Multiply by 2:

$$
2y-6=3x-6
$$

Therefore:

$$
\boxed{3x-2y=0}
$$


---

