# Analyse de la Production d'Énergie Solaire en Tunisie

## 🌞 Description

Ce projet consiste en une **analyse approfondie de la production solaire et des conditions météorologiques** dans différentes stations en Tunisie.  
L'objectif est de comprendre les facteurs qui influencent la production d'énergie solaire et le niveau de batterie, et de fournir des recommandations pour optimiser les installations photovoltaïques.

Le rapport a été développé avec **RMarkdown** et fournit des visualisations interactives pour explorer les données.

---

## 📂 Contenu du Projet

- `donnees_cleaned.csv` : jeu de données principal (mesures météo, rayonnement solaire, production, batterie)
- `solar_analysis.Rmd` : fichier RMarkdown contenant l'analyse complète
- `README.md` : ce fichier explicatif

---

## 🛠️ Technologies et Packages Utilisés

- **Langage** : R
- **Packages principaux** :
  - `tidyverse` : manipulation de données et visualisations
  - `lubridate` : gestion des dates et heures
  - `plotly` : graphiques interactifs
  - `DT` : tableaux interactifs
  - `corrplot` : visualisation des corrélations
  - `scales`, `knitr` : mise en forme et publication

---

## 📊 Analyse Réalisée

1. **Exploration des données**
   - Statistiques descriptives
   - Distribution des variables clés
   - Identification des valeurs extrêmes et top journées

2. **Analyse temporelle**
   - Profil horaire moyen de production
   - Comparaison saisonnière et mensuelle
   - Identification des meilleures périodes pour la production

3. **Analyse des corrélations**
   - Identification des variables influentes sur la production solaire
   - Relations entre production, rayonnement, température et humidité

4. **Comparaison des stations**
   - Classement des stations les plus productives
   - Analyse des critères géographiques et climatiques

5. **Analyse des batteries**
   - Corrélation production → niveau batterie
   - Fenêtre optimale de charge

6. **Modélisation prédictive**
   - Régression linéaire simple (Rayonnement seul)
   - Régression linéaire multiple (Rayonnement + Température)
   - Visualisation Observé vs Prédit

---

## 📌 Conclusions et Recommandations

- La **production dépend principalement du rayonnement solaire**
- **Température et humidité** jouent un rôle secondaire
- **Fenêtre optimale de production** : 10h à 14h
- **Meilleure saison** : été (juin-juillet)
- **Station la plus performante** : `nom_station` (référence aux données)
- **Recommandations** :
  - Dimensionner les batteries pour absorber les pics
  - Planifier les usages énergivores pendant les heures de production maximale
  - Prioriser les nouvelles installations dans les zones à fort rayonnement et faible humidité

---