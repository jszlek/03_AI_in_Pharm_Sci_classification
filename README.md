# 03_AI_in_Pharm_Sci_classification
Classification example in Python
__Author__: Jakub Szlęk (j.szlek[at]uj.edu.pl)

Requested libraries:
`pandas`, `numpy`, `scikit-learn`=>0.21.3, `seaborn`, `matplotlib`
Tested under Python=3.6.5
Data set after:
Mansouri, K., Ringsted, T., Ballabio, D., Todeschini, R., Consonni, V. (2013). Quantitative Structure - Activity Relationship models for ready biodegradability of chemicals. Journal of Chemical Information and Modeling, 53, 867-878 (https://pubs.acs.org/doi/pdf/10.1021/ci4000213)

In order to run on `conda`:
 1) Open terminal in the repository folder (in Windows click `start` and start typing `Anaconda prompt`)
 2) Type `conda create --name classif python=3.6.5 numpy pandas matplotlib seaborn scikit-learn nb_conda_kernels jupyter`
 3) After installation type `conda activate classif` to activate Python virtual environment
 4) Then type `jupyter-notebook` to run the `jupyter` server
