## The AutoCSP Project

The AutoCSP project addresses problems where the solution is a combination of multiple decision variables, so-called combinatorial optimization problems. 
The goal is to find a combination that fulfills all constraints that the problem has while optimizing an objective function. 
Examples for these problems include machine or job scheduling, timetabling, lot sizing, or vehicle routing, all of which are highly relevant in industrial settings like production planning or delivery scheduling and are embedded in intelligent decision support systems. 

The state-of-the-art technique to solve these problems are dedicated constraint solvers, which are highly optimized and have been investigated for a long time. 
Still, searching for good or even optimal solutions often is time-consuming due to the enormous number of possible combinations that need to be explored while facing strong restrictions on which combinations form a feasible solution. 
This is especially true when the same problem has to be repeatedly solved with different inputs, for example in daily production planning or fleet scheduling tasks. 
Even though the general problem stays the same, experiences from earlier solutions are not used to solve new instances faster.

### Goal

AutoCSP advances the scientific knowledge and state-of-the-art through problem-specific solvers that combine data-driven machine learning (ML) models and logic-driven constraint solvers in a hybrid intelligent system. 
These solvers are automatically generated from a constraint model, i.e. the description of the problem to be solved, and are self-taught to solve constraint satisfaction and optimization problems while maintaining correctness and time-efficiency. 
To achieve this goal, the project investigates 

1. how to generate training data just from the problem description, 
2. how to present the data such that the ML model understands it, 
3. how to efficiently learn from this data, and 
4. how to bring everything together in one system.

### About

The AutoCSP project is hosted by [Simula Research Laboratory](https://www.simula.no/) and funded by the Norwegian Research Council as a three-year researcher project with international mobility under grant number 324674. It is led by [Helge Spieker](https://www.simula.no/people/helge). 
The research activities are carried out in collaboration with the [Machine Learning and Artificial Intelligence Lab](https://mlai.cs.uni-bonn.de/) at the University of Bonn, Germany.

