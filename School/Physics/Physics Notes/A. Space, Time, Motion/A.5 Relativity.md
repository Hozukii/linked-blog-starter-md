    Reference frames
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
  - **Proper time interval**,$\Delta t_0$ - The time interval between two events as measured by an observer who records the two events occurring at the same point in space
	  - it is the shortest time interval between events measured by any observer. 
- Time dilation formula:
$$\Delta t = \gamma \Delta t_0$$
## Length contraction
- The length of the object, a rod for example, $\Delta x'$ can be determined in reference frame $S'$ from a measurement of the position of its ends.
- We know from Lorentz; $\Delta x' = \gamma (\Delta x - v \Delta t)$, where $\Delta x$ is the length of the rod as observed from reference frame $S$. Assuming $\Delta t = 0$, the equation simplifies:
#### $$ \Delta x = \dfrac {\Delta x '}{\gamma}$$
- Since $\gamma > 1$, any length in another reference frame, which is moving relative to us, will always be less than the length we would measure if the object was in our own reference frame. 
### Proper length
**Proper length**, $L_0$ - is its length when stationary in the same reference frame as as the observer. 
The length contraction formula can be:
#### $$L = \dfrac {L_0} \gamma$$
## The Muon-decay experiment
- **muon**, $\mu$, a unstable elementary subatomic particle. 
- The muon particle effectively provides us a tiny clock that travels at a speed very close to the speed of light. 
- Produced naturally in the Earth's atmosphere as a results of collisions and high-energy cosmic radiation. 
	- The muons produced at around 10km above
	- have an average speed of around $0.995c$ in the Earth's frame reference. 
### Muon decay and the predictions of classical physics 
- The time taken for the muons to descend from 10km is calculated as:
$$t = \dfrac x v = \dfrac {10 \cdot 10^3}{0.995 \cdot 3.00 \cdot 10^8} = 3.35 \cdot 10^{-5}$$
- During this time most will have decayed. we can determine the fraction that arrives by calculating the number of half-lives involved
number of half-lives elapsed as muons travel down to the Earth's surface:
$$\dfrac {\text{total time}}{\text{half-life} } = \dfrac {3.35 \cdot 10^{-5}}{1.56 \cdot 10^{-6}} = 21.5$$
The fraction reaching surface:
$$ f = \begin {pmatrix} \dfrac 12 \end{pmatrix} ^{21.5} = 3.37 \cdot 10^{-7}$$
- Classical physics predicts that only about 1 muon reaches the surface for every 3 million that are created in the upper atmosphere.
- In reality more are detected. 
- The fraction is about 0.2., 
### Muon decay using relativity and time dilation
- In Earth's reference frame, proper length is 10km, speed is $0.995c$, the time interval is $3.35 \cdot 10^{-5}$
- However, in the reference frame of muons' would be measuring the proper time interval: $$\Delta t = \gamma \Delta t_0$$
with:
$$\gamma = \dfrac 1 {\begin {pmatrix} \sqrt {1 - \dfrac {0.995^2 c^2}{c^2}}\end {pmatrix}} = 10$$
So that: 
$$ \begin {matrix} 3.35 \cdot 10^ {-5} = 10 \Delta t_0 \\ \Delta t _0 = 3.35 \cdot 10^{-6}  s \end {matrix}$$
Such that:
$$\dfrac {\text{total time}}{\text{half-life} } = \dfrac {3.35 \cdot 10^{-6}}{1.56 \cdot 10^{-6}} = 2.15$$
and:
$$ f = \begin {pmatrix} \dfrac 12 \end{pmatrix} ^{2.15} = 0.23$$
### Muon decay using relativity and length contraction
- From muon's reference frame, the $10km$ thickness is contracted:
$$ L  = \dfrac {L_0}{\gamma} = \dfrac {10 \cdot 10^3}{10} = 1000m$$
Then:
$$t = \dfrac xv = \dfrac {1000}{0.995 \cdot 3.00 \cdot 10^8} = 3.35 \cdot 10^{-6}$$

