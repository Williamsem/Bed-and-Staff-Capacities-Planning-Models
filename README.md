# Bed and Staff Capacities Planning Models
This is a repository of the files for the project entitled 'Linking Predictive and Prescriptive Analytics For Modelling Healthcare Services for Frail and Elderly Patients'.

## Installation

To run the contents of this repository simply clone this repository by running the following line in the terminal:

```bash
git clone https://github.com/Williamsem/Bed-and-Staff-Capacities-Planning-Models.git
```
### Python Dependency
This project needs `PuLP` to run. Download the correct version of `PuLP` by running the following line in the terminal:

```bash
$ python -m pip install -r requirements.txt
```
Note Gurobi requires an external license to be used.

### Excel Dependency
This project requires `OpenSolver` to run. Download the correct version of `OpenSolver` from the following link: https://opensolver.org/installing-opensolver/

## Usage

### Python Model
Access the jupyter notebook and run the code. There are four jupyter notebooks:
  1. `Bed-and-Staff-Capacities-Planning-Models/Python Tools/Blank Models/Deterministic - blank.ipynb` - contains an empty version of the determinisitic model. 
  2. `Bed-and-Staff-Capacities-Planning-Models/Python Tools/Blank Models/Two-Stage Stochastic - blank.ipynb` - contains an empty version of the stochastic model.
  3. `Bed-and-Staff-Capacities-Planning-Models/Python Tools/Implementation - Examples/Deterministic - Worked Example.ipynb` - contains a worked example of the determinisitic model. 
  4. `Bed-and-Staff-Capacities-Planning-Models/Python Tools/Implementation - Examples/Stochastic - Worked Example.ipynb` - contains a worked example of the stochastic model. 

### Excel Model
Open and Save the Excel File. 
The deterministic model can be found in the `Deterministic` worksheet, with the stochastic model being found in the `Stochastic` worksheet.
To run either of the two models:
  1. Select the `Data` ribbon on the top of the sheet.
  2. Select the `Solve` button on the OpenSolver section.
  3. The model will output the results into the worksheet.
  

