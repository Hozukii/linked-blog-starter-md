# Kepler's Laws of Planetary Motion
## Kepler's First Law
- The planets orbit in elliptical paths, with the Sun at one of the two foci
	- **Ellipse** - Closed curve consisting of points whose distances from each of two fixed points (foci) always add up to the same value. 
![[Elipticalpathofaplanet.png|400]]
## Kepler's Second Law 
- A line joining a planet and the Sun sweeps out equal areas in equal times
	- planets move faster when they are closer to the Sun
![[Equalareasinequaltimes.png|400]]
## Kepler's Third Law
- the squares of the orbital periods of the planets are directly proportional to the cubes of the semi-major axes of their orbits.
	- In reality, $R$ is assumed to be the average distance from the sun because it's close to being circular
#### $$T^2 \propto R^3$$
$T$ - period
$R$ - semi-major axes - radius
- Average distance from earth to sun - $1.50 \cdot 10^{11} m \ (1au)$
# Newton's Universal Law of Gravitation 

## Newton's Law 
- **Newton's universal Law of gravitation** - There is a gravitational force between two masses, where:
#### $$ F = G \dfrac {m_1 \cdot m_2}{r^2}$$
- $m_1 \ \& \ m_2$ - point masses
- $r$ - distance between masses
- $G$ - universal gravitation constant
	- $6.67 \cdot 10^{-11} N m^2 kg^{-2}$
	- the small value reflects that gravitational forces are small unless one or both of the masses are very large.