# Space-time
- In relativity, space and time are joined to form a single four-dimensional $(x,y,z,t)$ concept called space time
- Things cannot move through space without also moving through time.
- Conversely, we cannot measure time without referring to things moving through space. 
- If everything stayed in exactly the same place and nothing moved, we would have no indication of time passing
## Space-time interval
- In classical physics, distance, $\Delta s$, in 3d $(x,y,z)$ can be calculated using Pythagorean theorem: $(\Delta s)^2 = \Delta x^2 + \Delta y^2 + \Delta z^2$
- $\Delta s$, distance between two points in 4d space-time $(x,y,z,t)$ can be calculated from: $(\Delta s)^2 = c^2 \Delta t ^2 - \Delta x^2 - \Delta y ^2 - \Delta z^2$
- **Space-time interval**, $\Delta s$ - combines both the spatial and temporal elements of space-time into a single value. 
- Since we are restricting to the x-direction only:
#### $$ (\Delta s)^2 = (c \Delta t )^2 - \Delta x ^2$$
- Different observers may measure different time intervals and different distances between events, but they will agree on the space-time interval between events. 
	- therefore:
#### $$ c^2 (\Delta t')^2 - (\Delta x')^2 = c^2 (\Delta t )^2 - (\Delta x)^2$$
- any object moving at the speed of $c$ will have a value of 0
- Any object moving slower than $c$ will have a positive value 
- Any object moving faster than $c$ will have a negative value 
---
- A proper time interval, $\Delta t_0$, - time between two events that take place at the same location, $\Delta x = 0$ therefore:
$$ \begin {matrix}\Delta s^2 = c^2 \Delta t_0^2 - \Delta x = c^2 \Delta t_0 ^2 -0  \\ \Delta s ^2 = c^2 \Delta t_0 ^2 \end{matrix}$$
- The proper length of an object, $L_0$ - its length when stationary in the same reference frame as the observer, $\Delta t = 0$ therefore:
$$ \begin {matrix} \Delta s ^2 = c^2 \Delta t^2 - \Delta x^2 = c^2 0^2 - \Delta x^2 \\ \Delta s ^2 = -\Delta x^2 \end {matrix}$$
	- Negative is to do with how $\Delta s^2$ is defined
## Space-time diagrams
- **Space-time diagrams** - Graphs showing variations of objects' positions with time, adapted to compare different frames of reference. 
![[Pasted image 20240611161859.png|250]]

- Normally drawn with distance, $x$, on the horizontal and time,$t$ , on the vertical. 
	- More commonly it shows $c t$, speed of light x time
- Events are represented as points. 
- Events that occur on the same horizonal line are simultaneous. 
- Events that occur on the same vertical line occur at the same location. 
### World lines
- **world line** - The path that an object traces on a space-time diagram
- An object travelling through space-time can be imagined as a series of consecutive events.
![[Pasted image 20240611162226.png|250]]

- This particular world line does not pass through the origin because the object is observed a short time after the observer started their clock. 
- Since: $v = \dfrac xt$ , the gradient of a world line is given by:
#### $$ \dfrac {ct}x = \dfrac cv$$
- Steeper the gradient, the slower the object is travelling. 
	- has no unit

![[Pasted image 20240611162400.png|300]]

- Line 1 - vertical line since by the observer in the same reference frame, the object is stationary.
- Line 2 - moving ojbect 
- Line 3 - faster moving object 
- Line 4 - has a gradient of 1 ($45 \degree$) It represents : $v = c$, meaning it's travelling at the speed of light which can only be light
###### Angles between world lines and $ct$-axis
$$\tan \theta = \dfrac x{ct} = \dfrac vc$$
therefore: 
#### $$ \theta = \tan ^{-1} \begin {pmatrix}  \dfrac vc \end{pmatrix}$$
### Adding another frame of reference to a space-time diagram
![[Pasted image 20240612153654.png|300]]

