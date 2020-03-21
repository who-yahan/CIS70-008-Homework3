In this homework, you will be experiment with the ROCSTories dataset, which consists of 5-sentence long stories. You will build a few classifiers for the Story Cloze task. The task involves predicting which of two candidate 5th sentences best ends a story.

You should walk through the IPython Notebook here. It walks you through building a sentiment-based system for predicting the correct next ending as well as two neural network-based approaches that learn a classifier for the task.

You should create a writeup describing the experiments you conduct. We will be primarily grading you on this writeup, although you should also submit your code. Your writeup should include

Your accuracy on the two validation sets and the 2016 test set using…
A sentiment-based classifier
A neural network trained only on the train set, as well as 2 variants.
A neural network trained in a supervised way on the validation set, as well as 2 variants.
Descriptions of your approaches for each of the above methods/variants. Try to make your descriptions detailed enough that another student could reimplement your approach from them.
An error analysis:
Find a couple examples your sentiment classifier gets wrong and discuss them.
Are there any examples that all of your classifiers get wrong? What do you notice about them?


Over the above experiments on model getting from the 2016 train set, we can see from the
average accuracy of three datasets, the best number of hidden layers should be 2 hidden layers
with hidden units = [1024, 512]. Then we use this structure to test other hyperparameters.

