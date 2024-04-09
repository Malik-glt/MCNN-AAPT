# MCNN-AAPT: 
The purpose of this research work is to combine pre-trained language models with deep-learning neural networks to identify functional classes of amino acids and peptides from other secondary active transporters and also to predict the same function class for a solute carrier protein (SLC). The purpose of this computational framework is to enhance our understanding of the functional roles of secondary active transporters and solute carrier proteins (SLCs), thus facilitating insights into their interaction with the processes in the cell and the diseases they cause. In order to increase our understanding of the complex world of cellular proteins and their relevance to human diseases, these techniques can help researchers improve their understanding of the complex world of cellular proteins.
## Fig. 1: Our Comprehensive Research Workflow: An Architectural Blueprint
![](https://github.com/Malik-glt/Decoding-Cellular-Functions/blob/main/Comprehensive%20Research%20Workflow.png)

## Methodology

There are two main sources for the dataset. The first set, covering secondary active transporters, including amino acids and peptides, was taken from the Universal Protein (UniProt) database [1]. As part of the second part of the study, the data were gathered from the Transporter Classification Database (TCDB), which is based on Pizzagalli et al. [2]. In order to extract complex features from protein sequences and fine-tune them based on our dataset after preprocessing, we used Prottrans, a previously trained protein language model [3]. As a result of this method, it was possible to capture all the encoded information within the sequences, allowing for more accurate predictive modeling to be done. We use convolutional neural networks (CNNs) in conjunction with a variety of window scanning methods in order to provide a comprehensive analysis of protein sequences. By considering multiple window sizes, this strategy allowed for a comprehensive evaluation of sequence patterns by considering multiple window sizes. A diagram of the complete architecture is shown in Figure 1, whereas a diagram of the classification model is shown in Figure 2.

## Fig. 2: Multiple-window scanning deep learning networks

![](https://github.com/Malik-glt/Decoding-Cellular-Functions/blob/main/Multiple-window%20CNN.png)

## References
1.	UniProt: the Universal Protein knowledgebase in 2023. Nucleic Acids Research, 2023. 51(D1): p. D523-D531.
2.	Pizzagalli, M.D., A. Bensimon, and G. Superti‐Furga, A guide to plasma membrane solute carrier proteins. The FEBS journal, 2021. 288(9): p. 2784-2835.
3.	Elnaggar, A., et al., ProtTrans: Toward Understanding the Language of Life Through Self-Supervised Learning. IEEE Trans Pattern Anal Mach Intell, 2022. 44(10): p. 7112-7127.
