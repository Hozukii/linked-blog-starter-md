- Used a model software called UG.
- Hypermesh is used to tackle physics simulations 
- CFD - computational fluid dynamics 

### Propeller slip/ pitch / actual slip / theoretical slip
- each time a screw make a complete turn, it has completed a "pitch"
	- Pitch is the distance the screw travelled during one complete turn 
	- A fluid produces drag against the propeller, so the propeller never actually reaches its full pitch.
- The lost distance of the pitch due to drag is **propeller slip**
**Propeller slip** - The difference between theoretical and the actual distance travelled by the propeller in each rotation - the difference of theoretical and actual speed. 
![[Pasted image 20240728225429.png|300]]

### Blade Element Theory 
Blade Element Theory is a method of predicting the performance of a propeller. The theory analyzes  forces acting on small sections on the blade such as torque or thrust. This theory does not account for tip vortex or the effect of the other propeller. It treats each blade as independent from other blades. 

![[Pasted image 20240728221240.png]]
![[Pasted image 20240728221245.png]]
https://www.aerodynamics4students.com/propulsion/blade-element-propeller-theory.php
![[Pasted image 20240728221424.png]]
https://www.youtube.com/watch?v=7D53Xmo3vy4&list=PLUHGprUixGhWMxW4-yumvCTq5K9TuBvaP

$V_{ax}$ - Axial flow velocity - the velocity of the air that the propeller is experiencing
$V_\theta$ - angular flow velocity - rotational velocity of the propeller
$\theta$ - geometric pitch angle 
$\alpha$ - angle created by the flow angle of attack. 

The difference angle between thrust and lift direction is defined as:
$\Phi = \theta - \alpha$ 
Using trigonometry we can write that the elemental thrust and circumferential force are:
$\Delta T = \Delta L \cdot \cos \Phi  - \Delta  D \cdot \sin \phi$
$\Delta F_ \theta = \Delta D \cdot \cos \Phi + \Delta L \cdot \sin \Phi$
The Torque required to turn the element of the blade is:
$\Delta Q  = r \cdot \Delta F_\theta$ 
$r$ - distance between the element and the axis of rotation of the propeller
### Lift and Drag equation
$F_L = c_L \cdot \dfrac {\rho V^2}2 \cdot A$
$F_D = c_D \cdot \dfrac {\rho V^2} 2 \cdot A$
$c_L$ - lift coefficient
$c_D$ - drag coefficient
$V$ - flow velocity - velocity of the fluid
$A$ - body Area

#### Lift and Drag equation in BEM
$\Delta L = c_L \cdot \dfrac {\rho V^2}2 \cdot c \cdot dr$
$\Delta D = c_D \cdot \dfrac {\rho V^2}2 \cdot c \cdot dr$
$c$ - chord - measured in $m$
$dr$ - elemental width - measured in $m$
$c \cdot dr$ - the surface area of the blade
