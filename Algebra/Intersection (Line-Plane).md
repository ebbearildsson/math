#algebra 
#linear-algebra 
## Definition
A shared [[Point]] or [[Line]] between a line and a [[Plane]]
> They will only share a line if the line is embedded in the plane.

![[6BEC07E3-D10C-4290-9B00-5E33CF34C05E.png]]
## Methods
1. Algebraic
	By taking the vector notation form of the plane, $(p-p_{0})\cdot n=0$, and the line, $p=l_{0}+ld$, one can then substitute the line equation into the plane's: $$\begin{align}((l_{0}+ld)-p_{0})\cdot n=0\\(l\cdot n)d+(l_{0}-p_{0})\cdot n = 0\\d=\frac{(p_{0}-l_{0})\cdot n}{l\cdot n}\end{align}$$ If $l\cdot n = 0$ it would be division by zero thus no [[Intersection]] is made as the line is [[Parallel]] to the plane unless $(p_{0}-l_{0})\cdot n = 0$ because then the line is contained within the plane. Otherwise if $l\cdot n \neq 0$ there is a singular point of intersection which can be calculated by calculating $d$ from the equation above and then by inserting it into the original line equation. 
1. Parametric
