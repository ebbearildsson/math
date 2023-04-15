#geometry
#linear-algebra 
## Definition
The [[Distance]] between a [[Point]] and a [[Plane]].
## Methods
1. [[Normal Vector]]
By using the plane's normal vector, $n:(x_{n},y_{n},z_{n})$, a [[Line]] can be constructed with the direction of the normal but passing through the point, $Q:(x_{q},y_{q},z_{q})$. Then by inserting the line, $l:Q+nt$, in the plane's normal form, $\pi: Ax+Bx+Cx=D$, the distance can be extracted by solving for $t$ and putting that value back into the line's [[Equation]]. $$
\begin{align}
A(x_{q}+x_{n}t)+B(y_{q}+y_{n}t)+C(z_{q}+z_{n}t)=D\\
-\frac{Ax_{q}+By_{q}+Cz_{q}-D
}{Ax_{n}+By_{n}+Cz_{n}}=t_{plane}\\
Q+nt_{plane}=\text{Closest Point}
\end{align}$$
2. Product 
By taking the [[Dot Product]] between the point, $(x,y,z)$ and the plane's normal form [[Coefficients]], $(A,B,C,D)$ the result will be the distance. $$(A,B,C,D)\cdot (x,y,z,1)=distance$$