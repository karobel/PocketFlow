# 💰 MonBudget

> Application web de gestion de finances personnelles, inspirée de WeStash — sans inscription, sans serveur, tout reste sur ton appareil.

![HTML](https://img.shields.io/badge/HTML-single%20file-orange?style=flat-square)
![CSS](https://img.shields.io/badge/CSS-vanilla-blue?style=flat-square)
![JS](https://img.shields.io/badge/JS-vanilla-yellow?style=flat-square)
![Mobile](https://img.shields.io/badge/mobile-friendly-green?style=flat-square)

---

## ✨ Fonctionnalités

- **🏠 Tableau de bord** — solde du mois, revenus, dépenses, navigation par mois
- **📋 Transactions** — ajout, suppression, filtrage par type (revenus / dépenses), regroupement par mois
- **🎯 Budgets** — définir un plafond par catégorie avec barre de progression
- **📊 Statistiques** — camembert de répartition des dépenses, histogramme revenus vs dépenses sur 6 mois, taux d'épargne
- **💼 Épargne** — objectifs avec barre de progression, date cible, ajout de montants

## 📱 Design

Inspiré de l'application **WeStash** : fond gris clair, cartes blanches arrondies, accent orange doré, barre de navigation en bas. Entièrement responsive et optimisé pour mobile.

## 🚀 Installation

Aucune installation requise. C'est un fichier HTML unique.

```bash
git clone https://github.com/ton-username/monbudget.git
cd monbudget
# Ouvre finances.html dans ton navigateur
open finances.html
```

Ou héberge-le gratuitement sur **GitHub Pages**, **Netlify** ou **Vercel** en un clic.

## 🗂️ Structure

```
monbudget/
└── finances.html   # L'application entière (HTML + CSS + JS)
```

## 💾 Données

Toutes les données sont stockées localement dans le **localStorage** de ton navigateur. Rien n'est envoyé sur un serveur. Tes finances restent privées.

> ⚠️ Vider le cache du navigateur supprime les données. Pense à exporter régulièrement si tu l'utilises au quotidien.

## 📦 Dépendances externes

- [Chart.js 4.4](https://www.chartjs.org/) — graphiques (chargé via CDN)
- [Google Fonts — Nunito](https://fonts.google.com/specimen/Nunito) — typographie

## 🛠️ Catégories disponibles

🛒 Courses · 🏠 Loyer/Crédit · 💡 Factures · 🚗 Transport · 🍽️ Resto · 🎬 Loisirs · 💊 Santé · 💅 Beauté · 🛍️ Shopping · 💰 Épargne · 💼 Salaire · ✨ Autre

## 📄 Licence

MIT — libre d'utilisation, de modification et de distribution.
