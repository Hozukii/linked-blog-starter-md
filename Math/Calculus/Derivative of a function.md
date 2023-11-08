## Instantaneous rate of change of a function
Let $f$ be a continous function on interval $[a,b]$ such that for $C \in [a,b]$ we have: 
### $$\lim_{h\to 0} \dfrac{f(x +h) - f(x)}{h} = f'(x) = \dfrac{dy}{dx}$$
![[calculus.png| 250]]
it is to find the derivative from the first principle

## Average rate of change of a function
### $$ \text{average rate of change} = \dfrac{\text{change in y}}{\text{change in x}} = \dfrac{f(x_2) - f(x_1)}{x_2 - x_1}$$
|![[average  rate of change of a function.svg| 500]]
## Laws of derivatives
- If a function has a derivative at $x = a$, we say it is *differentiable* at $x=a$
- if $f$ is a differentiable at $x = a  \implies \space f$ is continuous at $x = a$
- if $f$ is a continuous at $x = a \centernot\implies \space f$ is differentiable at $x =a$
# Simples rules for differentiation
1. $c' = 0$
2. $[c \cdot f(x)]' = c \cdot f' (x)$
3. $(f(x) \pm g(x)' = f'(x)\pm g'(x)$
### Power Rule
$f(x) x^n,  n \in Q$ then $f'(x) = n \cdot x^{n-1}$  
### Product Rule
$$\dfrac d{dx} [f(x) \cdot g(x)] = f(x) \cdot g'(x) + g(x) \cdot f'(x)$$
### Chain Rule
$$f'(z) = f'(g(x)) \cdot g'(x), z = g(x) $$
- Used for composite functions for example:
$$\dfrac d{dx}[(f(x))^n] = n(f(x))^{n-1} \cdot f'(x)$$