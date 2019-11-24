# Network Analysis
# Using network analysis to study the molecular and regulatory mechanisms involved in RETT Syndrome
===============================================================================
## november 27, 2019
## Practical prepared by: Dr. Martina Summer-Kutmon and Dr. Lauren Dupuis
---------------------------------------------------------------------------------------------------

In this part, we want to show you different ways of how you can build biological network relevant for a biological research topic. 
Cytoscape has a lot more functionality and you are free to explore other apps in the project if you want to. 


### Build network for down-regulated RETT syndrome genes

#### **Step 1: Gene selection**
•	Import the dataset (RETT_vs_control_FC_filtered.txt) in Excel. 
•	Select the significantly down-regulated genes with a log2FC < -0.58 → filter the table by log2FC (<-0.58) and the P.Value (< 0.05). 
•	Copy the Ensembl IDs of the 128 genes.
#### **Step 2: Create PPI network for gene selection**
•	In Cytoscape, go to the Control Panel and select the STRING protein query (drop-down box left to search field) and paste the 133 gene 
names in the query field 

![Figure 4](https://github.com/LaurenDupuis/Helis-Academy-Omics-June-2019/blob/master/images/Figure_4_NA.png?raw=true)

•	Click on the search icon.
•	Cytoscape will create a network with 128 nodes and 172 edges

> **Question A** Are all nodes connected or do you see subnetworks or unconnected nodes?

•	Select the largest connected subnetwork (click shift and select the area of the subnetwork with the computer mouse). Go to File - 
New Network - From selected nodes, all edges.
•	A new network will be created only containing the largest connected subnetwork with 71 nodes and 161 edges.

#### **Step 2: Investigate the network properties of the network**
•	Go to “Tools → Network Analyzer → Network Analysis → Analyze Network...”
o	The network should be treated as an undirected network (protein-protein interactions, in general, do not have a direction)
•	This tool will calculate all network properties such as degree and betweenness for you.

> **Question B** What are node degree and node betweenness? Describe in your own words

> **Question C** Look at the “Node degree” and “Node betweenness” tab in Results panel of the Network Analyzer. How are node degree 
> and betweenness distributed in this network? Do the distributions make sense? Are there any interesting observations?

#### **Step 3: Create visualization to show disease score and degree**
•	In the NetworkAnalyzer result dialog, click on “Visualize Parameters”. Select the node degree as node color gradient (Map node color 
to → Select “Degree”) and the node betweenness as node size.

![Figure 5](https://github.com/LaurenDupuis/Helis-Academy-Omics-June-2019/blob/master/images/Figure_5_NA.png?raw=true)

> **Question D** Describe the overall network visualization. Large nodes have a high betweenness and the redder the node, the higher 
> the degree.

> **Question E** Can you find any hub nodes? (Hint: columns in Cytoscape are sortable by clicking on the header)
> TYROBP has highest degree. 







