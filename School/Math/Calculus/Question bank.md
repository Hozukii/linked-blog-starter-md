## IVP
$$\dfrac {dy}{dx} -3 x \cdot sec(y) = 0 \space y(0) = 1$$
$$\dfrac {dy}{dx} + \dfrac {2xy}{x^2 + 1} = 2x \space y(0) = 0$$
$$ \dfrac {dy}{dx} = \dfrac {x^2 + 3xy + y^2}{x^2} \space ,x>0 \space ,y(1) = 1$$
# Homogenous Differential Eq

## Solving the IVP
$\dfrac{dy}{dx} = \dfrac {x^3 + y^3}{xy^2}$, $y(1) = 1$

$x^2 \cdot \dfrac {dy}{dx} = y^2 + xy + 4x^2$, $y(1) = 2$

$xy \cdot \dfrac {dy}{dx} = 1 + x + y^2$, $y(1) = 0$
ans: $y^2 = 3x^2 - 2x-1$

$\dfrac {dy}{dx} = \dfrac {(x+y)^2 - xy}{x^2}$, $y(1) = \sqrt 3$


# Linear Differential equations & Method of integrating Factor
## Solve the following IVP
$\dfrac {dy}{dx} -3y = e^x$, $y(0) =2$

$2x \cdot \dfrac {dy}{dx} -y = x +1$, $y(2) = 4$

$x \cdot \dfrac {dy}{dx}-y = x\cdot ln(x)$, $x > 0$, $y(1) =2$

$x^2 \cdot \dfrac{dy}{dx} + xy = \dfrac 2x$, $y(2) = 1$

$\dfrac {dy}{dx} + tan(x)\cdot y = sec(x)$

$(x-1)\cdot \dfrac {dy}{dx} + xy = (x-1)e^{-x}$
$\dfrac {dy}{dx} = \dfrac yx +1$

## L'Hopital Rule 
$$ \lim_{x\to 0} \dfrac {2^x -1}x $$ ans: $ln2$ 
$$\lim_{x\to 0} \left(\dfrac 1x - \dfrac 1{sin(x)}\right)$$
ans: $0$
$$\lim_{x\to 0} \dfrac {e^x - 1 - x - \dfrac {x^2}2}{x^3}$$
ans:$\dfrac 16$
$$\lim_{x\to 0} \dfrac{sin(x^2)}{ln[cos(x)]}$$
ans:$-2$
$$\lim_{x\to 0} \dfrac {ln(1+x)-x}{cos(x)-1}$$
ans:$1$
$$\lim_{x\to 0} \dfrac{cos(x)-cos(2x)}{x^2}$$
ans $\dfrac 32$
$$\lim_{x\to 0} {x^2-sin(x)}{x^3}$$
?
$$\lim_{x\to 0} \dfrac {cos^2(3x)-1}{x^2}$$
ans: $-9$
$$\lim_{x\to 0} \dfrac {cos(7x)-1}{x \cdot sin(x)}$$ $ans: -\dfrac {49}2$
$$\lim_{x\to \infty} \left[x^2(arctan(x^2)-\dfrac \pi2)\right]$$

$$\lim_{x\to 0} \dfrac {tan(x)-x}{2cos(x)-2sin(x)-cos(x)-1}$$
ans: $0$
$$\lim_{x\to \pi} \left( \dfrac {sin^2x - tan^2 x}{(x-\pi)^4} \right)$$
ans:$-1$

## Kinematics
$$\lim_{x\to 0 }\left(\dfrac {e^{-3x^2} + 3 \space cos(2x)-4}{3x^2}\right)$$

## Kinematics / application
-  origin/main
Exam Q, P1, 7marks
A particle moves along a straight line in such a way that after $t$ seconds, it's displacement in metres, satisfies the equation:
$$s^2 + s -2t = 0$$
Find the expression for the particles' velocity & acceleration

---
A particle travels with velocity:
$$v = \dfrac 1t - 1$$
Find the **distance** travelled by the particle between $t = 0.5$ second and $t = 2$ seconds

Lola has made a cup of tea. The tea's temperature $T$ is initially $85\degree C$ and it cools according to diff eq:
$$\dfrac {dT}{dt} = -0.1(T-20)$$
Where $t$ is time in minutes. Given that Lola likes to drink her tea at a temperature between $40 \degree C$ and $65 \degree C$ how long will she have to wait?


---
A particle moves along a straight line so that its vertical velocity, $v$ after $t$ seconds is:
$$v(t) = e^{sin(t)} + 4 \space sin(t), 0 \le t \le 6$$
a) Find the value of $t$ for which the particle is at rest
b) Find the acceleration of the particle when it changes direction
c) Find the total distance travelled by the particle


1. A particle moves along a straight line with the velocity $v$ (in $m/s$ ) given by the equation:
	$v (t) = 7 \space cos (t) - 5t^{cos(t)}$ , for $0 \le t \le 7$
a) Find the particle's maximum speed
b) Determine the total distance travelled by the particle
c) Find the acceleration of the particle when it changes direction of motion, as well as the time when that happens
ans: t = 0.864 sec & a = - 9.25

--- 
The volume of a melting snowball decreases at a rate proportional to its surface area. Initially, the snowball has volume $1000cm^2$ and it loses half of its volume after 5 minutes. I the shape of the snowball remains spherical during the entire melting period, estimate when it disappears.

--- 
The acceleration of a body moving through a liquid is given by:
$$ a = \left(-\dfrac {v^2}{200}- 32\right) m/s^2$$
Where $v$ is the velocity of the body (in m/s). The initial velocity body was 40m/s. Find (i) the distance travelled and (ii) the time taken until the body momentarily comes to rest

## Euler 

Consider the following IVP 
$\dfrac {dy}{dx} - \dfrac 2x y = \dfrac 3{x^2}$ ,       $y (2) = 5$

1. Use the Euler's Method with the step size 0.2 to find an approximate value of y(3), clearly displaying **all** intermediate values of x and y
2. Draw the graph of he approximated solution curve, obtained with the step size of 0.2 for all $x \in (0,4)$. Based on that graph, explain whether your approximated solution will be an under- or overestimate of the actual value of y(3)
3. Solve the IVP analytically and hence determine the actual value of y(3) correct to five decimal places
4. Find the percentage error when y(3) is approximated by the final value found in part 1. Give our answer to two significant figures 