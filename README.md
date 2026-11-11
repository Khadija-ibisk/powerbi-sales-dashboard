# 📊 Dashboard Power BI – Analyse des ventes

![Power BI](https://img.shields.io/badge/Power%20BI-DAX-F2C811?logo=powerbi&logoColor=black)
![Modèle](https://img.shields.io/badge/mod%C3%A8le-en%20%C3%A9toile-blue)

Projet de **Business Intelligence** (Bachelor 3, Ynov Campus) : transformer des fichiers CSV bruts en un
**tableau de bord interactif** pour piloter la performance commerciale.

## 🎯 Objectifs

- Importer et préparer les données de ventes (Power Query)
- Construire un **modèle en étoile** performant
- Développer des **mesures DAX** (chiffre d'affaires, quantités, KPI de croissance)
- Concevoir un dashboard orienté prise de décision

## 🧱 Modèle de données

```
                 Temps (Dim_Date)
                        │
 Clients ─── Ventes (table de faits) ─── Produits
                        │
                 Régions (Dim_Region)
```

| Table | Rôle |
|---|---|
| `Ventes.csv` | Table de faits : lignes de vente, quantités, montants |
| `Clients.csv` | Dimension clients (segment) |
| `Produits.csv` | Dimension produits (catégorie, prix) |
| `Regions.csv` | Dimension géographique |
| `Temps.csv` | Calendrier (année fiscale 2023) |

## 📌 Résultats clés

| Indicateur | Résultat | Impact métier |
|---|---|---|
| Chiffre d'affaires | **732 K** sur **500 ventes** | Vue consolidée de la performance |
| Meilleure région | **Casablanca, ~33 % du CA** | Prioriser les investissements marketing sur cette zone |
| Tendance mensuelle | Pics saisonniers marqués | Anticiper les stocks avant les pics |
| Catégories | Clothing, Food, Electronics équilibrées ; Electronics en tête en valeur | Mettre en avant les produits à forte valeur |

## 📁 Contenu

```
├── Analyse_des_ventes.pbix   # rapport Power BI (à ouvrir avec Power BI Desktop)
├── data/                     # sources CSV du modèle
└── docs/                     # support de soutenance
```

## ▶️ Ouvrir le projet

1. Installer [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (gratuit).
2. Ouvrir `Analyse_des_ventes.pbix`.
3. Si besoin, mettre à jour le chemin des sources : **Transformer les données → Paramètres de la source de données** → dossier `data/`.

## 🛠️ Compétences

`Power BI` · `Power Query` · `DAX` · `modélisation en étoile` · `data storytelling`

---
Khadija Ibisk – Bachelor Dev IA & Data Engineering, Ynov Campus
