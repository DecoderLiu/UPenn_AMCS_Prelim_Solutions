
## 1. Prove the convergence of power series

Proof: We would need Dirichlet's criterion to solve this problem.

> **Dirichlet Criterion**
> Let $\{a_n\}$ be a complex sequence with bounded partial sums and $\{b_n\}$ a real squence that monotonically decreasing to zero. Then $\sum a_nb_n$ converges.

Notice that for $x\not\in \mathbb{Z}$, $e^{2\pi ix}\neq 1$, then
$$\left| \sum_{n=1}^N e^{2\pi inx}\right| = \left|\frac{e^{2\pi ix} - e^{2\pi i(N+1)x}}{1- e^{2\pi ix}}\right|\leq \frac{2}{|1- e^{2\pi ix}|} < M$$
for some $M\in \mathbb{N}$

Hence by Dirichlet Criterion, $\sum \frac{e^{2\pi inx}}{n}$ converges for any $x\not\in \mathbb{Z}$.

## 2. Find the upper bound of a boundary integral. 

Proof: 
