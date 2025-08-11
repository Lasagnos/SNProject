# Report - Comparative Analysis of Interaction Layers in Criminal Networks

University project for the course *Social Network Analysys*, Università di Bologna, *y.2024/2025*

**Professor**: Saverio Giallorenzo

**Students**: Angelo Greco, Francesca Mazzetti, Gianpiero Giuseppe Tovo, Giuseppe Scafa

========
## Files and Directory info

In the `Dataset` folder, there are the networks obtained from the "Montagna" italian police operation. The 'Original' version is the one downloaded on [zenodo](https://zenodo.org/records/3938818), while the 'Cleaned' verison'is the one resulting from the execution of `DatasetCleaning.ipynb`.

========
## Files and Directory info
...

========
## Project requirements

The exam’s hand-in consists of a report in PDF format of **at most 5000 words** (also after revisions) — approximately, these correspond to 30k characters and 9–10 pages. *Reports that exceed the word count will be penalised*. The report shall detail the context, the problem/motivation, the data, the measures applied, and the results obtained (along with their qualitative interpretation). 

In the report, it is fundamental to indicate A) what phenomena are investigated, B) what measures are applied, and C) how each measure is interpreted to explain the related phenomenon.

Simplified example: A) we want to study which nodes are in the core of the studied network, B) we apply the k-core measure, C) k-core interprets core-periphery as the connected set of nodes where each is joined to at least k of the others, hence, we expect to find core nodes in the set with the highest k-value.

### Requirements checklist

* It is clear how many networks you are going to analyse and their shape (monomodal, bipartite, etc.).

* For each network in the study, it is clear what are the nodes and what are the edges (when there exists an edge between nodes) and whether these are oriented or not.

* You apply a wide-enough range and number of measures to describe the phenomena you want to study (measures include centrality, groups, clustering, redundancy, equivalences, homophily, small-worldness, scale freedom, cohesion, connectedness, compactness, triad census, core-periphery, etc.).

* For each measure, you explain why you apply it (what phenomenon you investigate with it) and what semantics the measure has for your network (e.g., on a transport network, you apply betweenness centrality to find its most important junctions, since it measures the extent to which a node lies on paths between other nodes).

* The effort behind the study is appropriate for the number of students behind the project. Suggestion: projects can consider applying the same study design on different networks, to compare these (qualitatively and/or quantitatively) through the results of the same array of measures.
