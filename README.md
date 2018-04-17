<<<<<<< HEAD
# RNAdecay
RNAdecay is an R package for modeling RNA abundance decrease after inhibition of transcription. Estimates for decay rate and decaying decay rate parameters are generated by maximum likelihood optimization for each gene/transcript. Up to four treatments can be compared with each other. This is accomplished by modeling all possible treatment effects on decay and decaying decay rates using separate models or model constraints. Best models are selected using AICc comparison. Workflows and functions are provided for decay data normalization, modeling, and visualization. This software was developed as part of a study of RNA decay pathway contributions to decay genome-wide in _Arabidopsis thaliana_ ( [Sorenson et al., 2018, Proceedings of the National Academy of Sciences 201712312](https://doi.org/10.1073/pnas.1712312115).

C++ compilation is required upon installation from source. Modeling makes use of the functionality of the TMB package to generate high performance dynamically linked libraries from objective functions coded in C++ for efficient computation. C++ source files for these functions are provided but must be compiled. Compiling C++ code requires a compiler be installed separatedly on your system (e.g., Rtools34 or later for Windows,  https://cran.r-project.org/bin/windows/Rtools/; Xcode comand line tools for Mac, http://railsapps.github.io/xcode-command-line-tools.html; R development package for Linux, r-base-dev). 

To install and use the development version of `RNAdecay` use the following commands on the R console: 
```{r}
install.packages("devtools")
devtools::install_github("reedssorenson/RNAdecay@R-v4.2")
library(RNAdecay)
```
=======
# RNAdecay
RNAdecay is an R package for modeling RNA abundance decrease after inhibition of transcription. Estimates for decay rate and decaying decay rate parameters are generated by maximum likelihood optimization for each gene/transcript. Up to four treatments can be compared with each other. This is accomplished by modeling all possible treatment effects on decay and decaying decay rates using separate models or model constraints. Best models are selected using AICc comparison. Workflows and functions are provided for decay data normalization, modeling, and visualization. This software was developed as part of a study of RNA decay pathway contributions to decay genome-wide in _Arabidopsis thaliana_ ([Sorenson et al., 2018, Proceedings of the National Academy of Sciences 201712312](https://doi.org/10.1073/pnas.1712312115)).

C++ compilation is required upon installation from source. Modeling makes use of the functionality of the TMB package to generate high performance dynamically linked libraries from objective functions coded in C++ for efficient computation. C++ source files for these functions are provided but must be compiled. Compiling C++ code requires a compiler be installed separatedly on your system (e.g., Rtools34 or later for Windows,  https://cran.r-project.org/bin/windows/Rtools/; Xcode comand line tools for Mac, http://railsapps.github.io/xcode-command-line-tools.html; R development package for Linux, r-base-dev). 

To install and use the development version of `RNAdecay` use the following commands on the R console: 
```{r}
install.packages("devtools")
devtools::install_github("reedssorenson/RNAdecay@R-v4.2")
library(RNAdecay)
```
>>>>>>> 6348625a4176d22804ebafedf857ed5938765d20
