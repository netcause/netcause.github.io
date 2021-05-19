### Welcome!

<h4>Date: August 14-15, 2021</h3><br>

<h4> Presenters: <a href="https://www.cs.uic.edu/~elena/">Elena Zheleva</a>  (UIC) & <a href="https://darbour.github.io">David Arbour</a> (Adobe Research)</h4>

<h4>Description:</h4>

The task of causal inference -- inferring the effect of interventions and counterfactuals from data -- is central to a vast number of scientific and industrial applications. Causal reasoning with big data requires accounting for the bias, noise, heterogeneity, and complex relationships inherent to such data. To capture these data properties, it is customary to model real-world data sources as relational systems and to reason about them probabilistically. Relations in data can be represented through heterogeneous networks in which nodes represent interdependent entities, such as people, companies, websites, and diseases, while edges denote different relationships between these entities, such as friendship, hyperlink, contribution, and spread of disease. Relational data is not independent and identically distributed (i.i.d.), and the attributes of one node can be correlated with the attributes of its neighboring nodes and even cause changes to them. For example, people who interact may share similar ideas and beliefs (homophily) and impact each other?s views on the world (contagion). 

This tutorial will present state-of-the-art research on causal inference for network data, also known as causal inference with interference. The tutorial will start by motivating research in this area with real-world applications, such as measuring influence in social networks and market experimentation. We will discuss the challenges of applying existing causal
inference techniques designed for i.i.d. data to relational data, some of the solutions that currently exist and the gaps and opportunities for future research. Since randomized controlled trials are considered the gold standard in causal inference, we will present existing network experiment designs for measuring different possible effects of interest in networks. Then we will focus on causal inference from observational data, its representation, identification, and estimation. Finally, we will present how causal structure learning can help with causal discovery in networks.
