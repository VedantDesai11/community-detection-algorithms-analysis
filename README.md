# CommunityDetectionAlgorithmsAnalysis
Analyzing and comparing different community detection algorithms on different types of graphs

1)Place input graphs in Graphs directory.
2)Update BASE_DIR in InputConfig and AnalysisConfig(Analysis Directory).
3)Place query in AnalysisConfig. Format : SLC,<communityAlgo>,<layer-name> 
	algorithms called: infomap, louvain, edgebetweenness
	layer names example: A, D, M
4)Run using readInput.py
5)Select InputConfig file and AnalysisConfig file. 
6)Check results in Analysis folder under corresponding expression directory.