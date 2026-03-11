---
title: "UnxWares - Public Devlog #3"
date: "2026-03-08"
author: "David Gheghea"
authorEmail: "david.gheghea@unxwares.com"
category: "Devlogs"
tags: ["devlog", "cloud", "iaas", "infrastructure", "saas"]
description: "Ce troisième devlog public d’UnxWares couvre la période du 2 au 8 mars 2026. Il revient sur la stabilisation de l’infrastructure interne, le déploiement de nouveaux services distribués, les avancées importantes sur le design system et l’espace client, ainsi que plusieurs évolutions organisationnelles dont l’intégration au programme Pépite Normandie et la signature d’un accord open source avec RepoFlow."
excerpt: "Troisième devlog d’UnxWares : stabilisation de l’infrastructure, Redis clusterisé, progression du design system Svelte, avancées de l’espace client et intégration officielle au programme Pépite Normandie."
image: "https://unxwares.com/images/uw-cloud/infrastructure/mikrotik_ccr2004.png"
featured: true
draft: false
---

## Période : du 2 mars 2026 au 8 mars 2026

Bienvenue dans ce troisième devlog public d’UnxWares.

Cette semaine a été marquée par un travail important de stabilisation technique et de structuration de l’écosystème logiciel.
Plusieurs améliorations ont été apportées à l’infrastructure interne, tandis que le développement du design system et de l’espace client continue de progresser.

Parallèlement, plusieurs étapes importantes ont été franchies sur le plan organisationnel avec l’intégration officielle au programme Pépite Normandie et la mise en place d’un partenariat open source.


---

## 🏗️ Infrastructure

Une phase de diagnostic approfondi a été menée sur l’infrastructure de base de données interne afin d’identifier et corriger plusieurs problèmes affectant la stabilité globale du système.
Les correctifs appliqués ont permis d’améliorer la fiabilité et la résilience des services dépendant de cette infrastructure.

Dans une logique d’optimisation des performances, une solution **Redis clusterisée** a été déployée pour les services internes.
Cette architecture permet d’améliorer la gestion du cache et la rapidité d’accès aux données pour plusieurs composants de la plateforme.

Nous avons également déployé une **plateforme collaborative interne pour l’équipe UnxWares**, permettant le stockage, le partage de fichiers et l’organisation du travail au quotidien.

Enfin, afin d’accompagner la croissance du projet, de nouveaux espaces de **stockage décentralisé** ont été loués et intégrés à l’infrastructure existante.


---

## 💻 Développement

Le développement de l’écosystème logiciel s’est poursuivi avec une étape importante : la transition vers l’utilisation d’une **bibliothèque UI interne basée sur Svelte**.

Un travail conséquent a été réalisé pour :

* créer de nombreux composants réutilisables,
* structurer et finaliser le **Design System** interne,
* uniformiser l’interface des différentes applications de l’écosystème.

Le site vitrine (<https://www.unxwares.com>) a également reçu plusieurs corrections et améliorations :

* correction des derniers bugs identifiés,
* amélioration du système de gestion des langues,
* correction de différents problèmes d’affichage.

Du côté de l’open source, une nouvelle contribution a été apportée au projet **Excalidash**, avec des améliorations visant à renforcer sa compatibilité avec les environnements **Kubernetes**.

Le développement de l’espace client (customers.unxwares.cloud) continue également de progresser.
Cette semaine a notamment permis :

* l’intégration des premières liaisons avec notre **processeur de paiement**,
* l’amélioration de l’interface utilisateur,
* la progression des fonctionnalités internes.

Ces avancées rapprochent progressivement la plateforme d’une version plus complète et exploitable.


---

## 🔧 Maintenance

Plusieurs opérations de maintenance ont été réalisées en parallèle afin de garantir la stabilité de l’infrastructure et de préparer les futures évolutions techniques de la plateforme.


---

## 👨‍💼 Emploi

L’équipe continue de s’agrandir.

Un **nouveau développeur à temps partiel** a rejoint le projet afin de travailler sur le développement de l’outil interne de **provisioning**, un composant clé pour l’automatisation de la gestion des ressources cloud.

Par ailleurs, les discussions autour du **stage de 8 semaines en BUT TC** se poursuivent.

Enfin, l’accord de stage pour un étudiant en BTS SIO a été transmis afin de finaliser les démarches administratives.


---

## 🔐 Sécurité

La sécurité reste un axe constant de travail.
Plusieurs vérifications et ajustements internes ont été réalisés afin de maintenir un niveau élevé de protection des services et des données.


---

## 💼 Administration

Cette semaine marque une étape importante pour la structuration du projet.

Après une dernière présentation, **UnxWares a officiellement intégré le programme Pépite Normandie**, qui accompagne les projets entrepreneuriaux issus de l’enseignement supérieur.

Nous avons également conclu un **accord open source avec RepoFlow**, ouvrant la voie à des collaborations techniques et à la structuration de certains projets publics autour de notre écosystème.

Enfin, la **comptabilité 2025** a été finalisée et officiellement clôturée, marquant la fin administrative de cet exercice.


---

## 🚀 Et ensuite ?

Les prochaines semaines seront consacrées à plusieurs axes majeurs :

* poursuite du développement de l’espace client,
* amélioration continue du design system et des interfaces,
* développement de l’outil interne de provisioning,
* consolidation de l’infrastructure cloud.

Merci de suivre l’évolution du projet — la suite arrive bientôt.
