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

# First law of Thermodynamics
- Thermal energy supplied to a gas:
$$Q = \Delta U + W$$
-  Here $\Delta U$ is the change in internal energy U of the system
- $W$ - work done
- Q is the net heat transferred into the system - that is, Q is the sum of all heat transfer into and out of the system
- We can use the principle of conservatin of energy, the gas may gain internal energy, U, and / or the gas will expand and do work on the sorroundings, W
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
- 
