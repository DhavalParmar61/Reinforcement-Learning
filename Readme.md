Improving sample complexity of HRL algorithms

we have taken inspiration from paper by Hongyao Tang et al. (2019) that suggest to use sub transitions to train higher level policy. Generaly transitions used by higher level policy are quite sparce so higher level policy takes more time to train. We can make learning faster by making this transition more denser by using subtransition. We have implemented this idea with HDQN on 6 state stochastic process and shown results in paper that proposed idea really helps in getting better rewards in less number of steps.
