# FMCAP
Instance data for the paper "The first mile is the hardest: A deep learning-assisted matheuristic for container assignment in first-mile logistics"

This repository contains the test data for the 20 small and 20 realistic instances from the working paper by Emde and Tudoran (2023): The first mile is the hardest: A deep learning-assisted matheuristic for container assignment in first-mile logistics.

Each instance is in a separate text file, in the format of comma-separated values (CSV). The columns are separated by semicolons. Each file contains two tables.

The first table contains general information about the instance (number N of vendors, container capacities and availabilities, etc.).

The second table contains information about the individual vendors, of which there are either N = 20 (small instances) or N = 1000 (large instances). The first column refers to the vendor ID (running index) and the remaining 14 columns denote the demand in liters for each of the 14 periods in the planning horizon.
