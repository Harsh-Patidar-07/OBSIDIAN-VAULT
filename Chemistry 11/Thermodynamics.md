![[Pasted image 20261001123314.png]]


---
$$1\text{ cal} \approx 4.2\text{ J}$$
$$1\text{ bar}\cdot\text{m}^3 = 10^5\text{ J} = 100\text{ kJ}$$
$$1\text{ atm} = 760\text{ torr}$$
$$1\text{ J} = 10^7\text{ ergs}$$
---

# A important concept

#### 1. What does "Irreversible Stage Expansion" mean?

In thermodynamics, work done by or on a gas is defined by the opposing external pressure ($P_{\text{ext}}$) that the gas pushes against:

$$w = -\int P_{\text{ext}} \, dV$$

- In a **reversible** expansion, the external pressure is constantly adjusted to stay infinitesimally close to the internal pressure ($P_{\text{ext}} \approx P_{\text{int}}$), leading to the smooth curve integral $w = -nRT \ln(V_2/V_1)$.
    
- In an **irreversible expansion against external pressure**, the piston is suddenly released against a fixed, constant external pressure ($P_{\text{ext}} = \text{constant}$).
    

When an exam problem says an ideal gas expands irreversibly from State 1 to State 2, it means the external opposing pressure drops abruptly to the pressure of the destination state ($P_2$), and the gas expands against that fixed resistance:

$$w = -P_{\text{ext}} \int_{V_{\text{initial}}}^{V_{\text{final}}} dV = -P_{\text{ext}} (V_{\text{final}} - V_{\text{initial}})$$

#### 2. Calculating Work for Each Stage

The question gives three states:

- **State 1:** $(P_1 = 8.0\text{ bar}, V_1 = 4.0\text{ L}, T_1 = 300\text{ K})$
    
- **State 2:** $(P_2 = 2.0\text{ bar}, V_2 = 16\text{ L}, T_2 = 300\text{ K})$
    
- **State 3:** $(P_3 = 1.0\text{ bar}, V_3 = 32\text{ L}, T_3 = 300\text{ K})$
    

**Stage 1 (State 1 $\to$ State 2):** The gas expands from $4.0\text{ L}$ to $16\text{ L}$ against the opposing pressure of State 2 ($P_{\text{ext}, 1} = 2.0\text{ bar}$):

$$w_1 = -P_{\text{ext}, 1}(V_2 - V_1)$$

$$w_1 = -(2.0\text{ bar}) \times (16\text{ L} - 4.0\text{ L}) = -2.0 \times 12 = -24\text{ bar}\cdot\text{L}$$

>The compression stops once the internal gas pressure reaches equilibrium with the external pressure

---

