# Reconnaissance de Formes 3D avec les Réseaux de Neurones Graphiques (GNN)

## Description
Ce projet a pour objectif d'explorer l'application des **réseaux de neurones graphiques (GNN)** pour la **reconnaissance de formes 3D**. Il s'agit d'un modèle capable de traiter des objets en 3D, représentés sous forme de graphes, et de classer ou d'identifier ces objets selon différentes formes géométriques.

Les **graphes** sont utilisés pour représenter les objets en **3D**, où **les nœuds** représentent des caractéristiques des objets (par exemple, des points de surface) et **les arêtes** représentent les relations spatiales entre ces points. Cette approche permet de traiter les objets complexes de manière efficace, en capturant les dépendances entre les différentes parties de l'objet.

Ce projet peut être appliqué dans des domaines comme la **robotique**, la **modélisation 3D** et la **reconnaissance d'objets** dans des environnements virtuels ou réels.

## Table des Matières
- [Contexte](#contexte)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Fonctionnalités](#fonctionnalités)
- [Architecture du Modèle](#architecture-du-modèle)
- [Exemples](#exemples)
- [Contributeurs](#contributeurs)
- [Licence](#licence)

## Contexte
Les **réseaux de neurones graphiques (GNN)** sont des modèles d'apprentissage profond capables de traiter des données structurées sous forme de graphes. Dans ce projet, nous appliquons les **GNN** pour analyser des objets 3D et les reconnaître en utilisant des graphes comme représentation des objets.

Les **formes 3D** sont représentées sous forme de nuages de points ou de maillages, et chaque point ou élément du maillage est un nœud dans le graphe. Les relations spatiales entre les différents points sont capturées sous forme d'arêtes, permettant au modèle d'apprendre les interactions entre les différentes parties de l'objet.

## Installation

### Prérequis
Avant de commencer, assurez-vous d'avoir installé Python 3.6 au moins ainsi que les bibliothèques suivantes :
- **PyTorch**
- **DGL** (Deep Graph Library)
- **Numpy**
- **Matplotlib**
- **Scikit-learn**

### Installation des dépendances
Pour installer les dépendances, exécutez la commande suivante dans votre terminal :

```bash
pip install torch dgl numpy matplotlib scikit-learn
```


## Auteurs
- **Takouchouang Fraisse Sacre**
- **Collaborateur : Dr Vinh** 

