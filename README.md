# snoKARR-seq
Scripts to process and analyze snoKARR-seq data

Ref: Liu et al., SnoRNA-facilitated protein secretion revealed by transcriptome-wide snoRNA target identification. (2024). Cell.

| package | source | version |
|---|---|---|
|`Python`| 	-	|v 3.9.12|
|`numpy`	|PyPI|	v 1.24.3|
|`pandas`	|PyPI|	v 2.0.2|
|`matplotlib`	|PyPI|	v 3.7.1|
|`cigar`	|PyPI|	v 0.1.3|
|`pysam`	|PyPI|	v 0.21.0|
|`pybedtools`	|PyPI|	v 0.9.0|
|`Coolbox`	|PyPI|	v 0.3.8|
|`seaborn`	|PyPI|	v 0.11.2|
|`pybedtools`	|PyPI|	v 0.8.1|
|`networkx`	|PyPI|	v 2.8.1|
|`scikit-learn`	|PyPI|	v 1.1.1|
|`scipy`	|PyPI|	v 1.10.1|
|`biopython`	|PyPI|	v 1.80|
|`GSEApy`	|PyPI|	v 1.1.0|


`snoRNA_rRNA_analysis.ipynb` is the notebook used to analyze snoRNA-rRNA interactions

`snoKARR_map_processing_clustering.ipynb` is the notebook used to map snoRNA-non-rRNA interactions and process the chimeric reads for clustering

`DG_sim.ipynb` is the notebook for DG clustering, based on a published work: [Zhang et al. 2022 Genome Research](https://genome.cshlp.org/content/early/2022/03/24/gr.275979.121.abstract) (https://github.com/zhipenglu/CRSSANT).

`RNAplex_vaRNA_combo.ipynb` is the notebook for [RNAplex](https://www.tbi.univie.ac.at/RNA/RNAplex.1.html) duplex structure prediction and [VARNA](https://varna.lisn.upsaclay.fr/index.php?lang=en&page=home&css=varna) RNA structure visualization
