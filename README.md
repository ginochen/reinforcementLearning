# Just some notes before the projects starts!

# What's the target Q for NN learning when there's no observation?
The randomly initialized Q-value is complete garbage. The maximum Q-value of the next state gives a tiny reward to the garbage, this is the target for the network, and it works!
