# Analyse_marche_tech
Une analyse des marchés tech vis a vis des formations versus emplois et entreprises tech fr vs ocde

# Projet 2 – Analyse du marché tech français

Ce projet vise à analyser l’adéquation entre l’offre de formations tech en France et les compétences actuellement demandées sur le marché du travail. En parallel on regarde aussi le positionnement des entreprises tech vs des entreprises de l'ocde afin de mieux comprendre leurs positionnements.

## 🎯 Objectifs

- Identifier les **technologies les plus demandées** en France à partir d’offres d’emploi
- Classer les **formations tech** selon plusieurs critères : technologies couvertes, notes d'avis, retour à l'emploi
- comparer les salaires moyens entre 4 pays: France, Suisse, Italieet Irlande
- Créer une base de données centralisée et **visualisable dans Metabase**

## 📁 Données utilisées

- `top_competences.csv` → importé dans PostgreSQL (`top_competences`)
- `top_formations.csv` → importé dans PostgreSQL (`top_formations`)
- Les données proviennent d’un **scraping sur Welcome to the Jungle** + avis agrégés (Trustpilot, Google)
- Des données viennent de ma V.1 sur les formations tech
- Le comparatif des salaires vient de relevés sur google avis.

## 🛠️ Stack technique

- **Python** (scraping & nettoyage)
- **PostgreSQL** (stockage)
- **Metabase** (visualisation)
- **DBeaver** (gestion DB)

## 📊 Visualisations produites

- Bar chart des **10 compétences les plus demandées**
- Tableau dynamique des **top formations tech**, filtrable par métier

## 📌 Résultats clés

- Les technologies les plus demandées sont : Python, JavaScript, SQL, etc.
- Certaines formations se démarquent par leur pertinence vis-à-vis des attentes du marché

## 👤 Auteur

**Romain Gac**, en formation Data Analyst, certifié Coursera.  
Projet réalisé dans le cadre de la construction d’un portfolio professionnel
