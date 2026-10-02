\# AutoLoc



Plateforme de gestion de location de véhicules multi-agences, développée avec Java 17 et Spring Boot dans le cadre de l'UP ASI (Architecture des Systèmes d'Information), ESPRIT.



\## Objectifs du projet



\- Centraliser la gestion du parc de véhicules de plusieurs agences

\- Permettre aux clients de rechercher et réserver un véhicule disponible

\- Gérer le cycle de vie d'une location : réservation, prise en charge, retour, facturation

\- Offrir aux responsables un suivi de l'activité de leur agence

\- Exposer les fonctionnalités via une API REST documentée (Swagger)



\## Acteurs



| Acteur | Rôle |

|---|---|

| Client | Consulte les véhicules, effectue et suit ses réservations |

| Agent d'agence | Gère les réservations, la remise et le retour des véhicules |

| Responsable d'agence | Supervise l'agence, son parc de véhicules et ses agents |

| Administrateur | Administre la plateforme : agences, utilisateurs, paramètres |



\## Premiers cas d'utilisation



\*\*Client\*\* : s'inscrire / s'authentifier, rechercher un véhicule disponible (agence, dates, catégorie), réserver un véhicule, consulter ou annuler ses réservations.



\*\*Agent d'agence\*\* : valider une réservation, enregistrer la remise du véhicule (état, kilométrage), enregistrer le retour et calculer les frais éventuels.



\*\*Responsable d'agence\*\* : gérer le parc de véhicules de l'agence (ajout, modification, maintenance), gérer les agents, consulter les statistiques de l'agence.



\*\*Administrateur\*\* : gérer les agences, gérer les comptes utilisateurs et les rôles, paramétrer les catégories de véhicules et les tarifs.



\## Stack technique



Java 17, Spring Boot, Spring Data JPA, MySQL, Lombok, springdoc-openapi, JUnit 5 / Mockito, Maven, Git/GitHub, Postman.



\## Environnement (Atelier 0)



Preuve de l'environnement fonctionnel : voir le dossier `docs/`.

