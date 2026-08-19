DAY 2



19/8/2026



## How do you start a rocket engine?



### Purging and Thermal Conditioning: 

* the engine must be prepared for the extremely low temperatures its about to experience from the propellants. the cold temperatures can cause the pumps and valves to become brittle and prone to failure.
* the purging process involved blasting gaseous N2 or He (for hydrolox engines) to eliminate the air pockets and moisture. If any water is present in the line when the cryo propellants are introduced, it will freeze, potentially clog up the orifices and lead to engine damage. These failures are also very hard to investigate as the evidence melts away due to heat from combustion.



### Engine Chill down:

* The propellant will begin to flow through the system at a controlled flow rate where it starts to thermally condition the engine to get it to the cryogenic temperatures. 
* the propellants that have now gone through the engine may have to be vented into the atmosphere. LOX poses no risk when this is done, but the fuel is either cooled down again into a liquid or burned in a flare stack to avoid sudden detonation
* Not only is the engine chilled to protect itself from the cold propellant, its also done to protect the propellant from the relatively warm engine.
* if the propellant boils off before it reaches the impellers in the pumps, it can cause cavitation and damage the blades and can also cause them to overspeed which leads them to deliver the incorrect amount of propellant into the combustion chamber. this can cause the engine to burn at stochiometric conditions, which releases the maximum amount of heat and can cause damage.



Exceptions to Hypergolic prop:

Hypergolic propellants combust upon immediate contact and can be stored at room temperature, thus eliminating the need for an engine cooldown.



### Spin Up:

* After the engine has been pre-conditioned for starting, the next step is to get the pumps spinning. the most important thing to remember is that pressure flows through a gradient: always from high to low pressure. In order to ensure that a flame is not sent backwards, the upstream pressures must be high, and this is dependant upon the pumps.
* the turbine is spun from the exhaust of a gas generator/pre burner, which is in turn fed by the pumps. this creates a hard dynamic that the turbine must be spinning to get propellants into the pre burner, but the pre burner must produce exhaust to get the turbines running too.
* the simplest way of bypassing this is to use an electric motor to drive the turbine (Rocket lab Rutherford Engine). but this is not feasible for larger engines where a lot more energy is required to get everything spinning.
* hence the turbine is started by using a high pressure gas pumped into the gas gen/PB. for a short period of time, the pumps are basically powered by a cold gas thruster. this means that for multiple starts, the rocket must carry enough inert gas to cause spin up. some engines use a little solid or hypergolic propellant that act as gas gens for a small amount of time.



### Bootstrapping:

bootstrapping is a process where the engine carefully lights up using only tank pressure and energy stored in the thermal difference between the propellant and the engine (the vented fuel from thermal conditioning is sent into the pre burner). to do this, the pre burner will produce gas due to the hydrogen flowing and boiling off. this causes the turbine to spin. with some extremely precision, some oxygen is sent into the pre burner. the pressure slowly begins to ruse until the engine reaches operational pressure. 



### Transients: 

* transients are basically the in between moments before it reaches steady state.
* in bootstrapping, the liquid that flash boils from hitting the engines pre burner expands as it becomes a gas. this expansion is what spins the turbine. however, this pressure also exerts a back pressure on the rest of the system, slowing down the flow rate of the propellant. when boil off decreases, flow rate increases and vice versa. its like constant pressure oscillations are created. 
* there are also delays between action and reaction. if the pressure waves are too extreme, the pressure gradient will flow backward, which can stall the startup sequence or even blow up the engine. 
* additionally, any time a valve opens, the pressure is changed, thus affecting the flow. the entire engine start up sequence is full of these feedback loops.



### Ignition Process:





#### Ignition on the ground: 

* once the engine is conditioned for launch, the propellants begin flowing into the engine. the ignition triangle consists of the fuel, oxidiser and the ignition source. 
* any slight error in the ignition process can lead to a hard start, where the propellants combust at the wrong time, wrong place or the wrong ratio. this can over pressure the engine and cause detonation. 
* the simplest form is what the Russians did: they put large wooden braces with pyrotechnics on top of them inside each combustion chamber. the downside is that this cannot be done in space
* a large number of engines also use an electric current that sparks over a gap to ignite the engine, but this requires a large source of power.
* laser methods are another alternative.
* pyrophoric fluids ( TEA - TEB: fluid that is hypergolic with oxygen) are also used, they have a low mass and are reliable. once injected into the engine, ignition begins when oxygen flows into it too.
* the raptor engine has a ffsc so homogenous combustion takes place- spontaneous combustion when hot methane and ox come in contact.



#### Ignition in space:

* the main issue is that the vehicle is an inertial frame of reference and has no normal force acting on it. the propellants are just floating around in the tanks, not necessarily near the inlets.
* to first get the propellants at the bottom of their tanks, ullage thrusters are used. using cold gas thrusters for this is the most common solution as they are easily restartable (simple valve operation) 
* hot firing is also another method used by the Soyuz, proton and some titan rockets. this is when engines on the upper stage are igniting while the stage below is still firing (gravity helps here).





