# sp500perturbator
Master thesis project for the M.Sc. in Physics of Complex Systems @ Politecnico di Torino

This repo contains the code for my (Gerardo Castagno) master thesis in Physics of Complex Systems @ Politecnico di Torino, under the supervision of Andrea Barral and Alessandro Sabatino (Intesa Sanpaolo).

The master thesis focuses on developing an AI model designed to generate profitable investment strategies that outperform market benchmarks. Specifically, the model constructs a portfolio of 500 US equities, determining optimal positions and allocations for each stock. The goal is to maximize returns while minimizing risk and transaction costs.

The repo contains 2 notebooks:
- "dataprep" containing the code used to create the LSTM matrices used to train and test the proposed AI model;
- "sp500_perturbation" containing the custom subclassed model, the training procedure, the test data generation procedure (which employs a rolling-forward loop due to the peculiar nature of the model), the code for the evaluation of the performances of the generated strategies, the code for the analysis of the generated test portfolio-weights allocation and the code for the feature subset selection & hyperparameter tuning processes.
