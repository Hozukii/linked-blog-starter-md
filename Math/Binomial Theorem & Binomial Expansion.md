			# Binomial Expansion
**Def**: if $n$ & $k$ are integers such that $k \le n$ then we define a **Binomial coefficient**
## $$\binom nk = \dfrac{n!}{k! \cdot (n-k)!}$$
and we read $\binom nk$ as "n choose k"
# Binomial Theorem
$$\binom n 0 = \dfrac{n!}{0! \cdot (n-0)!} = \dfrac{n!}{n!} = 1$$
$$\binom n 1  = \dfrac{n!}{1! \cdot (n-1)!} = \dfrac{n(n-1)!}{(n-1!)} = n$$
$$\binom n n  = \dfrac{n!}{n! \cdot (n-n!)} = 1$$
- The expression $(a+b)$ is called a binomial, and $(a+b)^b$ is called the $n^{th}$ power of a binomial
- we have: 
$$(a +b)^1 = a + b$$
$$(a + b)^2 = a^2 + 2ab + b^2$$
$$(a+b)3 = a^3 + 3a^2b + 3ab^2 + b^3 $$
$$etc...$$
## Binomial theorem: Let n $n \in \mathbb{Z}^+$
$$(a + b)^n = a^n + \binom n1 a^{n-1} \cdot b + \binom n 2 a^{n-2} \cdot b^2 + \binom n r a^{n-r} \cdot b^r \space ... b^n $$
### General theorem: 
### $$T_{r + 1 } = \binom n r a^{n-r} \cdot b^r$$
