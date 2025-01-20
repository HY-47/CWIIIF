# cwiiif

##Project Description
The multi-layer network studied in this article has the same nodes in each layer but may have different edges, which results in nodes with the same properties having different labels. Therefore, we have developed a technique for assigning different weights to network layers based on certain criteria. The layer weights can reflect the importance and impact of each layer of the network in terms of structure and dynamics. By using hierarchical weighting techniques, important nodes in multi-layer networks can be more effectively identified. However, hierarchical weighting techniques also face the following challenges:
-How to handle information loss;
-How to develop an appropriate weighting scheme;
-How to merge weighted results from different layers.

The existing methods include aggregating different layers together, uniformly weighting different layers, or weighting only based on some network structure attributes (such as node aggregation degree). Although these methods can identify important nodes, they still have shortcomings in dealing with issues such as information loss and differences in network layer influence.

To address these challenges, this paper proposes an algorithm called * * CWIIIF * * (Coupled Weighting for Inner and Inter layer Influence Factors) that couples the influence factors within and between layers to identify important nodes in multi-layer networks. This algorithm can more accurately identify the most influential nodes in multi-layer networks.

##Contribution
1. * * Propose a new set of intra - and inter layer influence parameters * *, and integrate different parameters as layer weight coefficients to reasonably allocate different weights to each layer of the network.
2. * * Establish a coupling equation * *, and map the intra layer influence vectors of nodes to scalar values based on layer weight coefficients, in order to rank the influence capabilities of nodes.
3. * * Propose coupling weighted intra - and inter layer influencing factors * *, which can accurately identify the most influential nodes in multi-layer networks through this algorithm.
4. * * Experimental verification * *: Experiments were conducted on nine real multi-layer network datasets, and the results showed that the CWIIIF algorithm is almost always the best performing method, verifying the effectiveness of this method in identifying influential nodes in multi-layer networks.

##Installation
python==3.7
Windows: 10
RAM: 16+ GB  
CPU: 4+ cores, 3.3+ GHz/core
GPU: 16+ GB


1. Clone repository:
```bash
git clone  https://github.com/HY-47/cwiiif.git
