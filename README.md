# CSE-543T-Final-Project
# Environment and Libraries

This project requires Python 3 and the following Python libraries installed:

* NumPy
* Pandas
* SciPy

Need to have software installed to run and execute a Jupyter Notebook

# Code Structure

The code is structured as follows:

*1.* Data Loading and Preprocessing: The data from nutrients_csvfile_small.csv is loaded using pandas and preprocessed to replace certain values and convert columns to numeric types.

*2.* Factor Definition: The taste and preference factors for each food category are defined. These scores are used to personalize the optimization to the user's preferences.

*3.* Calorie Calculation: The required calories are calculated based on the user's details such as weight, height, age, gender, and activity level.

*4.* Objective Function Definition: The objective function for the optimization is defined as the sum of the difference between the actual percentage and optimal percentage regarding carbohydrate, fat, and protein. This is the function that the optimization algorithms will attempt to minimize.

*5.* Constraint Definition: The constraints for the optimization are defined. These include constraints on the total calorie intake, the number of food items, and the total volume of food.

*6.* Optimization: The optimization is run using different algorithms (SLSQP, Trust-Contr Solver, COBYLA, TNC, L-BFGS-B, Powell's Conjugate Direction Method) to solve the optimization problem.

*7.* Result Display: The results of the optimization are displayed. This includes the optimal amount of each food item to consume based on the defined objective function and constraints.
