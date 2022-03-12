# Network reaction norms: taking into account network position and plasticity in response to environmental change

To better consider variation in an individual node's position and response (i.e., plasticity) to environmental change we introduce the network reaction norm (NRN) approach. 

As an illustrative example we used behavioural data on chacma baboons, collected over a period of seven years, to construct a time series of networks using a moving window approach. We used these data with NRN to quantify both the consistency with which individuals maintained social behaviour (node strength) and central positions (eigenvector centrality) within the social network when faced with changes in their environment.
    
We also use simulated data to highlight the benifits and limitations of an network reaction norm (NRN). For example, below is a simulated network where only the red edge changes in response to food availability.

![net_sim](https://github.com/tbonne/NRN/blob/main/code/figs/g16_small.png) 

*Figure 1: Two cluster network used to simulate data for a test case of the network reaction norm approach. The grey edges are fixed, while the red dashed edge is made dependent on the availability of food.*

We can then fit a network reaction norm to quantify how node strength and eigenvector centrality changes in response to food availabilty.

![net_nrn](https://github.com/tbonne/NRN/blob/main/code/figs/Fig_cov_NRN_str_eigen_sim.png)
*Figure 2: Network reaction norms applied to the simulated example: a) changes in mean strength of each node in response to food availability, b) changes in mean eigenvector for each node in response to food availability*

The code and data are available in the code folder. Please feel free to email me at tyler.bonnell@gmail.com if you have any questions.
