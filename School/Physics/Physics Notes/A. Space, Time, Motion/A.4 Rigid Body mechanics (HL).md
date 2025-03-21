# Rotational dynamics
*We will assume that the bodies are rigid*
- **dynamics** - branch of physics concerned with motion and its causes.
- **Rotation** - refers to movement about an axis within the body
	- It does not concern with location
- **revolution** - usually concerns movement of a body around an exterior point 
## comparing rotational motion to linear motion
we can compare our understanding of linear dynamics to rotational dynamics 

| linear motion                 | Rotational motion        |
| ----------------------------- | ------------------------ |
| force                         | torque                   |
| mass (measurement of inertia) | moment of inertia        |
| Linear displacement           | angular displacement     |
| linear speed / velocity       | angular speed / velocity |
| linear acceleration           | angular acceleration     |
| linear momentum               | angular momentum         |
| linear kinetic energy         | rotational kinetic energy       |

# Torque
- **Torque**, $\uptau$, Product of a force and the perpendicular distance from the axis of rotation to its line of action.
#### $$\uptau = Fr \space sin\theta$$
- $F$ - Force 
- $\theta$ - The angle between the line of action of the force and ta line joining the point of application of the force to the axis of rotation. 
- $r$ - distance from the axis of rotation to the point of application of the force. 
- SI unit: $Nm$ (not $Nm^{-1}$) while he same unit as joules, it is not equivalent
- vector quantity
![[Pasted image 20240527194227.png|350]]

- It is important to identify the place where rotation occur
	- Most commonly this will involve an axis of rotation(Terms pivot, hinge, and fulcrum are often used for situations in which movement is not complete, nor continuous)
- **Line of action** - A straight line in which a force is applied
	- Any force applied not on the object's line of action will tend to start , or change, rotational motion if possible
- $F_1$ has no turning effect 
- $F_2$ has the biggest turning effect
- $F_3$ is somewhere in between
- When there is no actual rotation, torque is sometimes called the **moment** of a force
## combining torques
- Torque is a vector quantity but generally we will only be concerned about where it tends to produce clockwise or anticlockwise motion
#### couples
- **Couples** - pair of equal-sized forces that have different line of action but which are parallel to each other and act in opposite directions, either side of the axis of rotation. 
- A couple produces no resultant force, therefore no translational acceleration
- Net resultant force is zero, however, net torque is not zero because they are not acting in the same **line of action**
![[Pasted image 20240527200513.png|200]]
![[Pasted image 20240527200525.png|200]]
- $\uptau = 2Fr \space sin \ \theta$
### Rotational equilibrium
**equilibrium** - when object remain at rest or constant motion
**Translational equilibrium** - When there is no *resultant force* acting on an object
>[!note] Rotational equilibrium
> **Rotational Equilibrium** -  when there is no resultant torque acting on an object, so it remains stationary or continues to rotate with a constant angular speed
> If an object is in rotational equilibrium it means: Clockwise torque = anticlockwise torque

## angular displacement, velocity, and acceleration

#### Angular displacement
- Any point on a rigid rotating body will be moving along a circular path 
- **Angular displacement** - the total angle, $\theta$, through which a rigid body has rotated from a fixed refence point. 
	- Usually measured in radians(or degrees.)
#### $$\theta = \dfrac sr$$
$s$ - arc length travelled 
$r$ - radius
![[Pasted image 20240528185247.png|200]]
#### Angular velocity
- vector quantity but direction will not be important here
- **Angular velocity**, $\omega$, is defined as the change of angular displacement divided by the time taken
#### $$ \omega = \dfrac{\Delta \theta}{\Delta t}$$
- SI unit: $rad s^{-1}$
- Angular velocities are often quoted in rotations per minute (rpm) 
	- 1 rpm = $0.10 \space rads^{-1}$
- The if velocity is the same, depending on the distance it will change in angular speed
- Linear speed can be calculated as:
#### $$v = \omega r$$
#### Angular acceleration
**Angular acceleration**, $\alpha$, - $\dfrac{\text{rate of change of angular velocity}}{time}$
#### $$a = \dfrac{\Delta \omega}{\Delta t}$$
- SI unit: $rads^{-2}$
- There is a simple relationship between angular and linear acceleration
- Since: $\Delta \omega = \dfrac{\Delta v}{r} \to \alpha = \dfrac{\Delta v}{\Delta tr}$
#### $$\alpha  = \dfrac ar $$

$\alpha$ - angular acceleration
$a$ - linear accelreration
$r$ - radius
![[Pasted image 20240528185627.png|300]]
# Equations of Motion for Angular Acceleration 
We can compare with the suvat equation:

| SUVAT                     | Equations for uniform angular acceleration          |
| ------------------------- | --------------------------------------------------- |
| $s = \dfrac{(u + v)}{2}t$ | $\Delta \theta = \dfrac{(\omega_f + \omega_i)}{2}t$ |
| $v = u + at$              | $\omega_f  = \omega_i + at$                         |
| $s = ut + \dfrac 12 at^2$ | $\Delta \theta = \omega_i t + \dfrac 12 at^2$       |
| $v^2  = u^2 + 2as$        | $\omega_f^2 = \omega_i^2 + 2a\Delta \theta$         | 

