Machine Learning

# ML Notes

## Definitions

### What are the machine learning models

A more technical definition would be that a machine learning model is a block of code or framework that can be modified to solve different but related problems based on the data provided.

<center>(OR)</center>

A model is an extremely generic program(or block of code), made specific by the data used to train it. It is used to solve different problems.

### How are model training algorithms used to train a model?

Two key pieces of information: a model and data are used to create a trained model. This process is called model training.

### What is model inference?

Model inference is when the trained model is used to generate predictions.

### Is it true or false that you always need to have an idea of what you're making when you're handling your raw data?

False, because unsupervised learning uses unlabeled data and only works to find the patterns present in data, so you don't always need to have a end result in mind when you receive your raw data.

### What are the major steps involved in machine learning process.

![Five Major machine Learning Steps](https://video.udacity-data.com/topher/2021/April/608c4397_steps/steps.png)

### What is Supervised tasks?

A task is supervised if you are using labeled data. We use the term labeled to refer to data that already contains the solutions, called labels.

### What is Unsupervised tasks?

A task is considered to be unsupervised if you are using unlabeled data. This means you don't need to provide the model with any kind of label or solution while the model is being trained.

### What is clustering?

Unsupervised learning task that helps to determine if there are any naturally occurring groupings in the data.

### What is categorical label and How we can work on it?

A categorical label has a discrete set of possible values, such as "is a cat" and "is not a cat." In a machine learning problem in which you want to identify the type of flower based on a picture, you would train your model using images that have been labeled with the categories of flower you would want to identify. Furthermore, when you work with categorical labels, you often carry out classification tasks\*, which are part of the supervised learning family.

### What is continuos label?

A continuous (regression) label does not have a discrete set of possible values, which means possibly an unlimited number of possibilities. which often means you are working with numerical data. In the snow cone sales example, we are trying to predict the number\* of snow cones sold. Here, our label is a number that could, in theory, be any value.

### Process of defining machine learning problem.

1. Define a very specific task.
2. Identify the machine learning task we might use to solve this problem.

### is it important to understand the data needed for ml task?

Yes, Understanding the data needed helps you select better models and algorithms so you can build more effective solutions.

### what is the most important step of the machine learning process?

Working with data is perhaps the most overlooked—yet most important—step of the machine learning process. In 2017, an O’Reilly study showed that machine learning practitioners spend 80% of their time working with their data.

### What are the Aspects of Working with Data

There are four aspects of working with data.
![four aspects of working with data](https://video.udacity-data.com/topher/2021/April/608c4dfa_datasteps/datasteps.png)

### What is Data collection?

Data collection can be as straightforward as running the appropriate SQL queries or as complicated as building custom web scraper applications to collect data for your project. You might even have to run a model over your data to generate needed labels. Here is the fundamental question:

> Does the data you've collected match the machine learning task and problem you have defined?

### What is Data inspection?

The quality of your data will ultimately be the largest factor that affects how well you can expect your model to perform. As you inspect your data, look for:

1. Outliers
2. Missing or incomplete values
3. Data that needs to be transformed or preprocessed so it's in the correct format to be used by your model

### What is Summary statistics?

Models can assume how your data is structured.

Now that you have some data in hand it is a good best practice to check that your data is in line with the underlying assumptions of your chosen machine learning model.

With many statistical tools, you can calculate things like the mean, inner-quartile range (IQR), and standard deviation. These tools can give you insight into the scope, scale, and shape of the dataset.

### What is Data visualization?

You can use data visualization to see outliers and trends in your data and to help stakeholders understand your data.

### What is the first step in model training?

The first step in model training is to randomly split the dataset. This allows you to keep some data hidden during training, so that data can be used to evaluate your model before you put it into production. Specifically, you do this to test against the bias-variance trade-off.

### How to split the dataset?

we can Splitting our dataset into two sets of data:

1. Training dataset: The data on which the model will be trained. Most of your data will be here. Many developers estimate about 80%.
2. Test dataset: The data withheld from the model during training, which is used to test how well your model will generalize to new data.

### What is Model parameters?

Model parameters are settings or configurations the training algorithm can update to change how the model behaves. Depending on the context, you’ll also hear other more specific terms used to describe model parameters such as weights and biases. Weights, which are values that change as the model learns, are more specific to neural networks.

### What is Loss function?

A loss function is used to codify the model’s distance from this goal. For example, if you were trying to predict a number of snow cone sales based on the day’s weather, you would care about making predictions that are as accurate as possible. So you might define a loss function to be “the average distance between your model’s predicted number of snow cone sales and the correct number.” You can see in the snow cone example this is the difference between the two purple dots.

### What is model training?

The end-to-end training process is

1. Feed the training data into the model.
2. Compute the loss function on the results.
3. Update the model parameters in a direction that reduces loss.

You continue to cycle through these steps until you reach a predefined stop condition. This might be based on a training time, the number of training cycles, or an even more intelligent or application-aware mechanism.

### What is Hyperparameters?

Hyperparameters are settings on the model which are not changed during training but can affect how quickly or how reliably the model trains, such as the number of clusters the model should identify.
Hyperparameters are important because they directly control the behaviour of the training algorithm and have a significant impact on the performance of the model is being trained.

> “A good choice of hyperparameters can really make an algorithm shine”.

In statistics, hyperparameter is a parameter from a prior distribution; it captures the prior belief before data is observed.
In any machine learning algorithm, these parameters need to be initialized before training a model.

### What is Linear models?

One of the most common models covered in introductory coursework, linear models simply describe the relationship between a set of input numbers and a set of output numbers through a linear function (think of y = mx + b or a line on a x vs y chart).

Classification tasks often use a strongly related logistic model, which adds an additional transformation mapping the output of the linear function to the range [0, 1], interpreted as “probability of being in the target class.” Linear models are fast to train and give you a great baseline against which to compare more complex models. A lot of media buzz is given to more complex models, but for most new problems, consider starting with a simple model.

### What is Tree-based models?

Tree-based models are probably the second most common model type covered in introductory coursework. They learn to categorize or regress by building an extremely large structure of nested if/else blocks, splitting the world into different regions at each if/else block. Training determines exactly where these splits happen and what value is assigned at each leaf region.

For example, if you’re trying to determine if a light sensor is in sunlight or shadow, you might train tree of depth 1 with the final learned configuration being something like if (sensor_value > 0.698), then return 1; else return 0;. The tree-based model XGBoost is commonly used as an off-the-shelf implementation for this kind of model and includes enhancements beyond what is discussed here. Try tree-based models to quickly get a baseline before moving on to more complex models.

### Define Deep learning models.

Extremely popular and powerful, deep learning is a modern approach based around a conceptual model of how the human brain functions. The model (also called a neural network) is composed of collections of neurons (very simple computational units) connected together by weights (mathematical representations of how much information to allow to flow from one neuron to the next). The process of training involves finding values for each weight.
Various neural network structures have been determined for modeling different kinds of problems or processing different kinds of data.

A short (but not complete!) list of noteworthy examples includes:

- FFNN: The most straightforward way of structuring a neural network, the Feed Forward Neural Network (FFNN) structures neurons in a series of layers, with each neuron in a layer containing weights to all neurons in the previous layer.
- CNN: Convolutional Neural Networks (CNN) represent nested filters over grid-organized data. They are by far the most commonly used type of model when processing images.
- RNN/LSTM: Recurrent Neural Networks (RNN) and the related Long Short-Term Memory (LSTM) model types are structured to effectively represent for loops in traditional computing, collecting state while iterating over some object. They can be used for processing sequences of data.
- Transformer: A more modern replacement for RNN/LSTMs, the transformer architecture enables training over larger datasets involving sequences of data.

### Using Log Loss

Log loss seeks to calculate how uncertain your model is about the predictions it is generating. In this context, uncertainty refers to how likely a model thinks the predictions being generated are to be correct.
For example, let's say you're trying to predict how likely a customer is to buy either a jacket or t-shirt.

Log loss could be used to understand your model's uncertainty about a given prediction. In a single instance, your model could predict with 5% certainty that a customer is going to buy a t-shirt. In another instance, your model could predict with 80% certainty that a customer is going to buy a t-shirt. Log loss enables you to measure how strongly the model believes that its prediction is accurate.

In both cases, the model predicts that a customer will buy a t-shirt, but the model's certainty about that prediction can change.

### What are the things used to evaluate the linear regression model?

There are many different tools that can be used to evaluate a linear regression model. Here are a few examples:

- Mean absolute error (MAE): This is measured by taking the average of the absolute difference between the actual values and the predictions. Ideally, this difference is minimal.
- Root mean square error (RMSE): This is similar MAE, but takes a slightly modified approach so values with large error receive a higher penalty. RMSE takes the square root of the average squared difference between the prediction and the actual value.
- Coefficient of determination or R-squared (R^2): This measures how well-observed outcomes are actually predicted by the model, based on the proportion of total variation of outcomes.

### What is Bag of words?

A technique used to extract features from the text. It counts how many times a word appears in a document (corpus), and then transforms that information into a dataset.

### Data vectorization

A process that converts non-numeric data into a numerical format so that it can be used by a machine learning model.

### Silhouette coefficient

A score from -1 to 1 describing the clusters found during modeling. A score near zero indicates overlapping clusters, and scores less than zero indicate data points assigned to incorrect clusters. A score approaching 1 indicates successful identification of discrete non-overlapping clusters.

### Stop words:

A list of words removed by natural language processing tools when building your dataset. There is no single universal list of stop words used by all-natural language processing tools.

### Residual

A residual is the vertical distance between a data point and the regression line. Each data point has one residual.

### Cost Function/ Loss Function

Cost function is a function that takes both predicted outputs by the model and actual outputs and calculates how much wrong the model was in its prediction.

### Gradient descent (GD)

Gradient descent (GD) is an iterative first-order optimisation algorithm used to find a local minimum/maximum of a given function. This method is commonly used in machine learning (ML) and deep learning(DL) to minimise a cost/loss function (e.g. in a linear regression).

### Recall

Recall literally is how many of the true positives were recalled (found), i.e. how many of the correct hits were also found.

### F1 Score

F1 score is defined as the harmonic mean between precision and recall. It is used as a statistical measure to rate performance. In other words, an F1-score (from 0 to 9, 0 being lowest and 9 being the highest) is a mean of an individual's performance, based on two factors i.e. precision and recall.

### Harmonic Mean Definition

The Harmonic Mean (HM) is defined as the reciprocal of the average of the reciprocals of the data values.. It is based on all the observations, and it is rigidly defined. Harmonic mean gives less weightage to the large values and large weightage to the small values to balance the values correctly. In general, the harmonic mean is used when there is a necessity to give greater weight to the smaller items. It is applied in the case of times and average rates.

<center>

![](https://latex.codecogs.com/svg.latex?%5Chuge%20%7B%7B%5Ccolor%7BGolden%7D%20%7D%20%5Cbegin%7Bequation*%7D%20%5Cfrac%202%20%7B%5Cfrac%7B1%7D%7BP%7D%20+%20%5Cfrac%7B1%7D%7BR%7D%20%7D%20%5Cend%7Bequation*%7D%20%7D)

</center>

### Bayes error rate

In statistical classification, Bayes error rate is the lowest possible error rate for any classifier of a random outcome and is analogous to the irreducible error. A number of approaches to the estimation of the Bayes error rate exist.

### Batch, Mini Batch & Stochastic Gradient Descent

This article explains all these concepts in details, check out this [article](https://towardsdatascience.com/batch-mini-batch-stochastic-gradient-descent-7a62ecba642a)

### How we should divide the data?

All experiments should be conducted on different portions of your data.

- Training data set — Use this set for model training, 70–80% of your data is the standard.
- Validation/development data set — Use this set for model hyperparameter tuning and experimentation evaluation, 10–15% of your data is the standard.
- Test data set — Use this set for model testing and comparison, 10–15% of your data is the standard.

These amounts can fluctuate slightly, depending on your problem and the data you have.

### Underfitting

Poor performance on training data means the model hasn’t learned properly and is underfitting. Try a different model, improve the existing one through hyperparameter or collect more data.

### Overfitting

Great performance on the training data but poor performance on test data means your model doesn’t generalize well. Your model may be overfitting the training data. Try using a simpler model or making sure your the test data is of the same style your model is training on.

Another form of overfitting can come in the form of better performance on test data than training data. This may mean your testing data is leaking into your training data (incorrect data splits) or you've spent too much time optimizing your model for the test set data. Ensure your training and test datasets are kept separate at all times and avoid optimizing a models performance on the test set (use the training and validation sets for model improvement).

### Generalization

The ability for a machine learning model to perform well on data it hasn't seen before

## Important Points

- The workflow of Scikit-Learn
  1.  Get Data Ready
  2.  Pick a model
  3.  Fit the model to the data and make prediction
  4.  Evaluate the model
  5.  Imrove through experimentations
  6.  Save and reload your trained model.
- In supervised learning, there are two main identifiers you will see in machine learning:
  1.  Categorical label
  2.  continuous label
- Discrete: A term taken from statistics referring to an outcome taking on only a finite number of values (such as days of the week).
- A label refers to data that already contains the solution.
- Machine learning practitioners spend 80% of their time working with their data.
- Impute is a common term referring to different statistical tools which can be used to calculate missing values from your dataset.
- Outliers are data points that are significantly different from others in the same sample.
- The model training algorithm iteratively updates a model's parameters to minimize some loss function.
- Practitioners often use machine learning frameworks that already have working implementations of models and model training algorithms. You could implement these from scratch, but you probably won't need to do so unless you’re developing new models or algorithms.
- Practitioners use a process called model selection to determine which model or models to use. The list of established models is constantly growing, and even seasoned machine learning practitioners may try many different types of models while solving a problem with machine learning.
- Be prepared to iterate.
- Foster a habit of trying new things, measuring success, and comparing results across iterations.
- Hyperparameters are set manually and they are not updated during model training.
- Model Accuracy is the fraction of predictions a model gets right.
- The applications of machine learning are quite varied, and therefore you often need to find evaluation metrics that are specific to your exact application.
- Hyperplane: A mathematical term for a surface that contains more than two planes.
- Plane: A mathematical term for a flat surface (like a piece of paper) on which two points can be joined by a straight line.
- Words like 'a' and 'the': The machine learning community refers to these words as stop words.
- data vectorization is the process to convert text into numbers.
- There are three concepts that are at the core of machine learning: data, a model, and learning.
- Our goal should be to minimize the residual sum or squares(RSS)
- The most effective machine learning people is they're very clear-eyed about what to tune in order to try to achieve one effect. This is a process we call orthogonalization.
- It's not always easy to combine all the things you care about into a single row number evaluation metric. In those cases I've found it sometimes useful to set up satisficing as well as optimizing matrix.
- a larger neural network is formed by taking many of the single neurons and stacking them together. So, if you think of this neuron that's being like a single Lego brick, you then get a bigger neural network by stacking together many of these Lego bricks.
- Scale has been driving deep learning progress and by scale I mean both the size of the neural network we need just a new network a lot of hidden units a lot of parameters a lot of connections as well as scale of the data.
