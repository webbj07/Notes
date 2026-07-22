### Overview
The limit of a function is the value that a function approaches as its inputs reach a particular value. i.e. for the function $f(x)$, the limit as x approaches a would be written as $$\lim_{x\rightarrow a} f(x) = L$$
This process is useful in many different parts of calculus, are the fundamental concepts behind [[Basic Derivatives]] and [[Basic Integrals]].
### Calculation
Limits can be calculated in several different ways depending on the situation. In the simplest of cases, evaluating a limit could be the same as evaluating a function. For example, take some function $f(x)$ and its limit $\lim_{x\rightarrow a}=L$. If the value of $f(a)$ exists, then the limit $L$ is just the value of $f(a)$. In more complex cases, a series of limit laws needs to be applied to find an answer.
#### Limit Laws
1. $$\lim_{x\rightarrow a}x= a$$
2. $$\lim_{x\rightarrow a}c = c$$
3. Given that $f(x)$  and $g(x)$ respectively approach L and M at a ,$$\lim_{x\rightarrow a} (f(x) + g(x)) = \lim_{x\rightarrow a} f(x) + \lim_{x\rightarrow a} g(x) = L+M $$ 
4. $$\lim_{x\rightarrow a} (f(x) - g(x)) = \lim_{x\rightarrow a} f(x) - \lim_{x\rightarrow a} g(x) = L-M $$
5. $$\lim_{x\rightarrow a} c\cdot f(x) = c\cdot L$$
6. $$\lim_{x\rightarrow a} (f(x) \cdot g(x)) = \lim_{x\rightarrow a} f(x) \cdot \lim_{x\rightarrow a} g(x) = L\cdot M $$
7. $$\lim_{x\rightarrow a} \frac{f(x)}{g(x)} = \frac{\lim_{x\rightarrow a} f(x)}{\lim_{x\rightarrow a} g(x)} = \frac{L}{M}$$ assuming $M \neq 0$. Also see [[L'Hopital's Rule]] if $\frac{L}{M}$ is indeterminate
8. $$\lim_{x\rightarrow a} \sqrt[n]{f(x)} = \sqrt[n]{\lim_{x\rightarrow a}f(x)} = \sqrt[n]{L}$$ for all L if n is odd and for all $L \geq 0$ if n is even and $f(x) \geq 0$

Applying these laws and occasionally some techniques discussed in [[Continuity]] will generally give a simple answer.







