# influencer_optimization

###### Authors : V.Catteau, M.Cordier
Our goal in this project is to find optimal influencers on a social network. Influence of a node is represented by a SAR stochastic diffusion model, as defined in the virology litterature. We provide an introductory notebook to the problem, and a class for optimization with an example for a facebook and a youtube socials networks.

### Report Folder
Final report summarizing the project.

### References
Scientific documentation for the project

### network_optimizer.py
Class of optimizer which takes in input a graph, and the parameter of the contagion. You must precise the submodular function into the method $greedy_submodular(self, fun=None, cost_fun=None, budget=0.12, r=1, lazy=False)$

### submodular_fun.py
We introduce in the report a new submodular function for faster computations inspired from “A Class of Submodular Functions for Document Summarization" by Hui Lin and Jeff Bilmes, with a diversity-coverage function adapted to the network context.