## Graphs of rational motion
- Graphs for rotational motion can be interpreted in the same way as a graphs for linear motion
![[Pasted image 20240528185742.png|200]]
![[Pasted image 20240528185753.png|200]]

# Moment of Inertia
- **Moment of inertia** - The resistance to a change of rotational motion of an object, which depends on the distribution of mass around the chosen axis of rotation
	- Moment of inertia $I$, of a point mass, $m$, rotating at a distance $r$ from its axis is given by:
#### $$I = mr^2$$
SI unit: $kgm^2$
- Most spherical objects can be considered to behave like masses concentrated at their centre points. 
![[Pasted image 20240528190115.png|300]]

- In principle The moment of inertia of any real, extended mass can be determined by the addition of the individual moments of inertia of its point masses: 
#### $$I = \Sigma mr^2$$
- $r$ - distance from axis of rotation
- In practice, the moments of most simple-shaped objects about specific axes are well known. 
![[Pasted image 20240528190847.png]]

# Newton's second law for rotational motion
- For linear motion, $F = ma$ 
	- Seen in: [[A.2 Forces and Momentum#Newton's second law of motion]]
- For rotational motion:
#### $$ \text {torque,} \uptau = I \alpha$$
- $\uptau$ - resultant torque
- $I$ - moment of inertia
- $\alpha$ - angular acceleration
## conservation of angular momentum 
- **Angular momentum**, $L$  - the rotational equivalent of linear momentum $p = mv$. given by:
#### $$L = I \omega$$
Si unit: $kg m^2 s^{-1}$
$I$ - moment of inertia
$\omega$ - angular velocity
- **Conservation of angular momentum** - The total resultant angular momentum of a system is constant provided that no resultant external torque is acting on it. 
![[Pasted image 20240528191643.png|200]]
- Since the moment of inertia for $b$ is smaller than $a$ the angular velocity is larger since angular momentum is constant
## Angular impulse
- We have seen in [[A.2 Forces and Momentum#impulse]]
	- $J = F \Delta t$. 
	- Using newton's second law, a change in momentum, $\Delta p$ occurs because of impulse $F\Delta t$ 
- A change of angular momentum, $\Delta L = \Delta (I \omega)$ occurs because of an angular impulse, $t \Delta t$ : 
#### $$\Delta L = \uptau \Delta t$$
SI unit: $kgm^2s^{-1}$
$L$ - angular momentum
$\uptau$ - torque
$t$ - time

- If the torque changes then average value should be used. 
- The area under a torque-time graph is equal to angular impulse
## Rotational Kinetic Energy
From topic [[A.3 Work, Energy, and Power]], that linear kinetic energy is: 
$$ E_k = \dfrac 12 mv^2 = \dfrac {p^2}{2m}$$
- Rotational energy, $E_k$ - kinetic energy due to rotation, rather than translation:
#### $$E_k = \dfrac 12 I \omega^2 = \dfrac {L^2}{2I}$$
$\omega$ - angular velocity
$I$ - moment of inertia
$L$ - angular momentum

- It is common for an object to have both linear and rotational kinetic energy
	- ex: bicycle
### Rolling (without slipping)
- Consider a wheel with radius $r$ rotating with an angular speed $\omega$ 
- All points on its circumference will be moving with linear speed $v = \omega r$ 
- If point $P$ is moving with linear speed $v$, this must also be the overall speed of the motor bike, as shown on the central axle.
![[Pasted image 20240529192604.png|450]]

### Rolling down a slope
- **Roll** - Rotation of an object along a surface in which the lowest point of the object is instantaneously stationary. 
	- Requires friction
- An object, such as a ball or a wheel, which can roll down a hill will transfer its gravitational potential energy to both translational and rotational kinetic energy
 ![[Pasted image 20240529193145.png|350]]
$$ mg \Delta h = \dfrac 12 mv^2 + \dfrac 12 I \omega^2$$
- At the bottom of a slope, a sliding object will reach a higher speed than a rolling object. 
- rotating objects that have bigger moments of inertia will travel slower at the bottom of the same slope
- If the angle of the slope is too steep, rolling will not be possible
- Consider a solid sphere, for which:
$$ I = \dfrac 25mr^2$$
- Remember that $v = \omega r$:
$$mg\Delta h = \dfrac 12 m \omega ^2 r^2 + \begin{pmatrix} \dfrac 12 \end{pmatrix} \cdot \dfrac 25 mr^2 \omega^2 = \dfrac 7 {10} m\omega ^2 r^2$$
- Cancelling out the $m$ :
$$g\Delta h = \dfrac 12  \omega ^2 r^2 + \begin{pmatrix} \dfrac 12 \end{pmatrix} \cdot \dfrac 25 r^2 \omega^2 = \dfrac 7 {10} \omega ^2 r^2$$
