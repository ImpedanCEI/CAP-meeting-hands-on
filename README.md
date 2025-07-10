# CAP-meeting-hands-on
Wakis introduction and hands-on examples prepared for the CAP section meeting: 
* https://indico.cern.ch/event/1558279/

## `001_dielectric_barriers_and_PML.ipynb`


## `002_Wakefield_simulation.ipynb`

**hands-on example to follow the full impedance assessment workflow** using our in-house python packages: 
* [`Wakis`](https://github.com/ImpedanCEI/wakis) for the 3D electromagnetic wakefield simulations,
* [`IDDEFIX`](https://github.com/ImpedanCEI/IDDEFIX) for partially decayed wake extrapolation,
* [`BIHC`](https://github.com/ImpedanCEI/BIHC) for impedance-induced beam power loss, and
* [`neffint`](https://github.com/ImpedanCEI/neffint) for impedance to wake function conversion for beam dynamics simulations.

## Getting started
You can install wakis from GitHub to have the latest changes into your conda environment:
```bash
pip install wakis['notebook']
```
or 
```
pip install git+https://github.com/ImpedanCEI/wakis.git@main
```
