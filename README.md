# Hi, I'm Rabia 👋

Management Information Systems student at Istanbul Gelişim University, working
towards an ML Engineer role. I like the place where machine learning meets
optimization.

**Erasmus+ traineeship, University of Pisa (Jul–Sep 2026).** In Prof. Antonio
Frangioni's group I worked on BundleSolverML in the SMS++ optimization library:
an LSTM, written in C++ with LibTorch, that predicts the step parameter of a
bundle method at every iteration. I built the network module, its runtime
configuration, save/reload support and the tests.

## Projects

A three-step series that rebuilds the idea behind my traineeship from scratch, in Python:

1. **[subgradient-step-sizes](https://github.com/rabiaozers/subgradient-step-sizes)**
   — why choosing a step size is hard: constant, diminishing and Polyak steps on a nonsmooth function.
2. **[mini-bundle-method](https://github.com/rabiaozers/mini-bundle-method)**
   — a bundle method with my own exact master-problem solver, applied to a knapsack Lagrangian dual and tested against a brute-force referee.
3. **[Learning t](https://github.com/rabiaozers/mini-bundle-method/blob/main/LEARNED_T.md)**
   — an MLP and an LSTM in PyTorch that try to learn the bundle step parameter, compared against the rule and a greedy teacher. Honest result: better accuracy, but not a faster solver, and why.

## Tools

Python · PyTorch · LibTorch (C++) · pytest · Git · CMake