- Newton was able to show that this was consistent with Kepler's third law
- For circular gravitation orbits the necessary centripetal force
	- [[A.2 Forces and Momentum#Circular Motion and Centripetal forces]]
- For a relatively small mass, $m$, orbiting a much larger mass $M$:
- $\dfrac {\cancel m v^2}r = \dfrac {GM \cancel m}{r^2} \to \dfrac {GM}r$
- Since: $v = \dfrac {2 \pi r}{T}$
- $$ \left(  \dfrac {2 \pi r}T \right)^2 = \dfrac {GM}r \to \dfrac {r^3}{T^2} = \dfrac {GM}{4 \pi^2} \text {(a constant)}$$
- This is Kepler's third law on the right hand side 
# Gravitational Fields
- **Gravitational field** - A region (around a mass) in which another mass would experience a gravitational force
- **Field lines** - Representation of fields by a pattern of lines . 
	- Line shows the direction of force on a mass, of force on a positive charge , or on a north pole.
	- Closer the lines, the stronger the force 
![[Fieldlines.png]]
## Gravitational Field Strength
- **Gravitational field strength**, $g$ - the force per unit mass that would be experienced by a small test mass placed at that point.
#### $$ g = \dfrac Fm$$
- SI unit: $N \ kg ^{-1}$ numerically equal to acceleration due to gravity in $m \ s ^{-2}$
### Gravitational field strength around a  planet
- Can be found combining $g = \dfrac Fm$ and $F = G \dfrac {m_1 m_2}{r^2}$
$$ g = \dfrac Fm = \dfrac {G \cancel m_1 m_2}{\cancel m_1 r^2}$$
Representing the large mass by $M$, 
#### $$g = G \dfrac M {r^2}$$
#### Combining gravitational field strength 
- At point $P$, the total gravitational field strength is zero. 
- In general, if two or more masses are creating gravitational field strength at a certain point, then the total field strength is determined by adding the individuals fields, remembering that they are vector quantities
![[Opposingfieldscancel out.png]]

# Orbital motion
- **Satellite** - Object that orbits a much larger mass. 
	- Satellites can be natural or artificial 
- Thinking about Newton's cannonball thought experiment:
	- If a object was travelling at exactly the right speed and direction so that it remains at the same altitude, it remains in orbit: a satellite
- An actual satellite needs to be at least $200km$ above to avoid the effects of air resistance.
	- At that height the speed needed is about $8km^{-1}$
![[projectedatdiff speeds.png|400]]
## Orbital Speed and Time Period of a Satellite
- centripetal acceleration : [[A.2 Forces and Momentum#Centripetal Acceleration]],
	- centripetal acceleration, $g = \dfrac {v^2}r$
- or Considering forces:
	- centripetal force, $mg = \dfrac {mv^2}r$
- In order to maintain a satellite in a circular orbit around the earth, it needs to be given the correct speed, $V$, for its particular radius, $r$, as given by 
- $$g = \dfrac {v^2}{r}$$

- For example for a satellite to orbit on Earth's surface
$$v ^2 = 9.8 \cdot (6.4 \cdot 10^{6})$$
$$ v = 7.9 \cdot 10^3 ms^{-1} \ (7.9 km s^{-1})$$
- For a different height, the gravitational field strength can be calculated from:
  $$ g = \dfrac {GM}{r^2}$$
- All satellites at the same hegiht move with the same speed. The force of gravity acts perpendicularly to motion so that no work is done by that force.

- To calculate the period of an orbit $T$, : [[A.2 Forces and Momentum#Mathematics of Uniform Circular Motion]]
$$ v = \dfrac {2 \pi r}{T}$$
# Gravitational Potential Energy 
- In [[A.3 Work, Energy, and Power#Gravitational Potential Energy]], we introduced:
$$\Delta E_p = mg \Delta h$$
- This assumes that height does not depend on distance
---
- **Gravitational potential energy**,$E_p$ - The work done when bringing all the masses of a system to their present positions assuming that they were originally at infinity
![[Variatios.png]]
- The zero of gravitational potential energy is chosen to be where the masses are separated by an infinite distance
- Gravitational potential energy is always given as a negative since energy would have to be supplied to separate the masses to infinity, where a system then has zero gravitational potential energy. 
- The total work done does not depend on the path taken
# Equation for Gravitational Potential Energy 
- [[potential energy]] - To calculate the gravitational potential energy, we need to calculate the total amount of force needed to move the object to a certain position thus:
$$E_p = \int_{r^2}^{r^1}{F_r} \ dr$$
and since: $F_r = -\dfrac {Gmm}{r^2}$
$$E_p = -Gm_1m_2 \int_{r^2}^{r^1}{\dfrac {dr}{r^2}} = \dfrac {Gm_1m_2}{r_2}-\dfrac {Gm_1m_2}{r_1}$$

- It can be found using calculus looking at the area under force per distance
	- but calculus is not part of the course 
	- Gravitatinal force is not constant 
- The relationship can be stated as
	- Gravitational potential energy between two masses are given by :
#### $$ E_p = -G \dfrac {m_1 m_2}r$$
- because:
	- Work done = Force x distance = $G\dfrac {m_1 m_2}{r^2} \cdot r$
# Gravitational potential 
- **Gravitational potential**, $V_g$ - Wok done in moving a test mass of 1 kg to a specified point from infinity 
	- It can be considered as gravitational potential energy per unit mass
#### $$\text {Gravitational potential}, V_g = \dfrac {E_p}m = -G \dfrac Mr$$
- $M$ - very much larger mass
- $m$ - relatively small mass 
- It's a scalar quantity 
- SI unit: $J \ kg ^{-1}$
- all values are negative
## Equipotential Surfaces
- **Equipotential line (or surface)** - Line (or surface)  joining points of equal potential. 
	- always perpendicular to field lines
- Increasing separation of lines indicates a weakening of gravitational field
- All equipotential lines form closed loops
- They point from higher potential to lower potential 
![[Equipotential lines around spherical.png|400]]
## Gravitational potential difference 
- **Gravitational potential difference**, $\Delta V_g$ - Difference in gravitational potential between two points, which equals the work done when 1kg is moved between the ponits
#### $$ \Delta V_g = \dfrac W m \text {or } W = m \Delta V_g$$
- $W$ - work done on unit mass 1kg
- Work has to be done to increase its gravitational potential energy; that is to move it to higher potential
![[Workt.png]]
### Gravitational Potential-Distance Graphs 
- SHows the variation of gravitational potential around a spherical planet. 
- $W = \cancel m \Delta V_g = \cancel m g \Delta r$ 
	- if $\Delta r$ is small enough distance that the value of $g$ doesn't change.
		- This assumption would need further explanation or justification at HL
- Hence: **Gravitational potential gradient** - Rate of chane of potential with distance
	- Equal in magnitude to field strength (but different signs)
#### $$ \text {gravitational potential gradient} = g = \dfrac {\Delta V_g}{\Delta r}$$
- Gravitational field strength $= g = - \dfrac {\Delta V_g}{\Delta r}$
	- negative sign added to show that the direction of the vector quantity $g$ is opposite to the direction of increasing potential
![[uuuuuuu.png|400]]
# Speeds and energies of Satellites
## Escape Speed
- **Escape Speed** - Minimum theoretical speed that an object must be given in order to move to an infinite distance away from a planet. 
#### $$V_{esc} = \sqrt{\dfrac {2GM}r}$$
- We can calculate the minimum theoretical speed that a projectile of mass $n$ needs in order to "escape" from a planet of mass $M$

- explanation:
	- Kinetic needed = change in gravitational potential energy between location and infinity
$$ \dfrac 12 mv_{esc}^2 = 0- \left( \dfrac{-GMm}r \right)$$
which leads to 
$$V_{esc} = \sqrt{\dfrac {2GM}r}$$
Note that:
- This speed is the same, regardless of direction of travel
- We have assumed that there are no other significant gravitational fields (e.g. moon)
## Orbital Speed
- **Orbital Speed** - For a satellite in a circular orbit, its speed mast have the correct value for the chosen radius.
- In Kepler's third law:
$$\dfrac {r^3}{T^2} = \dfrac {GM}{4\pi^2}$$
Replacing using $T$ with $\dfrac {2\pi r}v$ gives us:
$$ \dfrac {r^3v^2}{4\pi^2r^2} = \dfrac {GM}{4\pi^2}$$
- Speed required to maintain a circular orbit, 
#### $$v_{orbital} = \sqrt{\dfrac {GM}r}$$
## Artificial satellites 
- To put satellites into orbit we need to provide enough energy to
	- Increase the gravitational potential energy of the satellite
	- Increase the gravitational potential energy of the launch vehicle fuel, etc.
	- Give the satellite the required kinetic energy for the required orbit 
	- overcome fictional fores
	- allow for thermal energy dissipation
- Gravitational potential energy of a satellite of mass $m$ orbiting a planet, or moon, of mass $M$ at a distance $r$ from the planet's center is given by:
#### $$ E_p = -G \dfrac {Mm}r$$
For a satellite already in orbit:
$$ \text {total energy, }E_T = E_k + E_p = \dfrac 12 mv^2_{orbital} + \left(-G\dfrac{Mm}r \right)$$
but we know that:
$$v^2_{orbital} = \dfrac {GM}r$$
- total energy of a satellite in a circular orbit:
$$E_T = -\dfrac 12 \dfrac {GMm}r$$
- Satellite in a circular orbit does not have enough energy to escape the gravitational field, so that both its potential energy and its total energy are negative
![[Pasted image 20240910134357.png|400]]
