# Projet 1 — Lecture et exploration d’un fichier CSV avec Pandas

<br>

## 📚 Contexte
Vous travaillez pour une papeterie-informatique qui souhaite commencer à analyser ses ventes.  
Vous disposez d’un fichier CSV `ventes_produit.csv` contenant les données de ventes des derniers mois.  
Avant toute analyse, il est nécessaire d’importer et d’explorer ce fichier afin de vérifier sa structure et la qualité des données.

<br>


## ⚙️ Environnement de travail
- **Python** : 3.13  
- **IDLE** : PyCharm

<br>

## 🎯 Objectifs
- Charger un fichier CSV avec `pd.read_csv()`
- Utiliser les méthodes d’exploration de base de Pandas
- Comprendre la structure et les types de données d’un DataFrame
- Détecter la présence éventuelle de valeurs manquantes

<br>

## 🛠 Fonctions Pandas à utiliser
- `pd.read_csv()`
- `.head()`
- `.tail()`
- `.info()`
- `.describe()`
- `.shape`
- `.columns`
- `.dtypes`
- `.isna().sum()`

<br>

## 📄 Données
Le fichier `ventes_produit.csv` contient 50 lignes et 6 colonnes :

| Colonne        | Description                                      |
|----------------|--------------------------------------------------|
| id             | Identifiant unique de la vente                   |
| produit        | Nom du produit vendu                             |
| categorie      | Catégorie du produit (Papeterie, Informatique)   |
| prix_unitaire  | Prix unitaire du produit en euros                |
| quantite       | Quantité vendue                                  |
| date_vente     | Date de la vente au format AAAA-MM-JJ            |

<br>

## 📋 Tâches
1. **Charger** le fichier CSV dans un DataFrame nommé `df`.
2. **Afficher** :
   - Les 3 premières lignes
   - Les 2 dernières lignes
3. **Lister** :
   - Le nombre total de lignes et de colonnes
   - Les noms de colonnes
4. **Afficher** :
   - Le type de chaque colonne
   - Les statistiques descriptives pour les colonnes numériques
5. **Vérifier** la présence de valeurs manquantes.
6. **Rédiger** un court résumé de vos observations dans le notebook.

<br>

## 📦 Livrables
- Un script Python ou notebook `projet_001.ipynb` contenant le code
