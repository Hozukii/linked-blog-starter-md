# Reference frames
- **reference frame** A coordinate system from which events in space and time are measured
	- **coordinate system** - numerical way to identify location and time
- Precise events are used to simplify our understanding
- **Events** - Single incident that occurs exactly at a precise time and location
## Different reference frames
- **Observer** - In relativity, its a hypothetical person who takes measurements from only one specific reference frame. 
	- An observer is always stationary relative to their own reference frame
- For example: If you happened to bang your head on a luggage at a train 2 times, what were the coordinates of these two events and the distance between them?
	- There are 3 possible reference frames that could be occupied by three different observers:
	1. An observer taking measurement sitting on the platform as the train moves past
	2. An observer taking measurements sitting on a seat in the train
	3. An observer taking measurements walking up the train at the same velocity as you. 
- According to newton each of the observers will record different values for how fast you are moving and you position when you bang your head
- but they will all agree on the time between the two events occurring and the distance you have moved up the carriage between the two events. 
### Inertial reference frames
- All reference frames are equally valid: there is no "correct" reference frame.
- **Inertial reference frame** - A frame of reference that is neither accelerating nor experiencing a gravitational field, in which masses obey Newton's lows of motion. 
# Newton's postulates concerning time and space
## Galilean relativity
- **Galilean relativity** - How relative motions were described before the discovery of special relativity 
- In Galilean relativity, al Newton's laws of motion are the same in all frames of reference (inertial)
- Whenever we move our point of view from one reference frame to another, we need to do what is called a *transformation* by applying standard equations
- **Galilean transformation** - The non-relativistic method of mathematically relating observations between reference frames
- If in reference frame $S$ the coordinates of an event are $(x,t)$, in reference frame $S'$, which has relative velocity $v$ compared to $S$, the coordinates of $(x',t')$ are 
#### $$x' = x - vt \ \ \text{and} \ \  t' = t$$
### Velocity Addition Equation
- **velocity addition** - Equation which connects the velocities of the same object as observed in two different reference frames
- If in reference frame $S$, the velocity of an object is $u$, in a reference frame $S'$,which has relative velocity of $v$ compared to $S$, the same movement will be recorded as having a velocity, $u' = u-v$ 
# Introducing special relativity
- **Special relativity** - Special relativity is a theory in physics formulated by Albert Einstein in 1905. It describes how the laws of physics are the same for all non-accelerating observers, and it introduces the concept that the speed of light in a vacuum is constant and independent of the motion of the light source or observer
## The two postulates of special relativity
###### First postulate: The laws of physics are identical (invariant) in all inertial reference frames
- Observations in different inertial reference frames all have equal worth; there is no single 'correct' frame of reference
- The Universe has no unique stationary reference frame
- No experiment is possible that can show an observer's absolute velocity though the Universe. 
###### Second postulate: The speed of light in a vacuum is constant, $c = 3.00 \cdot 10^8 ms^{-1}$
- A person on earth and the rocket travelling at 99% the speed of light will both observe the speed of light to be $3.00 \cdot 10^8 ms^{-1}$
### Implications of the two postulates
- since $v = \dfrac s t$ and if the $v$ is observed to be the same but the $s$, distance travelled is different for different reference frames, then time $t$ must be different
	- Time flows at different rates for different observers
- Space and time are linked as space-time. Space and time are not independent of each other, as they were assumed to be in Newtonian mechanics 
- **space-time** - The combination of space and time into a single entity that is used to describe the fabric of the Universe. 
	- Fundamentally, in relativity, time and space are not independent of each other. They are observed differently depending on the relative motion of an observer
## Lorentz transformation
- **Lorentz transformation** - The equation, involving the Lorentz factor, used to calculate the new position and time coordinate or spacial and temporal intervals, when transferring from one relativistic reference frame to another. 
- If in reference frame $S$, the coordinates of an event are $x$ and $t$, in reference frame $S'$, which has relative velocity of $v$ compared to $S$, the coordinates $(x',t')$, of the same event are given by: 
#### $$ x' = \gamma (x - vt)$$
#### $$ t' = \gamma \begin{pmatrix} t - \dfrac {vx}{c^2} \end{pmatrix}$$
- **Lorentz factor**, $\gamma$ - Scaling factor that describes the distortion of non-invariant quantities when moving between different relativistic reference frames:
	- Calculated using:
