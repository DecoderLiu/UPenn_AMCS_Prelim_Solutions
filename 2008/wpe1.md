
## 1. Prove the convergence of power series

Proof: We would need Dirichlet's criterion to solve this problem.

> **Dirichlet Criterion**
> 
> Let $\{a_n\}$ be a complex sequence with bounded partial sums and $\{b_n\}$ a real squence that monotonically decreasing to zero. Then $\sum a_nb_n$ converges.

Notice that for $x\not\in \mathbb{Z}$, $e^{2\pi ix}\neq 1$, then
$$\left| \sum_{n=1}^N e^{2\pi inx}\right| = \left|\frac{e^{2\pi ix} - e^{2\pi i(N+1)x}}{1- e^{2\pi ix}}\right|\leq \frac{2}{|1- e^{2\pi ix}|} < M$$
for some $M\in \mathbb{N}$

Hence by Dirichlet Criterion, $\sum \frac{e^{2\pi inx}}{n}$ converges for any $x\not\in \mathbb{Z}$.

## 2. Find the upper bound of a boundary integral. 

Proof: We would apply Green's Theorem to solve this problem.

> **Grenn's Theorem**
> 
> Let $C$ be a positively oriented, simple close, piecewise close curve in a plane, $D$ be the area bounded by $C$. $P$, $Q$ be functions of $(x,y)$ be defined on an open region that contains $D$ and having continuous partial derivatives there, then
> $$\oint_C Pdx +Qdy = \iint_D (\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y})dxdy$$

By Green's Theorem, $\left|\oint_{\partial D}xdy\right| = \left|\iint_D dxdy\right| = S(D)\leq \pi R^2$ since $D$ is enclosed by a circle of radius $R$.

The eqality is reached when $D$ coincides with the circle.


