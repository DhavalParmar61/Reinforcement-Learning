Improving sample complexity of HRL algorithms

Generally transitions used by higher level policy in HRL algorithms are very sparse so higher level policy takes more time to train. We can make learning faster by making this transition more denser by using sub-transition. We have taken inspiration from paper by Hongyao Tang et al. (2019). We have implemented this idea using HDQN algorithm on 6 state stochastic process and shown that proposed idea helps in getting better rewards in less number of steps.
