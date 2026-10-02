# Vectors: Special and Advanced Formulas (Class 11 & 12 / BITSAT)

## 1. Scalar Triple Product

Definition:

$$
[\vec a \ \vec b \ \vec c] = \vec a \cdot (\vec b \times \vec c)
$$

Determinant form:

$$
[\vec a \ \vec b \ \vec c] =
\begin{vmatrix}
a_1 & a_2 & a_3 \\
b_1 & b_2 & b_3 \\
c_1 & c_2 & c_3
\end{vmatrix}
$$

Properties:

$$
[\vec a \ \vec b \ \vec c] = [\vec b \ \vec c \ \vec a] = [\vec c \ \vec a \ \vec b]
$$

$$
[\vec a \ \vec b \ \vec c] = -[\vec b \ \vec a \ \vec c]
$$

If any two vectors are equal or parallel, then:

$$
[\vec a \ \vec b \ \vec c] = 0
$$

Three vectors are coplanar if and only if:

$$
[\vec a \ \vec b \ \vec c] = 0
$$

Volume of parallelepiped with coterminous edges $\vec a, \vec b, \vec c$:

$$
V = |[\vec a \ \vec b \ \vec c]|
$$

Volume of tetrahedron with coterminous edges $\vec a, \vec b, \vec c$:

$$
V = \frac{1}{6}|[\vec a \ \vec b \ \vec c]|
$$

---

## 2. Vector Triple Product

$$
\vec a \times (\vec b \times \vec c) = (\vec a \cdot \vec c)\vec b - (\vec a \cdot \vec b)\vec c
$$

$$
(\vec a \times \vec b) \times \vec c = (\vec a \cdot \vec c)\vec b - (\vec b \cdot \vec c)\vec a
$$

Vector product is not associative:

$$
\vec a \times (\vec b \times \vec c) \neq (\vec a \times \vec b) \times \vec c
$$

Jacobi identity:

$$
\vec a \times (\vec b \times \vec c) + \vec b \times (\vec c \times \vec a) + \vec c \times (\vec a \times \vec b) = \vec 0
$$

---

## 3. Products of Four Vectors

Scalar product of two cross products:

$$
(\vec a \times \vec b) \cdot (\vec c \times \vec d)
= (\vec a \cdot \vec c)(\vec b \cdot \vec d) - (\vec a \cdot \vec d)(\vec b \cdot \vec c)
$$

Vector product of two cross products:

$$
(\vec a \times \vec b) \times (\vec c \times \vec d)
= [\vec a \ \vec b \ \vec d]\vec c - [\vec a \ \vec b \ \vec c]\vec d
$$

Also:

$$
(\vec a \times \vec b) \times (\vec c \times \vec d)
= [\vec a \ \vec c \ \vec d]\vec b - [\vec b \ \vec c \ \vec d]\vec a
$$

Lagrange identity:

$$
|\vec a \times \vec b|^2 = |\vec a|^2|\vec b|^2 - (\vec a \cdot \vec b)^2
$$

---

## 4. Determinant Identities

$$
[\vec a + \vec b, \ \vec b + \vec c, \ \vec c + \vec a] = 2[\vec a \ \vec b \ \vec c]
$$

$$
[\vec a \times \vec b, \ \vec b \times \vec c, \ \vec c \times \vec a] = [\vec a \ \vec b \ \vec c]^2
$$

$$
[\vec a - \vec b, \ \vec b - \vec c, \ \vec c - \vec a] = 0
$$

$$
[\vec a, \ \vec b, \ \vec a \times \vec b] = |\vec a \times \vec b|^2
$$

Gram determinant:

$$
[\vec a \ \vec b \ \vec c]^2 =
\begin{vmatrix}
\vec a \cdot \vec a & \vec a \cdot \vec b & \vec a \cdot \vec c \\
\vec b \cdot \vec a & \vec b \cdot \vec b & \vec b \cdot \vec c \\
\vec c \cdot \vec a & \vec c \cdot \vec b & \vec c \cdot \vec c
\end{vmatrix}
$$

For unit vectors $\vec a, \vec b, \vec c$:

$$
[\vec a \ \vec b \ \vec c]^2
= 1 + 2(\vec a \cdot \vec b)(\vec b \cdot \vec c)(\vec c \cdot \vec a)
- (\vec a \cdot \vec b)^2 - (\vec b \cdot \vec c)^2 - (\vec c \cdot \vec a)^2
$$

---

## 5. Linear Dependence and Decomposition

If $\vec a, \vec b, \vec c$ are non-coplanar, then any vector $\vec r$ can be written uniquely as:

$$
\vec r = x\vec a + y\vec b + z\vec c
$$

where:

