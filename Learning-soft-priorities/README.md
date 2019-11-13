# Learning-soft-priorities-with-constrained-Bayesian-optimization
Exploiting the redundancy of the robot, a complex motion can be achieved by executing multiple tasks simultaneously, where the key is tuning the task priorities. Generally, the task priorities are predefined manually. In order to generate the task priorities automatically, different frameworks have been proposed to address this problem. In this paper, we intend to find a black-box optimization method to learn the soft tasks priorities, guaranteeing that the robot motion is optimized with high efficiency and no constraints violations occur. We compare the performance of several variants of Bayesian optimization with respect to fitness value and constraints violations, and finally we retain the one with Gaussian Process with multiple outputs, which is sample-efficient and leads to no safety constraints violations, as the optimal solution to address the problem.