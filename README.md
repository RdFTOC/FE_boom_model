# FE_boom_model
Finite element boom model to simulate system behaviour with environmental input

# What the project does
Simulate the boom behaviour and trajectory in environmental conditions obtained from three models: HYCOM, WWIII, CFSR.

Input consists of:
	-Starttime, Endtime, timestep
	
	-Mechanical properties of the boom
	
	-Hydrodynamic properties of the boom

Output consists of:
	-Position and speed of the nodes used in the simulation
	
	-Encoutered environmental conditions along it's trajectory
	
	-Number of escapes during the simulation period

# Why the project is useful
Orcaflex does not have the possibility to use time and location dependent environmental conditions. In addition, the current profile over depth is not something that can be modelled in Orcaflex. 

# How users can get started with the project
They don't :P

# Where users can get help with your project
Call or mail one of the contributers 

# Who maintains and contributes to the project
Overall TOC, especially:
	-Bruno Saint-Rose for the environmental models and input
	-Reijnder de Feijter for the structural and hydrodynamic response of the system and the overall implementation
