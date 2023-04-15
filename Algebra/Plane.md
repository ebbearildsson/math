#geometry
#linear-algebra 
## Definition
An object with height and width but no depth.
## Methods
1. Normal Form
The normal form of the plane must satisfy the following conditions: $$\begin{align}Ax+By+Cz=D\\ A^{2}+B^{2}+C^{2}=1\\ D \geq 0\end{align}$$To find this form given 3 points, $p_{0}=(x_{0},y_{0},z_{0}), p_{1}=(x_{1}, y_{1}, z_{1}), p_{2}=(x_{2},y_{2},z_{2})$, a [[Equation System]] can be created using the first of the criteria. $$
\begin{align}
ax_{0}+by_{0}+cz_{0}=d\\
ax_{1}+by_{1}+cz_{1}=d\\
ax_{2}+by_{2}+cz_{2}=d
\end{align}
$$By solving for $d$ one can eliminate the other variables and then simply choose the desired value for $d$ to get the values for the rest.
2. Parametric Form
Given 3 [[Point]]s $P, Q, R$, the parametric form can be written as: $$F(s,t)=(1-s-t)P+sQ+tR$$
3. Directional [[Vector]]s
Given 3 points, $p_{0}=(x_{0},y_{0},z_{0}), p_{1}=(x_{1}, y_{1}, z_{1}), p_{2}=(x_{2},y_{2},z_{2})$, one can calculate two directional vectors, $p_{01},p_{02}$, from which we can find the plane's [[Normal Vector]], $p_{n}=(x_{n},y_{n},z_{n})$, 
by taking the [[Dot Product]] of the directional vectors. This together with the origin point from which the directional vectors where constructed, $p_{0}$, can then be inserted into the normal form of the plane, $\pi$:$$\pi:x_{n}(x-x_{0})+y_{n}(y-y_{0})+z_{n}(z-z_{0})=0$$
