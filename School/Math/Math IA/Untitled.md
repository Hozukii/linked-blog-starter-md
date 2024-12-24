Lagrange interpolation also known as Lagrange polynomial is used to create a polynomial function  $P(x)$ of degree $(n-1)$ that passes through n points. 

The general formula is given by (Archer, 2024):
\begin{equation}
     P(x) = \sum^n_{j=1} P_j (x)
\end{equation}
where:
\begin{equation}
    P_j (x) = y_j  \prod^n_{\begin{matrix} k=1 \\ k \neq j  \end{matrix}} \dfrac {x-x_k}{x_j - x_k}
\end{equation}
Lagrange interpolation is particularly useful because it allows me to approximate the curves of the mouse's profile from sets of data points taken from images of the mouse. Additionally, Lagrange interpolation is particularly suited as Lagrange polynomials are straightforward to integrate. 
However, as the number of data points increases, the degree of the polynomial increases, increasing becoming challenging to calculate. Therefore, the number of data points should be minimized as much as possible. Another disadvantage of Lagrange interpolation is known as Runge's phenomenon. While Lagrange polynomials intersect through all the data points, oscillations in the function often occurs when the degree of polynomials is high. 
In figure 5, when trying to approximate the function : $f(x) = (1+25x^2)^{-1}, oscillation in the Lagrange polynomial can be seen at the edges. 

