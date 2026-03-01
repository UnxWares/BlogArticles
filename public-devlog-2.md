---
title: "UnxWares - Public Devlog #2"
date: "2026-03-01"
author: "David Gheghea"
authorEmail: "david.gheghea@unxwares.com"
category: "Devlogs"
tags: ["devlog", "cloud", "iaas", "infrastructure", "saas"]
description: "Ce deuxième devlog public d’UnxWares couvre la période du 23 février au 1er mars 2026. Il détaille la mise en place complète de l’infrastructure interne, le déploiement d’une version pré-production de l’espace client, les avancées sur le site vitrine et les fonctionnalités de gestion comptabilité, ainsi que les contributions open source, la maintenance des serveurs et le renforcement de la sécurité. Ce rapport vise à fournir une vision claire et transparente de l’évolution technique et organisationnelle du projet."
excerpt: "Deuxième édition du devlog public d’UnxWares : infrastructure stabilisée, espace client pré-production, développement du site vitrine, contributions open source, sécurité renforcée et préparation des prochaines étapes du projet."
image: "https://unxwares.com/images/uw-cloud/infrastructure/fortinet_fortigate_100e.png"
featured: true
draft: false
---

## Période : du 23 février 2026 au 1er mars 2026

Bienvenue dans ce deuxième devlog public d’UnxWares.  

Cette semaine a été marquée par une phase de structuration profonde : consolidation des outils internes, stabilisation de la plateforme, déploiement d’une version pré-production de l’espace client et avancées significatives sur l’écosystème logiciel.

L’objectif principal était clair : renforcer les fondations techniques tout en poursuivant le développement visible du projet.

---

## 🏗️ Infrastructure

Une étape majeure a été franchie avec la mise en place complète des outils internes destinés à l’équipe de développement.  
L’ensemble de l’environnement de travail est désormais structuré, centralisé et cohérent.

Nous avons déployé :

- les outils de monitoring et d’observabilité de la plateforme,
- les solutions de gestion interne des services,
- les outils de collaboration et de communication d’équipe,
- un pipeline CI/CD complet permettant l’automatisation des builds et des déploiements.

La migration vers notre propre plateforme Git a également été finalisée et intégrée directement au pipeline CI/CD, ce qui renforce notre autonomie technique et notre souveraineté sur la chaîne de développement.

Une version **pré-production** de l’espace client a été mise en ligne (customers.unxwares.com).  
Cette étape représente un jalon important : la plateforme entre désormais dans une phase de stabilisation fonctionnelle avant ouverture progressive.

Nous avons également mis en place plusieurs outils issus de l’écosystème CNCF pour la gestion des paquets, des images conteneurs (conformes à la spécification OCI) ainsi que des bibliothèques internes.  
Cela nous permet d’uniformiser les environnements et d’assurer une meilleure traçabilité des artefacts.

Enfin, un important travail de stabilisation globale a été réalisé afin d’améliorer la fiabilité de l’ensemble de l’infrastructure.

---

## 💻 Développement

Le site vitrine (https://www.unxwares.com) continue d’évoluer rapidement.

Cette semaine a vu :

- la mise en place du blog,
- l’intégration du thème sombre,
- l’ajout des pages légales (mission, CGV, CGU, politique de confidentialité),
- la structuration du design system global.

Du côté de l’espace client, une vue dynamique a été mise en place afin d’améliorer l’expérience utilisateur.  
Les fonctionnalités liées à la gestion comptabilité progressent également, posant les bases d’un futur module financier intégré.

Sur le plan open source, plusieurs contributions ont été réalisées :

- contribution au projet Excalidash avec l’ajout d’une fonctionnalité de base de données PostgreSQL,
- publication et amélioration de nouvelles Helm Charts open source,
- restructuration complète de la page GitHub du projet afin d’améliorer la lisibilité et la cohérence de l’écosystème public.

Ces contributions s’inscrivent dans la volonté d’UnxWares de participer activement à l’écosystème cloud et open source.

---

## 🔧 Maintenance

Une mise en conformité complète de notre serveur mail a été effectuée afin de respecter les normes de sécurité imposées par Google.

Ce travail permet d’améliorer la délivrabilité des emails, la réputation du domaine et la fiabilité des communications sortantes.

---

## 👨‍💼 Emploi

Plusieurs initiatives ont été lancées pour structurer la croissance de l’équipe.

Une proposition de stage de 8 semaines a été faite à un étudiant en BUT Techniques de Commercialisation à l’IUT Grand Ouest Normandie.

Un rendez-vous a également eu lieu avec un étudiant pour un futur stage de 5 semaines en développement.

Enfin, une proposition de participation a été faite à un étudiant en BUT Informatique afin de contribuer au développement des outils internes.

Ces démarches s’inscrivent dans une volonté de créer un environnement collaboratif et formateur autour du projet.

---

## 🔐 Sécurité

La sécurité continue d’être un axe prioritaire.

Les outils critiques ont été complètement isolés afin de limiter les surfaces d’exposition et compartimenter les accès sensibles.

Les plateformes SSO internes ont également été renforcées afin d’améliorer la gestion des identités et la protection des accès administrateurs.

---

## 💼 Administration

Plusieurs actions stratégiques ont été menées en parallèle.

La préparation du rendez-vous avec Pépite Normandie est en cours, dans une logique de structuration entrepreneuriale.

Une décision importante a été prise : quitter Discord au profit d’une alternative open source et souveraine basée sur Matrix.  
Cette transition s’inscrit dans la continuité de notre démarche d’indépendance technologique.

Des discussions sont également en cours avec l’équipe de RepoFlow dans le cadre d’un partenariat potentiel autour de la structuration open source souveraine du projet.

---

## 🚀 Et ensuite ?

Cette semaine marque une étape de consolidation majeure : l’infrastructure est stabilisée, l’espace client entre en pré-production et l’écosystème logiciel prend forme de manière cohérente.

Les prochaines semaines seront orientées vers :

- l’amélioration fonctionnelle de l’espace client,
- la finalisation des modules comptabilité,
- la poursuite des contributions open source,
- et la préparation des futures phases de mise en production.

Merci de suivre l’évolution du projet — la suite arrive bientôt.
