This repository contains the Mathematica notebook accompanying the paper "Network Effects of Tariffs" by Paolo Pin (April 2025).

About the Paper
The paper develops a model in which country-specific tariffs influence not only trade flows, prices, and welfare, but also reshape the global trade network itself. Trade flows are modeled as forming a Directed Acyclic Graph (DAG), and tariff changes can cause discrete reconfigurations of this network, leading to potentially large and nonlinear effects on market outcomes.

Key features:

General equilibrium model with endogenous trade flows.

Analysis of tariffs' impact on prices, welfare (consumer surplus, firm profits, government revenue).

Illustration of network effects with a numerical example involving the EU, USA, and China.

Formal proof that equilibrium trade networks must be acyclic.

About the Code
The provided Mathematica notebook (example_check_apr6.nb) implements the numerical example from the paper:

Solves for equilibrium prices and quantities under two different tariff regimes.

Shows how the imposition of a tariff can eliminate trade links, divert trade flows, and affect welfare components.

Reproduces the main tables and calculations used in the example.

The code is self-contained and intended for replication and further exploration of the model.

How to Use
Open the notebook file example_check_apr6.nb with Mathematica (version 12 or later recommended).

Evaluate the sections step-by-step to reproduce the results in the paper.

Feel free to modify supply and demand functions or tariff rates to explore alternative scenarios.

Citation
If you use or refer to this code, please cite:

Paolo Pin (2025), Network Effects of Tariffs, Working Paper.
