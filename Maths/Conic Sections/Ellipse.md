# Ellipse — BITSAT Formula Sheet

## 1. Standard Equations and Basic Properties

### 1.1 Major axis along the x-axis

**Standard equation:**

$$\boxed{\frac{x^2}{a^2}+\frac{y^2}{b^2}=1}, \qquad a>b>0$$

- Centre: $(0,0)$
    
- Vertices: $(\pm a,0)$
    
- Co-vertices: $(0,\pm b)$
    
- Foci: $(\pm c,0)$
    
- Relationship: $\boxed{c^2=a^2-b^2}$
    
- Eccentricity: $\boxed{e=\frac ca=\sqrt{1-\frac{b^2}{a^2}}}$
    
- Directrices: $\boxed{x=\pm\frac ae}$
    
- Length of major axis: $2a$
    
- Length of minor axis: $2b$
    
- Length of latus rectum: $\boxed{\frac{2b^2}{a}}$
    
- Endpoints of the latus recta through the foci:  
    $\left(\pm c,\pm\frac{b^2}{a}\right)$, with both signs considered independently.
    

### 1.2 Major axis along the y-axis

**Standard equation:**

$$\boxed{\frac{x^2}{b^2}+\frac{y^2}{a^2}=1}, \qquad a>b>0$$

- Centre: $(0,0)$
    
- Vertices: $(0,\pm a)$
    
- Co-vertices: $(\pm b,0)$
    
- Foci: $(0,\pm c)$
    
- Relationship: $c^2=a^2-b^2$
    
- Eccentricity: $e=c/a$
    
- Directrices: $y=\pm a/e$
    
- Length of latus rectum: $2b^2/a$
    

### 1.3 Shifted ellipse

For a horizontal major axis:

$$\boxed{\frac{(x-h)^2}{a^2}+\frac{(y-k)^2}{b^2}=1}$$

- Centre: $(h,k)$
    
- Foci: $(h\pm c,k)$
    
- Vertices: $(h\pm a,k)$
    

For a vertical major axis:

$$\boxed{\frac{(x-h)^2}{b^2}+\frac{(y-k)^2}{a^2}=1}$$

- Centre: $(h,k)$
    
- Foci: $(h,k\pm c)$
    
- Vertices: $(h,k\pm a)$
    

### 1.4 Parametric coordinates

For the horizontal ellipse:

$$\boxed{P=(a\cos\theta,b\sin\theta)}$$

For the vertical ellipse:

$$\boxed{P=(b\cos\theta,a\sin\theta)}$$

For the horizontal ellipse, the eccentric-angle parameterisation is especially useful in tangent and chord questions.

### 1.5 Focal distances

For the horizontal ellipse and point $P=(a\cos\theta,b\sin\theta)$:

$$\boxed{PF_1=a+c\cos\theta}$$

$$\boxed{PF_2=a-c\cos\theta}$$

Here $F_1=(-c,0)$ and $F_2=(c,0)$.

Therefore:

$$\boxed{PF_1+PF_2=2a}$$

The sum of distances from any point on an ellipse to its two foci is constant.

---

## 2. Tangents

### 2.1 Tangent at a point $(x_1,y_1)$

For the horizontal ellipse:

$$\boxed{\frac{xx_1}{a^2}+\frac{yy_1}{b^2}=1}$$

For the vertical ellipse:

$$\boxed{\frac{xx_1}{b^2}+\frac{yy_1}{a^2}=1}$$

The point $(x_1,y_1)$ must lie on the ellipse.

### 2.2 Tangent in parametric form

For the horizontal ellipse, at $(a\cos\theta,b\sin\theta)$:

$$\boxed{\frac{x\cos\theta}{a}+\frac{y\sin\theta}{b}=1}$$

For the vertical ellipse, at $(b\cos\theta,a\sin\theta)$:

$$\boxed{\frac{x\cos\theta}{b}+\frac{y\sin\theta}{a}=1}$$

### 2.3 Tangent with a given slope

For the horizontal ellipse:

$$\boxed{y=mx\pm\sqrt{a^2m^2+b^2}}$$

For the vertical ellipse:

$$\boxed{y=mx\pm\sqrt{a^2+b^2m^2}}$$

The two signs represent the two parallel tangents of that slope.

### 2.4 Condition for a line to be tangent

For the horizontal ellipse, let the line be

$$lx+my+n=0$$

The condition for tangency is

$$\boxed{n^2=a^2l^2+b^2m^2}$$

For the vertical ellipse:

$$\boxed{n^2=b^2l^2+a^2m^2}$$

For a line $y=mx+c$ tangent to the horizontal ellipse:

$$\boxed{c^2=a^2m^2+b^2}$$

---

## 3. Normals

### 3.1 Normal at a point

For the horizontal ellipse:

$$\boxed{y-y_1=\frac{a^2y_1}{b^2x_1}(x-x_1)}$$

For the vertical ellipse:

$$\boxed{y-y_1=\frac{b^2y_1}{a^2x_1}(x-x_1)}$$

These slope forms assume the relevant denominators are nonzero. At axis vertices, use the corresponding vertical or horizontal normal directly.

### 3.2 Normal in parametric form

For the horizontal ellipse at $(a\cos\theta,b\sin\theta)$:

$$\boxed{ax\sec\theta-by\csc\theta=a^2-b^2}$$

This form is inconvenient when either sine or cosine is zero. A safer equivalent form is

$$\boxed{(a^2-b^2)\text{ is not a common factor; use } \frac{ax}{\cos\theta}-\frac{by}{\sin\theta}=a^2-b^2}$$

