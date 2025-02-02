# Monte-Carlo-Simulation-of-Uranium-235
The aim of this project was to estimate the critical mass of uranium 235. In a chain reaction, a uranium atom is hit by a stray neutron resulting in fission. This releases energy producing several more neutrons which could initiate further fissions. 
In smaller amounts of uranium, most neutrons escape, but at a certain critical mass, a self-sustaining reaction can occur.


The following codes aim to model this in 1d and 3d using Monte Carlo simulations:

**neutrons.py** Gives an experimentally similiar distribution of the number of secondary neutrons produced.

**1d model.py** In this model, the uranium extends upon a line of length L, where fission can occur anywhere along the line. Starts the simulation with 100 initial neutrons, the code outputs the number of neutrons that cause secondary fissions.

**3d model.py** Extends the 1d model to 3d using spherical coordinates.

**critical plots.py** Provides plots to visualise the critical value of counts as L varies in the 1d and 3d model.

