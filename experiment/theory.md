## Inroduction 

Chemical kinetics and reactor design are at the heart of producing almost all industrial chemicals.The selection of a reaction system that operates in the safest and most efficient manner can be the key to the success or failure of a chemical plant. The reaction occurred in a reactor is exothermic or endothermic.The reactor is generally assembled with a jacket or coil in order to maintain the reaction temperature in the reactor. If heat is evolved due to exothermic reaction, a coolant stream is required to pass through the jacket or coil to remove the extra heat. On the other hand, if endothermic reaction occurs in the system, the flow of heating medium is passing through jacket or coil for maintain the reaction temperature. A reactor operates at a constants temperature, then that is called as the isothermal reactor. If any exothermic or endothermic reactions are involved in the reactor, the temperature of the reactions mixture varies with time and we need to develop the energy balance equation for this non-isothermal reactor. In case of adiabatic reactor no interchange of heat between the system and surroundings. So no heating and cooling medium are required. A chemical reactor is a vessel where reactions are carried out purposefully to produce products from reactants by means of one or more chemical reactions. A chemical reactor may be characterized by the mode operation according to the flow condition. A classification can be made in this respect as follows:
1. Batch reactor
2. Semi batch reactor
3. Flow reactors
     a. Tubular reactor
     b. Continuous stirred tank reactor
           

## Activation Energy

Activation energy is defined as the minimum energy required starting a chemical reaction. The activation energy of a reaction is denoted by E, and unit is kilojoules per mole. Activation energy can be thought of as the height of the potential barrier (sometimes called the energy barrier) separating two minima of potential energy (of the reactants and products of a reaction). For a chemical reaction to proceed at a reasonable rate, there should exit an appreciable number of molecules with energy equal to or greater than the activation energy.

 ### Reaction Rate Constant             
For many reaction, and particularly elementary reaction, the rate expression can be written as a product of a temperature-dependent term and composition dependent term.<br><b>`ri=fi(temperature).f2(composition)`</b><br>For such reactions the temperature-dependent term, the reaction rate constant, has been found in practically all cases to be well represented by Arrhenius's law<br> $$k=\alpha exp(-\frac{E}{RT})$$<br>At the same concentration, but at two different temperatures, Arrhenius's law indicates that<br>$$ln (\frac{k_2}{k_1})=\frac{E}{R}(\frac{1}{T_1}-\frac{1}{T_2})$$<br>Where, Frequency factor or pre-exponential factor
                                <br>E = Activation energy
                                <br>R = Universal gas constant.</p><br>

                           
 ### Heat Of Reaction    
Heat of reaction is the amount of heat that must be added or removed during a chemical reaction in order to keep all of the substances present at the same temperature. If the pressure in the vessel containing the reacting system is kept at constant value, the measured heat of reaction also represents the change in the thermodynamic quantity called enthalpy, or heat content, accompanying the process- i.e., the difference between the enthalpy of the substances present at the start of the reaction. Thus, the heat of reaction determined at constant pressure is also designated the enthalpy of reaction, represented by the symbol ΔH
 . If the heat of reaction is positive, the reaction is said to be endothermic and if negative, exothermic.
 
 ### Continuous Stirred Tank Reactor Theory
 The continuous stirred tank reactor or back mix reactor is a very common processing unit in chemical and polymer industry. Its names suggest, it is a reactor in which the contents are well stirred and uniform throughout. The CSTR is normally run at steady state, and is usually operated so as a to be quite well mixed. The CSTR is generally modeled as having no spatial variations in concentrations, temperature, or reaction rate throughout the vessel. Since the temperature and concentration are identical everywhere within the reaction vessel, they are the same at the exits point as they are elsewhere in the tank.
 
### Steady State
A situation in which all the state variables remain constant despite parallel processes trying to change them, is referred to as the steady state.
### Time Constant
When we talk about time constant, it's essential to take into account the context in which we are talking about it. In our case, time constant can be defined as 63% of the time that will be taken for a body to reach steady state.

#### Setup

The following second-order, exothermic chemical reaction takes place in the reactor:

