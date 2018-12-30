# solar_energy_systems
Agent Based Modeling of networks of solar energy systems. 

The python class SolarES defines the solar energy system. 
It includeds methods for energy generation, storage, transfer and generation and storage failures.
The python class network is used to build a Network using python dictionaries.
It includes methods for adding and deleting nodes & edges, finding nodes, calculating node degree, total number of edges. 
Function setup_BA_network will build network using Barabási–Albert (BA) algorithm.
Function setup_Random_network will build network using Erdős–Rényi (ER) algorithm.
Function connectionfailure will delete particular percentage of the edges from a given network.
Function updatesolarES will uodate all the SolarES agents using methods from class SolarES
