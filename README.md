# Decision Tree Survey Results

This repository contains all results from a survey
evaluating techniques for human-in-the-loop-learning
of decision tree classifiers.
Details on the methodology used to conduct this
survey can be found in the open-access journal
publication *Constructing Explainable Classifiers From the
Start --- Enabling Human-In-the Loop Learning*.
Results from each of the three experiments can be found in
their respective subdirectories.
Details on how to interpret these results for each experiment
can be found below. Note that within a group an individual
participant's results appear on the same row for all result files. 

# Experiment One
A subdirectory exists for responses from each of the two groups
of participants. The following files can be found within these subdirectories.

- AccuracyDifference.csv: Each row contains the difference in accuracy between the participants response and the true accuracy of the tree for each tree in the experiment.

- AccuracyTime.csv: Each row contains the time taken for the participant to estimate the accuracy of each tree in the experiment.

- LeafRImp.csv: Each row contains the calculated relative impurity between the leaf selected by the participants and the most impure leaf in the tree for each tree in the experiment.

- LeafTime.csv: Each row contains the time taken for the participant to select the most impure leaf for each tree in the experiment.

# Experiment Two
A subdirectory exists for responses from each of the two groups
of participants. The following files can be found within these subdirectories.

- LeafCorrect.csv: Each row indicates whether the participant selected the correct response to whether the leaf node was reached for each tree in the experiment. A one indicates a correct response and a zero indicates incorrect response.

- LeafTime.csv: Each row contains the time taken for the participant to
provide a response for each tree in the experiment.


# Experiment Three
Each row in the file Likert.csv contains a participant's responses to the six likert question.
The corresponding videos for each question can be found in the Videos folder.
Responses for each question should be interpreted as follows:

- 0 - Strong preference for UserClassifier system

- 1 - Some preference for UserClassifier system

- 2 - No preference between two systems

- 3 - Some preference for parallel-coordinates based system

- 4 - Strong preference for parallel-coordinates based system
