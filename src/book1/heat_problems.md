# Solving Heat Problems

### Principle
When solving heat problems, we **must** remember:
$$Q_{released} = Q_{absorbed}$$
or, if there is heat lost to the surrounding:
$$Q_{released} = Q_{absorbed} + Q_{loss}$$


---

### Maths with Heat
Main ways to relate heat:
- $Q = Pt$, commonly used for $Q_{released}$
- $Q = C\Delta T$
- $Q = mc\Delta T$
\*This is just a summary, for more details please refer to their related pages

---
# Examples
these are uncommon and challenging examples, for more trivial examples check out ur phy notes

### 1. Thermal equilibrium

> **This question and the answer is verified by Andrew!**

$200 g$ of $100\degree C$ water is poured in a $500g$ glass cup. The glass cup was originally $25\degree C$. Assume no heat is lost to the surrounding.

Given: $c_{water} = 4200\ J\ kg^{-1}\ \degree C^{-1}$ and $c_{glass} = 840\ J\ kg^{-1}\ \degree C^{-1}$

**(a)** Find the final temperature when the water and the glass achieved thermal equilibrium.

1. Relate heat released and absorbed (units are omitted due to complexity)
> $$
\begin{align}
Q_{released\ by\ water} &= Q_{absorbed\ by\ glass} \\
m_wc_w\Delta T_w &= m_gc_g\Delta T_g \\
(0.2)(4200)\Delta T_w &= (0.5)(840)\Delta T_g \\
\Delta T_w &= 0.5\Delta T_g \\
\end{align}
$$
- Note that although water releases heat, $\Delta T_w$ is positive here.

2. Equal temperatures due to thermal equilibrium
> $$
\begin{align}
T_{w,f} &= T_{g,f} \\
T_{w,i} - \Delta T_w &= T_{g,i} + \Delta T_g \\
100\degree C - 0.5\Delta T_g &= 25\degree C + \Delta T_g \\
75\degree C &= 1.5\Delta T_g \\
\Delta T_g &= 50\degree C
\end{align}
$$
- $w,i$ means water initial; $g,f$ means glass final
- We substituted $\Delta T_w = 0.5\Delta T_g$ from step 1
3. Find final temperature
> $T = T_{g,i} + \Delta T_g = 25\degree C + 50\degree C = 75\degree C$

**(b)** The glass of water is now heated with a heater of power rating $200W$. The heater was on for duration $t$. After that, the glass and water achieved thermal equilibrium of $90\degree C$ in some time. Find $t$.

> Since energy is required to raise both their temperatures by the same amount:
> 
> $\Delta T_g = \Delta T_w = 90\degree C - 75\degree C = 15\degree C$
$$
\begin{align}
Q_{released} &= Q_{absorbed} \\
Pt &= m_wc_w\Delta T_w + m_gc_g\Delta T_g \ \ \ \ \ \ \ \ (*1) \\
(200W)t &= (0.2kg)(4200)(15\degree C) + (0.5kg)(840)(15\degree C) \\
t &= 63s \\
\end{align}
$$

- $(*1)$ We only need to account for the total amount of energy absorbed, as the temperatures will become equal through heat transfer. We can ignore the uneven distribution of temperatures during heating.
