# Visualisation-interactive-du-PIB-des-tats-Unis-1947-2015-avec-D3.js
# 📊 Visualisation interactive du PIB des États-Unis (1947–2015)

Ce projet est une visualisation de données réalisée avec **D3.js**, illustrant l’évolution du **Produit Intérieur Brut (PIB)** des États-Unis entre 1947 et 2015. Il s'agit d'un défi du programme **FreeCodeCamp - Data Visualization Certification**.

---

## 🚀 Fonctionnalités

- Graphique à barres responsive et interactif
- Tooltip dynamique au survol des barres
- Axes générés automatiquement avec les ticks via D3
- Données chargées en temps réel depuis une source externe

---

## ✅ Spécifications techniques

Projet conforme aux 13 critères suivants :

1. Le graphique possède un titre avec `id="title"`
2. Il y a un axe des abscisses (`id="x-axis"`) et un axe des ordonnées (`id="y-axis"`)
3. Les deux axes comportent des ticks (`class="tick"`)
4. Chaque barre a la classe `bar`
5. Chaque barre contient les attributs `data-date` et `data-gdp`
6. L’ordre des données est respecté dans le rendu
7. La hauteur des barres est proportionnelle aux données de PIB
8. Les barres sont alignées avec les valeurs des axes
9. Un tooltip s’affiche au survol (`id="tooltip"`)
10. Le tooltip contient un `data-date` correspondant

---

## 📦 Technologies utilisées

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **D3.js v7**
- **FreeCodeCamp Testable Projects CDN**

---

## 📁 Données utilisées

Données publiques fournies par FreeCodeCamp :  
📂 [GDP-data.json](https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json)

---

## 🧪 Tester le projet

Si tu veux tester le projet avec les tests FreeCodeCamp :

1. Ouvre le fichier HTML dans un navigateur
2. Le script suivant est requis pour lancer les tests :

```html
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
