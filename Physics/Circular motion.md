> Use right hand thumb rule to find direction of angular velocity from direction of normal velocity.
> - curl fingers of right hand into the direction of normal velocity, now the direction in which thumb points is the direction of angular velocity 


---

> For circular motion, **radial acceleration cannot be 0** , but **tangential acceleration can be 0**


---

# Vertical Circular motion

## 1. General Equations (Mass $m$ on a String of Length $R$)

Let $\theta$ be the angle made with the **lowest vertical point**:

- **Velocity at angle $\theta$:**
    
    $$v^2 = u^2 - 2gR(1 - \cos\theta)$$
    
- **Tension at angle $\theta$:**
    
    $$T = \frac{mv^2}{R} + mg\cos\theta = \frac{m}{R}\left[u^2 - gR(2 - 3\cos\theta)\right]$$
    

## 2. Motion Classification Based on Bottom Velocity ($u$)

|**Condition on u**|**Path / Motion Type**|**Key Physical Phenomenon**|
|---|---|---|
|**$0 < u \le \sqrt{2gR}$**|**Simple Oscillation**|Velocity becomes zero before or at the horizontal level ($\theta \le 90^\circ$). Tension never becomes zero ($T > 0$).|
|**$\sqrt{2gR} < u < \sqrt{5gR}$**|**Leaves Circular Path (Projectile Motion)**|Tension drops to zero ($T = 0$) between $90^\circ < \theta < 180^\circ$ while velocity is still positive ($v > 0$). String slacks, bob executes projectile motion.|
|**$u \ge \sqrt{5gR}$**|**Complete Full Loop**|Tension remains $\ge 0$ throughout the entire circle. $T \ge 0$ at the top ($\theta = 180^\circ$).|

## 3. Critical Values for String (Light String + Bob)

|**Position**|**Angle (θ)**|**Minimum Velocity for Full Loop (u=5gR​)**|**Minimum Tension**|
|---|---|---|---|
|**Bottom (L)**|$0^\circ$|$v_L = \sqrt{5gR}$|$T_L = 6mg$|
|**Horizontal (M)**|$90^\circ$|$v_M = \sqrt{3gR}$|$T_M = 3mg$|
|**Top (H)**|$180^\circ$|$v_H = \sqrt{gR}$|$T_H = 0$|

> **Key Rule:** $T_{\text{bottom}} - T_{\text{top}} = 6mg$ (constant for any complete vertical loop).

## 4. Light Rigid Rod / Bead in a Vertical Tube

Because a rigid rod cannot slack ($T$ can be negative/compressive):

- **Condition to complete loop:** Bob just needs to reach the top with $v \ge 0$.
    
- **Critical Velocities:**
    
    - Bottom: $u_{\text{min}} = \sqrt{4gR} = 2\sqrt{gR}$
        
    - Horizontal: $v_{\text{horizontal}} = \sqrt{2gR}$
        
    - Top: $v_{\text{top}} = 0$
        

## 5. Slacking & Projectile Conditions ($\sqrt{2gR} < u < \sqrt{5gR}$)

When the string slacks at angle $\theta$ (measured from the lowest point, $90^\circ < \theta < 180^\circ$):

- **Angle where tension becomes zero ($T = 0$):**
    
    $$\cos\theta = \frac{2gR - u^2}{3gR}$$
    
- **Speed at the instant of slacking:**
    
    $$v_{\text{slack}} = \sqrt{-gR\cos\theta}$$
    
- **After slacking:** Bob acts as a projectile launched at speed $v_{\text{slack}}$ at an angle of $(180^\circ - \theta)$ above the horizontal.


---

