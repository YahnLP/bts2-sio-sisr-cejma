# Cas réel – GendBuntu : migrer la gendarmerie de Windows vers Ubuntu

*BTS SIO SISR 2e année – CEJMA – S14*

> [!NOTE]
> **Comment travailler.** Lis le cas réel et ses sources, réponds par écrit aux questions, puis ouvre « Voir la réponse attendue ». Les faits viennent des sources citées en fin de page ; en cas de doute, **retourne à la source**. Ce cas complète l'étude de cas fictive de la séance.

## Le dossier

**Les faits (article du 10 novembre 2010).** La **Gendarmerie nationale** remplace progressivement **Windows** par le système libre **Ubuntu** sur ses postes de travail. Le parc comprend environ **85 000 ordinateurs**, répartis sur environ **4 500 sites**. À la date de l'article, **7 000** postes (fixes et portables) sont déjà déployés.

| Élément | Information rapportée |
|---|---|
| **Début de la réflexion** | **Avant 2005** |
| **Rythme prévu** | **10 000 postes par an** |
| **Objectif** | **90 %** du parc sous Ubuntu en **2015** |
| **Motif principal** | Le **coût** : un responsable déclare que Windows coûterait « **2 millions d'euros de plus** par an » |
| **Résultats cités (2010)** | Environ **2 M€ d'économies par an** ; des serveurs locaux Ubuntu remplacent environ **4 500 serveurs** départementaux dédiés ; la mise à jour de l'antivirus, qui demandait **un an** de déplacements, se fait en **deux semaines** sans déplacement |

> [!NOTE]
> L'article **ne parle pas** de formation ni d'accompagnement des utilisateurs, et ne mentionne pas d'éventuelles difficultés. Ce silence ne prouve **pas** qu'il n'y en a pas eu.

## Pourquoi ce cas est utile

Il illustre une **transformation numérique** pilotée par le **coût** et la **maîtrise technique**, sur un grand nombre d'utilisateurs. Il permet de s'interroger sur la **conduite du changement** (Kotter, Lewin) : urgence, communication, formation, victoires rapides.

## Questions

**1.** Vérifie la **cohérence** du plan : à 10 000 postes par an, combien de postes seront migrés entre novembre 2010 et 2015, et quelle part du parc cela représente-t-il ? Compare à l'objectif de 90 %.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

Cinq ans à 10 000 postes : 50 000, plus les 7 000 déjà déployés, soit **57 000** postes, soit 57 000 / 85 000 ≈ 67 %. L'objectif de 90 % correspond à 0,9 × 85 000 = 76 500 postes, soit environ **7,65 ans** à ce rythme. Le rythme annoncé **ne suffit donc pas** : il aurait fallu l'accélérer, ou l'objectif a été formulé autrement. La source ne l'explique pas : **chercher une source plus récente**.
</details>

**2.** Calcule l'économie annuelle par poste si les 2 M€ sont rapportés à l'ensemble du parc. Quelle précaution prendre ?

<details markdown="1">
<summary>Voir la réponse attendue</summary>

2 000 000 / 85 000 ≈ 23,5 € par poste et par an. C'est une **hypothèse** : l'économie citée porte sur le coût de licences « et frais associés », et seule une partie du parc était migrée en 2010. Autre limite : l'article est publié par l'**éditeur d'Ubuntu**.
</details>

**3.** Associe ce cas aux étapes de Kotter : lesquelles apparaissent dans l'article, lesquelles manquent ?

<details markdown="1">
<summary>Voir la réponse attendue</summary>

- **Urgence** : la pression du **coût** (2 M€ par an).
- **Victoires rapides** : l'antivirus mis à jour en deux semaines, les serveurs locaux.
- **Vision et objectif** : 90 % en 2015.
- **Absentes de la source** : communication, **formation**, **relais** et suivi de l'adoption.

Ces absences concernent **l'article**, pas forcément le projet.
</details>

**4.** Quelles **résistances** le projet a-t-il pu rencontrer chez les utilisateurs ? Propose un volet du plan d'accompagnement pour chacune.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

**Habitudes** (attachement aux logiciels connus) → formation et documentation ; **peur** de perdre en efficacité → référents dans chaque unité ; **incompatibilité** d'outils → support renforcé les premières semaines ; **manque de confiance** → retour des premiers utilisateurs. (Hypothèses pédagogiques, non tirées de la source.)
</details>

**5.** Quels **indicateurs** suivrais-tu pour juger la réussite de la migration ?

<details markdown="1">
<summary>Voir la réponse attendue</summary>

**Taux d'adoption** (postes migrés ÷ postes visés), **volume d'incidents** par poste, **satisfaction** des utilisateurs, **coût** par poste, **délai** de déploiement des mises à jour de sécurité.
</details>

## Sources

- [Canonical – La Gendarmerie nationale upgrades 85,000 PCs to Ubuntu Desktop Edition (10 novembre 2010, en anglais)](https://canonical.com/blog/la-gendarmerie-nationale-upgrades-85000-pcs-to-ubuntu-desktop-edition?format=md) : chiffres, motifs, résultats (lu).

> [!NOTE]
> **À valider :** la source est un billet de **l'éditeur d'Ubuntu**, donc **partial**, et date de **2010**. La situation actuelle du parc n'a **pas** été vérifiée : ne présente pas ces chiffres comme actuels. La page est en anglais ; le nom « GendBuntu » est celui de ce projet, courant dans la presse mais absent de la source lue.
