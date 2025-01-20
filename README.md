# data_science_analytics-lab
#ROLL NUMBER-2206216

#QUESTION-1
Use linear regression to fit a straight line to the given database. Set your learning rate to 0.5. What are the cost function value and learning parameters values after convergence? Also, mention the convergence criteria you used.

ANSWER-
The current implementation uses a fixed number of epochs (epochs=1000) as the convergence criterion. The gradient descent algorithm iterates for the specified number of epochs, regardless of whether the model has converged.
To improve the convergence criterion, we can implement an early stopping mechanism based on the change in the loss function (Mean Squared Error). For example, we could stop the training if the change in MSE between consecutive iterations falls below a small threshold.
To solve this, I need the database (data points) to fit a straight line using linear regression. Please provide the dataset or specify the data points.


#QUESTION-2
Use linear regression to fit a straight line to the given database. Set your learning rate to 0.5. What are the cost function value and learning parameters values after convergence? Also, mention the convergence criteria you used.

ANSWER:-
Averaging the cost (e.g., using MSE instead of SSE) has these advantages:-
Independent of Dataset Size: Normalized cost makes it easier to compare across datasets of different sizes.
Stable Updates: Prevents large gradient values, ensuring smoother and more stable parameter updates.
Interpretability: Represents error per data point, making it more meaningful and easier to understand.
Consistent Scaling: Keeps the cost function manageable, especially for large datasets.
