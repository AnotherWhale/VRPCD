# VRPCD

A program to solve multi-period vehicle routing problems with cross-docking using Gurobi. Supports heterogenous vehicles.

## How it works

- Accepts datasets in csv format, which contains data of supply, demand, travel cost, travel time, and vehicles.
- The data is processed using Gurobi solver to minimize total transportation cost

## How to run

1. Install Gurobi
2. Make sure datasets are in the appropriate folder
3. Open `VRPCD.ipynb`
4. Choose which datasets to run by changing appropriate variables
5. The solution output will be shown in the console
