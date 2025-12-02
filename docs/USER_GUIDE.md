# 📘 Guide Utilisateur - TaskForge

Bienvenue sur le guide officiel de **TaskForge** — votre outil de gestion de projet collaborative conçu pour les équipes agiles.

> **Version du document :** 0.2.0 
> **Dernière mise à jour :** Décembre 2025

---

## 📑 Table des matières

0. [Démarrage rapide](#-démarrage-rapide)
1. [Inscription et Connexion](#1-inscription-et-connexion)
2. [Création et Gestion des Projets](#2-création-et-gestion-des-projets)
3. [Gestion des User Stories](#3-gestion-des-user-stories)
4. [Gestion des Tâches](#4-gestion-des-tâches)
5. [Gestion des Sprints](#5-gestion-des-sprints)
6. [Gestion des Versions](#6-gestion-des-versions)
7. [Bonnes pratiques](#7-bonnes-pratiques)

---

## 🚀 Démarrage rapide

Pour les utilisateurs pressés, voici les étapes essentielles :

| Étape | Action |
|-------|--------|
| 1 | Créez votre compte ou connectez-vous |
| 2 | Créez un projet |
| 3 | Ajoutez des User Stories au backlog |
| 4 | Découpez-les en tâches |
| 5 | Planifiez vos sprints |
| 6 | Livrez via les versions |

---

## 1. Inscription et Connexion

### 🆕 Créer un compte

1. Sur la page d'accueil, cliquez sur **Créer un compte**.
2. Remplissez le formulaire :

   | Champ | Description | Obligatoire |
   |-------|-------------|:-----------:|
   | Nom d'utilisateur | Identifiant unique (3-20 caractères) | ✅ |
   | Adresse email | Email valide pour les notifications | ✅ |
   | Mot de passe | Minimum 8 caractères | ✅ |

3. Cliquez sur **Créer mon compte**.

### 🔐 Se connecter

1. Cliquez sur **Connexion**.
2. Entrez vos identifiants (nom d'utilisateur + mot de passe) et cliquez sur **Se connecter**.
3. Accédez à votre **Tableau de bord**.

---

## 2. Création et Gestion des Projets

Le projet est l'espace de travail central de votre équipe.

### ➕ Créer un projet

1. Depuis le tableau de bord, cliquez sur **Voir mes projets**.
2. Cliquez sur **➕ Créer un projet**.
3. Remplissez la fiche :

   | Champ | Description |
   |-------|-------------|
   | **Nom du projet** | Nom court et explicite (ex: "App Mobile v2") |
   | **Description** | Contexte et objectifs du projet |
   | **Membres** | Collaborateurs à inviter, maintenez Ctrl/Cmd pour en sélectionner plusieurs |

4. Cliquez sur **Créer le projet**.

### ✏️ Modifier un projet

1. Dans la liste des projets, cliquez sur l'icône ✏️ (crayon).
2. Modifiez les informations souhaitées.

### 🗑️ Supprimer un projet

> **⚠️ ATTENTION : Action irréversible !**  
> La suppression efface définitivement le projet ET toutes ses données (User Stories, tâches, sprints, versions).

1. Cliquez sur l'icône 🗑️ (corbeille).
2. Confirmez la suppression en appuyant sur **Supprimer**.

---

## 3. Gestion des User Stories

Une **User Story** décrit une fonctionnalité du point de vue de l'utilisateur final.

### Format recommandé

```
En tant que [type d'utilisateur],
je veux [action/fonctionnalité],
afin de [bénéfice attendu].
```

**Exemple :**
> *En tant qu'utilisateur, je veux pouvoir réinitialiser mon mot de passe, afin de récupérer l'accès à mon compte.*

### ➕ Créer une User Story

1. Entrez dans la **Vue détaillée** d'un projet en cliquant dessus.
2. Cliquez sur **➕ User Story**.
3. Remplissez le formulaire :

   | Champ | Description |
   |-------|-------------|
   | **Titre** | Résumé court (ex: "Page de Login") |
   | **Description** | Détail de la fonctionnalité |
   | **Priorité** | 🟢 Basse / 🟡 Moyenne / 🔴 Haute |
   | **Membres** | Personnes assignées |

4. Cliquez sur **Créer**.

### Actions sur une User Story

| Icône | Action |
|:-----:|--------|
| ✏️ | Modifier le contenu |
| ❌ | Supprimer |

---

## 4. Gestion des Tâches

Les tâches sont les étapes techniques pour réaliser une User Story.

### ➕ Créer une tâche

1. Sélectionnez une User Story.
2. Cliquez sur **🔽** pour dérouler son contenu.
3. Cliquez sur **➕ Tâche**.
4. Définissez :
   - **Titre** : Action concrète (ex: "Créer le formulaire HTML")
   - **Description** : Détails techniques
   - **Priorité** : Importance relative (🟢 Basse / 🟡 Moyenne / 🔴 Haute)
   - **Membres** : Développeur assigné

### Bonnes pratiques pour les tâches

> **💡 Conseil :** Découpez vos tâches pour qu'elles durent **1 à 4 heures maximum**. Cela facilite :
> - Le suivi de l'avancement
> - L'estimation du temps restant
> - La répartition du travail

**Exemples de découpage :**

| ❌ Trop vague | ✅ Bien découpé |
|--------------|----------------|
| "Faire le login" | "Créer le formulaire de connexion" |
| | "Implémenter la validation côté client" |
| | "Créer l'API d'authentification" |
| | "Écrire les tests unitaires" |

---

## 5. Gestion des Sprints

Les **Sprints** sont des cycles de travail (généralement 1 à 4 semaines) dédiés à la réalisation d'un ensemble de User Stories.

### ➕ Créer un Sprint

1. Dans la vue projet, cliquez sur **Gérer les Sprints**.
2. Cliquez sur **+ Nouveau Sprint**.
3. Configurez :

   | Champ | Description |
   |-------|-------------|
   | **Nom du sprint** | Ex: "Sprint 1 - Authentification" |
   | **Date de début** | Début du sprint |
   | **Date de fin** | Fin du sprint |
   | **Statut** | Planifié → Actif → Terminé |

### Cycle de vie d'un Sprint

```
📋 Planifié  →  ▶️ Actif  →  ✅ Terminé
```

| Statut | Description |
|--------|-------------|
| **Planifié** | Sprint en préparation, User Stories assignables |
| **Actif** | Sprint en cours, travail en progression |
| **Terminé** | Sprint clôturé |

### 🔗 Assigner des User Stories

1. Dans la liste des User Stories, cliquez sur **Assigner à un sprint...**.
2. Sélectionnez le sprint cible.
3. La User Story apparaît maintenant dans le sprint.

### ⚠️ Supprimer un Sprint

La suppression d'un sprint **ne supprime pas** les User Stories. Elles retournent automatiquement dans le backlog.

---

## 6. Gestion des Versions

Les **Versions** (ou releases) regroupent des User Stories terminées pour une livraison.

### ➕ Créer une Version

1. Cliquez sur l'onglet **Versions**.
2. Cliquez sur **+ Nouvelle Version**.
3. Remplissez :

   | Champ | Description | Exemple |
   |-------|-------------|---------|
   | **Numéro de version** | Versioning sémantique | v1.0.0 |
   | **Titre** | Nom de la release | "Version initiale" |
   | **Description** | Notes de version | Changelog détaillé |

### Convention de versioning

Nous recommandons le **versioning sémantique** :

```
vMAJEUR.MINEUR.PATCH

Exemples :
- v1.0.0 → Première version stable
- v1.1.0 → Nouvelle fonctionnalité
- v1.1.1 → Correction de bug
- v2.0.0 → Changement majeur (breaking change)
```

### Cycle de vie d'une Version

```
📋 Planifiée  →  🔄 En cours  →  🚀 Publiée  →  📦 Archivée
```

### 📎 Gérer le contenu d'une Version

1. Cliquez sur la version souhaitée.
2. **Ajouter** : Cliquez sur **+Ajouter** à côté d'une User Story pour l'inclure.
3. **Retirer** : Cliquez sur **Retirer** à côté d'une User Story incluse pour l'exclure.

---

## 7. Bonnes pratiques

### 📌 Organisation du backlog

- Priorisez régulièrement vos User Stories
- Gardez les descriptions à jour
- Archivez les éléments obsolètes

### ⏱️ Planification des Sprints

- Commencez par des sprints de 2 semaines
- Ne surchargez pas : prévoyez 70-80% de capacité
- Incluez du temps pour les imprévus

### 👥 Collaboration

- Assignez des responsables clairs
- Mettez à jour les statuts quotidiennement
- Communiquez les blocages rapidement

---


*Merci d'utiliser TaskForge ! 🎉*