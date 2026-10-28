# Parabola — BITSAT Formula Sheet

## 1. Standard Equations and Basic Properties


The standard geometric equation of a parabola is:

$$(x - x_0)^2 + (y - y_0)^2 = \left(\frac{Ax + By + C}{\sqrt{A^2 + B^2}}\right)^2$$

Here, $(x_0, y_0)$ is the focus $S$, and $Ax + By + C = 0$ is the directrix.


---


### 1.1 Parabola opening right or left

**Standard equation:**

$$y^2=4ax$$

- Vertex: $(0,0)$
    
- Focus: $(a,0)$
    
- Directrix: $x=-a$
    
- Axis: $y=0$
    
- Latus rectum: $x=a$
    
- Length of latus rectum: $4a$
    
- Endpoints of latus rectum: $(a,\pm 2a)$
    
- Eccentricity: $e=1$
    
- Opens right when $a>0$; left when $a<0$.
    

### 1.2 Parabola opening up or down

**Standard equation:**

$$x^2=4ay$$

- Vertex: $(0,0)$
    
- Focus: $(0,a)$
    
- Directrix: $y=-a$
    
- Axis: $x=0$
    
- Latus rectum: $y=a$
    
- Length of latus rectum: $4a$
    
- Endpoints of latus rectum: $(\pm 2a,a)$
    
- Opens upward when $a>0$; downward when $a<0$.
    

### 1.3 Shifted parabola

For $y^2=4ax$ shifted to vertex $(h,k)$:

$$(y-k)^2=4a(x-h)$$

- Vertex: $(h,k)$
    
- Focus: $(h+a,k)$
    
- Directrix: $x=h-a$
    

For $x^2=4ay$ shifted to vertex $(h,k)$:

$$(x-h)^2=4a(y-k)$$

- Vertex: $(h,k)$
    
- Focus: $(h,k+a)$
    
- Directrix: $y=k-a$
    

### 1.4 Parametric coordinates

For $y^2=4ax$, a general point is

$$P(at^2,2at)$$

For $x^2=4ay$, a general point is

$$P(2at,at^2)$$

For $y^2=4ax$:

- Slope of tangent at parameter $t$: $1/t$
    
- Slope of normal at parameter $t$: $-t$
    

### 1.5 Focal distance

For $y^2=4ax$ and point $P(at^2,2at)$:

$$SP=a(1+t^2)$$

where $S=(a,0)$ is the focus and $a>0$.

---

## 2. Tangents

### 2.1 Tangent at a point $(x_1,y_1)$

For $y^2=4ax$:

$$\boxed{yy_1=2a(x+x_1)}$$

This applies when $(x_1,y_1)$ lies on the parabola.

For $x^2=4ay$:

$$\boxed{xx_1=2a(y+y_1)}$$

### 2.2 Tangent in parameter form

For $y^2=4ax$, at $P(at^2,2at)$:

$$\boxed{ty=x+at^2}$$

For $x^2=4ay$, at $P(2at,at^2)$:

$$\boxed{tx=y+at^2}$$

### 2.3 Tangent with a given slope

For $y^2=4ax$, a tangent with slope $m$ is

$$\boxed{y=mx+\frac{a}{m}}$$

For $x^2=4ay$, a tangent with slope $m$ is

$$\boxed{y=mx-am^2}$$

For $y^2=4ax$, the tangent with slope $m$ touches the parabola at

$$\left(\frac{a}{m^2},\frac{2a}{m}\right)$$

For $x^2=4ay$, the point of contact is

$$\left(2am,am^2\right)$$

### 2.4 Condition for a line to be tangent

For $y^2=4ax$, consider the line

$$y=mx+c$$

It is tangent when

$$\boxed{c=\frac{a}{m}}$$

Equivalently, $mc=a$.

For a general line $lx+my+n=0$ to be tangent to $y^2=4ax$:

$$\boxed{ln=am^2}$$

For a general line $lx+my+n=0$ to be tangent to $x^2=4ay$:

$$\boxed{mn=al^2}$$

These conditions assume the line is represented by the stated coefficients and the corresponding standard parabola.

---

## 3. Normals

### 3.1 Normal at a point

For $y^2=4ax$, at $(x_1,y_1)$:

