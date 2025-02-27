# TOPS
Implementation of paper:- https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&amp;arnumber=8294229
Abstract—We present a new approach to ensemble learning. Our
approach differs from previous approaches in that it constructs
and applies different predictive models to different subsets of the
feature space. It does this by constructing a tree of subsets of the
feature space and associating a predictor (predictive model) to each
node of the tree; we call the resulting object a tree of predictors.
The (locally) optimal tree of predictors is derived recursively; each
step involves jointly optimizing the split of the terminal nodes of
the previous tree and the choice of learner (from among a given
set of base learners) and training set—hence predictor—for each
set in the split. The features of a new instance determine a unique
path through the optimal tree of predictors; the final prediction
aggregates the predictions of the predictors along this path. Thus,
our approach uses base learners to create complex learners that
are matched to the characteristics of the data set while avoiding
overfitting. We establish loss bounds for the final predictor in terms
of the Rademacher complexity of the base learners. We report the
results of a number of experiments on a variety of datasets, showing
that our approach provides statistically significant improvements
over a wide variety of state-of-the-art machine learning algorithms,
including various ensemble learning methods.
