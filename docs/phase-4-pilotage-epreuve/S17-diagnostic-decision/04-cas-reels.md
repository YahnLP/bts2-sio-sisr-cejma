# Cas réel – Munich et LiMux : faut-il quitter le logiciel libre ?

*BTS SIO SISR 2e année – CEJM et CEJMA – S17*

> [!NOTE]
> **Comment travailler.** Lis le cas réel et ses sources, réponds par écrit aux questions, puis ouvre « Voir la réponse attendue ». Les faits viennent des sources citées en fin de page ; en cas de doute, **retourne à la source**. Ce cas complète l'étude de cas fictive de la séance.

## Le dossier

**Le contexte.** Depuis environ **2003**, la ville de **Munich** a remplacé Windows sur ses postes de travail par **LiMux**, une distribution **Linux** adaptée. La migration visait à **envoyer un message** à Microsoft et à **faire des économies**, mais elle a été **difficile** (Le Monde Informatique). Début 2017, environ **15 000** ordinateurs de la ville fonctionnent sous LiMux et environ **5 000** sous Windows.

**La décision (février 2017).** Le conseil municipal vote une motion ; la presse informatique titre que la ville « **abandonne officiellement Linux pour Windows** ». Selon Le Monde Informatique :

| Élément | Information |
|---|---|
| **Échéance** | **31 décembre 2020** pour déployer un **client uniforme** fondé sur une nouvelle image Windows |
| **Outils demandés** | Bureautique standard et produits courants, pour la **compatibilité**, y compris avec **SAP** |
| **Raisons avancées** | De nombreuses **applications métier** de la ville ne fonctionnent que sous Windows ; la coexistence de **deux systèmes** est critiquée, surtout après un **changement de direction** de la ville |
| **Étude** | **Accenture**, mandaté par le maire, recommande le retour à Windows et la suite **Office** de Microsoft. Coût estimé de la **cohabitation** de LiMux et des nouveaux clients Windows : **18,9 M€** au départ |
| **Critiques** | **Indépendance** de l'étude contestée ; lien possible avec l'installation du siège allemand de Microsoft à Munich ; question du **respect des règles européennes d'achat** (achat sans mise en concurrence) ; l'opposition annonce un coût de **plusieurs millions d'euros** |

**Un autre récit.** La **Free Software Foundation Europe (FSFE)** affirme que les médias ont mal présenté la décision : le conseil aurait demandé à l'administration de **concevoir une stratégie** d'architecture informatique unifiée, avec les applications LiMux devenues inutiles, l'ampleur des **amortissements** et un **budget approximatif**, avant une **décision finale**. Selon la FSFE, le rapport d'Accenture trouvait surtout des **problèmes d'organisation** (structures et responsabilités floues), non techniques ; changer de système ne les réglerait pas. La FSFE défend le logiciel libre : **c'est une partie prenante engagée**, pas une source neutre.

## Pourquoi ce cas est utile

