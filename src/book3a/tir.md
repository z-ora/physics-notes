# Total Internal Reflection

Total internal reflection (TIR) occurs if:
1. light travels from an **optically denser** medium to an **optically less dense** medium
2. angle of incidence > critical angle ($i > C$)


---

### Critical angle $C$

Critical angle is the angle of incidence that causes light to refract **along the boundary of the two medium**

![](assets/tir_compare.png)

|                        | Figure 1 | Figure 2    | Figure 3 |
| ---------------------- | -------- | ----------- | -------- |
| angle of incidence $i$ | $i < C$  | $i = C$     | $i > C$  |
| TIR occurs?            | no       | just occurs | occurs   |

Applying General Snell's Law on figure 2, we have:

$$C = sin^{-1}(\dfrac{n_{to}}{n_{from}})$$
where $n_{to} < n_{from}$ (If you don't know why, refer to the first condition for TIR)

<details>
<summary>See the math</summary>

$$
\begin{align}
n_{from} \cdot sinC & = n_{to} \cdot sin90\degree \\
n_{from} \cdot sinC & = n_{to} \ \ \ \ \ \ \ \ \ \ \ \ \ (sin90\degree = 1) \\
sinC & = \dfrac{n_{to}}{n_{from}} \\
C & = sin^{-1}(\dfrac{n_{to}}{n_{from}})
\end{align}
$$

</details>


### Relation between $C$ and $n$

Situation: a light ray is going from medium 1 to medium 2, where $n_1 > n_2$

| If ...                     | $n_1$ increases                                                                                                                                  | $n_2$ increases                                                                                                                                  |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Then ...**               | $C$ decreases                                                                                                                                    | $C$ increases                                                                                                                                    |
| **Feel<br>The<br>Physics** | light compared to original:<br>- becomes much faster in medium 2<br>- bends away from normal more<br>- easier to TIR<br>$\therefore C$ decreases | light compared to original:<br>- becomes less faster in medium 2<br>- bends away from normal less<br>- harder to TIR<br>$\therefore C$ increases |


Actually, we can use this equation for comparing changes
$$C \approx \dfrac{n_{to}}{n_{from}}$$
**This equation is NOT correct, it only lets u see how C changes with both n**

