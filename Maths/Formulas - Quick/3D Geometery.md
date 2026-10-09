# 3D Geometry Formulas (Class 11 and 12 Combined)

## 1. Coordinate Basics

### 1.1 Distance Formula

Distance between two points $A(x_1, y_1, z_1)$ and $B(x_2, y_2, z_2)$:

$$
AB = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2}
$$

### 1.2 Section Formula

If a point $P$ divides the line segment joining $A(x_1, y_1, z_1)$ and $B(x_2, y_2, z_2)$ in the ratio $m : n$ internally, then:

$$
P = \left( \frac{mx_2 + nx_1}{m+n}, \frac{my_2 + ny_1}{m+n}, \frac{mz_2 + nz_1}{m+n} \right)
$$

Midpoint when $m = n$:

$$
P = \left( \frac{x_1 + x_2}{2}, \frac{y_1 + y_2}{2}, \frac{z_1 + z_2}{2} \right)
$$

### 1.3 Distance of a Point from Coordinate Axes

For point $P(x, y, z)$:

- Distance from x-axis: $\sqrt{y^2 + z^2}$
- Distance from y-axis: $\sqrt{x^2 + z^2}$
- Distance from z-axis: $\sqrt{x^2 + y^2}$

---

## 2. Direction Cosines and Direction Ratios

### 2.1 Direction Cosines

If a directed line makes angles $\alpha, \beta, \gamma$ with the positive x, y, z axes respectively, then:

$$
l = \cos\alpha, \quad m = \cos\beta, \quad n = \cos\gamma
$$

Fundamental identity:

$$
l^2 + m^2 + n^2 = 1
$$

### 2.2 Direction Ratios

Any three numbers $a, b, c$ proportional to the direction cosines are called direction ratios.

$$
l = \pm \frac{a}{\sqrt{a^2 + b^2 + c^2}}, \quad
m = \pm \frac{b}{\sqrt{a^2 + b^2 + c^2}}, \quad
n = \pm \frac{c}{\sqrt{a^2 + b^2 + c^2}}
$$

Take the same sign consistently.

### 2.3 Direction Ratios of a Line Joining Two Points

For the line joining $A(x_1, y_1, z_1)$ and $B(x_2, y_2, z_2)$:

$$
\text{d.r.'s} \propto (x_2 - x_1), \ (y_2 - y_1), \ (z_2 - z_1)
$$

Direction cosines:

$$
l = \frac{x_2 - x_1}{AB}, \quad
m = \frac{y_2 - y_1}{AB}, \quad
n = \frac{z_2 - z_1}{AB}
$$

where $AB$ is the distance between the two points.

---

## 3. Equations of a Line in Space

### 3.1 Vector Equation

A line passing through a point with position vector $\vec{a}$ and parallel to vector $\vec{b}$:

$$
\vec{r} = \vec{a} + \lambda \vec{b}, \quad \lambda \in \mathbb{R}
$$

### 3.2 Cartesian Equation (Symmetric Form)

Line passing through $(x_1, y_1, z_1)$ with direction ratios $a, b, c$:

$$
\frac{x - x_1}{a} = \frac{y - y_1}{b} = \frac{z - z_1}{c}
$$

### 3.3 Line Through Two Points

Line passing through $A(x_1, y_1, z_1)$ and $B(x_2, y_2, z_2)$:

$$
\frac{x - x_1}{x_2 - x_1} = \frac{y - y_1}{y_2 - y_1} = \frac{z - z_1}{z_2 - z_1}
$$

---

## 4. Angle Between Two Lines

If two lines have direction cosines $(l_1, m_1, n_1)$ and $(l_2, m_2, n_2)$, the angle $\theta$ between them satisfies:

$$
\cos\theta = \left| l_1l_2 + m_1m_2 + n_1n_2 \right|
$$

In terms of direction ratios $a_1, b_1, c_1$ and $a_2, b_2, c_2$:

$$
\cos\theta = \left| \frac{a_1a_2 + b_1b_2 + c_1c_2}{\sqrt{a_1^2 + b_1^2 + c_1^2} \sqrt{a_2^2 + b_2^2 + c_2^2}} \right|
$$

Conditions:

- Perpendicular lines: $a_1a_2 + b_1b_2 + c_1c_2 = 0$
- Parallel lines: $\frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2}$

