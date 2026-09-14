# How to find if 2 vectors are in same plane ( coplanar )

**Step 1: Check if direction vectors are parallel (Inspection only)**

Look at $\vec{b}_1$ and $\vec{b}_2$. If one is a scalar multiple of the other:

$$\vec{b}_1 = k \vec{b}_2$$

The lines are parallel, which means **they are automatically coplanar**. You are done in 2 seconds without writing anything.

**Step 2: If directions are not parallel, use the $3 \times 3$ Box Product Determinant**

When lines are not parallel, they lie in the same plane if and only if they intersect. This means the connecting vector $(\vec{a}_2 - \vec{a}_1)$ and the two direction vectors $\vec{b}_1, \vec{b}_2$ must form zero volume:

$$[\vec{a}_2 - \vec{a}_1 \quad \vec{b}_1 \quad \vec{b}_2] = 0$$

Write the $3 \times 3$ determinant directly from the numbers:

$$\begin{vmatrix} x_2 - x_1 & y_2 - y_1 & z_2 - z_1 \\ b_{1x} & b_{1y} & b_{1z} \\ b_{2x} & b_{2y} & b_{2z} \end{vmatrix} = 0$$

- **If determinant $= 0$:** The lines are coplanar (they intersect).
    
- **If determinant $\neq 0$:** The lines are skew (not coplanar).
    

This single determinant is the fastest computational route because computing a cross product first and then doing a dot product actually evaluates this exact same determinant in two separate steps.


---

