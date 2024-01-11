# nonlincharge_publication.ipynb

This Jupyter notebook contains the code for conducting experiments and simulations on the nonlinear charging of lithium-ion batteries. It uses the PyBaMM library for battery modeling and simulation.

## Contents

The code performs a series of simulations by varying various parameters, including the step voltage (`V0`) in the nonlinear potentiodynamic charging case. An experiment is created and simulated for each combination of these parameters.

The simulations use the Doyle-Fuller-Newman (DFN) model for lithium-ion batteries with various model parameters, including SEI film resistance, SEI porosity change, and irreversible lithium plating.

The results of the simulations, including time, voltage, current, lithium loss and SEI loss, are stored in a list of dictionaries.

## Dependencies

- numpy
- tqdm
- scipy
- pybamm
- scienceplots

## Usage

To use this notebook, open it in Jupyter and run the cells. Make sure you have installed all necessary dependencies.

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for details.
