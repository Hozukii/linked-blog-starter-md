	### Why it's relevant 
- I like modelling objects. While I usually model through the use of quad meshes I think modelling objects with other methods could spark new ideas or appreciate the modern techniques of modelling objects  - personal engagement
- With my interest in technology and design, I think that knowing the volume of a certain mouse shape could be interesting. Its application can be seen in estimating the amount of volume a mouse has in order to fit a certain amount of sensors and battery.
### What is to be done  
- By using double integration and slicing the mouse into different sections, since the mouse is flat on the bottom of the mouse, a approximate model for the mouse can be found in order to model and calculate the volume of the mouse. 
- The mouse wheel will be ignored
- 
### What needs to be done. 
- How to choose the interpolation points
	- Chebyshev's nodes
### Lagrange Interpolation
- Used when we have multiple points and we need to fit a curve within those curves 
- Make a polynomial which is zero at every point except the desired coordinate
- Repeat for all points 
- Then add together
![[lagrange interpolation.png|400]]
![[mouse points.png]]

#### Chebyshev's nodes

### resources/ sources
- How to Set Up Double Integrals
	- https://www.youtube.com/watch?v=gifQWtTWqEY
- $$\int_{0}^{2}\left(\int_{x\left(x-4\right)+4}^{5}\left(2\frac{\left(x-8\ \right)\left(x-13\right)\left(x-17\right)\left(x-20\right)}{-8\cdot-13\cdot-17\cdot-20}+5\frac{\left(x\ \right)\left(x-13\right)\left(x-17\right)\left(x-20\right)}{8\cdot-5\cdot-9\cdot-12}+6\frac{\left(x\ \right)\left(x-8\right)\left(x-17\right)\left(x-20\right)}{13\cdot5\cdot-4\cdot-7}+5\frac{\left(x\ \right)\left(x-8\right)\left(x-13\right)\left(x-20\right)}{17\cdot9\cdot4\cdot-3}+\frac{\left(x\ \right)\left(x-8\right)\left(x-13\right)\left(x-17\right)}{20\cdot12\cdot7\cdot3}+2.5\frac{\left(y-2.5\right)\left(y-4\right)\left(y-5\right)}{-2.5\cdot-4\cdot-5}+2.2\frac{\left(y\right)\left(y-4\right)\left(y-5\right)}{\left(2.5\right)\left(-1.5\right)\left(-2.5\right)}+2.5\frac{\left(y\right)\left(y-2.5\right)\left(y-5\right)}{\left(4\right)\left(1.5\right)\left(-1\right)}+3.2\frac{\left(y\right)\left(y-2.5\right)\left(y-4\right)}{\left(5\right)\left(2.5\right)\left(1\right)}-3.2\right)\ dy\right)dx$$