<img src="images/5.JPG"  style="width:500px;height:400px;"/> <br>
Reactant A and B is continuously fed to the reactor with a volumetric flow rate FA0 and FB0, a molar concentration CA , and CB temperature T0. The contents are uniformly mixed by motorized agitator. An exit stream, which contains a mixture of reactant A and B and product C and D, is withdrawn from the reactor continuously with a volumetric flow rate F. The prescribed reaction is exothermic and it is necessary to add a cooling jacket to keep it temperature below 315K. A coolant stream volumetric flow rate Fj and inlet temperature Tj0 continuously takes out the heat to maintain the described reaction temperature.
### Mathematical modeling of continuous stirred tank reactor
#### Assumptions

- The mixture density (p) and heat capacity (Cp) are assumed constant.
- The reacting mixture is assumed to be well mixed.
- The heat losses from the process to the atmosphere are negligible.
- The overall heat transfer coefficient is assumed constant.
#### Inputs to the system are
- Initial concentration of component A =CA0
- Initial concentration of component B =CB0
- Flow rate of A =FA0
- Flow rate of B =FB0
- Jacket flow rate =Fj
- Feed temperature =T0
- Jacket temperature =Tj0

### Component continuity equation
The component balance equation is <br>

$$			
\begin{bmatrix}
Rate\ of\ accumulation\\\\
within\ the\ system
\end{bmatrix} =
\begin{bmatrix}
Rate\ of\ flow\\\\
into\ the\ system
\end{bmatrix} -
\begin{bmatrix}
Rate\ of\ flow\\\\
out \ of \ the \ system
\end{bmatrix} +
\begin{bmatrix}
Rate \ of \ generation\ by\ chemical\\\\
reaction\ within\ the\ system
\end{bmatrix} 
$$

### For component A (Reactant)
Flow rate of component A into the reactor = FA0<br>Flow rate of component Aout of the reactor = FCA<br>
Rate of generation of component A by chemical reaction = -(-rA)V<br>

$$ Rate\ of\ accumulation\ of\ component\ A\ within\ the\ reactor\ =\ d \frac{(VC_A))}{dt}$$<br>

Here, (-rA) is the rate of disappearance of species A. V is the volume of the reactor. From equation (1), we obtain<br>

$$d \frac {(VC_A)}{dt}=F_{A0}C_{A0}-FC_A-(-r_A)V$$ <br>

$$\frac{dC_A}{dt}=\frac{(F_{A0}C_{A0}-FC_A)}{V}-(-r_A)$$ <br>

For the given second order reaction, the rate of disappearance is<br>
$$(-r_A)=k(C_A C_B-\frac{C_C C_D}{K_C})$$<br>
$$k=39178exp[5472.7(\frac{1}{273}-\frac{1}{T})]$$ <br>
$$K_c=exp(\frac{1698}{T})$$<br>
Substituting Equation (7) and (8) into equation (6), then we get<br>
$$(-r_A)=3918exp[5472.7(\frac{1}{273}-\frac{1}{T})]-(C_A C_B-\frac{C_C C_D}{exp( \frac{1698}{T})})$$ <br>
Substituting Equation (9) into equation (5), then we get<br>
$$\frac{dC_A}{dt}=\frac{(F_{A0}C_{A0}-FC_A)}{V}-3918exp[5472.7(\frac{1}{273}-\frac{1}{T})]-(C_A C_B-\frac{(C_C C_D)}{exp(\frac{1698}{T})})$$</p>
### For component B (Reactant)
Flow rate of component B into the reactor =FB0CB0 <br>
Flow rate of component B out of the reactor =FCB <br>
Rate of generation of component B by chemical reaction = (-rB)V <br>

$$ Rate\ of\ accumulation\ of\ component\ A\ within\ the\ reactor\ =\ d \frac{(VC_B))}{dt}$$<br>

Here,(-rB) is the rate of disappearance of species B and (-rA)=(-rB)<br>
From equation (1), we obtain<br>
$$\frac{d(VC_B)}{dt}=F_{B0}C_{B0}-FC_B-(-r_A)V $$ <br>

$$\frac{dC_B}{dt}=(F_{B0}C_{B0}-FC_B)V-(-r_A)$$ <br>

Substituting Equation (7) into equation (12), then we get<br>

$$\frac{dC_B}{dt}=\frac{(F_{B0}C_{B0}-FC_B)}{V}-3918exp[5472.7(\frac{1}{273}-\frac{1}{T})]-(C_A C_B-\frac{C_C C_D}{exp(\frac{1698}{T})})$$
                            
