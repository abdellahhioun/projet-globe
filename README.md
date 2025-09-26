# ProjetGlobe - Refonte Intranet Plateforme Éducative

## Description
ProjetGlobe est un projet de refonte complète de l’intranet de La Plateforme, une grande école du numérique. La plateforme offre deux espaces distincts : un pour les étudiants et un pour l’équipe pédagogique. L’objectif est de faciliter la gestion des promotions, des projets, des inscriptions, des rendus et du suivi des compétences tout en garantissant la sécurité, la conformité RGPD, l’accessibilité et une évolutivité orientée SaaS multi-tenant.

## Fonctionnalités principales
- Authentification via compte Google (SSO)
- Gestion des promotions, des unités de formation, des étudiants et des projets
- Création, gestion et validation des groupes projets
- Suivi des rendus et progression des compétences des étudiants
- Journaux d’activité et statistiques par promotion
- Interface utilisateur accessible et conforme RGPD
- Architecture multi-tenant assurant l’isolation des données par organisme

## Architecture & Technologies
- Base de données relationnelle multi-tenant avec identifiant `tenantid`
- Contrôle d’accès basé sur les rôles (étudiant, équipe pédagogique, accompagnateur, intervenant externe)
- API REST modulaires
- Frontend développé avec React et NestJS
- Méthodologies de gestion de projet agiles et cycle en V selon les phases

## Équipe Projet
- Directeur technique / Chef de projet
- Product Owner (représentant des besoins pédagogiques)
- Scrum Master
- Architecte solution / Tech Lead
- Responsable développement / Team Lead
- Ingénieur QA
- Responsable sécurité
- Designer UX/UI et expert accessibilité
- Délégué à la protection des données (DPO)
- PMO (pilotage méthodologique)
- Consultants externes ponctuels

## Documentation associée
- [Cahier des charges](cahier-des-charges.pdf) : spécifications fonctionnelles et contraintes
- [Organigramme équipe](organigramme.pdf) : rôles et responsabilités
- [Schéma base de données](database_scheme.pdf) : modélisation MCD/MLD multi-tenant
- [Diagramme applicatif](application_diagram.pdf) : architecture technique principale
- [Compte rendu choix méthode](cr_choix_methode.pdf) : méthodologie projet et gestion des risques

## Installation et utilisation
*(À compléter selon vos spécificités techniques et environnement de déploiement)*

## Licence
*(À définir en fonction des conditions de propriété intellectuelle)*

---

Pour plus d’informations, veuillez consulter la documentation associée ou contacter le responsable de projet.
