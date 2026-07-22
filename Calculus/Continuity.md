### Evaluating Continuity
A function is continuous if $\lim_{x\rightarrow a} f(x) = f(a)$ and both $f(a)$ and $\lim_{x\rightarrow a} f(x)$ are defined. Verify these conditions to determine continuity.
#### Classifying Discontinuities
##### Removable Discontinuity
A removable discontinuity is a discontinuity where the function is not defined at only one point, but is continuous around that point in such a way that replacing that point with the value of the function's limit at that point would create continuity. This looks like a "hole" in the graph of the function.

A discontinuity is removable if $\lim_{x\rightarrow a} f(x)$ exists but does not satisfy some other condition for continuity.
##### Jump Discontinuity 
A jump discontinuity is a discontinuity where the function suddenly "jumps" to a new value without any connection between the 2 parts of the function. This usually occurs in piece-wise defined functions.

$f(x)$ has a jump discontinuity if $\lim_{x\rightarrow a^+} f(x)$ and $\lim_{x\rightarrow a^-}f(x)$ exist, but  $\lim_{x\rightarrow a^+}f(x) \neq \lim_{x\rightarrow a^-}f(x)$

### Derivatives and Continuity
If a function $f(x)$ is differentiable at $a$, then $f(x)$ is continuous at $a$.