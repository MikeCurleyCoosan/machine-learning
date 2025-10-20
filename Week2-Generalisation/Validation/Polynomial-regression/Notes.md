
# Generalisation is the goal of ML

*Want good performance for new data
*How good the generalisation, is how well it performs on previously “unseen data” i.e. data not
used to train the set.

## Definition:

▪ Generalisation is the model’s ability to give sensible outputs to sets of input that it has never seen before

▪ Root-mean-squared (RMS) error could be used to measure: 𝐸𝑅𝑀𝑆 = $$\sqrt{2𝐸(𝑤 ∗)/𝑁}$$

▪ Back to previous idea of checking how far away pred is away from the original y, what is
the problem?

▪ We are checking the Generalisation of the model by using data it was trained on - i.e. it
is NOT previously unseen.

▪ Our model may be overfit to the training data.

##
▪ The opposite problem is under-fitting.
▪ You can’t even seem to reduce your training loss to anything reasonable. This is like  