---

## 5. Shortest Distance Between Two Lines

### 5.1 Skew Lines

For lines $\vec{r} = \vec{a}_1 + \lambda \vec{b}_1$ and $\vec{r} = \vec{a}_2 + \mu \vec{b}_2$:

$$
d = \left| \frac{(\vec{a}_2 - \vec{a}_1) \cdot (\vec{b}_1 \times \vec{b}_2)}{|\vec{b}_1 \times \vec{b}_2|} \right|
$$

Cartesian form: For lines

$$
\frac{x - x_1}{a_1} = \frac{y - y_1}{b_1} = \frac{z - z_1}{c_1}
$$

and

$$
\frac{x - x_2}{a_2} = \frac{y - y_2}{b_2} = \frac{z - z_2}{c_2}
$$

$$
d = \frac{
\left|
\begin{vmatrix}
x_2 - x_1 & y_2 - y_1 & z_2 - z_1 \\
a_1 & b_1 & c_1 \\
a_2 & b_2 & c_2
\end{vmatrix}
\right|
}{
\sqrt{(b_1c_2 - b_2c_1)^2 + (c_1a_2 - c_2a_1)^2 + (a_1b_2 - a_2b_1)^2}
}
$$

### 5.2 Parallel Lines

For parallel lines $\vec{r} = \vec{a}_1 + \lambda \vec{b}$ and $\vec{r} = \vec{a}_2 + \mu \vec{b}$:

$$
d = \left| \frac{(\vec{a}_2 - \vec{a}_1) \times \vec{b}}{|\vec{b}|} \right|
$$

---

## 6. Plane

### 6.1 General Equation

$$
ax + by + cz + d = 0
$$

where $(a, b, c)$ is the normal vector to the plane.

### 6.2 Point-Normal Form

Plane passing through $(x_1, y_1, z_1)$ with normal $(a, b, c)$:

$$
a(x - x_1) + b(y - y_1) + c(z - z_1) = 0
$$

### 6.3 Intercept Form

Plane cutting axes at $(p, 0, 0)$, $(0, q, 0)$, $(0, 0, r)$:

$$
\frac{x}{p} + \frac{y}{q} + \frac{z}{r} = 1
$$

### 6.4 Normal Form

If $p$ is the perpendicular distance from origin and $l, m, n$ are the direction cosines of the normal:

$$
lx + my + nz = p
$$

### 6.5 Plane Through Three Non-Collinear Points

Plane passing through $A(x_1, y_1, z_1)$, $B(x_2, y_2, z_2)$, $C(x_3, y_3, z_3)$:

$$
\begin{vmatrix}
x - x_1 & y - y_1 & z - z_1 \\
x_2 - x_1 & y_2 - y_1 & z_2 - z_1 \\
x_3 - x_1 & y_3 - y_1 & z_3 - z_1
\end{vmatrix} = 0
$$

### 6.6 Vector Equation of Plane

$$
\vec{r} \cdot \hat{n} = p
$$

where $\hat{n}$ is the unit normal vector and $p$ is the distance from origin.

---

## 7. Angles Involving Planes

### 7.1 Angle Between Two Planes

For planes $a_1x + b_1y + c_1z + d_1 = 0$ and $a_2x + b_2y + c_2z + d_2 = 0$:

$$
\cos\theta = \left| \frac{a_1a_2 + b_1b_2 + c_1c_2}{\sqrt{a_1^2 + b_1^2 + c_1^2} \sqrt{a_2^2 + b_2^2 + c_2^2}} \right|
$$

Conditions:

- Perpendicular planes: $a_1a_2 + b_1b_2 + c_1c_2 = 0$
- Parallel planes: $\frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2}$

### 7.2 Angle Between a Line and a Plane

