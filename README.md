# MSc-Thesis
## Master Information Studies: Data Science track

### Beyond the Fold: Exploring Uniform Random Sampling in HP Model Protein Folding
*Author: Jesse Kommandeur, University of Amsterdam, submitted in partial fulfilment for the degree of master of science*

**Abstract**: Protein folding is a fundamental process in biology, with profound implications for understanding biological functions and diseases. The identification of native and stable protein conformations is an integral aspect of this process but is time-consuming to do experimentally, leading researchers towards computational and algorithmic methodologies such as the HP model. In light of the complexities associated with accurately simulating the process of folding proteins, the focus has therefore often shifted towards (meta)heuristics. However, these methods face limitations due to the prevalence of invalid conformations in the search space, posing challenges in achieving uniformly random and unbiased initial populations for algorithms. This paper addresses these issues and raises a twofolded question. The first involves the potential of ensuring uniform randomness in initial populations of metaheuristic algorithms to not bias protein folding simulation and optimization. The second aspect explored the impact of five sampling techniques on the diversity and quality of these initial populations. Experimental results demonstrate a clear disparity in the effectiveness of different sampling methods for generating initial protein conformations. The two break sampling methods require extensive resampling for longer proteins, whereas both backtracking methods, though less dependent on resampling, face computational challenges with increased protein lengths. This highlights a fundamental trade-off between the efficiency of these methods and their adaptability to larger protein sequences. Additionally, this paper identifies a crucial gap in the field: the absence of effective benchmarking methods for assessing the uniform randomness of longer protein sequences. As we progress in sampling proteins of realistic lengths, the exponential growth in possible conformations poses a formidable challenge in assessing these models and approaches. As we observe these challenges of finding uniformly random and unbiased initial populations of conformations, the empirical evidence could suggest that protein folding might be harder than other problems within their NP-hard class.

**Keywords**: Protein Folding, Uniform Random Sampling, Break Sampling, Backtracking, Solution Space Sampling

<p align="center">
<img src="https://github.com/jessekommandeur/Protein-Folding/blob/main/Thesis/fcover.png" width="600" height="600">



The source code of this Protein Folding research project is hosted on GitHub and Kaggle using the MIT License. Under the public Protein Folding repository, I have several code repositories:
- [Algorithms](https://github.com/jessekommandeur/Protein-Folding/edit/main/Code) - This Github folder contains all notebooks with algorithmic code for each of the experiments.
- [Data](https://github.com/jessekommandeur/Protein-Folding/edit/main/Data) - This folder contains all generated datasets up to 25MB that were used in this research project.
- [Data](https://www.kaggle.com/datasets/jessekom/protein-folding-hp-model) - This page contains all generated datasets up to 7GB that were used in this research project.
- [Timing data](https://github.com/jessekommandeur/Protein-Folding/edit/main/Timing_Data) - This Github folder contains the notebook and data that was used to time the experiments. 
- [Validation](https://github.com/jessekommandeur/Protein-Folding/edit/main/Validation) - This Github folder contains all notebooks with validation statistics and code for each of the experiments. 
- [Visualization](https://github.com/jessekommandeur/Protein-Folding/edit/main/Visualization) - This Github folder contains all notebooks that were used to visualize the data of the experiments. 
- [Thesis](https://github.com/jessekommandeur/Protein-Folding/edit/main/Thesis) - Here you can view and/or read the thesis itself. It’s also available on: 
- [Presentation slides](https://github.com/jessekommandeur/Protein-Folding/tree/main/Presentation%20slides) - These are all presentations that were given during the weekly thesis sessions under the supervision of Daan van den Berg at the VU Campus in Amsterdam
