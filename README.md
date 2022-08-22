# FraserTojeiroChittendenPaper
Release repository of all the code, figures and notebooks used to generate the GMM clusters in the paper: . Email tsfraser@uwaterloo.ca for additional questions regarding data access, code, etc.


Notebook is roughly divided into sections that produce figures based off of the original star formation and metallicity histories as well as their smoothed variants. For reasons explained in the paper, we used the smoothed histories instead, as they provide a more robust basis.

Additional analysis in the form of testing out and comparing the mean mass weighted metallicity age, the mass weighted stellar and halo age are also included. The overlap fraction, a measure of how much a population from n clusters migrates to the n+1th cluster, is also computed, to help characterize what happens when the number of clusters in our parameter space is increased.


Note, that in order to run this code, you either need to use the publicly available data from IllustrisTNG, or you can email me for the files, as they are far too big for github, even in their compressed form (~500Mb). I have included the notebook used to generate the star formation histories as an exemplar.


If parts the PCA component plots look flipped in comparison to what you see in the paper, it should be noted that we flipped them to ensure they are easier to read+identify. Components are unique up to the choice of sign, so this process does not meaningfully affect the presented result.


If there are any questions or concerns regarding the data or code in this repository, do not hesitate to contact me! I will be updating and maintaining this repo.

