### Overview 
The derivative of a function is a function whose value at every point is the slope of the line tangent to the original function at that point. This can be calculated as $$ \lim_{h\rightarrow 0} \frac{f(a+h) - f(a)}{h}$$ assuming this limit exists. The above equation gives the derivative at  $x=a$.

To find a function for the derivative of $f(x)$, apply the formula $$f^\prime (x) = \lim_{h\rightarrow 0} \frac{f(x+h) -f(x)}{h}$$
### Derivative Rules
There are several rules that can be applied to most derivative problems that greatly simplify the process. 
1. $f(x) = c : f^\prime (x) = 0$
2. $f(x) = x^n : f^\prime (x) = n\cdot x^{n-1}$
3. $$\frac{d}{dx}(f(x)+g(x)) = \frac{d}{dx}(f(x)) + \frac{d}{dx}(g(x))$$
4. $$\frac{d}{dx}(f(x)-g(x)) = \frac{d}{dx}(f(x)) - \frac{d}{dx}(g(x))$$
5. $f(x) = k\cdot f(x) : f^\prime (x) = k\cdot f^\prime (x)$
6. $$\frac{d}{dx}(f(x)\cdot g(x)) = f^\prime(x)\cdot g(x) + g^\prime(x)\cdot f(x)$$
7. $$\frac{d}{dx}\frac{f(x)}{g(x)} = \frac{f^\prime(x)\cdot g(x) - g^\prime(x) \cdot f(x)}{g(x)^2}$$
8. $h(x) = f(g(x))$ $$h^\prime(x) = f^\prime(g(x))\cdot g^\prime(x)$$