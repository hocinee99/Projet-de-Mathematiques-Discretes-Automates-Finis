# Projet Automates Finis - Mathématiques Discrètes (LU2IN005)

**Note obtenue : 20/20** 🏆  
**Université :** Sorbonne Université (Année 2024-2025)

## 👥 Membres du Binôme
- **Hocine BOUKHEMZA** (Numéro étudiant : 21327665)
- **Walid KAOUANE** (Numéro étudiant : 21314924)

---

## 📝 Présentation du projet
Ce projet a été réalisé dans le cadre de l'UE LU2IN005 (Mathématiques Discrètes). L'objectif principal de ce TME était de programmer en Python les algorithmes fondamentaux sur les automates finis vus en cours et en TD, en s'appuyant sur des structures de données orientées objet fournies.

## ⚙️ Fonctionnalités implémentées
Le projet est structuré autour de trois classes principales : `State` (état), `Transition` et `Automate`. Les algorithmes et méthodes que nous avons programmés et testés couvrent les domaines suivants :

1. **Prise en main et manipulation** : 
   - Création et modification dynamique d'automates (ajout/suppression d'états et de transitions).
   - Recherche d'états successeurs (`succElem`).
   - Création d'automates depuis une description textuelle (fichiers `.txt`).
2. **Exercices de base** : 
   - Vérification des propriétés des automates (déterminisme et complétude).
   - Algorithmes de complétion.
3. **Déterminisation** : 
   - Implémentation de l'algorithme de déterminisation (transformation d'un Automate Fini Non-Déterministe en un Automate Fini Déterministe).
4. **Opérations sur les langages acceptés** :
   - **Opérations ensemblistes** : Intersection, Union et Complémentation.
   - **Opérations rationnelles** : Concaténation et Étoile de Kleene.
5. **Visualisation** : 
   - Affichage graphique des automates via la bibliothèque `Graphviz` pour valider visuellement nos algorithmes.

---

## 📂 Structure des fichiers
- `automate_etudiant.ipynb` : Le Notebook Jupyter contenant l'ensemble de notre code, les algorithmes implémentés et toutes nos cellules de tests dédiées.
- `state.py`, `transition.py`, `automateBase.py` : Les bibliothèques contenant les définitions des structures de données (fichiers fournis non modifiés).
- `ExemplesAutomates/` : Répertoire contenant les fichiers `.txt` servant aux tests de construction d'automates.

---

## 🚀 Utilisation
### Prérequis
- Python 3
- Jupyter Notebook
- La bibliothèque graphique `Graphviz` installée pour l'affichage visuel des automates via la méthode `show()`.

### Exécution
1. Placez tous les fichiers (le notebook, les fichiers python fournis et le dossier `ExemplesAutomates`) dans un même répertoire.
2. Ouvrez le fichier `automate_etudiant.ipynb` avec Jupyter Notebook.
3. Exécutez la première cellule pour charger les classes (`State`, `Transition`, `Automate`).
4. Déroulez les cellules de test de haut en bas pour observer l'exécution de nos fonctions et le rendu graphique de nos automates.
