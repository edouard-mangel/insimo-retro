---
# doc pour le config de cet encart : https://sli.dev/custom/#headmatter
theme: default
addons: []
# title of your slide, will inferred from the first header if not specified
title: "Insimo-retro"
# titleTemplate for the webpage, `%s` will be replaced by the slides deck's title
titleTemplate: "%s - 27/06/2025"
author: Edouard MANGEL
# keywords field for exported PDF, comma-delimited
keywords: "slidev, slides, presentation, vue, vuejs, insimo-retro, insimo, retro"
exportFilename: "Insimo-retro.pdf"

layout: cover
class: sc_bg

defaults:
  transition: slide-left|slide-right
---

# Refonte du hub de simulateurs par La Crafterie Tech
<br>

## Rétrospective
<br>


---
transition: slide-down
class: sc_bg
---

# 🎯 Objectifs de la prestation 
Hub pour les simulateurs de InSimo

## Contexte
Le hub actuel n'est plus maintenable et nécessite une refonte pour intégrer plusieurs simulateurs et améliorer l'expérience utilisateur.

**Le hub doit être fonctionnel pour le salon de la santé et de l'innovation le 11 juin 2025.**
<v-click>

## Objectifs fonctionnels et techniques 

</v-click>
<v-clicks>

- **Application front-end** - Pour afficher des parcours de formation des nouveaux simulateurs
- **Plusieurs simulateurs** - Intégration de plusieurs simulateurs pour une expérience d'apprentissage enrichie
- **Maintenabilité du code** - L'application doit être facile à maintenir et à faire évoluer
- **Présence de tests automatisés** - Pour garantir la fiabilité

</v-clicks>


---
class: ro_bg
layout: default
title: '📆 Phase 1 : itérations 1 et 2'
---

# 📆 Réalisation du projet 
Par La Crafterie Tech

## Phase 1 : itérations 1 et 2 

### Equipe 
Collectif Ytreza 100%

### Méthodologie 
<v-clicks>

- Intégration des maquettes "from scratch"
- TDD 100%,
- Mob Programming pour toutes les tâches de développement. 

</v-clicks>

---
class: ro_bg
layout: default
title: '📆 Phase 2 : itérations 2 à 10'
---

# Réalisation du projet 
Par La Crafterie Tech

## 📆 Phase 2 : itérations 3 à 10

### Equipe 

Edouard MANGEL, Thomas Stocker, Marc Bouvier et certains membres du collectif Ytreza à temps partiel 

<v-click>

### Méthodologie 
</v-click>

<v-clicks>

- Utilisation de bibliothèque de composants Vue.js pour accélérer le développement,
- TDD 100%, 
- Pair/Mob Programming pour les tâches complexes,
- Travail en solo pour les tâches simples ou exploratoires
</v-clicks>


---
class: ro_bg
---

# 🛠️ Principales réalisations 

<v-click>

## Application front-end
</v-click>
<v-clicks>

- Application web de hub pour Sim and Care et Robotis, 
- Parcours de formation des simulateurs
- Résultats des simulations

</v-clicks>
<v-click>

## Intégration à Electron pour packager une application desktop
</v-click>
<v-clicks>

- Lancement des processus Unity (Sim and Care et Robotis)
- Interprétation des données de configuration des simulateurs
- Récupération et analyse des résultats des simulations

</v-clicks>

---
layout: default
class: dis_bg
---

# 📊 Résultats mesurables 
KPIs, indicateurs de performance, résultats quantitatifs et qualitatifs

## Délais
<v-clicks>


- Anticipation des risques, approche incrémentale et itérative,
- Compromis sur les fonctionnalités pour respecter les délais,
- Livraison d'une version fonctionnelle pour chaque simulateur pour le salon. 
</v-clicks>


<v-click>

## Conformité avec l'attendu 

</v-click>
<v-clicks>

- Prise en compte immédiate des retours de l'équipe InSimo,
- Aucun bug détecté pour les fonctionnalités livrées,

</v-clicks>


---
layout: default
class: dis_bg
---

# Apprentissages & recommandations 
Bilan de la prestation

## Ce qui a bien fonctionné

<v-clicks>

- Respect des délais,
- Application front-end fonctionnelle et maintenable,
- Tests automatisés couvrant les principales fonctionnalités,
- Collaboration efficace avec l'équipe InSimo,
- Passation de connaissances réussie.
</v-clicks>
<v-click>

## Ce qui pourrait être amélioré

- Scope flou en termes de répartition des rôles et responsabilités.

</v-click>


---
layout: end
class: sc_bg
---

# Merci pour cette opportunité !

## Merci à toute l'équipe d'InSimo pour cette collaboration enrichissante