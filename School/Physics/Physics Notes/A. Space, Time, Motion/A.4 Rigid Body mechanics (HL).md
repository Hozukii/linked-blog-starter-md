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
Insert image ...

- $F_1$ has no turning effect 
- $F_2$ has the biggest turning effect
- $F_3$ is somewhere in between
- Also depends of the distance, $r$ from the axis of rotation
- the "turning effect" of a force, $F$ is the **torque**
- **Torque** $\uptau = Fr \space sin\theta$
--- 

- When there is no actual rotation, torque is sometimes called the **moment** of a force
## combining torques

- Torque is a vector quantity but generally we will only be concerned about where it tends to produce clockwise or anticlockwise motion
#### couples
- **Couples** - pair of equal-sized forces that have different line of action but which are parallel to each other and act in opposite directions, either side of the axis of rotation. 
- A couple produces no resultant force, therefore no translational acceleration
- Net resultant force is zero, however, net torque is not zero because they are not acting in the same **line of action**
Insert image...

#### Rotational equilibrium
**equilibrium** - when object remain at rest or constant motion
**Translational equilibrium** - When there is no *resultant force* acting on an object
>[!note] Rotational equilibrium
> **Rotational Equilibrium** -  when there is no resultant torque acting on an object, so it remains stationary or continues to rotate with a constant angular speed
> If an object is in rotational equilibrium it means: Clockwise torque = anticlockwise torque

## angular displacement, velocity, and acceleration

#### Angular displacement
- Any point on a rigid rotating body will be moving along a circular path 
- **Angular displacement** - the total angle, $\theta$, through which a rigid body has rotated from a fixed refence point. Usually measured in radians(or degrees.)
- Equation:
$$\theta = \dfrac sr$$
#### Angular velocity
- vector quantity but direction will not be important here
- **Angular velocity**, $\omega$, is defined as the change of angular displacement divided by the time taken
- Equation:
$$ \omega = \dfrac{\Delta \theta}{\Delta t}$$
- SI unit: $rad s^{-1}$ radians(or degrees) per second
- Angular velocities are ofter quoted in rotations per minute (rpm) 
	- 1 rpm = $0.10 \space rads^{-1}$
- The if velocity is the same, depending on the distance it will change in angular speed
- Linear speed: $v = \omega r$
#### Angular acceleration
**Angular acceleration**, $\alpha$, - $\dfrac{\text{rate of change of angular velocity}}{time}$
$$a = \dfrac{\Delta \omega}{\Delta t}$$
- SI unit: $rads^{-2}$
- There is a simple relationship between angular and linear acceleration
- Since: $\Delta \omega = \dfrac{\Delta v}{r} \to \alpha = \dfrac{\Delta v}{\Delta tr}$
$$\alpha  = \dfrac ar $$


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
insert image 

- **Moment of inertia** - The resistance to a change of rotational motion of an object, which depends on the distribution of mass around the chosen axis of rotation

- **Moment of inerti**, $I$, of a point mass, $m$, rotating at a distance $r$ from its axis is given by:
$$I = mr^2$$

