Implicit differentiation is a variation of [[Derivatives]] used to find the slopes of tangent curves of equations that are not functions (ex. the implicit function $x+y=25$). Using implicit differentiation avoids having to solve for an explicit function of x or y.
#### Steps
1. Take the derivative of both sides of the equation. (remember the chain rule)
2. Rewrite the equation so that all terms containing $\frac{dy}{dx}$ are on one side and all terms that do not contain $\frac{dy}{dx}$ are on the other side
3. Factor out $\frac{dy}{dx}$ on the left 
4. Solve for $\frac{dy}{dx}$
#### Example
$x^3sin(y)+y=4x+3$, find $\frac{dy}{dx}$
$$\frac{d}{dx}(x^3sin(y)+y)=\frac{d}{dx}(4x+3)$$
$$\frac{d}{dx}(x^3sin(y))+\frac{d}{dx}(y)=4$$
$$3x^2sin(y)+cos(y)\frac{dy}{dx}\cdot x^3 + \frac{dy}{dx}=4$$
$$x^3cos(y)\frac{dy}{dx}+\frac{dy}{dx} = 4-3x^2sin(y)$$
$$\frac{dy}{dx}(x^3cos(y)+1)=4-3x^2sin(y)$$
$$\frac{dy}{dx}=\frac{4-3x^2sin(y)}{x^3cos(y)+1}$$

