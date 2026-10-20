# Cours – Modèle économique et seuil de rentabilité

*BTS SIO SISR 2e année – CEJMA – S03 – à lire avant l'[étude de cas](02-etude-de-cas.md)*

> [!NOTE] Ce que tu dois savoir déjà
> - **Prérequis :** S02 ; notions de coût et de marge de la 1re année.

## À la fin de ce cours tu sauras

- [ ] Décrire un **modèle économique** avec le canevas en neuf blocs
- [ ] Distinguer **charges fixes** et **charges variables**
- [ ] Calculer **marge sur coûts variables** et **seuil de rentabilité**
- [ ] Calculer les indicateurs d'un **abonnement**
- [ ] Commenter un résultat et proposer une action

## I. Le modèle économique

Un **modèle économique** (*business model*) décrit **comment l'entreprise crée, délivre et capte de la valeur** : à qui elle vend quoi, comment, et comment elle gagne de l'argent. Le **canevas de modèle économique** d'Osterwalder le décrit en **neuf blocs**.

| Bloc | Question |
|---|---|
| **Segments de clientèle** | Pour qui crée-t-on de la valeur ? |
| **Proposition de valeur** | Quel problème résout-on, quel besoin satisfait-on ? |
| **Canaux** | Comment atteint-on les clients ? |
| **Relation client** | Quel type de relation (assistance, libre-service, communauté) ? |
| **Flux de revenus** | Comment les clients paient-ils ? |
| **Ressources clés** | De quoi a-t-on besoin (équipes, plateformes, données) ? |
| **Activités clés** | Que doit-on faire de mieux que les autres ? |
| **Partenaires clés** | Qui aide (fournisseurs, revendeurs) ? |
| **Structure de coûts** | Quelles sont les dépenses principales ? |

### Modèles de revenus courants dans le numérique

| Modèle | Principe | Exemple |
|---|---|---|
| **Vente** (licence) | Le client achète une fois | Logiciel installé |
| **Abonnement** | Paiement régulier pour un service continu | Application en ligne |
| **Freemium** | Version gratuite, options payantes | Outil en ligne avec fonctions avancées payantes |
| **Commission** (plateforme) | Prélèvement sur chaque échange | Place de marché |
| **Publicité** | L'annonceur paie, l'utilisateur est gratuit | Service financé par des annonces |

Le choix du modèle a des conséquences : un abonnement donne des revenus **réguliers**, mais demande de **garder** les clients.

## II. Charges fixes et charges variables

| Type | Définition | Exemples |
|---|---|---|
| **Charges fixes** | Ne dépendent pas (à court terme) du volume d'activité | Salaires de l'équipe, loyer, hébergement de base |
| **Charges variables** | Évoluent avec le volume | Licences par client, support par client |

## III. Marge sur coûts variables et seuil de rentabilité

| Notion | Formule |
|---|---|
| **Marge sur coûts variables** (MCV) | Chiffre d'affaires − charges variables |
| **Taux de MCV** | MCV ÷ chiffre d'affaires |
| **Seuil de rentabilité** (SR), en chiffre d'affaires | Charges fixes ÷ taux de MCV |
| **Seuil de rentabilité en quantité** | Charges fixes ÷ MCV **unitaire** (arrondi à l'entier **supérieur**) |
| **Résultat** | MCV − charges fixes |
| **Marge de sécurité** | Chiffre d'affaires réalisé − seuil de rentabilité |
| **Indice de sécurité** | Marge de sécurité ÷ chiffre d'affaires réalisé |

Le **seuil de rentabilité** est le niveau d'activité où le **résultat est nul** : en dessous, l'entreprise perd de l'argent ; au-dessus, elle en gagne. La **marge de sécurité** indique de combien l'activité peut baisser avant la perte.

### Exemple

Une entreprise vend un service **600 €** par client et par an, avec **240 €** de charges variables par client, et supporte **400 000 €** de charges fixes.

- MCV unitaire : 600 − 240 = **360 €** ; taux de MCV : 360 ÷ 600 = **60 %**.
- Seuil en quantité : 400 000 ÷ 360 = 1 111,1 → **1 112 clients**.
- Seuil en chiffre d'affaires : 400 000 ÷ 0,60 ≈ **666 667 €**.

## IV. Les indicateurs d'un abonnement

| Indicateur | Définition | Formule |
|---|---|---|
| **MRR** (revenu mensuel récurrent) | Revenus mensuels d'abonnement | Clients × prix mensuel |
| **Taux de départ** (*churn*) mensuel | Part des clients qui partent chaque mois | Clients perdus ÷ clients au début du mois |
| **Durée de vie moyenne** d'un client | Durée pendant laquelle un client reste abonné | 1 ÷ taux de départ mensuel |
| **Coût d'acquisition** d'un client (CAC) | Coût pour obtenir un nouveau client | Dépenses commerciales ÷ nouveaux clients |
| **Valeur vie client** (LTV) | Marge qu'un client rapporte durant sa vie | Marge mensuelle par client × durée de vie |

Un rapport **LTV ÷ CAC** élevé indique que gagner un client est rentable ; un taux de départ élevé détruit la valeur. On compare ces indicateurs d'une période à l'autre.

**Test flash.** Charges fixes de 90 000 €, MCV unitaire de 30 €. Quel est le seuil en quantité ?

<details markdown="1">
<summary>Voir la réponse</summary>

90 000 ÷ 30 = **3 000** unités. En dessous, l'entreprise perd de l'argent.
</details>

## Comprendre pas à pas

### Seuil de rentabilité : un exemple complet

Un service de supervision vendu **40 € par mois et par client**. Charges **variables** par client : **12 €**. Charges **fixes** : **9 000 € par mois**.

| Étape | Calcul | Résultat |
|---|---|---:|
| **Marge sur coûts variables** (MCV) par client | \(40 - 12\) | **28 €** |
| **Seuil de rentabilité** (en clients) | \(9\,000 / 28\) | **321,4 → 322 clients** |

On arrondit **au-dessus** : 321 clients ne couvrent pas les charges fixes.

### Indicateurs d'abonnement : un exemple

**500 clients**, **40 €** par mois, **4 %** de départs par mois, **CAC** de **200 €**.

| Indicateur | Calcul | Résultat |
|---|---|---:|
| **MRR** | \(500 \times 40\) | **20 000 €** |
| **Durée de vie moyenne** | \(1 / 0{,}04\) | **25 mois** |
| **LTV** (avec marge de 28 € par mois) | \(28 \times 25\) | **700 €** |
| **LTV / CAC** | \(700 / 200\) | **3,5** |

> [!TIP]
> Un **LTV / CAC** supérieur à **3** est souvent cité comme un repère de bonne santé, mais cette valeur est une **convention de métier**, pas une règle.

### Modèle de revenus : qui paie et pour quoi ?

Pour décrire un modèle économique : **segment de clientèle**, **proposition de valeur**, **canaux**, **revenus**, **coûts**. Dans le freemium, **la gratuité sert d'acquisition** et une **minorité paie** pour des fonctions avancées.

Un cas réel est détaillé dans [Spotify](04-cas-reels.md).

## À retenir

- Le canevas : **segments, proposition de valeur, canaux, relation, revenus, ressources, activités, partenaires, coûts**.
- **MCV** = CA − charges variables ; **SR** = charges fixes ÷ taux de MCV (ou ÷ MCV unitaire en quantité, arrondi au supérieur).
- **Marge de sécurité** = CA − SR.
- Abonnement : **MRR, churn, durée de vie = 1 ÷ churn, CAC, LTV**.
