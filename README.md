# OpSDE
OpSDE Solves Differential Equations

In this repository, we'll try to solve differential equations (DEs) using optimization. The idea is that we can transform the problem of solving a DE to an optimization problem, by guessing a solution that depends on several parameters and adjusting these parameters so that the left- and right-hand-sides of the DE are close.

One way to do this is to represent the solution as an artificial neural network (ANN), since the derivatives are usually quite trivial. However, we will experiment with different methods for different problems, and see what is going on.

For ANNs and optimization algorithm, we will use the ones I have in [ASAP](https://github.com/dkaramit/ASAP), but improve them as we work on different problems.

That's it for now.

Enjoy,
Dimitris