Une décision informatique se joue sur trois champs à la fois. Ici : **économique** (coût de la cohabitation, économies), **juridique** (règles des **marchés publics**, indépendance vis-à-vis d'un fournisseur) et **managérial** (organisation, deux systèmes, conduite du changement). Il montre aussi qu'un même fait est **raconté différemment** selon la source : il faut **croiser** et **critiquer**.

## Questions

**1.** Calcule la part du parc sous LiMux en 2017. Rapporte le coût de 18,9 M€ au nombre de postes LiMux : que signifie ce chiffre ?

<details markdown="1">
<summary>Voir la réponse attendue</summary>

Parc : 15 000 + 5 000 = 20 000 postes ; LiMux : 15 000 / 20 000 = **75 %**. 18,9 M€ / 15 000 ≈ **1 260 € par poste LiMux** : c'est un **ordre de grandeur pédagogique** ; la source ne dit pas que cette somme porte sur ces 15 000 postes, ni sur quelle période. Ce n'est pas le coût total de la migration, que l'article ne donne pas.
</details>

**2.** Classe les arguments du dossier selon les trois champs (économique, juridique, managérial).

<details markdown="1">
<summary>Voir la réponse attendue</summary>

- **Économique** : coût de 18,9 M€ de la cohabitation ; économies visées en 2003 ; coût annoncé par l'opposition.
- **Juridique** : règles européennes sur les achats publics sans mise en concurrence ; indépendance de l'étude commandée par le maire ; neutralité vis-à-vis d'un fournisseur.
- **Managérial** : applications métier incompatibles ; deux systèmes à maintenir ; problèmes d'**organisation** selon la FSFE ; conduite du changement difficile ; changement de direction.
</details>

**3.** Construis une **grille de décision pondérée** pour choisir entre « rester sous LiMux », « migrer vers Windows » et « corriger l'organisation puis décider ». Propose critères, poids et notes **justifiés par le dossier**.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

*Exemple de réponse* (poids et notes **subjectifs**, à justifier) : critères **coût** (30 %), **compatibilité avec les applications métier** (30 %), **risque juridique** (20 %), **faisabilité organisationnelle** (20 %). Notes de 1 à 5 : Rester sous LiMux : 3 / 2 / 4 / 3 → note = 0,3 × 3 + 0,3 × 2 + 0,2 × 4 + 0,2 × 3 = **2,9**. Migrer vers Windows : 2 / 5 / 2 / 3 → 0,6 + 1,5 + 0,4 + 0,6 = **3,1**. Corriger l'organisation puis décider : 4 / 3 / 4 / 4 → 1,2 + 0,9 + 0,8 + 0,8 = **3,7**. Le classement dépend des **poids** : refais le calcul avec 50 % pour la compatibilité (**analyse de sensibilité**). Les notes viennent de **lectures** du dossier, pas de mesures.
</details>

**4.** Les deux récits (presse informatique, FSFE) se contredisent-ils sur les **faits** ? Qu'est-ce qui relève de l'**interprétation** ?

<details markdown="1">
<summary>Voir la réponse attendue</summary>

Sur les **faits** : le vote du 15 février 2017, le projet d'un client uniforme et l'étude d'Accenture sont convergents. Sur la **portée** : la presse parle d'une décision de retour à Windows ; la FSFE parle d'une **demande de stratégie**, avec décision finale **ultérieure**. L'attribution des **causes** (déménagement de Microsoft, problèmes d'organisation) est de l'**interprétation**, avec des intérêts différents (partisans du logiciel libre, opposants). Aucune de ces deux sources ne remplace la **délibération** du conseil.
</details>

**5.** Formule une **recommandation** en quatre éléments (choix, raisons, conditions, risques résiduels) à partir de la grille.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

*Exemple* : **Choix** : réaliser d'abord un audit de l'organisation informatique, puis décider ; **raisons** : la compatibilité des applications métier est un vrai problème, mais l'étude évoque des difficultés d'organisation que le changement de système ne règle pas ; **conditions** : une étude **indépendante**, un chiffrage complet (coût total de possession, formation) et le respect des règles d'achat public ; **risques résiduels** : retard, coût de la cohabitation (18,9 M€ estimés), démotivation des équipes. Objection prévisible : « on perd du temps » → réponse : un calendrier court avec une décision à date fixe.
</details>

## Sources

- [Le Monde Informatique – La ville de Munich abandonne officiellement Linux pour Windows (16 février 2017)](https://www.lemondeinformatique.fr/actualites/lire-la-ville-de-munich-abandonne-officiellement-linux-pour-windows-67387.html) : décision, chiffres, critiques (lu).
- [FSFE – What happened in Munich (1er mars 2017)](https://FSFE.org/news/2017/news-20170301-01) : lecture alternative de la décision (lu ; source engagée).

> [!NOTE]
> **À valider :** deux sources de **février-mars 2017** seulement ; ce qui s'est passé **ensuite** (décision finale, calendrier, coûts réels) n'a **pas** été vérifié : ne présente pas ce cas comme l'histoire complète. Le chiffre de 18,9 M€ est une **estimation** d'un consultant, reprise par la presse. Les poids et notes de la question 3 sont un **exemple** à discuter, pas une vérité.