- Represents reference frame $S'$ in which it's from the reference frame of line 2 from the previous diagram. 
- The axes of $S,$ frame of reference are tilted and not perpendicular to each other. The coordinates of event 1 in S, $x_1$ and $ct_1$ transforms to $x'_1$ and $ct'_1$ IN $S'$

![[Pasted image 20240612154159.png|300]]

- In reference frame $S'$, Events 1 and Events 2 occur at the same place, but at different times. 
- The same two events in reference frame $S$ occur at different places and at different times. 

![[Pasted image 20240612154358.png|300]]

- Events 3 and 4 are simultaneous for an observer in reference frame $S'$ but at different locations. 
- In reference frame $S$ they occur at different locations and times
### Lines of constant space-time interval

- We have seen that space-time interval is in invariant quantity: 
$$ \Delta s^2 = c^2 (\Delta t')^2 - (\Delta x')^2 = c^2 (\Delta t )^2 - (\Delta x)^2$$
![[Pasted image 20240612161007.png|400]]

![[Pasted image 20240612161213.png|400]]
- We can draw lines of constant space-time interval (invariant hyperbole) on space-time diagrams
- Calculations using the coordinates of any point on a line of constant space-time interval will give the same numerical result
- If observers in each of the reference frames were measuring the length of a stationary rod, with one end at the origin of their reference frame $(0,0)$, they would all record the same proper length of the rod $1m$
- The scales of the axes on space-time diagrams are not equal for different frames of references. 
### Simultaneity in space-time diagrams
- All inertial observers will agree that two events are simultaneous if they occur in the same place
- However, they may disagree as to the order of two events that occur at two different points in space. 
![[Pasted image 20240613170651.png|350]]

- For one observer, event 0 occurs then 1 and 2 occurring simultaneously, then event 3
- For another observer, event 0 and 1 occurs simultaneously then event 2 and 3 simultaneously
### Time dilation in space-time diagrams 
![[Pasted image 20240613171127.png|350]]

- Looking at the muon experiment. The angle formed is $44.9 \degree$ for $v = 0.995c$ (exaggerated for the diagram)
- Event 0 is the formation of the muon particle
- Event 1 is the arrival at Earth's surface
- Reference frame $S$ is of Earth
- Reference $S'$ is of the muon particle 
- To measure the scale of the vertical $ct$-axis, we follow the dashed line of constant space-time interval from Event 1
- Where it can be calculated by measuring the interval $c\Delta t'$.
- The interval according to the observer in reference frame $S$ can be calculated using $c\Delta t$
- In the muon reference frame, Event 1 occurs at time $\Delta t'$, and both events occur at $x' = 0$ 
- Thus the observer measures the spatial separation between two events to be zero, so the time, $\Delta t'$ is the proper time between the two events, shown correctly to scale on the $ct$-axis
- This occurs at a specifical space-time interval, where $\Delta s^2 = c^2 \Delta t'^2$ 
### Length contraction is space-time diagrams
![[Pasted image 20240613172048.png|350]]

- In order to measure a length correctly we must measure the position of each end of the length at the same time. 
- The two space-time events used to determine the two ends of the length in a given reference frame must occur simultaneously in that reference frame. 
- Since each is stationary in Earth's reference frame, the separation between them is a proper length and is labelled $L_0$ on the diagram.
- In the muon's reference frame, $S'$, the distance between the Earth's atmosphere and the Earth's atmosphere can be using simultaneous event $0$ and $0'$. where the world line of the frame both events occur when $t' = 0$
- $L'$ could be measer off the scale on the $x'-axis$ but we would need to calculate the scale to do this 
- Instead, we can sketch the curve that links alll the point with space-time interval $\Delta s^2 = -L'^2$. 
- It can clearly be seen that the propre length is much larger than the contracted length, $L'$ confirming the length contraction occurs 
- Careful measurement would also show that:
$$ L' = \dfrac {L'}\gamma$$
