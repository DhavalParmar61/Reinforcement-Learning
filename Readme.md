Improving sample complexity of HRL algorithms

<<<<<<< HEAD
We have taken inspiration from the paper by Hongyao Tang et al. (2019) that suggests using sub-transitions to train higher level policy. Generally, transitions used by higher level policy are quite sparse so higher level policy takes more time to train. We can make learning faster by making this transition denser by using sub-transitions.

We have implemented the idea considering the HDQN algorithm on 6 state stochastic process and results in the report show that the proposed approach helps in getting better rewards in less number of steps.
=======
Generally transitions used by higher level policy in HRL algorithms are very sparse so higher level policy takes more time to train. We can make learning faster by making this transition more denser by using sub-transition. We have taken inspiration from paper by Hongyao Tang et al. (2019). We have implemented this idea using HDQN algorithm on 6 state stochastic process and shown that proposed idea helps in getting better rewards in less number of steps.
>>>>>>> 615d2db09be3af226334109b27cb6ebabb67f73d
