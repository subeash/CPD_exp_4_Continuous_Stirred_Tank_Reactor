## Procedure

Please follow these steps to do the experiment.

#### 2. Introduction

Mixing Vessels play an essential role in chemical processes. Its utilities are varied and range from mixing chemicals to changing temperatures of fluids. In the study of stirred tank heaters, we will use it primarily as an instrument for varying the temperature of fluid present in the tank. We generally use a heating coil or jacket filled with a hot fluid surrounding the tank. Here, we will be using the coil to heat the tank. For simplicity, we will have the same phase for both the tank fluid and the coil fluid. We also assume that no change of phase takes place in either of the fluids i.e. the ones in the tank and in the surrounding coil. For studying our setup in detail, it's important to get acquainted with the following terms.

#### 2.1 Material and Energy Balance

Chemical Processes usually require flow of substances. As the materials pass through various processing operations, it becomes extremely important to accurately understand and subsequently describe their flow. This is done with the help of material and energy balance which are essentially based on the principles of mass and energy conservation. If the unit operation, whatever its nature is seen as a whole it may be represented diagrammatically as a box. The mass and energy going into the box must balance with the mass and energy coming out.
### 2.2 Material Balance
The law of conservation of mass leads to what is called a mass or a material balance.
Mass In = Mass Out + Mass Stored Raw Materials = Products + Wastes + Stored Materials.

### 2.3 Energy Balance
Energy, just like mass, is conserved in the processing operations. The energy coming into a unit operation can be balanced with the energy coming out and the energy stored.
Energy In = Energy Out + Energy Stored
### 2.4 Steady State
A situation in which all the state variables remain constant despite parallel processes trying to change them, is referred to as the steady state.
### 2.5 Time Constant
When we talk about time constant, it's essential to take into account the context in which we are talking about it. In our case, time constant can be defined as 63% of the time that will be taken for a body to reach steady state.
### 2.6 Setup
Let's have a look at the setup we are going to use in our experiment.
### 2.7 Assumptions
-The density of the coil as well as the tank's fluid material remains constant.
-The specific heat capacity of the coil as well as the tank's fluid material remains constant.
-The stirring is such that as soon as a drop of material enters the tank or the coil it has the same temperature as that of the rest of the bulk material.
-The fluid is incompressible.
-No accumulation occurs inside the tank or the coil, i.e., mass inflow is equal to the mass outflow.
-No radiation takes place
-There is only one state of a particular fluid present in the tank as well as the coil throughout the experiment, i.e., the state of the fluid dose not change during the experiment.
### 2.8 Tank Analysis
Now, let's apply the concepts we learnt just now. We will consider the tank first. The fluid is entering it with a temperature and flow rate and leaving it with a temperature and flow rate . We assume that temperature inside the tank is uniform and is equal to the outlet temperature. We will assume this for the coil as well. Now, applying mass conservation
#### Mass stored = Mass in - Mass out
$$ \frac{d(S d_t) }{dt}=V_i d_t - V_o d_t $$

where S denotes the volume of the tank. Assuming that the tank volume stays the same and the density of the fluid is a constant, then
$$\frac{dS}{dt}=0 $$

$$ V_i = V_o $$

Now, we will apply energy conservation
### Energy In = Energy Stored + Energy Out
In the case of the stirred tank heater
### Energy in = Energy through inflow + Energy through heat transfer = 

$$V_i d c_p(T_i - T<sub>gr</sub>) + H$$

where,
T<sub>gr - Reference Temperature
 
H - Rate of Heat Transfer into the tank
 
C<sub>p - Specific Heat Capacity
 
 
### Energy stored = 
 
$$\frac{d(S d_t c_p(T_i - T<sub>gr</sub>)}{dt}$$
 
### Energy Out = 

 $$V_o d_t c_p(T_o - T<sub>gr</sub>)$$
 
 Hence,
 
$$V_i d c_p(T_i - T_gr) + H = d((S d_t c_p(T_i - T<sub>gr</sub>))$$

 $$\frac{(S d_t c_p d(T_o - T<sub>gr</sub>))}{dt} = V_o d_t C_p[(T_i - T<sub>gr</sub>)+(T_i - T<sub>gr</sub>)] + H as (V_i - V_o)$$
 
$$\frac{(S d T_o)}{d_t} = V_o(T_i - T_o) + \frac{H}{(d_t c_p)}$$

 ### 2.9 Coil Analysis
 
 The fluid is entering the coil with a temperature T<sub>i-coil</sub> and the flow rate V<sub>i-coil</sub> and leaving it with the temperature T<sub>i-coil</sub> and flow rate V<sub>i-coil</sub>. d<sub>coil<sub> is the density of fluid in the coil. We will now consider the coil and will repeat the same things which we did for the tank.
 
 Applying mass conservation,
 ### Mass Stored = Mass In - Mass Out
 
 $$\frac{d(S_(coil) d_j)}{dt} = V<sub>i−coil</sub>d<sub>coil</sub>−V<sub>o−coil</sub>d<sub>coil</sub>$$
 
 where S denotes the volume of the coil. Assuming that the coil volume stays the same and the density of the fluid is a constant, then
 
$$\frac{dS<sub>coil</sub>}{dt} =0$$
 
$$V<sub>i-coil</sub> = V<sub>o-coil</sub>$$
 
 As in the case of the tank
 ### Energy In= Energy Store + Energy Out
  $$ V<sub>i-coil</sub> d<sub>coil</sub> c<sub>p-coil</sub>(T<sub>i-coil</sub>-T<sub>gr</sub>) - H = \frac{d(S<sub>coil</sub> d<sub>coil</sub> c<sub>p-coil</sub>(T<sub>i-coil</sub>-T_(gr))}{dt} + V<sub>o-coil</sub>d<sub>coil</sub> c<sub>p-coil</sub>(T<sub>o-coil</sub>-T<sub>gr</sub>) $$
 
 $$ S<sub>coil</sub> d<sub>coil</sub> c<sub>p-coil</sub> \frac {d (T<sub>o-coil</sub>-T<sub>gr</sub>)}{dt} = V<sub>o-coil</sub>d_(coil) c<sub>p-coil</sub>[(T<sub>i-coil</sub>-T<sub>gr</sub>) + (T<sub>o-coil</sub> - T<sub>gr</sub>)] + H as$$
 $$V<sub>i-coil</sub> = V<sub>o-coil</sub> $$
 
  $$ S<sub>coil</sub> \frac{d(T<sub>o-coil</sub>)}{dt} = V<sub>o-coil</sub>(T<sub>i-coil</sub> - T<sub>o-coil</sub>) + \frac{H}{d<sub>coil</sub> c<sub>p-coil</sub>} $$
 
 We can Replace the H in the equation with
 
 $$UA(T<sub>o-coil</sub> - T<sub>o</sub>)$$ 
 
 where U and A are the heat transfer coefficient and the area exposed to heat transfer .
 Finally we have to solve these two ordinary differential equation to get the steady state temperatures of the tank as well as the coil.
 
