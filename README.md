# Multi-armed bandits algorithms for personalized recommendations in the field of online maps

This work explores the aspects of using  multi-armed bandits algorithms to issue personalized recommendations for route types. The hypothesis is put forward that taking into account the context of a route request will improve the quality of such recommendations, therefore, the study focuses on the family of contextual multi-armed bandits. Greedy strategies and UCB are taken as the baseline.
During the experiment on synthetic data, algorithms that take into account the context had twice as much accuracy as UCB and the random model.

The structure of this work is as follows:

1. Implementation of the greedy strategy, UCB strategy and linear multi-armed bandits algorithms (LinUCB and LinPRUCB)  in python
2. Generating synthetic data using fuzzy logic rules
3. Using the generated data for conducting numerical experiments

*Used technologies and algorithms:*
- Python;
- MAB, linear MAB, contextual MAB;
- Fuzzy logic rules
