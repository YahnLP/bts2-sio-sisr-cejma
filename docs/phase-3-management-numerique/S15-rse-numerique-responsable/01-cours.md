# Cours – RSE et numérique responsable

*BTS SIO SISR 2e année – CEJMA – S15 – à lire avant l'[étude de cas](02-etude-de-cas.md)*

> [!NOTE] Ce que tu dois savoir déjà
> - **Prérequis :** les parties prenantes et les finalités de l'entreprise (1re année, S03) ; la conduite du changement (S14).

## À la fin de ce cours tu sauras

- [ ] Définir la **RSE** et ses trois piliers
- [ ] Citer les **parties prenantes** et leurs attentes
- [ ] Décrire les **impacts environnementaux** du numérique
- [ ] Appliquer des **leviers** de numérique responsable
- [ ] Calculer un **PUE** et un gain énergétique

## I. La responsabilité sociétale des entreprises

La **RSE** désigne la prise en compte, par l'entreprise, des **enjeux sociaux et environnementaux** dans son activité, en plus de la performance économique. On la présente en **trois piliers** :

| Pilier | Exemples |
|---|---|
| **Économique** | Pérennité, achats responsables, éthique des affaires |
| **Social** | Conditions de travail, diversité, formation, santé |
| **Environnemental** | Énergie, déchets, émissions, matériel |

La RSE est **volontaire** dans son principe, mais encadrée par des règles croissantes (information extra-financière, devoir de vigilance, etc.). Des **référentiels** existent (norme **ISO 26000**, labels). Elle répond aux attentes des **parties prenantes** : clients, salariés, investisseurs, pouvoirs publics, riverains.

> [!WARNING]
> Le détail des obligations de reporting (seuils, calendrier) évolue vite : il est **à vérifier** dans un texte à jour avant de le citer.

## II. Les impacts du numérique

Le numérique a un impact **environnemental** à chaque étape :

| Étape | Impact |
|---|---|
| **Fabrication** des équipements | Extraction de matières, énergie, souvent la part la plus lourde |
| **Usage** | Consommation électrique des postes, serveurs, réseaux |
| **Hébergement** | Énergie des centres de données et de leur refroidissement |
| **Fin de vie** | Déchets électroniques, recyclage |

Les chiffres globaux varient selon les sources : on cite toujours **l'organisme et l'année**, ou l'on s'en tient aux ordres de grandeur qualitatifs.

## III. Les leviers du numérique responsable

| Levier | Exemple |
|---|---|
| **Allonger la durée de vie** | Garder un poste 6 ans au lieu de 4, réparer |
| **Réemploi** | Don ou revente de matériel reconditionné |
| **Achats responsables** | Critères de réparabilité, labels |
| **Sobriété** | Éteindre, dimensionner juste, supprimer les données inutiles |
| **Éco-conception** | Applications et sites moins gourmands |
| **Efficacité énergétique** | Hébergement efficace, refroidissement optimisé |

Le **PUE** (*Power Usage Effectiveness*) mesure l'efficacité d'un centre de données : **PUE = énergie totale ÷ énergie consommée par les équipements informatiques**. Un PUE de 1,0 serait parfait ; plus il est proche de 1, mieux c'est.

Le **coût annuel d'un équipement** = prix d'achat ÷ durée d'utilisation.

## IV. Piloter la démarche

Une démarche RSE passe par : un **diagnostic**, des **objectifs** chiffrés, un **plan d'action**, des **indicateurs** et un **suivi**. Il faut éviter l'**écoblanchiment** (*greenwashing*) : annoncer plus que ce que l'on fait.

**Test flash.** Un centre de données consomme 100 kWh pour ses serveurs et 150 kWh au total. Quel est son PUE ?

<details markdown="1">
<summary>Voir la réponse</summary>

150 ÷ 100 = **1,5**. Les 50 kWh supplémentaires servent notamment au refroidissement et à l'alimentation.
</details>

## Comprendre pas à pas

### Citer un chiffre correctement

Un chiffre sur l'impact du numérique est utilisable seulement avec :

1. **L'organisme** (qui le dit ?).
2. **L'année** et le **périmètre** (France, monde ; quelles activités ?).
3. **Le scénario** pour une projection.
4. **L'unité** (Mt CO2eq, TWh).

> [!WARNING]
> « Le numérique représente 2,5 % » ne veut rien dire seul. « Selon la note de l'Arcep de mars 2023, le numérique représentait **2,5 % de l'empreinte carbone de la France en 2020** » se vérifie.

### Calculer le PUE et le coût annuel d'un équipement

| Calcul | Exemple | Résultat |
|---|---|---:|
| **PUE** = énergie totale ÷ énergie des équipements informatiques | 150/100 | **1,5** |
| **PUE** après amélioration du refroidissement | 125/100 | **1,25** |
| **Coût annuel** = prix ÷ durée d'utilisation | 900/4 | **225 €** |
| **Coût annuel** avec 6 ans d'usage | 900/6 | **150 €** |

### Choisir un levier : où se trouve l'impact ?

| Question | Si la réponse est… | Levier prioritaire |
|---|---|---|
| D'où vient la plus grosse part de l'impact ? | La **fabrication** | Durée de vie, réemploi, achats |
| L'usage consomme-t-il beaucoup ? | Oui | Efficacité énergétique, sobriété |
| Les données sont-elles toutes utiles ? | Non | Supprimer, archiver |
| Les applications sont-elles lourdes ? | Oui | Éco-conception |

Un exemple de chiffres publics à lire et à critiquer : [l'empreinte du numérique en France](04-cas-reels.md).

## À retenir

- RSE = 3 piliers (économique, social, environnemental) ; parties prenantes.
- Impacts du numérique : fabrication, usage, hébergement, fin de vie.
- Leviers : durée de vie, réemploi, sobriété, éco-conception, efficacité.
- **PUE** = énergie totale ÷ énergie informatique.
- Éviter l'**écoblanchiment**.
