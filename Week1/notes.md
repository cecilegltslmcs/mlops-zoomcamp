## Introduction

MLOps : ensemble de bonnes pratiques et d'outils pour mettre des modèles de ML en production.
- Design : Est-ce que mon problème a besoin d'utiliser du ML
- Entrainement
- Opération : mise à disposition du modèle ; déploiement
MLOps aide à automatiser ces étapes, à faire en sorte que les résultats soient reproductibles en un clic ou qu'on puisse déployer un modèle aisément.

 - Découpage du notebook en plusieurs parties : 
	- Load & Prepare Data
	- Vectorize
	- Entraînement (utilisation d'experiment tracker & model registry - Week 2)
=> Utilisation de ML Pipeline pour chaque étape (Week 3)

- Serving le modèle pour mise à disposition pour les usagers (Week 4)
- Mise en place de monitoring pour s'assurer que le modèle fonctionne bien (Week 5) 

## Maturité

Les différents niveaux de maturité sont issus de cet article de Microsoft : [MLOps Maturity model](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/guide/mlops-maturity-model)