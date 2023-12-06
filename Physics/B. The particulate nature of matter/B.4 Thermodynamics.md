  - **Thermodynamics** - Branch of physics involving transfers of thermal energy to do useful work
# Work done when Gas Expands
- **Isobaric **- Occuring at constant pressure
- Work done = force x distance
- Work done by gas = force x distance moved in direction of force
- Force = Pressure x area 
- Distance in this case is change in volume $\Delta V = A\Delta s$ 
>[!abstract] Isobaric work
>- Work done when a gas changes volume at constant pressure, $W = P\Delta V$

- **State of a gas** - Specified by quoting the pressure, P, T, V, n
# Zeroth law of Thermodynamics
- Related to thermal equilibrium(no net heat flow)
-  **zeroth law of thermodynamics** -If two systems are  in thermal equilibrium, with a *third system* then those two are in thermal equilibrium with each other. 
![[Pasted image 20231205181428.png|300]]
- Trivial but very important since it shows that if the two objects are at the same temperature before contact there will be no heat flow.
# First law of Thermodynamics
- Thermal energy supplied to a gas:
$$Q = \Delta U + W$$
-  Here $\Delta U$ is the change in internal energy U of the system
- $W$ - work done
- Q is the net heat transferred into the system - that is, Q is the sum of all heat transfer into and out of the system
- We can use the principle of conservation of energy, the gas may gain internal energy, U, and / or the gas will expand and do work on the surroundings, W
## Changes in internal energy of an ideal monatomic gas
We've seen in [[B.3 Gas laws#Internal energy of an ideal gas]] that the internal energy of an ideal monatomic gas can be calculated from:
$$U = \dfrac 32 Nk_B T = \dfrac 32 nRT $$
So the change in internal energy, $\Delta U$ of an ideal monatomic gas can be calculated from:

$$\Delta U = \dfrac 32 Nk_B \Delta T = \dfrac 32 nR\Delta T$$
## Four thermodynamic processes
#### Isothermal process $\Delta U = 0$
$$Q = 0 + W$$
- There is no change in the internal energy because temperature is constant
- thus PV = constant
	- [[The laws of gas, pressure#Ideal gas law]]
	- [[B.3 Gas laws#Modelling gas behaviour ideal gases]]]
#### Isovolumetric process $W = 0$
$$Q = \Delta U + 0$$
- constant volume
- if thermal energy is transferred into a gas, it simply gains internal energy and its temperature rises. If thermal energy is transferred away from a gas, its internal energy and temperature decreases
#### adiabatic process $Q = 0$
$$0 = \Delta U + W$$
- No thermal energy is transferred between the gas and its surroundings
- in an adiabatic change of an ideal monatomic gas: 
	- $PV^{\dfrac 53} = constant$
#### Isobaric process $\Delta P = 0$
$$Q = \Delta U + W$$
and $W = P\Delta V$
- Any expansion or compression that occurs at constant pressure. 
# Thermodynamic cycles and PV diagrams
- **Thermodynamic cycles** - Series of thermodynamic processes that return a system to its original state
- The essential process in a heat engine is the transfer of thermal energy to produce expansion and do useful mechanical work 
![[Pasted image 20231130210119.png]]
## Efficiency of heat engines
- Efficiency is something previously discussed[[A.3 Work, Energy, and Power#Efficiency]]
- Efficiency of a heat engine:
$$\eta = \dfrac{\text{useful work}}{\text{input work}}$$
- Heat engines need a flow of thermal energy, which always flows frmo a hotter to colder regien. Some of that energy, but never all of it, is transferred to do useful work
![[Pasted image 20231130211009.png| 250]]
- A temperature difference is need so that there is flow of thermal energy. 
- Thermal energy $Q_h$ flows out of the hot reservoir and $Q_c$ flows into the cold reservoir. 
- The difference in thermal energy is transferred to do useful mechanical work, $W$
$$\eta = \dfrac{Q_h-Q_c}{Q_h}$$
#### Carnot cycle
- **Carnot cycle** - The thermodynamic cycle that produces the maximum theoretical efficiency
![[Pasted image 20231130211320.png]]
1. An isothermal expansion(AB)
2. Adiabatic expansion(BC)
3. Gas then returns to its original state by Isothermal(CD) and adiabatic compressions(DA)
- Efficiency of a heat engine using the carnot cycle
$$\eta_{carnot} = 1 - \dfrac{T_c}{T_h}$$
- Explanation in the entropy section
## Reversible and Irreversible Changes 
- **Irreversible process** - A process which cannot be reversed, and in which entropy always increases. All real macroscopic processes are irreversible 
	- Such as the required flow of some thermal energy into a cold reservoir. 
- **Reversible process** - A process that can be reversed so that the system and all of its surroundings return to their original state and there is no change in entropy. Impossible in macroscopic level
- Without outside interference, in any processes, ordered energy of particles will be irreversibly transferred to disordered energy. 
## Entropy 
**Entropy**, S - A measure of the disorder of a thermodynamic system of particles
## Second law of thermodynamics
- The overall entropy of the universe is always increasing. This implies that energy cannot spontaneously transfer from a place at low temperature to a place at high temperature. 
### Disorder and entropy in macroscopic systems 
- Gas in a large volume is more disordered / has greater entropy than the same gas at the same temperature in a smaller volume 
- Gas at higher temperature is more disorder / has greater entropy than the same gas in the same volume at a lower temperature 
- A liquid is more disordered / has greater entropy than a solid of the same material at the same temperature 
### Representing entropy mathematically
- To express entropy of a system of particles numerically, we need to countthe number of ways that the system can be arranged. 
- **microstates** - the numerous possible combinations of microscopic properties of a thermodynamic system
	- The greater the number of possible microstates of a system, the greater its disorder and the greate its entropy. 
- The symbol $\Omega$ is used to represent the number of possibele microstates of a system / its multiplicity. 
- $\Omega$ is a large number, $ln\Omega$ is more manageable 
>[!abstract] Etropy of a system of microscopic particles
>$$ S = k_B \cdot ln\Omega$$
>SI unit:$JK^{-1}$

>[!note]  Change of entropy of a macroscopic situation
>$\Delta S = \dfrac{\Delta Q}{T}$
>SI Unit: $JK^{-1}$
>$\Delta S$ - Change in entropy
>$\Delta Q$ - Thermal energy supplied or removed. 
>$T$ - Constant temperature

### Entropy in the Carnot Cycle
![[Pasted image 20231203214047.png | 400]]
- The theoretical Carnot cycle is a reversible process , so that there is no overall change of entropy at the end of each cycle. 
- During the isothermal expansion, AB, thermal energy is supplied, but the entropy rises and the volume rises. 
- During the adiabatic expansion, BC, the pressure and temperature decrease, but the entropy remains the same. 
- During the isothermal compression, CD, thermal energy is removed, the temperature remains constant the entropy falls as the volume decreases. 
- During the adiabatic compression, DA, the pressure and the temperature increase, but the entropy remains the same. 
