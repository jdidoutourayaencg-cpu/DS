nom :JDIDOU TOURAYA 
apogée :22006654
groupe : CAC2
<img src="WhatsApp Image 2024-09-02 à 19.02.12_1a8b3747.jpg" style="height:464px;margin-right:432px"/>
# Jeu de données : Iris

**Date de mise à disposition :** 30 juin 1988  
**Source originale :** R.A. Fisher, 1936  

Le jeu de données **Iris** est un petit jeu de données classique, largement utilisé en **statistique** et en **apprentissage automatique**. Il est considéré comme l’un des tout premiers jeux de données employés pour évaluer les méthodes de **classification**.

---

## 🧬 Caractéristiques générales

| Propriété | Description |
|------------|-------------|
| **Type de données** | Tabulaires |
| **Domaine** | Biologie |
| **Tâche associée** | Classification |
| **Type de variables** | Réelles |
| **Nombre d’instances** | 150 |
| **Nombre de caractéristiques** | 4 |

---

## 🌸 Description du contenu

Chaque **instance** du jeu de données correspond à **une plante d’iris**.  
Les données se répartissent en **trois classes**, représentant trois espèces distinctes :

- *Iris setosa*  
- *Iris versicolor*  
- *Iris virginica*  

Chaque espèce comporte **50 échantillons**.  

Une des classes (*Iris setosa*) peut être **séparée linéairement** des deux autres, tandis que *Iris versicolor* et *Iris virginica* ne le sont **pas**.

---

## 🎯 Objectif du jeu de données

L’objectif est de **prédire l’espèce d’une plante d’iris** à partir de quatre mesures morphologiques :

1. Longueur du sépale  
2. Largeur du sépale  
3. Longueur du pétale  
4. Largeur du pétale  

La variable cible est la **classe de la plante (espèce d’iris)**.

---

## 🧾 Informations supplémentaires

Ce jeu de données est **simple** et **très utilisé à des fins pédagogiques** pour illustrer les concepts de classification et d’analyse statistique.  

Cependant, il existe **quelques différences mineures** entre cette version et celle présentée dans l’article original de Fisher :

- **35ᵉ échantillon** : `4.9, 3.1, 1.5, 0.2, "Iris-setosa"`  
  → Erreur dans la quatrième caractéristique.  
- **38ᵉ échantillon** : `4.9, 3.6, 1.4, 0.1, "Iris-setosa"`  
  → Erreurs dans la deuxième et la troisième caractéristiques.  

---

## 📚 Références

- Fisher, R.A. (1936). *The use of multiple measurements in taxonomic problems.*  
  Annals of Eugenics, 7(2), 179–188.  