$$\boxed{y-y_1=-\frac{y_1}{2a}(x-x_1)}$$

This uses $\frac{dy}{dx}=\frac{2a}{y}$ and the negative reciprocal for the normal slope.

For $x^2=4ay$, at $(x_1,y_1)$:

$$\boxed{y-y_1=-\frac{x_1}{2a}(x-x_1)}$$

### 3.2 Normal in parameter form

For $y^2=4ax$, at $P(at^2,2at)$:

$$\boxed{y=-tx+2at+at^3}$$

For $x^2=4ay$, at $P(2at,at^2)$:

$$\boxed{x=-ty+2at+at^3}$$

### 3.3 Normal with a given slope

For $y^2=4ax$, if the normal slope is $m$, then the parameter is $t=-m$.

The normal is

$$\boxed{y=mx-2am-am^3}$$

For $x^2=4ay$, if the normal slope is $m$, then $t=-1/m$ (for $m\ne0$).

The normal is

$$\boxed{y=mx+\frac{2a}{m}+\frac{a}{m^3}}$$

For BITSAT, the parameter form is usually the more convenient one to remember.

---

## 4. Chords

### 4.1 Chord joining two parametric points

For $y^2=4ax$, let the endpoints have parameters $t_1$ and $t_2$.

The chord equation is

$$\boxed{(t_1+t_2)y=2x+2at_1t_2}$$

For $x^2=4ay$:

$$\boxed{(t_1+t_2)x=2y+2at_1t_2}$$

### 4.2 Chord with a given midpoint

For $y^2=4ax$, if the midpoint of a chord is $M(h,k)$, its equation is

$$\boxed{ky=2a(x-h)+k^2}$$

Equivalently,

$$\boxed{ky=2ax-2ah+k^2}$$

For $x^2=4ay$, if the midpoint is $M(h,k)$:

$$\boxed{hx=2a(y-k)+h^2}$$

Equivalently,

$$\boxed{hx=2ay-2ak+h^2}$$

These formulas describe a chord with the given midpoint when the resulting line intersects the parabola at two real points. A tangent is the limiting case of a chord.

### 4.3 Chord parallel to a given line

For $y^2=4ax$, a chord with slope $m$ has endpoints whose parameters satisfy

$$\boxed{t_1+t_2=\frac{2}{m}}$$

For $x^2=4ay$, a chord with slope $m$ has endpoints whose parameters satisfy

$$\boxed{t_1+t_2=2m}$$

Use these only when a question explicitly gives a chord's slope or parallel direction.

---

## 5. Intersection of a Line and a Parabola

### 5.1 Line intersecting $y^2=4ax$

Take a line

$$y=mx+c$$

Substitute into the parabola:

$$(mx+c)^2=4ax$$

This gives

$$m^2x^2+(2mc-4a)x+c^2=0$$

The roots of this quadratic give the $x$-coordinates of the intersection points.

### 5.2 Condition for tangency using the discriminant

For the quadratic above, tangency occurs when the discriminant is zero:

$$\boxed{(2mc-4a)^2-4m^2c^2=0}$$

Simplifying gives

$$\boxed{mc=a}$$

This reproduces the slope-form tangent condition.

### 5.3 General line intersecting $y^2=4ax$

For the line

$$lx+my+n=0$$

if $m\ne0$, then

$$y=-\frac{lx+n}{m}$$

Substituting into $y^2=4ax$ gives

$$\boxed{l^2x^2+(2ln-4am^2)x+n^2=0}$$

The discriminant tells you whether the line intersects the parabola at two distinct points, one repeated point (tangent), or no real points.

### 5.4 Sum and product of roots

If a line intersects a parabola and the resulting quadratic is

$$Ax^2+Bx+C=0$$

then the intersection coordinates can be found using

$$\boxed{x_1+x_2=-\frac BA}$$

$$\boxed{x_1x_2=\frac CA}$$

Substitute back into the line equation to obtain $y_1$ and $y_2$ when needed.

---

## 6. Quick Revision: Highest-Value Formulas

For $y^2=4ax$:

