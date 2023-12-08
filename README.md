# TSCNet - Case2

# Optimization of PST Taps

## Description
This Python script is designed to optimize the tap settings of Phase Shifting Transformers (PSTs) to maximize the minimum margin of critical elements in a power system. The optimization process ensures that the adjusted power flow for each critical element does not exceed a maximum permissible value, and maintains equality between certain PST taps.

## Installation
To run this script, ensure that you have Python installed on your system. You will also need the following Python packages:
- numpy
- scipy

These can be installed via pip:

## Usage
To run the optimization, execute the script. The script defines critical elements data, PST and PSDF data, and performs an optimization process using the `scipy.optimize.minimize` function.

The main components of the script include:
- Calculation of margins for critical elements.
- An objective function to maximize the minimum margin.
- Definition of bounds and constraints for the optimization problem.

After the optimization process, the script will output the optimized tap positions along with initial and final margins of the critical elements.


