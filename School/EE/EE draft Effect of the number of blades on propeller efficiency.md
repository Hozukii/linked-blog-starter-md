Research question: How does altering the number of blades of a propeller affects its efficiency?
## Introduction
Aerodynamics is the branch of physics and engineering that studies the behaviour of air and fluids in motion, particularly their interaction with solid objects such as aircrafts, propellers, and vehicles. It helps understand concepts such as drag, lift, and thrust. Its principles are applied across various fields, from the aviation industry, sports and architecture to help optimize performance and efficiency. Within aerodynamics, my topic of interest was propellers with their wide scope of applications from everyday tools such as hair dryers to commercial UAVs.
Propellers are used in many things from aircrafts to computer cooling and there are countless amount of different propeller designs that are in use today. I have always been interested in engineering and product design therefore I often keep an eye for design choices that engineers and designers make in their products. As I take a look at many tools and products, I was curious as to why there are so many different propeller designs even for things that seemingly achieve the same purpose. In hopes of getting closer to that answer, I decided to particularly observe the effect of the number of blades on propeller efficiency. Thus my research question is: How does altering the number of blades of a propeller affects its efficiency?

### Background information
- Blade element theory
- Bernoulli's principle/ actuator disk theory 
- torque / power 
- propeller efficiency 
### Propeller efficiency 
Propeller efficiency ($\eta$): 
$$ \eta = \dfrac {P_{out}}{P_{in}} = \dfrac {T \cdot v_T}{Q \cdot \omega}$$
However, for sake of simplicity and the lack equipment I will be substituting mechanical power $(Q \cdot \omega)$ as electrical power (Current x Voltage) thus: 
$$ \eta = \dfrac {T\cdot v_T}{I \cdot V}$$ 

#### Actuator Disk Theory 
Actuator disk theory also known as momentum theory is a one-dimensional model which applies conservation of mass and momentum in order to understand and predict the performance characteristics of a rotor. The theory assumes that the rotor is a infinitely thin disk with a diameter $D$ which induces uniform velocity of airflow across its surface. The flow of the fluid is assumed to be incompressible. 

![[Pasted image 20240804150120.png|400]]
- **Make new diagram because symbols are wrong**

The mass flow rate through the streamtube $\dot m$ is defined as:
$$ \dot m = \rho u A$$ The equation for thrust can also be derived:
$$T = \Delta p \cdot A = \dot m \cdot (v_0 - u_1)$$
and $u$ can be derived:
$$u = \dfrac 12 (v_0 + u_1)$$


### Blade Element Theory 
Blade Element Theory is a method of predicting the performance of a propeller. The theory analyzes forces acting on small sections on the blade such as torque or thrust. This theory does not account for tip vortex or the effect of the other propeller. It treats each blade as independent from other blades. 

![[Pasted image 20240728221240.png|400]]
https://www.aerodynamics4students.com/propulsion/blade-element-propeller-theory.php
![[Pasted image 20240728221424.png|400]]
https://www.youtube.com/watch?v=7D53Xmo3vy4&list=PLUHGprUixGhWMxW4-yumvCTq5K9TuBvaP

$V_{ax}$ - Axial flow velocity - the velocity of the air that the propeller is experiencing
$V_\theta$ - angular flow velocity - rotational velocity of the propeller
$\theta$ - geometric pitch angle 
$\alpha$ - angle created by the flow angle of attack. - the difference in angle between the flow angle of attack and the zero lift line.
The difference angle between thrust and lift direction is defined as:
$\Phi = \theta - \alpha$ 
Using trigonometry we can write that the elemental thrust and circumferential force are:
$\Delta T = \Delta L \cdot \cos \Phi  - \Delta  D \cdot \sin \phi$
$\Delta F_ \theta = \Delta D \cdot \cos \Phi + \Delta L \cdot \sin \Phi$
The Torque required to turn the element of the blade is:
$\Delta Q  = r \cdot \Delta F_\theta$ 
$r$ - distance between the element and the axis of rotation of the propeller
The equation for the force of lift and drag are defined as:
$F_L = c_L \cdot \dfrac {\rho V^2}2 \cdot A = c_L \cdot \dfrac {\rho V^2}2 \cdot c \cdot dr$
$F_D = c_D \cdot \dfrac {\rho V^2} 2 \cdot A = c_D \cdot \dfrac {\rho V^2}2 \cdot c \cdot dr$
$c_L$ - lift coefficient
$c_D$ - drag coefficient
$V$ - flow velocity - velocity of the fluid
$A , \ (c \cdot dr)$ - body Area
$c$ - chord - measured in $m$
$dr$ - elemental width - measured in $m$

Thus finally the equation for Thrust and Torque is:
$\Delta T = B \cdot \dfrac {\rho V^2}2 \cdot c \cdot (C_L\cdot \cos \Phi  - C_D \cdot \sin \Phi \cdot) \cdot dr$
$\Delta Q  = B\cdot \dfrac {\rho V^2}2 \cdot c \cdot (C_D \cdot \cos \Phi + C_L \cdot \sin \Phi) \cdot r \cdot dr$
Where $B$ is the number of blades on a propeller

## Propeller design
The propellers were designed using Autodesk Fusion which were 3d printed using the Bambu Lab A1 Mini. The design of the propeller was limited due to the capabilities of the 3d printer. The initial propeller utilised the NACA 2412 however, the thin tail wing of the airfoil compromised the strength of the propeller leading to excessive bending which can greatly affect the results. Therefore, the final airfoil shape was decided upon a simple stadium shape.  
![[Pasted image 20240804225013.png|500]]
(Dimensions of the airfoil measured in mm)
The propeller blade was given an angle of 15 degrees to create an angle of attack and to allow sufficient space between the propeller blades to prevent overlap

## Methodology
Independent variable: 
The independent variable for this research will be the number of blades of the propeller. A twin-bladed all the way till a six-bladed will be tested to observe the performance of the propeller. 
Dependent variables:
The velocity of the fluid and the thrust created will both be dependent on the number of blades of the propeller. 
Controlled variables:
The power supplied to the rotor will be unchanged using a 9volt battery. Furthermore, the design and the angle of the propeller will be kept consistent throughout the different propellers. 
Uncontrolled variables: 



### Data
- 6 bladed 
	- 0.95-1.06 amps
	- 3.9 m/s
- 2 bladed 
	- 0.89-0.87 amps
	- 3.5 m/s
	- 