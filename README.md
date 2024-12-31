# Clustering bayésien des séries semporelles : réplication et application

**Description**




Ce projet explore les techniques de modélisation bayésienne pour la classification et le clustering, en s'appuyant sur l'article intitulé : "Model-Based Clustering of Multiple Time Series", de S. Fröhwirth-Schnatter et S. Kaufmann (2008). 
L'objectif est d'utiliser des modèles de mélange fini pour regrouper des séries temporelles similaires en clusters, tout en estimant simultanément les paramètres spécifiques à chaque cluster. Ce projet applique ces techniques aux données réelles du PIB annuel de plusieurs pays à travers le monde.

**Méthodologie**
- Clustering basé sur des modèles :
Les séries temporelles sont regroupées en fonction de leurs dynamiques communes, en utilisant des modèles économétriques spécifiques à chaque cluster. Contrairement aux approches traditionnelles, l'appartenance aux clusters est estimée directement lors de la procédure d'inférence.

- Approche bayésienne :
La méthodologie repose sur les simulations MCMC pour :
    - Estimer les groupes et leurs paramètres simultanément.
    - Optimiser le nombre de clusters via des vraisemblances marginales.
    - Deux types de prior sont explorés : une probabilité proportionnelle à la taille relative des clusters (prior ignorance) et un prior logit basé sur des informations spécifiques aux séries.

**Application**
Utilisation des données réelles pour démontrer la capacité du modèle à identifier des clusters correspondant à des dynamiques économiques similaires.

**Références**

Sylvia Fröhwirth-Schnatter & Sylvia Kaufmann (2008) Model-Based Clustering of Multiple Time Series, Journal of Business & Economic Statistics, 26:1, 78-89, DOI: 10.1198/073500107000000106
