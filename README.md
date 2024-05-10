# SupervisedLearningAI

This code is used to implement a supervised machine learning program. Specifically, the code for the Custom learner was created for this project. Each learner (Custom, Neural Network, Decision Tree, Naive Bayes, 5 Nearest Neighbor, Majority Classifier, and Random Classifier) will find patterns in a labeled data set, build a model, and use it to classify new observations. The results are then compiled in results.html.

The purposes of each of the following files are stated below:

data - a folder containg all of the example data sets that will be used

planners - a folder containing all supervised learners that classify new observations
- custom.jar
- nnet.jar
- dtree.jar
- nbayes.jar
- 5nn.jar
- majority.jar
- random.jar

classes - a folder containing Java class files
- CustomLearner.class
- KNearestNeighborModel.class
- NeuralNetworkModel.class
- MajorityDiscreteModel.class
- MajorityNumericModel.class
- RandomDiscreteModel.class
- RandomNumericModel.class

All other files under the classes directory are part of an external Supervised Learning library.

src - a folder containg the source code
- CustomLearner.java - implements the Customer supervised learner
- KNearestNeighborModel.java - implements a model that uses the k Nearest Neighbor lazy learning classifier
- NeuralNetworkModel.java - implements a model that uses a feedforward neural network
- MajorityDiscreteModel.java - implements a model that always predicts the most common discrete class label
- MajorityNumericModel.java - implements a model that always predicts the most common numeric class label
- RandomDiscreteModel.java - implements a model that chooses a random value from all possible discrete class label values
- RandomNumericModel.java - implements a model that chooses a random value from all possible numeric class label values

All other files under the src directory are part of an external Supervised Learning library.

sl.jar - a program to test the provided supervised learners against a series of data sets and new observations

To compile and run the program, run the run-learner.bat file (Windows) or the run-learner.sh file (Mac/Linux).

To view the results, open the results.html file.

Code is available upon request.