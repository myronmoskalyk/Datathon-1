# Datathon-1
11-CHL5230-F23

## Research Questions

1. Is it possible to correctly predict for a patient’s lung cancer severity status based on patient parameters? (Age, Gender, Air Pollution, Alcohol Usage, Genetic Risk, Lung Disease, Obesity, Smoking, Passive Smoker, Chest Pain, Coughing of Blood)

2. If we ignore the label of lung cancer severities, can we cluster the patients with similar features into severities? Can we check this clustering and see if it is similar to the labels?

## Plans

### RQ1
1. Clean the data if needed
2. Separate the data into training and test sets
3. Perform K-NN on the training set (How to determine K?)
4. Check its performance on the test set

### RQ2
1. Separate the data into training and test sets
2. Drop the variable severity
3. Perform K-means clustering on the training set (Use K=4 because there are 4 levels of severities)
4. See if we get similar clustering as the variable severities
