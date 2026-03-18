# 📊 Organisation du projet – Menu Maker

---

## 📌 Objectif

Ce document décrit l’organisation du projet **Menu Maker**, la méthodologie utilisée, la structuration des tâches ainsi que la planification globale du développement.

Il s’appuie directement sur le **tableau Kanban réalisé sur Notion**, regroupant l’ensemble des User Stories et tâches techniques.

---

## 👥 Équipe projet

| Rôle                | Responsabilités                                              |
| ------------------- | ------------------------------------------------------------ |
| Front-end Developer | Interface utilisateur, UX, intégration                       |
| Back-end Developer  | API, base de données, logique serveur                        |
| Product Owner       | Définition des besoins, priorisation (simulé dans ce projet) |

---

## ⚙️ Méthodologie

Le projet est organisé selon une approche **Agile (Kanban)**.

### 🔄 Workflow des tâches

* 📝 **À faire** : tâches planifiées non commencées
* 🚧 **En cours** : tâches en développement
* 🧪 **À tester** : tâches terminées en attente de validation
* ✅ **Terminé** : tâches validées

---

## 🧩 Structure du backlog

Le backlog est structuré autour de :

### 📌 User Stories

Les fonctionnalités sont définies sous forme de **User Stories**, permettant de garder une vision centrée utilisateur.

Chaque User Story contient :

* un besoin utilisateur
* des critères de succès
* des spécifications fonctionnelles
* des spécifications techniques
* une priorité
* un sprint associé

---

### ⚙️ Tâches techniques

Des tâches techniques viennent compléter les User Stories pour :

* initialiser les environnements (Front / Back)
* mettre en place l’architecture
* gérer la sécurité
* intégrer les services externes
* assurer la qualité (tests, CI/CD, monitoring)

---

## 🧱 Découpage fonctionnel (Epics)

Le projet est structuré en plusieurs **Epics** :

| Epic             | Description                                              |
| ---------------- | -------------------------------------------------------- |
| Landing          | Découverte du produit                                    |
| Connexion        | Authentification utilisateur                             |
| Création de menu | Fonctionnalité principale                                |
| Back Office      | Fonctionnalités avancées (impression, CI/CD, monitoring) |

---

## 📊 Priorisation

Les tâches sont priorisées selon leur importance :

* **P1 (Critique)** : indispensables au fonctionnement du produit
* **P2 (Important)** : améliorent l’expérience utilisateur
* **P3 (Nice to have)** : fonctionnalités secondaires

---

## 🗓️ Organisation en sprints

Le projet est découpé en **sprints hebdomadaires**.

### 🧩 Exemple de progression

| Sprint    | Contenu                                       |
| --------- | --------------------------------------------- |
| Sprint 1  | Mise en place des environnements Front & Back |
| Sprint 2  | Landing page + authentification               |
| Sprint 3  | Création des catégories et plats              |
| Sprint 4  | Personnalisation du menu                      |
| Sprint 5  | Export PDF + impression                       |
| Sprint 6  | Gestion des menus                             |
| Sprint 7  | Fonctionnalités secondaires                   |
| Sprint 8+ | Sécurité, tests, monitoring, intégrations     |

---

## 🧪 Critères de qualité

Chaque tâche doit respecter :

* ✅ critères de succès définis
* 🧪 validation fonctionnelle
* 🔒 respect des contraintes techniques
* ♿ accessibilité minimale

---

## 🔐 Contraintes du projet

* Version **desktop uniquement**
* Compatibilité : Chrome, Firefox, Safari
* Accessibilité (navigation clavier, lecteur d’écran)
* Pas d’analytics utilisateur (non requis)

---

## 🔗 Liens utiles

* 📋 Kanban Notion : **[Lien à ajouter]**
* 📄 Spécifications techniques : ../02-technical-specs/specifications-techniques.pdf
* 📘 Spécifications fonctionnelles : ../01-functional-specs/specifications-fonctionnelles.pdf

---

## 🚀 Vision produit

L’objectif est de proposer un outil :

* simple à utiliser
* rapide à prendre en main
* orienté métier (restauration)
* permettant une diffusion multi-supports

---

## 📈 Axes d’amélioration

* Version mobile
* Ajout d’analytics
* Internationalisation
* Éditeur de menu avancé

---