### For component C (Product)
Flow rate of component C into the reactor = 0<br>
Flow rate of component C out of the reactor = FCC<br>
Rate of generation of component C by chemical reaction = (rc)V<br>

$$ Rate\ of \ accumulation\ of \ component \ C \ within \ the \ reactor =\frac{d(VC_C)}{dt} $$

Here,<br>
-(-rA)=(rc)<br>
From equation (1), we obtain<br>
$$\frac{d(VC_C)}{dt}=-FC_C+(-r_A)V$$ <br>

$$\frac{dC_C}{dt}=\frac{(-FC_C)}{V}+(-r_A)$$ <br>
Substituting Equation (7) into equation (13), then we get <br/>

$$\frac{dC_C}{dt}=\frac{(-FC_C)}{V}+39178exp[5472.7(\frac{1}{273}-\frac{1}{T})]-(C_A C_B-\frac{C_C C_D)}{exp(\frac{1698}{T})})$$

### Energy Balance Equation
The energy balance equation is

$$			
\begin{bmatrix}
Rate \ of\ energy\\\\
accumulation
\end{bmatrix} =
\begin{bmatrix}
Rate\ of\ energy\ input\\\\
into\ the\ system
\end{bmatrix} -
\begin{bmatrix}
Rate\ of\ energy\\\\
out \ of \ the \ system
\end{bmatrix} +
\begin{bmatrix}
Rate\ of\ energy\ added by\\\\
exothermic\ chemical\ reaction
\end{bmatrix} 
$$
                            </p>
### Reactor analysis
$$Rate\ of\ energy \ input\ into\ the\ reactor = F_\rho C_pT_0$$ <br>

$$Rate\ of\ energy\ out\ of\ the\ reactor =F_\rho C_pT+UA(T-T_j)$$ <br>

$$Rate\ of\ energy\ added\ by\ the\ exothermic\ reaction = (-\Delta H)V(-r_A)$$ <br>

$$Rate\ of\ accumulation\ of\ energy = \frac{d(V_\rho C_PT))}{dt} $$ <br>

 $$(-\Delta H) \ is \ the\ heat\ of\ reaction.$$<br>

From equation (20), we obtain<br>

$$\frac{d(V_\rho C_PT)}{dt}=F_\rho C_pT_0-UA(T-T_j)+(-\Delta H)V(-r_A)$$ <br>
Simplifying this equation, we get<br>
$$\frac{dT}{dt}=\frac{F}{V}(T_0-T)-\frac{\Delta H(-r_A)}{\rho C_P}-\frac{UA(T-T_j)}{V_\rho C_P}$$ <br>
Substituting Equation (7) into equation (22), then we get<br>

$$\frac{dT}{dt}=\frac{F}{V}(T_0-T)-\frac{(\Delta H)39178exp[5472.7(\frac{1}{273}-\frac{1}{T})]-(C_A C_B-\frac{C_C C_D}{exp(\frac{1698}{T})})}{\rho C_P}-\frac{UA(T-T_j)}{V_\rho C_P}$$ </p>
                            
### Jacket Analysis
$$Rate\ of\ energy\ input\ into\ the\ jacket\ =\ F_j \rho_jC_pjT_j0 $$<br>

$$Rate\ of\ energy\ out\ of\ the\ reactor\ =\ F_j \rho_jC_pjT_j-UA(T-T_j) $$<br>

$$Rate\ of\ accumulation\ of\ energy\ =\ \frac{d(V_j \rho_jC_pjT_j)}{dt}$$<br>

Vj is the volume of the jacket.
<br>From energy balance equation, we get<br>

 $$\frac{d(V_j \rho_jC_pjT_j)}{dt}=F_jrho_jC_pjT_j0-F_j \rho_jC_pjT_j+UA(T-T_j) $$<br>
 
 $$\frac{dT_j}{dt}=\frac{F_j}{V_j} (T_j0-T_j)+\frac{UA(T-T_j)}{V_j \rho_jC_pj}$$
                           
### Input Parameter
8. Initial concentration of component A = CA0
9. Initial concentration of component B = CB0
10. Flow rate of A = FA0
11. Flow rate of B = FB0
12. Jacket flow rate = Fj
13. Feed temperature =T0
14. Jacket temperature = Tj0
