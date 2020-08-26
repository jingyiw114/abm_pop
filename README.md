# abm_pop
Mata class for storing and retrieving properties of agent that can change over time in an agent based model. **abm_pop** will assume that state will persist until it is changed. So one only has to store something when it changes, and one does not need to copy the entire population at each iteration.

## Requirements and use

This requires [Stata](https://www.stata.com). The class itself is defined in the abm_pop.mata file. The class can be imported and used in an Agent Based Model by adding the line `do abm_pop.mata` to the .do file that defines the ABM. 