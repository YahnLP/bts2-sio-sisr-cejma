# Cours – Protéger la valeur créée : secret, droits et contrats

*BTS SIO SISR 2e année – CEJM et CEJMA – S05 – à lire avant l'[étude de cas](02-etude-de-cas.md)*

> [!NOTE] Ce que tu dois savoir déjà
> - **Prérequis :** S01 ; la propriété intellectuelle de la 1re année (S16) ; le contrat de travail en notions.

## À la fin de ce cours tu sauras

- [ ] Distinguer **brevet, droit d'auteur, secret des affaires**
- [ ] Dire **à qui appartient un logiciel** développé par un salarié ou un prestataire
- [ ] Rédiger l'essentiel d'une **clause de confidentialité** et d'une **clause de non-concurrence**
- [ ] Identifier les **conditions de validité** d'une clause de non-concurrence
- [ ] Argumenter une décision de protection

## I. Les moyens de protéger une valeur immatérielle

Pour une entreprise de services numériques, la valeur est dans le **code**, les **méthodes**, les **fichiers clients**, le **savoir-faire**. Plusieurs protections se combinent.

| Moyen | Ce qu'il protège | Formalité | Remarque |
|---|---|---|---|
| **Droit d'auteur** | L'**expression** d'une œuvre, dont le **logiciel** | **Aucune** : naît avec la création | Protège le code, pas l'idée ni l'algorithme |
| **Brevet** | Une **invention technique** nouvelle, inventive, industrialisable | Dépôt (en France, à l'INPI) | Les **programmes d'ordinateur « en tant que tels »** en sont exclus |
| **Marque** | Un **signe** distinctif | Dépôt | Vue en 1re année |
| **Secret des affaires** | Une **information** non divulguée qui a de la valeur | Mesures de protection | Protège savoir-faire, algorithmes, fichiers |
| **Contrats** | Les relations avec salariés, partenaires, clients | Écrit | Confidentialité, non-concurrence, cession de droits |

> [!NOTE]
> **L'idée n'est pas protégeable en soi.** Ce qui l'est, c'est sa **forme** (droit d'auteur), son **application technique** (brevet, sous conditions) ou son **secret**.

## II. Le logiciel : à qui appartient-il ?

Le logiciel est protégé par le **droit d'auteur** dès sa création. La question est : **qui détient les droits** ?

| Situation | Règle générale |
|---|---|
| **Salarié** qui crée le logiciel **dans l'exercice de ses fonctions** ou **selon les instructions** de l'employeur | Les **droits patrimoniaux** (exploiter, reproduire, modifier) sont **dévolus à l'employeur** |
| **Prestataire indépendant** (freelance, ESN) | Il **reste l'auteur** : le client n'a de droits que si le contrat prévoit une **cession** |
| **Collaboration** (plusieurs auteurs) | Œuvre de collaboration : droits partagés |

Une **cession de droits** doit être **écrite** et **précise** : quels droits sont cédés (reproduction, modification, représentation), pour quelle **étendue** et quelle **destination**, sur quel **territoire** et pour quelle **durée**. À défaut, le client risque de ne pouvoir ni modifier ni réutiliser librement le code qu'il a payé.

> [!NOTE]
> Un prestataire peut aussi accorder une **licence d'utilisation** plutôt qu'une cession : le client utilise le code, sans en devenir propriétaire.

## III. Le secret des affaires

Une information est protégée au titre du **secret des affaires** si elle réunit **trois conditions** :

1. elle n'est **pas généralement connue** ou aisément accessible pour les personnes du milieu concerné ;
2. elle a une **valeur commerciale**, **effective ou potentielle**, **parce qu'elle est secrète** ;
3. elle fait l'objet de **mesures de protection raisonnables** de la part de son détenteur.

Ces mesures sont concrètes : **accès limité**, **contrats de confidentialité**, chiffrement, journalisation des accès, mention « confidentiel ». Sans elles, le secret ne sera pas protégé en cas de litige.

Le secret protège sans limite de durée, tant qu'il reste secret, mais ne protège **pas** contre une découverte indépendante ou une rétro-ingénierie licite.

## IV. Les clauses contractuelles

| Clause | Contenu essentiel | Remarque |
|---|---|---|
| **Confidentialité** (NDA) | Quelles informations, qui y est tenu, **durée**, exceptions | S'applique aux salariés, partenaires, prestataires |
| **Non-concurrence** | Interdit d'exercer une activité concurrente **après** la fin du contrat | **Encadrée** pour les salariés (voir ci-dessous) |
| **Cession de droits** | Droits cédés, étendue, territoire, durée, prix | Pour les prestataires |
| **Propriété du code** | Qui détient le code, les livrables, les outils préexistants | À préciser dans le contrat de prestation |

### La clause de non-concurrence d'un salarié

Pendant le contrat, le salarié a déjà une **obligation de loyauté**. Après la rupture, il est **libre** d'exercer son métier, sauf **clause de non-concurrence**. Cette clause est **licite** seulement si elle remplit **cumulativement** ces conditions (jurisprudence) :

| Condition | Sens |
|---|---|
| **Intérêts légitimes** | Elle est **indispensable** à la protection d'un intérêt réel de l'entreprise |
| **Limitée dans le temps** | Durée raisonnable |
| **Limitée dans l'espace** | Zone géographique proportionnée |
| **Tient compte de l'emploi** | Spécificités du poste du salarié |
| **Contrepartie financière** | Le salarié est **indemnisé** de la restriction |

Une clause qui ne respecte pas ces conditions est **nulle** ou réduite par le juge : le salarié peut aller chez un concurrent. Une clause trop large (toute la France, deux ans, tout poste, sans indemnité) est fragile.

Même sans clause, un salarié ou un ancien salarié qui **détourne** des fichiers, dénigre ou manœuvre pour attirer la clientèle commet une **faute** (concurrence déloyale) : l'entreprise peut demander réparation devant le juge.

**Test flash.** Un freelance a écrit pour vous un module, sans contrat de cession. Pouvez-vous le revendre à d'autres clients ?

<details markdown="1">
<summary>Voir la réponse</summary>

**Non, pas sans accord** : le freelance reste l'auteur, et vous n'avez que les droits que le contrat prévoit. Il faut une **cession écrite et précise** (ou une licence) pour le revendre.
</details>

## Comprendre pas à pas

### Quel outil pour quelle valeur ?

| Ce qu'on protège | Outil | Condition principale | Limite |
|---|---|---|---|
| Un **code source**, un texte, un visuel | **Droit d'auteur** | Création **originale** ; aucune formalité | Protège la **forme**, pas l'**idée** |
| Une **invention technique** | **Brevet** | Nouveauté, activité inventive, application industrielle ; **dépôt** | Coût, durée limitée, divulgation |
| Un **signe distinctif** | **Marque** | **Dépôt** ; usage | Spécialité des produits ; renouvellement |
| Un **savoir-faire**, une méthode, un fichier clients | **Secret des affaires** | Information **secrète**, de **valeur**, **protégée** | Perdue si elle devient publique |
| La **fidélité** d'un salarié ou d'un partenaire | **Clauses** (confidentialité, non-concurrence) | Rédaction **valide** | Annulation si disproportionnée |

> [!NOTE]
> Plusieurs protections se **cumulent** : un logiciel peut être protégé par le **droit d'auteur**, ses algorithmes par le **secret**, et son **nom** par une **marque**.

### Le logiciel : à qui appartient-il ?

| Qui a écrit ? | Contexte | Qui a les droits ? |
|---|---|---|
| **Un salarié** | Dans ses fonctions | **L'employeur** (droits patrimoniaux) |
| **Un freelance** | Sans contrat de cession | **Le freelance** reste titulaire ; il faut une **cession écrite et précise** |
| **Un stagiaire** | Selon la convention et le contrat | À **prévoir par écrit** |

### Exemple guidé : vérifier une clause de non-concurrence

1. **Intérêt légitime ?** Un poste donnant accès à des secrets : oui ; un poste sans accès : douteux.
2. **Durée et zone raisonnables ?** Quelques mois à deux ans ; une zone proportionnée.
3. **Adaptée au poste ?** Elle vise les **activités réellement concurrentes**.
4. **Contrepartie financière ?** Sans elle, la clause est **nulle**.

Deux cas réels sont détaillés dans [Waymo contre Uber et la non-concurrence](04-cas-reels.md).

## À retenir

- **Droit d'auteur** : automatique, protège le code ; **brevet** : exclut le logiciel « en tant que tel » ; **secret des affaires** : trois conditions dont des **mesures de protection**.
- Logiciel d'un **salarié** : droits patrimoniaux à l'**employeur** ; d'un **prestataire** : **cession écrite** nécessaire.
- Clause de non-concurrence : intérêts légitimes, **temps**, **espace**, **emploi**, **contrepartie financière**.