$$
x = \frac{[\vec r \ \vec b \ \vec c]}{[\vec a \ \vec b \ \vec c]}, \quad
y = \frac{[\vec r \ \vec c \ \vec a]}{[\vec a \ \vec b \ \vec c]}, \quad
z = \frac{[\vec r \ \vec a \ \vec b]}{[\vec a \ \vec b \ \vec c]}
$$

Reciprocal vectors:

$$
\vec a' = \frac{\vec b \times \vec c}{[\vec a \ \vec b \ \vec c]}, \quad
\vec b' = \frac{\vec c \times \vec a}{[\vec a \ \vec b \ \vec c]}, \quad
\vec c' = \frac{\vec a \times \vec b}{[\vec a \ \vec b \ \vec c]}
$$

Properties:

$$
\vec a \cdot \vec a' = 1, \quad \vec a \cdot \vec b' = 0, \quad \vec a \cdot \vec c' = 0
$$

---

## 6. Area and Volume

Area of parallelogram with adjacent sides $\vec a, \vec b$:

$$
A = |\vec a \times \vec b|
$$

Area of triangle with sides $\vec a, \vec b$:

$$
A = \frac{1}{2}|\vec a \times \vec b|
$$

Area of triangle with vertices $\vec A, \vec B, \vec C$:

$$
A = \frac{1}{2}|(\vec B - \vec A) \times (\vec C - \vec A)|
$$

Area of quadrilateral with diagonals $\vec d_1, \vec d_2$:

$$
A = \frac{1}{2}|\vec d_1 \times \vec d_2|
$$

Volume of parallelepiped with edges $\vec a, \vec b, \vec c$:

$$
V = |[\vec a \ \vec b \ \vec c]|
$$

Volume of tetrahedron with edges $\vec a, \vec b, \vec c$:

$$
V = \frac{1}{6}|[\vec a \ \vec b \ \vec c]|
$$

Volume of tetrahedron with vertices $\vec A, \vec B, \vec C, \vec D$:

$$
V = \frac{1}{6}|(\vec B - \vec A) \cdot ((\vec C - \vec A) \times (\vec D - \vec A))|
$$

---

## 7. Coplanarity Conditions

Three vectors $\vec a, \vec b, \vec c$ are coplanar iff:

$$
[\vec a \ \vec b \ \vec c] = 0
$$

Four points $\vec A, \vec B, \vec C, \vec D$ are coplanar iff:

$$
(\vec B - \vec A) \cdot ((\vec C - \vec A) \times (\vec D - \vec A)) = 0
$$

Two lines $\vec r = \vec a_1 + \lambda \vec b_1$ and $\vec r = \vec a_2 + \mu \vec b_2$ are coplanar iff:

$$
(\vec a_2 - \vec a_1) \cdot (\vec b_1 \times \vec b_2) = 0
$$

---

## 8. Vector Equations of Lines and Planes

Line:

$$
\vec r = \vec a + \lambda \vec b
$$

Line through two points $\vec a, \vec b$:

$$
\vec r = \vec a + \lambda(\vec b - \vec a)
$$

Plane:

$$
\vec r \cdot \vec n = d
$$

Plane through point $\vec a$ with normal $\vec n$:

$$
(\vec r - \vec a) \cdot \vec n = 0
$$

Plane through three points $\vec a, \vec b, \vec c$:

$$
(\vec r - \vec a) \cdot ((\vec b - \vec a) \times (\vec c - \vec a)) = 0
$$

Plane parallel to $\vec b, \vec c$ through $\vec a$:

$$
\vec r = \vec a + \lambda \vec b + \mu \vec c
$$

Plane containing line $\vec r = \vec a + \lambda \vec b$ and point $\vec c$:

$$
(\vec r - \vec a) \cdot (\vec b \times (\vec c - \vec a)) = 0
$$

Line of intersection of planes $\vec r \cdot \vec n_1 = d_1$ and $\vec r \cdot \vec n_2 = d_2$ has direction:

$$
\vec b = \vec n_1 \times \vec n_2
$$

---

## 9. Distances

Distance from point $\vec p$ to plane $\vec r \cdot \vec n = d$:

$$
D = \frac{|\vec p \cdot \vec n - d|}{|\vec n|}
$$

Distance from point $\vec p$ to line $\vec r = \vec a + \lambda \vec b$:

$$
D = \frac{|(\vec p - \vec a) \times \vec b|}{|\vec b|}
$$

Shortest distance between skew lines $\vec r = \vec a_1 + \lambda \vec b_1$ and $\vec r = \vec a_2 + \mu \vec b_2$:

$$
D = \frac{|(\vec a_2 - \vec a_1) \cdot (\vec b_1 \times \vec b_2)|}{|\vec b_1 \times \vec b_2|}
$$

Distance between parallel lines:

$$
D = \frac{|(\vec a_2 - \vec a_1) \times \vec b|}{|\vec b|}
$$

Distance between parallel planes $\vec r \cdot \vec n = d_1$ and $\vec r \cdot \vec n = d_2$:

