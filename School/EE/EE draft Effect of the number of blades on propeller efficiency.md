Questions to ask Mr. Davis:
Should I include things that we have already learned in the background knowledge?
How many times should the data be repeated? 




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
https://society-of-flight-test-engineers.github.io/handbook-2013/propellers.html
Propeller efficiency ($\eta$): 
$$ \eta = \dfrac {P_{out}}{P_{in}} = \dfrac {T \cdot v_T}{Q \cdot \omega}$$
However, for sake of simplicity and the lack equipment I will be substituting mechanical power $(Q \cdot \omega)$ as electrical power (Current x Voltage) thus: 
$$ \eta = \dfrac {T\cdot v_T}{I \cdot V}$$ 

#### Actuator Disk Theory 
https://www1.grc.nasa.gov/beginners-guide-to-aeronautics/propeller-thrust/
https://www.e-education.psu.edu/aersp583/node/470

Actuator disk theory also known as momentum theory is a one-dimensional model which applies conservation of mass and momentum in order to understand and predict the performance characteristics of a rotor. The theory assumes that the rotor is a infinitely thin disk with a diameter $D$ which induces uniform velocity of airflow across its surface. The flow of the fluid is assumed to be incompressible. 
![[OC windtunnel.png|400]]
![[2 Momentum theory tunnel.png|400]]
- **Make new diagram because symbols are wrong**

The mass flow rate through the streamtube $\dot m$ is defined as:
$$ \dot m = \rho \cdot v_p \cdot A$$ The equation for thrust can also be derived:
$$T = \Delta p \cdot A = \dot m \cdot (v_e - v_0)$$
and $u$ can be derived:
$$v_p = \dfrac 12 (v_e + v_0)$$

the Area of the disk $A$ as a function of rotor diameter $D$ as:
$$A = \dfrac {\pi \cdot D^2}{4}$$


### Blade Element Theory 
Blade Element Theory is a method of predicting the performance of a propeller. The theory analyzes forces acting on small sections on the blade such as torque or thrust. This theory does not account for tip vortex or the effect of the other propeller. It treats each blade as independent from other blades. 

![[BET propeller blade.png|400]]
https://www.aerodynamics4students.com/propulsion/blade-element-propeller-theory.php
![[BET propeller shaft 2.png|400]]
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
![[Propeller airfoil design.png|500]]
(Dimensions of the airfoil measured in mm)
The propeller blade was given an angle of 15 degrees to create an angle of attack and to allow sufficient space between the propeller blades to prevent overlap. 5 propeller designs were made with 2-6 blades. The propellers were then 3d printed using PETG materials for its benefits in strength and availability. To reduce turbulence created by uneven surfaces, the propellers were lightly sanded down to remove any discrepancies in its surface. 
![[propellers CAD pictures transparent.png|500]]
(CAD models of the propellers)
![[Printed propellers.png|500]]
(Final 3d printed propellers)


## Methodology

Apparatus: 
- Multimeter
- anemometer
- motor
- 2 x 9V/ 6LR61 alkaline battery. 
- electrical wires
- 5 x Propellers (2-6 blades)
Method:
To account for the gradual decrease in battery performance, all of the data points were taken when the fans hit their top wind velocity. The anemometer was placed 1 cm away from the propeller to measure the velocity at the propeller. The current and potential difference during the experiment was measured using the multi-meter. To properly test the performance of the propeller, two tests were conducted using different batteries. Furthermore, the first experiment was done in order from the lowest to highest number of blades. The second experiment's order was randomised to see if the decrease in gradual decrease in performance of the batteries had any measurable effects on the results. 

![[Experiment setup.png|400]]

 
Independent variable: 
The independent variable for this research will be the number of blades of the propeller. A twin-bladed all the way till a six-bladed will be tested to observe the performance of the propeller. 
Dependent variables:
The velocity of the fluid and the thrust created will both be dependent on the number of blades of the propeller. The torque needed to power the propeller will also be dependent on the propeller design.
Controlled variables:
the design and the angle of the propeller will be kept consistent throughout the different propellers. The velocity of the wind was controlled as the experiment was done indoors. 
Uncontrolled variables: 
While slow and gradual, the decrease in performance of the alkaline battery was uncontrolled.  
While a alkaline 9 volt battery was used, measuring the voltage has showed that the battery while not under load had a voltage of 8.24-8.26 V. However, during load, the voltage decreased significantly caused by the internal resistance. Using ohm's law, the internal resistance of the battery was calculated. 
At 0.86 A, the potential difference of the battery was 6.13V. Therefore:
$$ (8.24 - 6.13 )V = (\text{internal resistance},\Omega) \cdot 0.86 A $$
$$  \text{internal resistance} = 2.45 \Omega$$


### Data
![[battery 1 Data.png]]
![[Battery 2 data.png]]



Calculation for power: 
$P = IV$ 

### Conclusion
- A constant power source could have been used to further increase the accuracy of the experiment
- A wind tunnel could have been used to make the calculations more accurate. 
- The quality of the 3 3d prints, some of the parts were uneven / had artifacts. Due to the printing method, the surfaces could have also been rough increasing unaccounted drag. 


### Bibliography
- Lawless, Al."Flight Test Engineering Reference Handbook." Society of Flight Test Engineers,2013
	https://society-of-flight-test-engineers.github.io/handbook-2013
	accessed 7 Aug. 2024
- Dasilva, Marcelo. "Propeller Thurst." Nasa, 2024
	https://www1.grc.nasa.gov/beginners-guide-to-aeronautics/propeller-thrust/#propeller-propulsion-system
	Accessed 7 Aug. 2024 
- Schmitz, Sven. "2a.1 The Actutator Disk Model."The Pennsylvania State University
	https://www.e-education.psu.edu/aersp583/node/470
	Accessed 7 Aug. 2024
- "Blade Element Theory for Propellers," Aerodynamics for Students
	https://www.aerodynamics4students.com/propulsion/blade-element-propeller-theory.php
	Accessed 7 Aug. 2024
- Wertheimer, Eliott. "Blade Element Theory Explained from Fundamental Principles." Science & Engineering with Elliot, 2019
	https://www.youtube.com/watch?v=7D53Xmo3vy4&list=PLUHGprUixGhWMxW4-yumvCTq5K9TuBvaP
	Accessed 7 Aug. 2024
	
