# RNAdecay
R package for modeling RNA abundance decrease after inhibition of transcription. Estimates for decay rate and decaying decay rate parameters are generated by maximum likelihood optimization for each gene/transcript. Up to four treatments can be compared with each other. This is accomplished by modeling all possible treatment effects on decay and decaying decay rates using separate models or model constraints. Best models are selected using AICc comparison. Workflows and functions are provided for decay data normalization, modeling, and visualization. This software was developed as part a study of RNA decay rate pathway contributions to decay genome-wide in Arabidopsis thaliana (Sorenson et al., 2018).
