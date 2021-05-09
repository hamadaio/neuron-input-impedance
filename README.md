# Neuron input impedance (_Z_<sub>in</sub>)

Neuron Simulation Environment script for computing max/min _Z_<sub>in</sub> and generating _Z_<sub>in</sub> map.

``impedance_map.hoc`` - generates _Z_<sub>in</sub> map
``max_Zin.hoc`` - computes the max & min _Z_<sub>in</sub> values by looping through the entire electrotonic neuronal structure.
``max_Zin_distance.hoc``- computes max & min _Z_<sub>in</sub> values within a radial maximum distance from the soma (``MAX_DIST``, line 24).

---

#### Example of rodent & human _Z_<sub>in</sub> map figure generated at 0 Hz (Hamada _et al._ 2021).

<img src="https://user-images.githubusercontent.com/42112716/117575320-92aeee00-b0e1-11eb-91b1-19e1c143e5dd.png" alt="input-impedance" width="500"/>