If the line has direction ratios $a, b, c$ and the plane has normal $(A, B, C)$, the angle $\theta$ between the line and the plane is:

$$
\sin\theta = \left| \frac{aA + bB + cC}{\sqrt{a^2 + b^2 + c^2} \sqrt{A^2 + B^2 + C^2}} \right|
$$

The angle between the line and the normal to the plane is $90^\circ - \theta$.

---

## 8. Distances Involving Planes

### 8.1 Distance of a Point from a Plane

Distance from point $(x_1, y_1, z_1)$ to plane $ax + by + cz + d = 0$:

$$
d = \left| \frac{ax_1 + by_1 + cz_1 + d}{\sqrt{a^2 + b^2 + c^2}} \right|
$$

### 8.2 Distance Between Two Parallel Planes

For planes $ax + by + cz + d_1 = 0$ and $ax + by + cz + d_2 = 0$:

$$
d = \frac{|d_1 - d_2|}{\sqrt{a^2 + b^2 + c^2}}
$$

---

## 9. Coplanarity of Two Lines

Two lines $\vec{r} = \vec{a}_1 + \lambda \vec{b}_1$ and $\vec{r} = \vec{a}_2 + \mu \vec{b}_2$ are coplanar if:

$$
(\vec{a}_2 - \vec{a}_1) \cdot (\vec{b}_1 \times \vec{b}_2) = 0
$$

Cartesian condition: For lines

$$
\frac{x - x_1}{a_1} = \frac{y - y_1}{b_1} = \frac{z - z_1}{c_1}
$$

and

$$
\frac{x - x_2}{a_2} = \frac{y - y_2}{b_2} = \frac{z - z_2}{c_2}
$$

$$
\begin{vmatrix}
x_2 - x_1 & y_2 - y_1 & z_2 - z_1 \\
a_1 & b_1 & c_1 \\
a_2 & b_2 & c_2
\end{vmatrix} = 0
$$

---

## 10. Sphere

### 10.1 Standard Equation

Sphere with centre $(h, k, l)$ and radius $r$:

$$
(x - h)^2 + (y - k)^2 + (z - l)^2 = r^2
$$

### 10.2 General Equation

$$
x^2 + y^2 + z^2 + 2ux + 2vy + 2wz + d = 0
$$

- Centre: $(-u, -v, -w)$
- Radius: $\sqrt{u^2 + v^2 + w^2 - d}$

### 10.3 Sphere with Diameter Endpoints

Sphere with diameter joining $(x_1, y_1, z_1)$ and $(x_2, y_2, z_2)$:

$$
(x - x_1)(x - x_2) + (y - y_1)(y - y_2) + (z - z_1)(z - z_2) = 0
$$

### 10.4 Equation of Sphere Passing Through Four Points

$$
\begin{vmatrix}
x^2 + y^2 + z^2 & x & y & z & 1 \\
x_1^2 + y_1^2 + z_1^2 & x_1 & y_1 & z_1 & 1 \\
x_2^2 + y_2^2 + z_2^2 & x_2 & y_2 & z_2 & 1 \\
x_3^2 + y_3^2 + z_3^2 & x_3 & y_3 & z_3 & 1 \\
x_4^2 + y_4^2 + z_4^2 & x_4 & y_4 & z_4 & 1
\end{vmatrix} = 0
$$

---

## 11. Quick BITSAT Focus Areas

- Direction cosines: $l^2 + m^2 + n^2 = 1$
- Angle between lines: $\cos\theta = \left| l_1l_2 + m_1m_2 + n_1n_2 \right|$
- Shortest distance between skew lines: $\left| \frac{(\vec{a}_2 - \vec{a}_1) \cdot (\vec{b}_1 \times \vec{b}_2)}{|\vec{b}_1 \times \vec{b}_2|} \right|$
- Point to plane distance: $\left| \frac{ax_1 + by_1 + cz_1 + d}{\sqrt{a^2 + b^2 + c^2}} \right|$
- Angle between line and plane: $\sin\theta = \left| \frac{aA + bB + cC}{\sqrt{a^2 + b^2 + c^2} \sqrt{A^2 + B^2 + C^2}} \right|$
- Coplanarity: $(\vec{a}_2 - \vec{a}_1) \cdot (\vec{b}_1 \times \vec{b}_2) = 0$


