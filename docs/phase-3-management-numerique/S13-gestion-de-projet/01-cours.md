# Cours – Conduire un projet

*BTS SIO SISR 2e année – CEJMA – S13 – à lire avant l'[étude de cas](02-etude-de-cas.md)*

> [!NOTE] Ce que tu dois savoir déjà
> - **Prérequis :** les structures et le mode projet (S11) ; l'organisation d'une équipe (S12).

## À la fin de ce cours tu sauras

- [ ] Définir un **projet** et ses contraintes (coût, délai, qualité)
- [ ] Découper un projet en **tâches** et construire un **réseau**
- [ ] Déterminer le **chemin critique** et les **marges**
- [ ] Lire un **diagramme de Gantt**
- [ ] Comparer démarche **prédictive** et **agile**
- [ ] Identifier et traiter des **risques**

## I. Qu'est-ce qu'un projet ?

Un **projet** est un ensemble d'activités **temporaires**, avec un **objectif** précis, un **début** et une **fin**. Il est encadré par trois contraintes liées : le **coût**, le **délai** et la **qualité** (ou périmètre). Modifier l'une agit sur les autres.

| Rôle | Mission |
|---|---|
| **Maîtrise d'ouvrage (MOA)** | Exprime le besoin, finance, valide |
| **Maîtrise d'œuvre (MOE)** | Réalise la solution |
| **Chef de projet** | Planifie, coordonne, rend compte |
| **Comité de pilotage** | Décide aux étapes clés |

## II. Découper et ordonner

On découpe le projet en **tâches** (organigramme des tâches). Pour chaque tâche : une **durée**, des **antécédents** (tâches à terminer avant), un responsable.

Le **réseau** relie les tâches. Pour chacune on calcule :

| Terme | Calcul |
|---|---|
| **Début au plus tôt (DPT)** | Fin au plus tôt du dernier antécédent |
| **Fin au plus tôt (FPT)** | DPT + durée |
| **Fin au plus tard (FPTard)** | Début au plus tard de la tâche suivante (la plus contraignante) |
| **Début au plus tard** | Fin au plus tard − durée |
| **Marge totale** | Début au plus tard − DPT |

Le **chemin critique** est la suite de tâches **sans marge** : tout retard sur l'une d'elles retarde le projet. C'est aussi le chemin **le plus long**, et il donne la **durée minimale** du projet.

## III. Le diagramme de Gantt

Le **Gantt** représente les tâches en barres sur un calendrier. Il montre la durée, l'ordre et le chevauchement ; on y fait apparaître les **jalons** (dates clés) et le chemin critique. C'est un outil de **suivi**.

## IV. Démarche prédictive ou agile

| | Prédictive (ex. cycle en V, cascade) | Agile (ex. Scrum) |
|---|---|---|
| Principe | Besoin figé au départ, étapes enchaînées | Itérations courtes, besoin qui évolue |
| Avantage | Visibilité sur coût et délai | Réactivité, retours rapides |
| Limite | Changement coûteux | Périmètre moins stable |

Le choix dépend de la **clarté du besoin**, du **risque** et du **contrat**. Une infrastructure à installer se prête plutôt à une démarche prédictive ; une application aux besoins incertains, à l'agilité.

## V. Gérer les risques

On identifie les risques, on les évalue (**probabilité × gravité**), puis on choisit : **éviter**, **réduire**, **transférer** (assurance, contrat) ou **accepter**. Les risques sont suivis tout au long du projet.

**Test flash.** Une tâche du chemin critique prend deux semaines de plus. Quelle conséquence ?

<details markdown="1">
<summary>Voir la réponse</summary>

Le projet est retardé de **deux semaines**, puisque les tâches du chemin critique n'ont pas de marge. (Sauf si l'on gagne du temps sur une autre tâche du chemin.)
</details>

## À retenir

- Projet = objectif, début, fin ; contraintes **coût, délai, qualité**.
- Réseau de tâches → **chemin critique** (le plus long, marge nulle).
- **Gantt** : outil de suivi.
- Prédictif ou agile selon le besoin ; risques = probabilité × gravité.
