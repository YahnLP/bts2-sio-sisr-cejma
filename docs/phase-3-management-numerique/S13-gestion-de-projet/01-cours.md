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

## Comprendre pas à pas

### Calculer un réseau de tâches pas à pas

*Exemple.* A (3 jours) précède B (4 jours) et C (2 jours) ; D (3 jours) suit B **et** C.

| Tâche | Antécédents | Début au plus tôt | Fin au plus tôt | Début au plus tard | Marge |
|---|---|---:|---:|---:|---:|
| A | – | 0 | 3 | 0 | 0 |
| B | A | 3 | 7 | 3 | 0 |
| C | A | 3 | 5 | 5 | **2** |
| D | B, C | 7 | 10 | 7 | 0 |

Le **chemin critique** est **A → B → D**, soit **10 jours** : la durée minimale du projet. C peut prendre **2 jours de retard** sans effet sur la date finale.

> [!NOTE]
> D commence quand **les deux** antécédents sont finis : on retient la fin au plus tôt **la plus tardive** (7, et non 5).

### Évaluer un risque : probabilité × gravité

| Risque | Probabilité (1-4) | Gravité (1-4) | Cote | Réponse |
|---|---:|---:|---:|---|
| Retard du fournisseur | 3 | 3 | 9 | **Réduire** : relances, second fournisseur |
| Panne du serveur de test | 2 | 2 | 4 | **Accepter** |
| Perte de données | 1 | 4 | 4 | **Transférer** (sauvegarde externalisée) ou **réduire** |

*Échelles fictives.* Les quatre réponses : éviter, réduire, transférer, accepter.

### Tenir les trois contraintes

| Si je… | Alors… |
|---|---|
| raccourcis le **délai** | le **coût** augmente (renforts) ou le **périmètre** diminue |
| élargis le **périmètre** | délai et coût augmentent |
| réduis le **coût** | délai plus long ou périmètre réduit |

Un grand projet public arrêté après sept ans : [ONP](04-cas-reels.md).

## À retenir

- Projet = objectif, début, fin ; contraintes **coût, délai, qualité**.
- Réseau de tâches → **chemin critique** (le plus long, marge nulle).
- **Gantt** : outil de suivi.
- Prédictif ou agile selon le besoin ; risques = probabilité × gravité.
