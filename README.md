# Just some notes before the projects starts!

# What's the target Q in loss function during unsupervised NN learning?
The randomly initialized Q-value outputs are complete garbage. The maximum Q-value of the next state gives a tiny reward to this garbage, which becomves the target for the network, and it works!
