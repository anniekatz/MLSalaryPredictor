# MLSalaryPredictor
Random Forest Regression machine learning model to predict salary of a specific tech job (based on levels.fyi anonymous salary data)

# Installation and User Guide

To interact with the Jupyter Notebook, please take the following steps to prepare your environment.

1. You may create a Conda environment, a Python virtual environment (venv) or use your
computer’s existing environment with Python 3.10. A computer with a monitor,
keyboard, and modern CPU (capable of running the model) are required.

2. Please ensure every Python package below is installed. You may install these using pip,
conda, or another Python package installation tool.

    a. Packages to install include:
    
      i. python3
      
      ii. scikit-learn
      
      iii. pandas
      
      iv. numpy
      
      v. jupyter
      
      vi. matplotlib
      
    
3. Once every Python package required has been installed, enter your environment using the
command line.

4. Navigate to the project folder: SalaryRegressionProject

5. On the command line, type ‘jupyter notebook’ to open Jupyter Notebooks in your
browser

6. Open the salary_regression_model.ipynb Jupyter Notebook file

7. Please run each cell in order. You can run each cell individually by pressing shift+enter.
You can run the notebook as a whole by clicking the double arrows at the top of the
notebook.

    a. Note: You do not need to run RandomizedSearchCV or GridSearch cells in the
“Model Tuning” section if you’re limited for time. The Evaluation section uses
the best metrics found in that section.

    b. At the end of the notebook, the Try It section has user interaction capabilities so
you can interact with the notebook

8. Navigate through the Problem Definition section and Data section. Run the cells to see
data visualizations and explanations, with a variety of descriptive methods to see
relationships and variances in the data.

9. Run the cells in the Model section to view the baseline model and its baseline metrics.

10. Run the cells in the Model Tuning section to view hyperparameter tuning methods used
and metrics changes.

    a. Please note: these may take some time to run. It’s not necessary to run these as the best parameters found are used in the Evaluation section

11. In the Evaluation Section, run the cell to view the final model’s metrics tested on the
never-been-used Test data

12. In the final Try It section, you can interact with the model yourself. Run the cell to start
the prompt. Enter an example user’s features, click “Run the Model”, and you will be
provided with an annual compensation estimate for that user.