For the vertical ellipse at $(b\cos\theta,a\sin\theta)$:

$$\boxed{\frac{bx}{\cos\theta}-\frac{ay}{\sin\theta}=b^2-a^2}$$

Use these only when $\sin\theta\cos\theta\ne0$; axis cases are obtained separately.

### 3.3 Normal slope in parameter form

For the horizontal ellipse, at parameter $\theta$:

$$\boxed{m_n=\frac{a\sin\theta}{b\cos\theta}}$$

For the vertical ellipse:

$$\boxed{m_n=-\frac{b\sin\theta}{a\cos\theta}}$$

These expressions apply when the tangent slope is finite and nonzero; handle axis points separately.

---

## 4. Chords

### 4.1 Chord joining two parametric points

For the horizontal ellipse, let the endpoints have eccentric angles $\alpha$ and $\beta$.

$$\boxed{\frac{x}{a}\cos\frac{\alpha+\beta}{2}+\frac{y}{b}\sin\frac{\alpha+\beta}{2}=\cos\frac{\alpha-\beta}{2}}$$

An equivalent algebraic form uses the endpoint coordinates $(x_1,y_1)$ and $(x_2,y_2)$:

$$\boxed{\text{Use the line through the two endpoints, found by the two-point form.}}$$

### 4.2 Chord with a given midpoint

For the horizontal ellipse, if the midpoint of a chord is $M(h,k)$:

$$\boxed{\frac{xh}{a^2}+\frac{yk}{b^2}=\frac{h^2}{a^2}+\frac{k^2}{b^2}}$$

For the vertical ellipse:

$$\boxed{\frac{xh}{b^2}+\frac{yk}{a^2}=\frac{h^2}{b^2}+\frac{k^2}{a^2}}$$

These equations give the chord whose midpoint is the specified point, provided the resulting line intersects the ellipse at two real points.

### 4.3 Chord parallel to a given line

For the horizontal ellipse, a line of slope $m$ can be written as

$$y=mx+c$$

Its intersection with the ellipse gives a quadratic in $x$. The midpoint of the chord is found by averaging the two roots.

For the horizontal ellipse, the midpoint coordinates $(h,k)$ of a chord with slope $m$ satisfy

$$\boxed{k=mh}$$

For the vertical ellipse, the same midpoint relation holds:

$$\boxed{k=mh}$$

In both cases, the chord's midpoint lies on a line through the centre parallel to the chord.

---

## 5. Intersection of a Line and an Ellipse

### 5.1 Line intersecting the horizontal ellipse

Given

$$y=mx+c$$

Substitute into

$$\frac{x^2}{a^2}+\frac{y^2}{b^2}=1$$

to obtain

$$\boxed{(a^2m^2+b^2)x^2+2a^2mcx+a^2(c^2-b^2)=0}$$

The roots give the $x$-coordinates of the intersection points.

### 5.2 Condition for intersection or tangency

For the line $y=mx+c$ and horizontal ellipse:

- Two distinct intersections: the discriminant is positive.
    
- Tangency: the discriminant is zero.
    
- No real intersection: the discriminant is negative.
    

The tangency condition simplifies to

$$\boxed{c^2=a^2m^2+b^2}$$

### 5.3 General line intersecting the horizontal ellipse

For

$$lx+my+n=0$$

substitute $y=-(lx+n)/m$ when $m\ne0$ into the ellipse equation. This yields a quadratic whose discriminant determines the number of intersections.

A more efficient approach for standard questions is to use the tangency condition directly:

$$\boxed{n^2=a^2l^2+b^2m^2}$$

### 5.4 Sum and product of roots

If the intersection equation is

$$Ax^2+Bx+C=0$$

then

$$\boxed{x_1+x_2=-\frac BA}$$

$$\boxed{x_1x_2=\frac CA}$$

Use these to find the midpoint of the chord or relationships between the intersection points.

---

## 6. Quick Revision — Highest-Value Formulas

For the horizontal ellipse $\frac{x^2}{a^2}+\frac{y^2}{b^2}=1$:

|Topic|Formula|
|---|---|
|Focus relationship|$c^2=a^2-b^2$|
|Eccentricity|$e=c/a$|
|Parametric point|$(a\cos\theta,b\sin\theta)$|
|Tangent at $(x_1,y_1)$|$\frac{xx_1}{a^2}+\frac{yy_1}{b^2}=1$|
|Parametric tangent|$\frac{x\cos\theta}{a}+\frac{y\sin\theta}{b}=1$|
|Tangent with slope $m$|$y=mx\pm\sqrt{a^2m^2+b^2}$|
|Tangency condition for $lx+my+n=0$|$n^2=a^2l^2+b^2m^2$|
|Midpoint chord, midpoint $(h,k)$|$\frac{xh}{a^2}+\frac{yk}{b^2}=\frac{h^2}{a^2}+\frac{k^2}{b^2}$|
|Latus rectum length|$2b^2/a$|
|Focal distance sum|$PF_1+PF_2=2a$|

## 7. What to Practise for BITSAT

1. Identify the centre, vertices, foci and eccentricity.
    
2. Find the tangent at a given point.
    
3. Find tangents with a given slope.
    
4. Apply the tangent condition to a line.
    
5. Find the chord with a given midpoint.
    
6. Solve straightforward line-ellipse intersection questions.
    
7. Use sum and product of roots to obtain the chord midpoint.
    

**Study rule:** Prioritise standard properties, tangents, midpoint chords and direct intersections. Leave complicated normal problems and obscure special-case formula collections until the rest of your syllabus is secure.


---

