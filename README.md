# Quantum-Optimization-of-Racingline
Part of Purdue AI Racing's VIP Class

# Abstract

Raceline optimization algorithms are among the most vital components of autonomous racing, as they guide a car’s trajectory in dynamic conditions to achieve the best lap time. Although classical solutions have been able to generate optimal racelines, prior algorithms are not perfect as they suffer from various drawbacks such as the curse of dimensionality. Thus, we turn to quantum computing algorithms as a novel approach to this problem, as they are currently at the forefront of optimization research and have been found to perform better than their classical counterparts in fields such as generative modeling. This is partly due to the probabilistic nature of quantum computing, which allows for the exploration of multiple solutions simultaneously. Additionally, specific models such as the Quadratic Unconstrained Binary Optimization (QUBO) quantum-annealer model have great theoretical promise for raceline optimization due to its ability to represent complex, interdependent variables as a quadratic function of binary variables.

Therefore, to explore quantum solutions, we deploy the QUBO model with past methods like racetrack discretization to create an optimal raceline trajectory for an autonomous Indy car that competes in the Indianapolis Autonomous Challenge. Specifically, we aim to develop racelines for driving at Indianapolis Motor Speedway, where the competition occurs. We compare this solution to a current state-of-the-art method using two metrics: computation time and lap time. This comparison will provide many insights into the current usefulness of quantum optimization models in raceline optimization and the potential these algorithms have to impact autonomous motion planning broadly with technological advances.

# Sources

Classical Optimization Python code being experimeted with comes from https://github.com/ParsaD23/Racing-Line-Optimization-with-PSO
