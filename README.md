In this challenge, we will predict healthcare costs using a regression algorithm.

We are given a dataset that contains information about different people including their healthcare costs. Let's use the data to predict healthcare costs based on new data.

The first two cells of this notebook import libraries and the data.

We should make sure to convert categorical data to numbers. We will use 80% of the data as the train_dataset and 20% of the data as the test_dataset.

Let's also pop off the "expenses" column from these datasets to create new datasets called train_labels and test_labels. We should use these labels when training our model.

We must create a model and train it with the train_dataset, and run the final cell in this notebook to check our model. The final cell will use the unseen test_dataset to check how well the model generalizes.

To pass the challenge, model.evaluate must return a Mean Absolute Error of under 3500. This means it predicts health care costs correctly within $3500.

The final cell will also predict expenses using the test_dataset and graph the results.
