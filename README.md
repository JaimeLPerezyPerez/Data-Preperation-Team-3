# Team 3: ML Pipelines And Erroneous Data - Autofix

This repository contains code that was used for the course Datapreparation by Team 3 (2023/2024) at the University of Amsterdam.

**authors**: Tünde de Vries, Sebastian Skalski, Rasanga Abeykoon, Jaime Perez y Perez, Danila Romanov

## Instructions for repository

[This file](Final_Used_Code.ipynb) contains all code that was used in the production of the results as reported in our project paper. In order to reproduce the results one must first: 
* Run all cells up to the collecting results section, with the exception of the cell with autofix test, "training models" cell and the cell that dumps trained models to a file under utility.
* Run the training models cell (This will train the models using specific random_states)
* Run any of the cells in "collecting results" to obtain the various test results or run new tests. For specific instructions see the markdown in the code above the "testing" cell.
* The testing cells will save the experiment results to user specified files. The plots as seen in our report can be produced by running the code under plotting results with the generated files.
