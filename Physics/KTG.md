$$v_{\text{mean}} = \frac{\sum v_i}{N}$$

$$v_{\text{rms}} = \sqrt{\frac{\sum v_i^2}{N}}= \sqrt{\frac{3RT}{M}} $$

---

### Efficiency Formula

$$\eta = \frac{W_{\text{net}}}{Q_{\text{in}}} \times 100\%$$

---

The total internal energy of a non-reacting gas mixture is simply the sum of the internal energies of each individual gas component. Each degree of freedom of a mole contributes $\frac{1}{2}RT$ of energy. Diatomic oxygen has 5 active degrees of freedom (3 translational + 2 rotational), while monoatomic argon has only 3 translational degrees of freedom.

**Standard Formula Used:**

$$U = n \left(\frac{f}{2}\right) R T$$


---

For any ideal gas, the molar heat capacity at constant pressure is strictly greater than at constant volume:

$$C_p > C_v > 0$$

---

- An isotherm is a curve of constant temperature. Any points lying on the exact same isothermal line share the identical temperature.
    
- On a $P\text{-}V$ plot, isotherms further away from the origin correspond to higher temperatures ($T \propto PV$).
    
- Molecular speed formulas (most probable speed, rms speed, mean speed) depend exclusively on temperature for a given gas.


---

## Very important stuff 

Refrigerator is inverse of Carnot Engine, formula of efficiency too


---

# Entropy concept

### 1. Intuition and Definition

Entropy ($S$) measures the dispersion of energy and the microscopic randomness of a system.

When heat energy $dQ$ enters a system, it increases molecular thermal agitation. Rudolf Clausius defined the infinitesimal change in entropy for a **reversible** path as:

$$dS = \frac{dQ_{\text{rev}}}{T}$$

_Why is $T$ in the denominator?_ Adding $100\text{ J}$ of heat to cold ice at $273\text{ K}$ causes a massive proportional surge in disorder compared to adding the same $100\text{ J}$ to steam already boiling wildly at $500\text{ K}$. The colder the system, the more sensitive its state is to added heat.

### 2. Entropy is a State Function

Like internal energy ($U$), entropy ($S$) depends only on the current thermodynamic state of the gas (its current $P$, $V$, and $T$), not on the path taken to get there:

- Over any closed reversible cycle: $\oint dS = 0$
    
- Between any two states 1 and 2: $\Delta S = S_2 - S_1$ is identical across all paths. If a process is irreversible, you calculate $\Delta S$ by imagining an equivalent reversible path connecting the same initial and final states.
    

### 3. The Master Formula for an Ideal Gas

From the First Law of Thermodynamics:

$$dQ_{\text{rev}} = dU + dW = n C_v dT + P dV$$

Divide every term by $T$:

$$dS = \frac{dQ_{\text{rev}}}{T} = n C_v \frac{dT}{T} + \frac{P}{T} dV$$

Using the ideal gas equation $\frac{P}{T} = \frac{nR}{V}$, we get:

$$dS = n C_v \frac{dT}{T} + n R \frac{dV}{V}$$

Integrating from state $(T_1, V_1)$ to $(T_2, V_2)$ gives the **fundamental master equation**:

$$\Delta S = n C_v \ln\left(\frac{T_2}{T_1}\right) + n R \ln\left(\frac{V_2}{V_1}\right)$$

Using $V \propto \frac{T}{P}$ and Mayer's relation ($C_p = C_v + R$), this can also be written in terms of pressure:

$$\Delta S = n C_p \ln\left(\frac{T_2}{T_1}\right) - n R \ln\left(\frac{P_2}{P_1}\right)$$

### 4. Standard Process Cases

- **Isochoric (Constant Volume, $V_1 = V_2$):**
    
    $$\Delta S_v = n C_v \ln\left(\frac{T_2}{T_1}\right)$$
    
- **Isobaric (Constant Pressure, $P_1 = P_2$):**
    
    $$\Delta S_p = n C_p \ln\left(\frac{T_2}{T_1}\right)$$
    
    _(Since $C_p > C_v$, heating a gas at constant pressure always generates more entropy than heating it between the same two temperatures at constant volume.)_
    
- **Isothermal (Constant Temperature, $T_1 = T_2$):**
    
    $$\Delta S_T = n R \ln\left(\frac{V_2}{V_1}\right) = -n R \ln\left(\frac{P_2}{P_1}\right)$$
    
- **Reversible Adiabatic (Isentropic, $dQ_{\text{rev}} = 0$):**
    
    $$\Delta S = \int \frac{0}{T} = 0 \implies S = \text{constant}$$
    

### 5. Second Law of Thermodynamics (Entropy Formulation)

For any isolated system (or the entire Universe):

$$\Delta S_{\text{total}} = \Delta S_{\text{system}} + \Delta S_{\text{surroundings}} \ge 0$$

- $\Delta S_{\text{total}} = 0$ for an idealized **reversible** process.
    
- $\Delta S_{\text{total}} > 0$ for any spontaneous, natural **irreversible** process.
    
- $\Delta S_{\text{total}} < 0$ is physically impossible.
    

_(Note: The entropy of a specific subsystem can decrease, e.g., $\Delta S_{\text{sys}} = -8\text{ J/K}$, but only if the surroundings gain at least that much entropy to ensure the net sum remains $\ge 0$.)_


---

**Kelvin-Planck Statement:** "It is impossible to construct an engine operating in a cycle whose sole effect is the extraction of heat from a single thermal reservoir and the complete conversion of that heat into mechanical work."


---

#### Three-Step Execution Checklist for Cyclic Problems

1. **Identify Direction & Steps:** Label every leg ($A \to B$, $B \to C$, etc.) and check arrow direction.
    
2. **Flag the Sign of $Q$ for Each Leg:**
    
    - **Isochoric ($V = \text{const}$):** $Q = n C_v \Delta T = \frac{C_v}{R} V \Delta P$
        
        - $P \uparrow \implies Q > 0$ (**Input**)
            
        - $P \downarrow \implies Q < 0$ (**Rejected**)
            
    - **Isobaric ($P = \text{const}$):** $Q = n C_p \Delta T = \frac{C_p}{R} P \Delta V$
        
        - $V \uparrow \implies Q > 0$ (**Input**)
            
        - $V \downarrow \implies Q < 0$ (**Rejected**)
            
    - **Isothermal ($T = \text{const}$):** $Q = W = nRT \ln(V_f / V_i)$
        
        - Expansion $\implies Q > 0$ (**Input**)
            
        - Compression $\implies Q < 0$ (**Rejected**)
            
    - **Adiabatic:** $Q = 0$
        
3. **Filter Before Summing:**
    
    - If the question asks for **work** or **net heat** $\to$ take the enclosed loop area.
        
    - If the question asks for **heat required / supplied** $\to$ sum **only** the $Q > 0$ legs.
        
    - If the question asks for **efficiency ($\eta$)** $\to$ use $\eta = \frac{W_{\text{net}}}{Q_{\text{in}}}$, where the denominator is strictly the $Q > 0$ sum.


---

Compressibility ($\beta$) is the reciprocal of the bulk modulus ($B$) and represents the fractional decrease in volume per unit increase in pressure:

$$\beta = \frac{1}{B} = -\frac{\Delta V}{V \cdot \Delta P}$$


---

