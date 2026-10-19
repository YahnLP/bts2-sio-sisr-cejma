# Étude de cas – Mistral Logiciels : un projet de sauvegarde

*BTS SIO SISR 2e année – CEJMA – S13*

> [!NOTE]
> **Comment travailler.** Lis le dossier, puis réponds **par écrit** à chaque question : notion, application au dossier (cite le document), conclusion. Ouvre ensuite « Voir la réponse attendue » pour te corriger.

## Dossier : Mistral Logiciels

> [!NOTE]
> L'entreprise, les personnes et les chiffres sont **fictifs**.

### Document 1 – Le projet

**Mistral Logiciels**, éditeur de 60 salariés, veut remplacer son système de **sauvegarde**. Le client interne (la direction) exige une mise en production **dans les 15 semaines**. Une pénalité interne de **1 500 € par semaine de retard** est prévue.

### Document 2 – Les tâches

| Tâche | Description | Durée (semaines) | Antécédents |
|---|---|---|---|
| A | Cahier des charges | 3 | – |
| B | Achat du matériel | 4 | A |
| C | Rédaction des procédures | 2 | A |
| D | Installation et configuration | 5 | B |
| E | Préparation de la formation | 3 | C |
| F | Recette et mise en production | 2 | D, E |

### Document 3 – Un aléa

Le fournisseur annonce que la livraison du matériel prendra **2 semaines de plus** que prévu (tâche B).

### Questions

**1.** Dessinez le **réseau** (ordre des tâches) et calculez la **durée minimale** du projet.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

Deux chemins : A-B-D-F = 3 + 4 + 5 + 2 = **14 semaines** ; A-C-E-F = 3 + 2 + 3 + 2 = **10 semaines**. Durée minimale = **14 semaines**, soit dans le délai de 15 semaines.
</details>

**2.** Quel est le **chemin critique** ? Justifiez.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

**A-B-D-F** (14 semaines) : c'est le chemin le plus long, et ses tâches n'ont **aucune marge**.
</details>

**3.** Calculez les **marges** des tâches C et E.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

F commence au plus tôt en semaine 12 (fin de D) et au plus tard à la semaine 12. E finit au plus tôt à 8 et doit finir au plus tard à 12 : marge **4 semaines**. C finit au plus tôt à 5 et au plus tard à 9 : marge **4 semaines**. Elles peuvent glisser de 4 semaines sans retarder le projet.
</details>

**4.** Que provoque l'**aléa** du document 3 ? Calculez le coût éventuel.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

B passe à 6 semaines : A-B-D-F = 3 + 6 + 5 + 2 = **16 semaines**, soit **1 semaine** de plus que le délai de 15 semaines. Pénalité : 1 × 1 500 = **1 500 €**. Le chemin critique reste A-B-D-F.
</details>

**5.** Proposez **deux mesures** pour tenir le délai et évaluez leurs risques.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

Exemples : (1) **accélérer** D (renfort d'un technicien) : coût supplémentaire, risque de défauts de configuration ; (2) **chevaucher** une partie de D avec l'arrivée progressive du matériel : risque de reprises ; (3) négocier avec le fournisseur une livraison partielle. Les mesures portent sur le **chemin critique** : agir sur C ou E serait inutile.
</details>

## Je sais faire

Coche honnêtement ; ce que tu ne coches pas se reprend avant la séance suivante.

- [ ] Calculer les durées des chemins d'un réseau
- [ ] Identifier le chemin critique
- [ ] Calculer une marge
- [ ] Mesurer l'effet d'un retard
- [ ] Proposer des mesures sur le chemin critique

**Ce que je dois reprendre :** ______________________

**Ma question à poser à l'enseignant :** ______________________
