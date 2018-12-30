# solar_energy_systems
Agent Based Modeling of networks of solar energy systems. 
<ol>
<li>The python class SolarES defines the solar energy system. <br />
It includeds methods for energy generation, storage, transfer and generation and storage failures.</li>
<li>The python class network is used to build a Network using python dictionaries.
It includes methods for adding and deleting nodes & edges, finding nodes, calculating node degree, total number of edges.</li> 
<li>Function setup_BA_network will build network using Barabási–Albert (BA) algorithm.</li>
<li>Function setup_Random_network will build network using Erdős–Rényi (ER) algorithm.</li>
<li>Function connectionfailure will delete particular percentage of the edges from a given network.</li>
<li>Function updatesolarES will uodate all the SolarES agents using methods from class SolarES.</li>
</ol>
