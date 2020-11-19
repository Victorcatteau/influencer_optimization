# influencer_optimization

###### Authors : V.Catteau, M.Cordier
Graph/Network optimization over contagion with submodular functions. We provide an introductory notebook to the problem, and a class for optimization with an example for a facebook social network, with a SAR contagion model

### Report Folder
Final report summarizing the project.

### Referencesunderstanding
Scientific documentation for the project

### network_optimizer.py
Class of optimizer which takes in input a graph, and the parameter of the contagion. You must precise the submodular function into the method $greedy_submodular(self, fun=None, cost_fun=None, budget=0.12, r=1, lazy=False)$

### submodular_fun.py
We introduce in the report a new submodular function for faster computations inspired from “A Class of Submodular Functions for Document Summarization" by Hui Lin and Jeff Bilmes, with a diversity-coverage function adapted to the network context.
