# Python Tutorial on Network(x)

Home for the materials (notebooks, data, and commentary) associated to the introductory tutorial at the <a href="https://jointmathematicsmeetings.org/meetings/national/jmm2021/2247_intro">2021 JMM</a> Short Course on <a href = "https://meetings.ams.org/math/sc2021/meetingapp.cgi/Home/0"> Mathematical and Computational Methods for Complex Social Systems</a>. This tutorial is intended to provide a starting point for working with graphs and networks in Python and doesn't assume any specific programming background. The intended outline is approximately: 

* How do Jupyter notebooks work?
* Building and plotting Ego graphs
* Loading and processing larger graphs
* Centrality comparisons and null models
* Dynamics on networks

with the goal of providing lots of examples and opportunities for attendees to experiment.  

## Installation Instructions
The Python Install .pdf above provides some links and instructions for getting started with python on your own computer. If you would prefer not to install anything now, you can still follow along by either using the directions in that same .pdf for opening the notebooks with one of the cloud services or by simpling clicking the corresponding links above. For attendees with more experience or Python background the main short course webpage has an environment prepared for this material. 

## Notebooks
The main material we will be discussing in the tutorial is contained in the four Jupyter notebooks presented above. 

*  **0\_Jupyter\_Basics.ipynb** This notebook walks through the basic usage of Jupyter notebooks and how to interact with Python cells. It also includes examples of  basic arithmetic, variable assignment, data types, data structures,  and imports work in Python as well as a couple of exercises to check your understanding. If you already have some familiarity with Python, this one is safe to skip :)
* **1\_Ego\_Networks.ipynb** This notebook explores the basic properties of the Graph object in networkx by directly constructing ego networks. We will see how to access properties of the corresponding nodes and edges and visualize the networks using the `draw` function. 
* **2\_Social\_Networks.ipynb** In this notebook we will examine how to work with larger and more complex networks and evaluate the results of graph algorithms, including centrality calculations. The main motivating examples will show some of the common properties of social networks and how they differ from structured combinatorial graphs and random network models. 
* **3\_Network\_Dynamics.ipynb** In the final notebook we will put everything together, looking at how to model random walks, heat diffusion, and epidemiological disease spreading using networkx. 

<table>
  <tr><td>
<img src="https://github.com/vrdi/Networks-Breakout/blob/master/Day4/SIRplots/output.gif" width=300>
    </td><td>
<img src="https://github.com/vrdi/Networks-Breakout/blob/master/Day4/SIRplots/output2.gif" width=300>
        </td><td>
<img src="https://github.com/vrdi/Networks-Breakout/blob/master/Day4/SIRplots/output3.gif" width=300>
    </td></tr>
    <tr><td>
<img src="https://github.com/vrdi/Networks-Breakout/blob/master/Day4/SIRplots/proportions.png" width=300>
    </td><td>
<img src="https://github.com/vrdi/Networks-Breakout/blob/master/Day4/SIRplots/proportions2.png" width=300>
    </td><td>
<img src="https://github.com/vrdi/Networks-Breakout/blob/master/Day4/SIRplots/proportions3.png" width=300>

</td></tr>
</table>

## Other Resources

One hour isn't nearly enough time to explore all of the facets of networkx, so here are some good starting places if you are interested in learning more: 

* The NetworkX documentation is always a good starting spot and contains numerous examples in addition to the descriptions of functions and parameters: https://networkx.org/documentation/stable/index.html
* I taught a graduate class on Computational Tools for Complex Networks at WSU last semester and the course repository (with additional notebooks and exposition documents) can be found here: https://github.com/drdeford/Math_581_05 The notebooks don't have as much expository material as the ones for this tutorial session but do include more detailed computations.
* As a part of the 2019 VRDI, I taught a week of breakout sessions about networks with materials here: https://github.com/vrdi/Networks-Breakout
* If you are interested in trying out the GerryChain package for analyzing districting plans, you can find:
  * Mathematical background (some typos!): http://people.csail.mit.edu/ddeford/mcmc_intro.php
  * Templates and notebooks here: https://github.com/drdeford/GerryChain-Templates 
  * A bootcamp-style introduction here: https://github.com/vrdi/GerryChain-BootCamp

