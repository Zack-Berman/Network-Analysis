## Network Analysis of Transcriptional Regulation Systems in E. coli

All living cells are the product of gene expression systems involving the controlled expression of thousands of genes.  Genes can be regulated as a group, and groups of genes that are regulated together are known as operons. Transcriptional regulation networks control how cells organize and orchestrate gene expression by utilizing proteins known as transcription factors. In this network, the nodes are operons and each edge is directed from an operon that encodes a transcription factor to an operon that it directly regulates.

This analysis is done with the goal of locating key operons and unique network motifs (unique clusters) which can highlight key biological pathways and previously unknown interactions.

![Alt Text](https://github.com/Zack-Berman/Network-Analysis/blob/master/TF%20Network.png "Transcription Factor Network")

## Dependencies

- python
- pandas
- numpy
- scipy
- sklearn
- matplotlib
- seaborn
- networkx
- pyvis

## Acknowledgements 

The data for this project comes from the Weizmann Institute of Science. To view and download the data for yourself, or to learn more, [click here](http://www.weizmann.ac.il/mcb/UriAlon/e-coli-transcription-network).
