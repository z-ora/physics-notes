# Delta operations

> An object is initially projected downward from the Physics lab on the 5th floor to the basketball court. It arrives at a final speed of 20 m s⁻¹. Then this experiment is repeated from the music room on the 6th floor with the same initial downward speed. Find its speed when arriving the basketball court. 
> 
> (Assume that the height of each floor is 3.5 m. Take as usual _g_ = 9.81 m s⁻².)

$$
\begin{align}
v^2 & = u^2 + 2as \\
\Delta v^2 & = \Delta(u^2 + 2as) \\
& = \Delta(2as) \\
& = 2a\Delta s \\
& = ...
\end{align}
$$

### Addition / subtraction of constants
Delta eliminates constant terms

$C$ is constant:
$$
\begin{align}
\Delta y & = \Delta(C + 2x) \\
& = \Delta(2x) \\
\end{align}
$$

Proof:
$$
\begin{align}
\Delta y & = \Delta(C + 2x) \\
y' - y & = (C + 2x') - (C + 2x) \\
& = 2x' - 2x \\
& = \Delta(2x) \\
\end{align}
$$

### Multiplication / division of constants
Delta breaks through constant factors

$C$ is constant:
$$
\begin{align}
\Delta y & = \Delta(2Cx) \\
& = 2C\Delta x \\
\end{align}
$$

Proof:
$$
\begin{align}
\Delta y & = \Delta(2Cx) \\
y' - y & = (2Cx') - (2Cx) \\
& = 2C(x' - x) \\
& = 2C\Delta x \\
\end{align}
$$