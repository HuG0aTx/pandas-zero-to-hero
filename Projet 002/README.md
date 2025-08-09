# Projet 2 — Analyse de ventes mensuelles

<br>

## 📚 Contexte
Vous travaillez comme analyste junior dans une PME qui vend des produits électroniques.  
On vous fournit un fichier contenant les ventes mensuelles de différents produits sur une année.  
Votre rôle est d’explorer et de préparer les données pour le service marketing, qui souhaite identifier les produits les plus performants et analyser les tendances saisonnières.

<br>

## ⚙️ Environnement de travail
- **Python** : 3.13  
- **IDLE** : PyCharm

<br>

## 🎯 Objectifs
- Maîtriser les opérations de base avec Pandas : importation, inspection, statistiques simples, regroupement, tris et création de colonnes.
- Réutiliser les notions vues au Projet 1.

<br>

## Fonctions Pandas à utiliser
- `pd.read_csv()`  
- `.head()`  
- `.shape`  
- `.sum()`  
- `.nunique()`  
- `.groupby()`  
- `.idxmax()` / `.idxmin()`  
- `.mean()`  
- `.sort_values()`  
- Création de colonnes avec `df['col'] = ...`

<br>

## 📄 Données  
- `Produit` : Nom du produit  
- `Categorie` : Catégorie du produit (Smartphone, Tablette, Accessoire, etc.)  
- `Mois` : Mois de vente (au format numérique 1-12)  
- `Ventes` : Nombre d’unités vendues  
- `CA` : Chiffre d’affaires en euros  

<br>

## 📋 Tâches
1. Charger le fichier CSV avec Pandas.  
2. Afficher les 5 premières lignes.  
3. Obtenir le nombre total de lignes et de colonnes.  
4. Calculer :  
   - Le total des ventes (`Ventes`)  
   - Le chiffre d’affaires total (`CA`)  
5. Afficher le nombre de produits distincts et de catégories distinctes.  
6. Trouver le produit avec le chiffre d’affaires annuel le plus élevé.  
7. Trouver la catégorie avec le chiffre d’affaires annuel le plus faible.  
8. Calculer le chiffre d’affaires moyen par mois pour chaque produit.  
9. Trier les produits par chiffre d’affaires total décroissant.  
10. Créer une nouvelle colonne `Prix_moyen` = `CA` / `Ventes`.

<br>

## 📦 Livrables
- Un script Python ou notebook `projet_XXX.ipynb` contenant le code
