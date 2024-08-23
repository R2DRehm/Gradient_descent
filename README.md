# Gradient Descent

Ce repository contient des notebooks qui explorent diverses méthodes d'optimisation, notamment la descente de gradient et le schéma d'Euler.

## Contenu

### 1. Gradient Descent

Le premier notebook présente l'algorithme de descente de gradient appliqué à diverses fonctions (convexes et non convexes), avec des exemples visuels et des explications. L'application se fait également sur une régression linéaire via l'estimation des paramètres par minimisation de la norme L2.

**Points abordés :**
- Descente de gradient classique pour une fonction convexe.
- Analyse de la convergence en fonction de la convexité de la fonction.
- Application pratique pour une régression linéaire ordinaire (OLS).
- Implémentation de la descente de gradient stochastique (SGD) pour minimiser une fonction coût.

Les visualisations incluent des graphiques 3D de la surface de la fonction objectif ainsi que des tracés des trajectoires d'optimisation.

### 2. Euler Scheme

Le second notebook explore le schéma d'Euler pour l'approximation de processus stochastiques.

**Points abordés :**
- Étude d'un potentiel double puits avec deux minimiseurs.
- Simulation des trajectoires de processus stochastiques via le schéma d'Euler.
- Comparaison de l'effet du bruit sur la convergence vers les minimiseurs locaux et globaux.
- Application du théorème ergodique pour interpréter les résultats en temps long.

Des graphiques sont fournis pour visualiser l'évolution des processus avec différents niveaux de bruit et points de départ.

## Structure des fichiers

- `Gradient_Descent.ipynb` : Implémentation de la descente de gradient et applications.
- `Euler_Scheme.ipynb` : Schéma d'Euler pour processus stochastiques.

## Exécution

Pour exécuter les notebooks, il vous suffit d'avoir Python installé avec les bibliothèques suivantes :

```bash
pip install numpy matplotlib scipy
