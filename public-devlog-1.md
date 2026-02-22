---
title: "UnxWares - Public Devlog #1"
date: "2026-02-22"
author: "David Gheghea"
authorEmail: "david.gheghea@unxwares.com"
category: "Devlogs"
tags: ["devlog", "cloud", "iaas", "infrastructure", "saas"]
description: "Ce premier devlog public d’UnxWares présente l’ensemble des avancées réalisées entre le 16 et le 22 février 2025. Au programme : modernisation de l’infrastructure, amélioration du réseau et de la sécurité, progression majeure du développement de l’orchestrateur cloud, refonte de plusieurs services web, ainsi que diverses opérations de maintenance et d’optimisation. Ce rapport vise à offrir une vision transparente de l’évolution technique et organisationnelle du projet."
excerpt: "Première édition du devlog public d’UnxWares : modernisation complète de l’infrastructure, avancées majeures sur l’orchestrateur cloud, nouveaux services déployés, amélioration de la sécurité et préparation des prochaines évolutions de la plateforme."
image: "https://unxwares.com/images/uw-cloud/infrastructure/hp_proliant_dl360p_gen8.png"
featured: true
draft: false
---

## Période : du 16 février 2025 au 22 février 2025

Bienvenue dans ce premier devlog public d’UnxWares.  
Ce rendez-vous a pour objectif de partager de manière transparente l’évolution du projet, les améliorations apportées à notre infrastructure ainsi que les avancées techniques réalisées durant la semaine.

Cette période a été particulièrement dense, avec un important travail de modernisation de l’infrastructure, des progrès majeurs côté développement et plusieurs initiatives visant à renforcer la fiabilité globale de la plateforme.

---

## 🏗️ Infrastructure

Une grande partie des efforts s’est concentrée sur la consolidation et la modernisation de l’infrastructure technique.

Le cluster externe a été entièrement réinstallé et mis à niveau afin d’améliorer la stabilité et les performances globales. En parallèle, le cluster interne a également bénéficié d’une mise à niveau complète, accompagnée d’un renforcement du réseau interne pour améliorer la résilience et la sécurité des communications.

Nous avons également :

- amélioré notre pipeline CI/CD afin d’accélérer et fiabiliser les déploiements,
- nettoyé et renforcé les règles pare-feu,
- simplifié les règles de routage sur le réseau public,
- effectué la mise à jour complète des périphériques d’infrastructure.

Dans une optique de montée en charge, de nouveaux espaces de stockage ont été loués et intégrés à l’environnement existant.

Un travail important a aussi été mené sur la plateforme de gestion des serveurs de jeu : l’ancien panel a été définitivement supprimé et la migration vers le nouveau système est désormais finalisée.

Enfin, plusieurs mesures préventives ont été mises en place pour limiter les risques de perte de données, notamment grâce au déploiement d’une base de données haute disponibilité.

Des tests sont également en cours autour d’une plateforme d’échange communautaire alternative à Discord, afin d’explorer des solutions plus ouvertes et maîtrisées.

---

## 💻 Développement

Côté développement, cette semaine marque une avancée majeure pour l’écosystème UnxWares.

Plusieurs Helm Charts open source ont été publiés afin de faciliter le déploiement de services cloud et de contribuer à la communauté Kubernetes.

Le site vitrine d’UnxWares a été entièrement refondu pour offrir une meilleure lisibilité et une présentation plus claire des services proposés.

L’orchestrateur cloud continue de progresser rapidement, avec la finalisation des outils internes d’administration qui permettent désormais une gestion plus efficace et automatisée de l’infrastructure.

Parmi les autres avancées importantes :

- configuration et crédibilisation du dépôt Artifact Hub,
- mise en ligne de la page de statut publique pour le suivi en temps réel des services,
- déploiement du site UnxWares Cloud,
- progression significative du dashboard UnxWares Cloud,
- refonte complète du système d’affichage des documents légaux.

Ces évolutions constituent des bases solides pour les prochaines phases de développement.

---

## 🔧 Maintenance

Plusieurs opérations de maintenance ont été réalisées afin d’améliorer l’expérience client et la stabilité réseau.

Un travail préparatoire important a également commencé autour du déploiement futur de l’IPv6, qui représente une étape clé pour l’évolution de l’infrastructure.

Le panel game a également reçu une mise à jour afin d’améliorer sa fiabilité et ses performances.

---

## 👨‍💼 Emploi

Dans le cadre du développement du projet, une proposition de stage de 5 semaines a été faite à un développeur afin de renforcer temporairement l’équipe et accélérer certains chantiers en cours.

---

## 🔐 Sécurité

La sécurité reste une priorité constante.  
Un audit complet a été réalisé et l’ensemble des vulnérabilités connues (CVE) identifiées sur l’infrastructure ont été corrigées.

---

## 🚀 Et ensuite ?

Ce premier devlog marque une étape importante : la stabilisation des fondations techniques d’UnxWares. Les prochaines semaines seront davantage orientées vers l’amélioration de l’expérience utilisateur, l’automatisation avancée et la poursuite du développement de l’écosystème cloud.

Merci de suivre l’évolution du projet — la suite arrive bientôt.