$$
D = \frac{|d_1 - d_2|}{|\vec n|}
$$

---

## 10. Foot of Perpendicular and Reflection

Foot of perpendicular from point $\vec p$ to plane $\vec r \cdot \vec n = d$:

$$
\vec p' = \vec p - \frac{\vec p \cdot \vec n - d}{|\vec n|^2}\vec n
$$

Reflection of point $\vec p$ in plane $\vec r \cdot \vec n = d$:

$$
\vec p'' = \vec p - 2\frac{\vec p \cdot \vec n - d}{|\vec n|^2}\vec n
$$

Foot of perpendicular from point $\vec p$ to line $\vec r = \vec a + \lambda \vec b$:

$$
\vec q = \vec a + \frac{(\vec p - \vec a) \cdot \vec b}{|\vec b|^2}\vec b
$$

Reflection of point $\vec p$ in line $\vec r = \vec a + \lambda \vec b$:

$$
\vec p'' = 2\vec q - \vec p
$$

---

## 11. Angles

Angle between vectors:

$$
\cos\theta = \frac{\vec a \cdot \vec b}{|\vec a||\vec b|}
$$

Angle between lines with direction vectors $\vec b_1, \vec b_2$:

$$
\cos\theta = \frac{|\vec b_1 \cdot \vec b_2|}{|\vec b_1||\vec b_2|}
$$

Angle between planes with normals $\vec n_1, \vec n_2$:

$$
\cos\theta = \frac{|\vec n_1 \cdot \vec n_2|}{|\vec n_1||\vec n_2|}
$$

Angle between line direction $\vec b$ and plane normal $\vec n$:

$$
\sin\theta = \frac{|\vec b \cdot \vec n|}{|\vec b||\vec n|}
$$

---

## 12. Angle Bisectors and Triangle Centers

Internal angle bisector direction of vectors $\vec a$ and $\vec b$:

$$
\frac{\vec a}{|\vec a|} + \frac{\vec b}{|\vec b|}
$$

External angle bisector direction:

$$
\frac{\vec a}{|\vec a|} - \frac{\vec b}{|\vec b|}
$$

Incenter of triangle with vertices $\vec A, \vec B, \vec C$:

$$
\vec I = \frac{a\vec A + b\vec B + c\vec C}{a+b+c}
$$

where:

$$
a = |\vec B - \vec C|, \quad b = |\vec C - \vec A|, \quad c = |\vec A - \vec B|
$$

Centroid of triangle:

$$
\vec G = \frac{\vec A + \vec B + \vec C}{3}
$$

---

## 13. Sphere in Vector Form

Sphere with center $\vec c$ and radius $R$:

$$
|\vec r - \vec c| = R
$$

General vector equation:

$$
\vec r \cdot \vec r - 2\vec c \cdot \vec r + \vec c \cdot \vec c - R^2 = 0
$$

Tangent plane to sphere at point $\vec r_0$:

$$
(\vec r - \vec r_0) \cdot (\vec r_0 - \vec c) = 0
$$

Condition for plane $\vec r \cdot \vec n = d$ to be tangent to sphere:

$$
\frac{|\vec c \cdot \vec n - d|}{|\vec n|} = R
$$

---

## 14. Projection and Component Formulas

Scalar projection of $\vec a$ on $\vec b$:

$$
\frac{\vec a \cdot \vec b}{|\vec b|}
$$

Vector projection of $\vec a$ on $\vec b$:

$$
\frac{\vec a \cdot \vec b}{|\vec b|^2}\vec b
$$

Component of $\vec a$ perpendicular to $\vec b$:

$$
\vec a - \frac{\vec a \cdot \vec b}{|\vec b|^2}\vec b
$$

---

## 15. Useful Inequalities and Identities

Parallelogram law:

$$
|\vec a + \vec b|^2 + |\vec a - \vec b|^2 = 2(|\vec a|^2 + |\vec b|^2)
$$

Polarization identity:

$$
\vec a \cdot \vec b = \frac{1}{4}\left(|\vec a + \vec b|^2 - |\vec a - \vec b|^2\right)
$$

Cauchy-Schwarz inequality:

$$
|\vec a \cdot \vec b| \le |\vec a||\vec b|
$$

Triangle inequality:

$$
|\vec a + \vec b| \le |\vec a| + |\vec b|
$$

Reverse triangle inequality:

$$
\big||\vec a| - |\vec b|\big| \le |\vec a + \vec b|
$$

If $\vec a \perp \vec b$:

$$
|\vec a + \vec b|^2 = |\vec a|^2 + |\vec b|^2
$$

If $\vec a \parallel \vec b$:

$$
|\vec a + \vec b| = |\vec a| + |\vec b| \quad \text{(same direction)}
$$

$$
|\vec a + \vec b| = \big||\vec a| - |\vec b|\big| \quad \text{(opposite direction)}
$$