# Olympic-Teams-Analysis

This project analyzes Olympic teams data to explore relationships between various factors and the number of medals won by each team. It uses linear regression to predict the number of medals based on the number of athletes and previous medals. The analysis also includes visualizations to provide insights into the data.

## Getting Started

To get started with this project, follow the instructions below.

### Prerequisites

- Python 3
- Jupyter Notebook (optional)

pip install pandas seaborn scikit-learn

. Place the `teams.csv` file in the project directory. This file contains the Olympic teams data.

### Usage

1. Open the Jupyter Notebook (optional):

##jupyter notebook


2. Open the `olympic_teams_analysis.ipynb` notebook.

3. Run the cells in the notebook to execute the code step by step.

4. Explore the analysis results and visualizations.

## Code Explanation

The project code performs the following steps:

1. Loads the Olympic teams data from the `teams.csv` file.

2. Selects the relevant columns for analysis.

3. Calculates the correlation between the columns and the 'medals' column.

4. Plots scatter plots and linear regression lines for 'athletes' vs 'medals' and 'age' vs 'medals'.

5. Plots a histogram for 'medals'.

6. Checks for rows with missing values and drops them.

7. Splits the data into training and test sets based on the 'year' column.

8. Creates a linear regression model and fits it on the training data.

9. Makes predictions on the test data using the trained model.

10. Calculates the mean absolute error between the actual and predicted medal counts.

11. Provides descriptive statistics for the 'medals' column.

12. Displays the test data for specific teams, such as 'USA' and 'IND'.

13. Calculates the absolute errors for each prediction.

14. Calculates the mean absolute error by team.

15. Calculates the average medals by team.

16. Calculates the error ratio by dividing the mean absolute error by the average medals.

17. Removes NaN and infinite values from the error ratio.

18. Plots a histogram for the error ratio.

19. Sorts the error ratio in ascending order.

## Results

The analysis provides insights into the Olympic teams data. It examines the correlation between various factors and the number of medals won. The linear regression model predicts the medal count based on the number of athletes and previous medals.

The results include visualizations such as scatter plots, regression lines, and histograms to help understand the relationships and distribution of the data.

The mean absolute error and error ratio are calculated to evaluate the accuracy of the predictions. These metrics provide an indication of how well the model performs in estimating the medal count for different teams.

## Contributing

Contributions to this project are welcome. If you have any suggestions or improvements, please feel free to submit a pull request.




