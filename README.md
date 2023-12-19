## Regression using a Neural Network

- This project is inspired by a [freeCodeCamp course](https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/linear-regression-health-costs-calculator). The dataset contains details of patients and their health expenses. It is a considerably small dataset with information about 1300 patients.
- The dataset was preprocessed using Pandas. The project originally expected an MAE below $3500. A simple neural network architecture with careful hypertuning resulted in an MAE of about $1300 which is substantially better than what was expected. Hypertuning was done using K-Fold Cross Validation.
- Other robust regression algorithms from scikit-learn like Theil-Sen Regressor, RANSAC Regressor and Random Forest Regressor were experimented with and out of those, Random Forest Regressor performed the best with an MAE of $2571.35. It can be observed that our simple neural network still managed to substantially outperform Random Forest Regressor.