---

# Important fact

- Two planes $A_1 x + B_1 y + C_1 z = D_1$ and $A_2 x + B_2 y + C_2 z = D_2$ are:
    
    - **Parallel:** if $\frac{A_1}{A_2} = \frac{B_1}{B_2} = \frac{C_1}{C_2} \neq \frac{D_1}{D_2}$
        
    - **Identical (coincident):** if $\frac{A_1}{A_2} = \frac{B_1}{B_2} = \frac{C_1}{C_2} = \frac{D_1}{D_2}$

---
# Plane form

**Standard Formula:**

- Parametric plane: $\vec{r} = \vec{a} + \lambda\vec{b} + \mu\vec{c}$
    
- Scalar dot product form: $\vec{r}\cdot\vec{n} = \vec{a}\cdot\vec{n}$, where $\vec{n} = \vec{b} \times \vec{c}$

---

# Plane information

For acute bisector, the signed distances have opposite signs:

![[Pasted image 20261007220831.png]]
![[Pasted image 20261007220847.png]]


---

![[Pasted image 20261007224855.png]]![[Pasted image 20261007224910.png]]


---

![[Pasted image 20261007225302.png]]


---

# Line of Intersection of Two Planes

## General Method

Suppose the two planes are given by:
$$a_1 x + b_1 y + c_1 z = d_1$$
$$a_2 x + b_2 y + c_2 z = d_2$$

Their respective normal vectors are:
$$\vec{n}_1 = (a_1, b_1, c_1)$$
$$\vec{n}_2 = (a_2, b_2, c_2)$$

Since the line of intersection lies in both planes, its direction is perpendicular to both normal vectors. Therefore, the direction vector $\vec{d}$ is the cross product of the two normals:
$$\vec{d} = \vec{n}_1 \times \vec{n}_2$$

### Steps:
1. **Direction Vector:** Find $\vec{d} = \vec{n}_1 \times \vec{n}_2$.
2. **Point on Line:** Find a particular point $(x_0, y_0, z_0)$ satisfying both plane equations by setting one variable to a convenient value (usually $0$) and solving the resulting $2 \times 2$ system.
3. **Form Equation of the Line:**
   - **Vector Form:**
     $$(x, y, z) = (x_0, y_0, z_0) + t(d_x, d_y, d_z)$$
   - **Parametric Form:**
     $$x = x_0 + t d_x, \quad y = y_0 + t d_y, \quad z = z_0 + t d_z$$
   - **Symmetric Form:**
     $$\frac{x - x_0}{d_x} = \frac{y - y_0}{d_y} = \frac{z - z_0}{d_z}$$

---

## Example

Consider the two planes:
$$P_1: x - y = 1$$
$$P_2: z = 1$$

### 1. Normal Vectors
$$\vec{n}_1 = (1, -1, 0)$$
$$\vec{n}_2 = (0, 0, 1)$$

### 2. Direction Vector
$$\vec{d} = \vec{n}_1 \times \vec{n}_2 = 
\begin{vmatrix}
\hat{\imath} & \hat{\jmath} & \hat{k} \\
1 & -1 & 0 \\
0 & 0 & 1
\end{vmatrix}
= (-1, -1, 0)$$

Since direction vectors can be scaled by any non-zero scalar, this is parallel to:
$$\vec{d} \parallel (1, 1, 0)$$

### 3. Finding a Point on the Line
From $P_2$, we have $z = 1$.  
Set $y = 0$ in $P_1$:
$$x - 0 = 1 \implies x = 1$$

Thus, a point on the line is:
$$(x_0, y_0, z_0) = (1, 0, 1)$$

### 4. Equation of the Line
- **Vector Form:**
  $$(x, y, z) = (1, 0, 1) + t(1, 1, 0)$$


---

