# Bayesian clustering of time series: replication and application

**Description**

This project explores Bayesian modeling techniques for classification and clustering, based on the paper “Model-Based Clustering of Multiple Time Series” by S. Fröhwirth-Schnatter and S. Kaufmann (2008). 
The aim is to use finite mixture models to group similar time series into clusters, while simultaneously estimating the parameters specific to each cluster. This project applies these techniques to real annual GDP data from several countries around the world.

**Methodology**
- Model-based clustering:
Time series are clustered according to their common dynamics, using econometric models specific to each cluster. Unlike traditional approaches, cluster membership is estimated directly during the inference procedure.

- Bayesian approach :
The methodology relies on MCMC simulations to:
    - Estimate clusters and their parameters simultaneously.
    - Optimize the number of clusters via marginal likelihoods.
    - Two types of prior are explored: a probability proportional to the relative size of the clusters (prior ignorance) and a logit prior based on series-specific information.

**Application**
Use of real data to demonstrate the model's ability to identify clusters corresponding to similar economic dynamics.

**Coding instruction**
1. Clone this repository:
```bash
git clone https://github.com/AminaManseur29/Bayesian_statistics_project.git
```
2. Navigate to the project folder:
```bash
cd Bayesian_statistics_project
```
3. Install the listed dependencies:
```bash
pip install -r requirements.txt
```
4. Run the jupyter notebook `Application_1.ipynb`

**References**

Sylvia Fröhwirth-Schnatter & Sylvia Kaufmann (2008) Model-Based Clustering of Multiple Time Series, Journal of Business & Economic Statistics, 26:1, 78-89, DOI: 10.1198/073500107000000106