#### $$ \gamma = \dfrac 1 {\begin {pmatrix} \sqrt{1-\dfrac {v^2}{c^2}}\end {pmatrix}}$$
- $\gamma > 1$ always
- for everyday macroscopic speeds, $v$ is much smaller than $c$ so that $\gamma$ has a value very close to one. 
### Equations for transforming distances and time intervals between two events
- Often interested in differences in x-coordinates and t-coordinates between events. That is, distances and time intervals. 
- Distance between two events:
$$ \Delta x' = \gamma(\Delta x - v\Delta t)$$
- Time interval between two events:
$$ \Delta t' = \gamma \begin {pmatrix} \Delta t - \dfrac {v \Delta x} {c^2} \end {pmatrix}$$
### Clock synchronization
- **Synchronized** - Two clocks are said to be synchronized if according to an observer they are reading the same time
- Simplest way is to flash a light midway in between and start when the light reaches the clocks
![[Pasted image 20240609201812.png|500]]

- If the distances are known $(L_1, L_2)$, then the clocks can be synchronized by setting them initially to $\dfrac{L_1}c$ and $\dfrac {L_2}c$ and then starting the clocks from those values when the flash is received. 
![[Pasted image 20240609202001.png|500]]

- Consider how an observer from different reference frame, $S'$, would detect the process. An observer who sees the clocks moving will see one clock moving towards the flash and the other clock moving away from the flash since speed of light is the same for all reference frames. 
![[Pasted image 20240609203104.png|500]]
- So in reference frame $S'$, the two clocks will no be synchronized, and the clock on the left will read earlier. 
### Simultaneity
- Consider a train where light beam is sent then reflected back on a mirror to their origin. 
![[Pasted image 20240609203331.png|500]]

- In reference frame $S$, (left), a observer on the train
	- The pulses are sent out simultaneously
	- The pulses reach the end simultaneously
	- The pulses return to observer $S$ simultaneously
- In reference frame $S'$, (right), a observer on the ground outside.
	- The pulses are sent out simultaneously
	- The pulses that travel down the carriage against the motion arrive at the end before the pulse that travels up the carriage
	- However, the observer in $S'$ still sees the pulses return to observer $S$ simultaneously
---
- If two (or more) event occur at the same place at the same time, then they are simultaneous for all observers in all reference frames. 
- If two (or more) events occur at different places, then it is possible that they could be simultaneous in one reference frame and not in another. 
### Velocity addition transformations
#### $$u' = \dfrac {u-v}{\begin{pmatrix} 1 - \dfrac{uv}{c^2}\end {pmatrix}}$$
$u$ - velocity of an object in one reference frame $S$ 
$u'$ - velocity of the same object in reference frame $S'$ 
$v$ - speed of $S'$ in respect to $S$ 

- $u'$ must always be less than $c$ 
- if $u$ and/or $v$ are small compared to $c$, the equation reduces to the Galilean form 
## Time dilation
- **Time dilation** - Relative to an observer who sees the two events occurring in the same place. All other observers measure an increase in the time interval between two events. 
- An observer in reference frame $S$ measures time interval,$\Delta t$ between successive ticks on a stationary clock in their reference frame. 
- Another observer in reference frame $S'$ moving with relative velocity, $v$, will measure a greater time interval for the same ticks, as given by the Lorentz transformation:
$$ \Delta t' = \gamma \begin {pmatrix} \Delta t - \dfrac {v \Delta x} {c^2} \end {pmatrix}$$
- Since the clock is stationary, $\Delta x = 0$, therefore:
  #### $$\Delta t' = \gamma \Delta t$$
  Since $\gamma > 1$ always, the time intervals between the ticks of a clock in a reference frame ($S'$) that is moving relative to the stationary clock are greater known as time dilation$
  ### Proper time interval
  - **Proper time interval** - The time interval between two events as measured by an observer who records the two events occurring at the same point in space
	  - it is the shortest time interval between events measured by any observer. 
- 