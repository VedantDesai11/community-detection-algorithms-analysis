# Community Detection Algorithms Analysis
Analyzing and comparing different community detection algorithms on different types of graphs

## How to use
* Place input graphs in Graphs directory.
* Update BASE_DIR in InputConfig and AnalysisConfig(Analysis Directory).
* Place query in AnalysisConfig. 
	* Query Format - SLC, CommunityAlgorithmName , Layer-name
	* Algorithms
		* infomap
		* louvain
		* multilevel
		* fast greedy
		* walktrap
		* leading eigenvector
	* layer names example: A, D, M
* Run using readInput.py
* Select InputConfig file and AnalysisConfig file. 
* Check results in Analysis folder under corresponding expression directory.

## Example results are place in Analysis directory

Comparison results printed on screen. Metrics used for comparison:
* Jaccard 
* Clustering Coefficient
* Modularity
* Time taken
* Number of Communities
* NMI

## Packages used
* igraph
* networkx
* infomap