|Topic|Formula|
|---|---|
|Parametric point|$(at^2,2at)$|
|Tangent at $(x_1,y_1)$|$yy_1=2a(x+x_1)$|
|Tangent at parameter $t$|$ty=x+at^2$|
|Tangent with slope $m$|$y=mx+a/m$|
|Normal at parameter $t$|$y=-tx+2at+at^3$|
|Chord joining $t_1,t_2$|$(t_1+t_2)y=2x+2at_1t_2$|
|Chord with midpoint $(h,k)$|$ky=2a(x-h)+k^2$|
|Line tangent condition, $y=mx+c$|$mc=a$|
|Focus|$(a,0)$|
|Directrix|$x=-a$|
|Latus rectum length|$4a$|

## 7. What to Practise for BITSAT

1. Find the tangent or normal at a given point.
    
2. Find the tangent with a given slope.
    
3. Find the equation of a chord joining two parametric points.
    
4. Find the chord whose midpoint is given.
    
5. Find intersection points of a line and a parabola.
    
6. Determine whether a line is tangent using the discriminant.
    
7. Identify the focus, directrix, vertex and latus rectum from the equation.
    

**Study rule:** Learn the boxed formulas, solve standard MCQs for each, and move on once you can apply them reliably. Do not spend disproportionate time on complicated multi-tangent conditions or obscure special cases.


---

For a parabola with vertex at the origin $O(0, 0)$, any point on the curve satisfies its equation. If a point $P(h, k)$ divides the segment joining $(x_1, y_1)$ and $(x_2, y_2)$ in the ratio $m : n$, the section formula states:

$$h = \frac{m x_2 + n x_1}{m + n}, \quad k = \frac{m y_2 + n y_1}{m + n}$$


---

## Parametric in example working 

By symmetry, an equilateral triangle with one vertex at the origin $O(0, 0)$ inscribed in $y^2 = 4ax$ has its other two vertices at $(x_1, y_1)$ and $(x_1, -y_1)$. The line connecting $O(0, 0)$ to $(x_1, y_1)$ makes an angle of $30^\circ$ with the axis of symmetry (x-axis).

**Step-by-Step Solution**

1. For $y^2 = 8x$, comparing with $y^2 = 4ax$ gives $4a = 8 \implies a = 2$.
    
2. Using parametric coordinates for the top vertex $P(at^2, 2at) = (2t^2, 4t)$:
    
    $$\tan 30^\circ = \frac{y_1}{x_1} = \frac{4t}{2t^2} = \frac{2}{t}$$
    
    $$\frac{1}{\sqrt{3}} = \frac{2}{t} \implies t = 2\sqrt{3}$$
    
3. The coordinates of vertex $P$ are:
    
    $$x_1 = 2(2\sqrt{3})^2 = 2(12) = 24$$
    
    $$y_1 = 4(2\sqrt{3}) = 8\sqrt{3}$$

---

## Important question

### Question 20

> **If $(2, -8)$ is one end of a focal chord of the parabola $y^2 = 32x$, then the other end of the focal chord is:**
> 
> (A) $(32, 32)$
> 
> (B) $(32, -32)$
> 
> (C) $(-2, 8)$
> 
> (D) $(2, 8)$

**Core Concept & Standard Formula**

For a parabola $y^2 = 4ax$, points are represented parametrically as $(at^2, 2at)$. For any chord passing through the focus, the parameters of its extremities satisfy:

$$t_1 \cdot t_2 = -1 \implies t_2 = -\frac{1}{t_1}$$

**Step-by-Step Solution**

1. For $y^2 = 32x$, $4a = 32 \implies a = 8$.
    
2. The given endpoint is $(x_1, y_1) = (2, -8)$:
    
    $$2at_1 = -8 \implies 2(8)t_1 = -8 \implies t_1 = -\frac{1}{2}$$
    
    _(Verification: $at_1^2 = 8\left(-\frac{1}{2}\right)^2 = 2$)_
    
3. Use the focal chord property:
    
    $$t_2 = -\frac{1}{t_1} = -\frac{1}{-1/2} = 2$$
    
4. The coordinates of the other extremity are:
    
    $$x_2 = at_2^2 = 8(2)^2 = 32$$
    
    $$y_2 = 2at_2 = 2(8)(2) = 32$$
    
    Hence, the other end is $(32, 32)$.
    

**Correct Option:** **(A) $(32, 32)$**


---

