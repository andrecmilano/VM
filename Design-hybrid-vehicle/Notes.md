#Reading the slides: Hybrid vehicle#

**Reasons hybrid vehicle are used:**
ICE’s have limited efficiency.
In an hybrid vehicle is increased the eficciency using alternative propulsion systems.

The power is used for 2 main loads: road load (torque of the wheels) and acessory.
most of the power is used for road porpuse.

**Road load**
Is composed by three forces
- A: aerodynamic, depends by:
    - C aerodynamic drag coefficient (around 0.4)
    - A vehicle front area (around 1.5m^2)
    - P air density
    - V effective air/vehicle relative velocity
- G: grade resistant
- R: rolling depends on:
    - tire pressure
    - tire temperature
    - type of surface

Another important force is the **inertia force**, it is the largest 
term in the acelleration and it governs the peak rating of engine as well as the vehicle
acceleration dynamics.

In the slides at this point are shown few graph, which show the different important of
these forces in different conditions.

**Fuel consuption**
The power required at the wheel is supplied by the ICE, through the transmission
here the efficiency is very important.
the istantaneus fuel consuption is m' = (Power) / (efficiency * fuel-heating-value)
The total fuel consuption is composed by:
- the integral when the power is higher than zero
- the integral when the power is lower than zero --> Idling losses

first weak point **Idling losses** 

The fuel consuption is strongly dependent on the operating point.
Here is shown a nice graph with the motor consuption speed(RPM)/torque graph.


WHY HYBRID?
Most common vehicle operate a low speed and low torque, to have plenty 
of power for accelerations. **Engines are tipically oversized compared to the required avarage**
**Engine size**
is determined in term of maximum requirements
--> low efficiencies on avarage

Hybrid vehicle could alleviate all this problem
Hybrid means combine more energy sources,
- get closer to the best efficient point
- downsize the engine but still meet the maximum power
- use regeneration
- mitigate idling 
- additional degree of freedom in controlling instantaneus torque
- enhance driveability and safety

###Classification###
**Energy sources**
electric or mechanical
**Level of hybridization**
micro/ (start-stop system) use battery storage to allow cars not to burn fuel 
while idling. Electric power do not provide propulsion to the wheels. 
Cost effective technology. +10% km/liter
mild/ the alternative energy source drives the wheel but never as the only power source
full/ alternative energy sole power source. More complex. +25% km/liter
**Type of Hybridization**
series, The primary energy source is used to provide energy to the electic source.
The ICE doesn't drive the wheels.
parallel, both the energy source provide energy to the wheels. 
This is the prefered strategy because low mass, more robust and packaging advantages.
series/parallel, it is parallel with an additional generator

NOTE: series/parallel not very clear

###Internal combustion energy overview###
ICE are Heat machines, converting fuel into mechanical work as a result of combustion process.
ICE operates on a finite volume of working fluid which changes from a fresh mixture of fuel and air to burnt gases after combustion. The combustion process is therefore sonsidered **internal**.

ICE caracteristics:
efficiency
power
torque
fuel consuption
emissions

most common 4-stroke several variants: Otto, Diesel, Atkinson, Miller
2-strokes are high power: compression and power

Atkinson
is a modified Otto where the intake valve is held open longer -> reverse flow of air during compression
This yields different expansion and compression ratio and at the end of the expansion, cylinder pressure is the same as atmospheric pressure.
+ fuel efficiency, - power density
Miller:
compensate the power density drawback with a supercharger

BSFC brake specific fuel consuption
is an important parameter to compare different engine types
It is a normalized value of engine fuel efficiency.
 = (istantaneus fuel consuption)/ (brake power)
OK! but how can you evaluate two different engine based on this value? it should be as low as possible?

Throttle and BSFC
when not at full throttle the engine has extra work to do during the intake --> pumping losses.
At light loads power is reduced more than fuel consuption.

In order to evaluate an engine is used the dynamometer. It collects data, such as speed torque powe and emissions. The results are presented in graphs.


ICE conclusions:
there is only one point where the engine efficiency is maximum and it is not in the avarage operating mode.
Optimally would like to keep it as close as possible to the optimal point. when less power is needed for traction it can recharge secondary power source, when more is required secondary dource can provide it.

##Trasmission##
Transmission engine and differential are reffered as **drivetrain**.
In case we directly connect the engine to the wheel it would not be possible torque @ 0 speed.
A REDUCTION GEAR IS NEEDED.
The transmission is like a constant value n which is divided for the angular speed of the engine to get the angular speed of the wheels.

Three type of transmission:
- MANUAL -- look the slide61 for the pictures
    Today 5 gears
    are becoming automated, eficciency of manual with advantages of automation
    Hybrid veik are optimized if veik control the shift point
- AUTOMATIC
    automatically change the gear ratio
    complex system, 5 components:
    - torque converter, connect the engine to the trasmission, it provides a variable amount of torque multiplication at low engine speed. It is not very energy eficcient.
    - planetary gear set, creates all the different gear ratios of the trasmission. It is composed by three elements: 
            - sun gear
            - planet gear
            - ring gear
    if the carrier is free to move with velociti wc
    - clutches and bands
    - valve body
    - hydraulic system
- VARIABLE RATIO









