# Molecular Design of Optimal Refrigerants
This repository contains an Excel Solver implementation for molecular design of optimal refrigerants via group contribution method as described in this following [paper](https://drive.google.com/file/d/1Q4UKufVrsbK1k-a7gVdfT93tKaRZMwGs/view?usp=drive_link).

## Installation
Please follow the steps in order if you want to make changes to the code.
### 1. Download Code
To download, press the green "Code" button, download, and extract the zip.
### 2. Install Solver Add-in
Next, go to the excel file where we will need to install the Solver Add-in. Go to File > Options > Add-Ins, then select "Excel Add-ins" in the Manage box, click "Go", and check the box next to "Solver Add-in" before clicking "OK".
### 3. Run Code
To run the code, go to the sheet titled "Model Constraints". Click on cell M16 and then go to Data > Solver. When the dialog box appears press Solve.

### Extra Features
Sensitivity analysis is performed for 3 different intial starting conditions in sheets titled "Answer Report 1", "Answer Report 2", "Answer Report 3".
All tabulated [Joback and Reid](https://doi.org/10.1080/00986448708960487) group contribution data is in the sheet titled "Model Data".

## Future
I would like to experiment more with global optimizers from OpenSolver like COUENNE and try out more accurate group contribution methods that account for 2nd order interactions (e.g. [Nannolal](http://chemthermo.ddbst.com/Parameters/2004-04_Nannoolal_Masters_Thesis.pdf)). Some questions to explore:
1. Are there noticeable periodic trends in relation to refrigerant properties?
2. What is the impact of molecule size on refrigerant properties?
3. How can we use this data to discover new, efficient, and safe refrigerants?

## Reference
Mathematical program formulation was adapted from the following [paper](https://doi.org/10.1002/aic.690490714).
