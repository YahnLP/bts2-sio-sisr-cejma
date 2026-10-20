# Cours – Organiser l'entreprise : structures et agilité

*BTS SIO SISR 2e année – CEJMA – S11 – à lire avant l'[étude de cas](02-etude-de-cas.md)*

> [!NOTE] Ce que tu dois savoir déjà
> - **Prérequis :** les finalités et les parties prenantes de l'entreprise (1re année, S03) ; la stratégie (S02).

## À la fin de ce cours tu sauras

- [ ] Comparer les structures **fonctionnelle, divisionnelle, matricielle, par projet**
- [ ] Distinguer **hiérarchie et coordination**
- [ ] Situer les organisations **agiles**
- [ ] Choisir une structure selon la taille et l'activité
- [ ] Diagnostiquer une organisation

## I. Organiser, c'est diviser et coordonner

Toute organisation répond à deux besoins qui s'opposent. Il faut **diviser le travail** (spécialiser, répartir les tâches) et **coordonner** ce qui a été divisé. Plus l'entreprise grandit, plus ces deux questions deviennent difficiles. Le chercheur **Henry Mintzberg** distingue plusieurs mécanismes de coordination.

| Mécanisme | Principe | Exemple |
|---|---|---|
| **Supervision directe** | Un responsable donne des ordres | Un chef d'équipe répartit les tâches |
| **Standardisation des procédés** | Des procédures décrivent comment faire | Procédure de traitement d'un incident |
| **Standardisation des résultats** | On fixe le résultat attendu | Objectif de délai de livraison |
| **Standardisation des qualifications** | La formation garantit les compétences | Certification technique |
| **Ajustement mutuel** | Les personnes se coordonnent entre elles | Échanges quotidiens d'une équipe agile |

## II. Les notions de base de la structure

| Notion | Définition |
|---|---|
| **Organigramme** | Représentation des postes et des liens hiérarchiques |
| **Ligne hiérarchique** | Chaîne d'autorité entre les niveaux |
| **Niveaux hiérarchiques** | Nombre d'étages de la structure |
| **Étendue du contrôle** | Nombre de personnes **directement** placées sous un responsable |
| **Unité de commandement** | Principe selon lequel chacun reçoit des ordres d'**un seul** supérieur (Fayol) |
| **Centralisation / décentralisation** | Les décisions sont prises en haut / à tous les niveaux |
| **Délégation** | Transfert d'une tâche **et** de l'autorité nécessaire pour la mener |

**Étendue du contrôle** = nombre de subordonnés directs d'un responsable. Trop étroite (2 personnes), elle crée des niveaux inutiles ; trop large (20 personnes), elle empêche un suivi réel.

## III. Les principales structures

| Structure | Principe | Avantages | Limites |
|---|---|---|---|
| **Fonctionnelle** | Regroupement par **métier** (développement, infrastructure, commercial) | Expertise, économies d'échelle | Cloisonnement ; décisions lentes entre services |
| **Divisionnelle** | Regroupement par **produit, client ou zone** | Autonomie, responsabilité sur un marché | Doublons de moyens ; concurrence interne |
| **Matricielle** | Double rattachement : **fonction** et **projet** | Mobilise l'expertise sur plusieurs projets | **Double commande** ; conflits d'autorité |
| **Par projet** | Équipe temporaire autour d'un projet | Souplesse ; focalisation sur l'objectif | Instabilité ; réaffectation en fin de projet |

Mintzberg décrit aussi des **configurations** d'organisation (structure simple, bureaucratie mécaniste, bureaucratie professionnelle, structure divisionnalisée, adhocratie). Les ESN, qui emploient des experts travaillant en projet, tendent vers des formes **professionnelles** ou **adhocratiques**.

## IV. Les organisations agiles

Les entreprises du numérique ont adopté des organisations dites **agiles** : de **petites équipes autonomes** et **pluridisciplinaires** (développeurs, testeurs, spécialistes du produit) responsables d'un produit ou d'un service, qui travaillent par **itérations courtes** et ajustent leur plan au fur et à mesure.

| Apport | Limite |
|---|---|
| Réactivité, responsabilisation | Coordination entre équipes à organiser |
| Moins de niveaux hiérarchiques | Besoin de **compétences** et de **maturité** des équipes |
| Satisfaction client plus rapide | L'autonomie ne supprime pas les **règles communes** (sécurité, qualité) |

Les modèles d'organisation ne se copient pas : on les **adapte** à la taille, à la culture et aux compétences de l'entreprise.

## V. Choisir une structure

La structure dépend de la **taille**, de la **stratégie**, de l'**environnement** (stable ou changeant), de la **technologie** et de la **culture**. Une petite entreprise a besoin de peu de niveaux ; une entreprise qui gère plusieurs clients ou marchés peut opter pour la forme divisionnelle.

**Test flash.** Un responsable a 2 subordonnés directs et chacun a 2 subordonnés. Quel est le défaut probable ?

<details markdown="1">
<summary>Voir la réponse</summary>

Une **étendue du contrôle trop étroite** : beaucoup de niveaux pour peu de personnes, donc de la lenteur et des coûts de management. On peut **aplatir** la structure.
</details>

## Comprendre pas à pas

### Étendue du contrôle et nombre de niveaux : un calcul

Plus un responsable encadre de personnes directement, **moins la structure a besoin de niveaux**. Pour 81 personnes à encadrer :

| Étendue du contrôle | Niveaux sous la direction | Calcul |
|---:|---:|---|
| 3 personnes par responsable | **4** | \(3 + 9 + 27 + 81\) (soit 120 postes de tous niveaux) |
| 9 personnes par responsable | **2** | \(9 + 81\) (soit 90 postes) |

> [!NOTE]
> Une étendue large aplatit la structure (moins de relais, décisions plus rapides) mais demande des équipes **autonomes** : c'est l'idée des équipes agiles.

### Choisir une structure : quelle question poser ?

| Situation | Structure probable |
|---|---|
| Petite ESN, un seul type de service | **Simple** ou **fonctionnelle** |
| Plusieurs clients ou marchés, besoin d'autonomie | **Divisionnelle** |
| Experts partagés entre plusieurs projets | **Matricielle** (attention à la double commande) |
| Mission ponctuelle | **Par projet** |
| Environnement changeant, équipes mûres | **Agile** (équipes pluridisciplinaires) |

### Repérer le mécanisme de coordination

| Phrase entendue | Mécanisme |
|---|---|
| « Le chef d'équipe distribue les tickets. » | Supervision directe |
| « Il y a une procédure pour chaque incident. » | Standardisation des procédés |
| « Objectif : livrer sous 24 h. » | Standardisation des résultats |
| « Il faut la certification pour intervenir. » | Standardisation des qualifications |
| « On se met d'accord à la réunion de 9 h. » | Ajustement mutuel |

Un cas réel d'organisation agile à grande échelle : [ING](04-cas-reels.md).

## À retenir

- Organiser = **diviser** et **coordonner**.
- Structures : **fonctionnelle**, **divisionnelle**, **matricielle** (double commande), **par projet**.
- **Étendue du contrôle** = nombre de subordonnés directs.
- **Unité de commandement** : un seul chef ; la matricielle la met en danger.
- **Agilité** : équipes autonomes, itérations courtes ; à adapter, non à copier.
