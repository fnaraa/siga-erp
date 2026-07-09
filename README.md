# SIGA'ERP

Application web de gestion de projet Scrum, développée dans le cadre de mon stage de fin d'études (PFE) chez **SIGA**, cabinet tunisien spécialisé Oracle.

![Status](https://img.shields.io/badge/status-completed-success)
![License](https://img.shields.io/badge/license-MIT-blue)

## À propos

SIGA'ERP est une application de gestion de projet basée sur la méthodologie **Agile/Scrum**, permettant aux équipes de suivre leurs sprints, visualiser leur avancement et gérer leur documentation de manière centralisée.

Projet réalisé en binôme avec [Ahmed Selim Bousleh](#), sous la supervision de **Nassim Arfaoui**.

## Fonctionnalités

- 📋 **Gestion de sprints** — planification et suivi des sprints Scrum
- 🗂️ **Tableau Kanban** — visualisation du workflow (To Do / In Progress / Done)
- 📈 **Burndown & Burn-Up Charts** — suivi de l'avancement en temps réel
- 📁 **Gestion documentaire** — intégration Alfresco ECM pour les documents projet
- 📧 **Notifications automatiques** — envoi d'emails via SMTP
- 👥 **Gestion des équipes et rôles**

## Stack technique

| Catégorie | Technologies |
|---|---|
| Backend | Oracle APEX, PL/SQL, Oracle XE 21c |
| Gestion documentaire | Alfresco ECM |
| Versioning | GitLab |
| Notifications | SMTP |

## Architecture

Architecture en 3-tiers (MVC), avec intégrations externes vers Alfresco (documents), un serveur SMTP (notifications) et GitLab (versioning).

<!-- Insérer ici le diagramme d'architecture SVG -->

## Captures d'écran

<!-- Insérer ici : Kanban, Burndown/Burn-Up, gestion Alfresco, dashboard sprint -->

| Kanban | Burndown Chart |
|---|---|
| ![Kanban](./docs/screenshots/kanban.png) | ![Burndown](./docs/screenshots/burndown.png) |

## Équipe

- **Iheb Dhaoui** — Développement
- **Ahmed Selim Bousleh** — Développement
- **Nassim Arfaoui** — Encadrant (SIGA)

## Contexte

Projet réalisé dans le cadre du PFE (Projet de Fin d'Études) — Licence Génie Logiciel et Systèmes d'Information (LGLSI), Faculté des Sciences de Gabès, 2025/2026.

## Contact

**Iheb Dhaoui**
- Email : ihebdhaouiipeiem@gmail.com
- LinkedIn : [linkedin.com/in/iheb-dhaoui-855a853a3](https://linkedin.com/in/iheb-dhaoui-855a853a3)

## Licence

Ce projet est sous licence MIT — voir le fichier [LICENSE](LICENSE) pour plus de détails.
