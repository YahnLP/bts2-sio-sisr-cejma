# Étude de cas – Atelier Pixel : qui possède quoi ?

*BTS SIO SISR 2e année – CEJM et CEJMA – S05*

> [!NOTE]
> **Comment travailler.** Lis le dossier, puis réponds **par écrit** à chaque question : notion, application au dossier (cite le document), conclusion. Ouvre ensuite « Voir la réponse attendue » pour te corriger.

## Dossier : un studio de développement dont la valeur est dans son code

> [!NOTE]
> L'entreprise, les personnes et les faits sont **fictifs**.

### Document 1 – L'entreprise

**Atelier Pixel** est un studio de **12 salariés** qui développe des sites de réservation en ligne. Son produit phare, **PixelBook**, regroupe un moteur de réservation, un module de paiement et un algorithme de calcul de prix.

### Document 2 – Les faits

1. **Léa**, salariée en CDI, a écrit le **moteur de réservation** pendant ses heures de travail, à la demande du gérant. Son contrat de travail ne dit rien sur les logiciels.
2. **Karim**, développeur indépendant, a écrit le **module de paiement** sur facture. Le contrat de prestation ne parle ni de droits ni de propriété.
3. L'**algorithme de calcul de prix** n'est connu que de trois personnes, qui ont signé un **accord de confidentialité** ; le code est stocké sur un serveur à **accès restreint**.
4. **Tom**, ancien salarié parti il y a deux mois, travaille chez un concurrent. Il a **emporté une copie du fichier clients**. Son contrat contient une **clause de non-concurrence de 2 ans, sur toute la France, pour tout poste informatique, sans indemnité**.
5. Le gérant envisage de **déposer un brevet** sur PixelBook.

### Questions

**1.** À qui appartiennent les droits sur le **moteur de réservation** de Léa et sur le **module de paiement** de Karim ? Justifiez.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

- **Léa** (salariée, création dans l'exercice de ses fonctions, à la demande du gérant) : les **droits patrimoniaux** sont **dévolus à l'employeur**, Atelier Pixel, sans clause particulière.
- **Karim** (prestataire indépendant) : il **reste l'auteur** du module. Sans cession écrite, Atelier Pixel n'a pas les droits d'exploitation étendue ni de modification.
</details>

**2.** Que faut-il faire avec Karim ? Précisez ce que doit contenir le **contrat de cession**.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

Régulariser par un **contrat de cession écrit** (ou une licence) : **droits cédés** (reproduction, modification, représentation), **étendue et destination**, **territoire**, **durée**, **prix**, règle sur les **outils préexistants** de Karim et sur la **maintenance** (code source remis). Tant qu'il n'est pas signé, Atelier Pixel risque de ne pas pouvoir modifier ou revendre le module.
</details>

**3.** Le gérant peut-il **breveter** PixelBook ? Quelle protection retenez-vous pour l'**algorithme de prix** ?

<details markdown="1">
<summary>Voir la réponse attendue</summary>

Les **programmes d'ordinateur « en tant que tels »** sont exclus du brevet : PixelBook ne peut pas être breveté tel quel (une invention technique plus large, avec un effet technique, serait à étudier avec un conseil en propriété industrielle). Le **code** est protégé par le **droit d'auteur** ; l'**algorithme**, idée non protégeable par le droit d'auteur, est protégé par le **secret des affaires** et la confidentialité.
</details>

**4.** L'algorithme de prix relève-t-il du **secret des affaires** ? Vérifiez les trois conditions.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

(1) **Non généralement connu** : connu de trois personnes seulement ; (2) **valeur commerciale** liée au secret : il détermine les prix, donc un avantage ; (3) **mesures de protection raisonnables** : accord de confidentialité et accès restreint (doc. 2, fait 3). Les trois conditions semblent remplies. À renforcer : journalisation des accès, mention « confidentiel », procédure à la sortie d'un salarié.
</details>

**5.** Analysez la **clause de non-concurrence** de Tom au regard des conditions de validité. Peut-on l'appliquer ?

<details markdown="1">
<summary>Voir la réponse attendue</summary>

- **Temps** : 2 ans, long mais pas déraisonnable en soi.
- **Espace** : toute la France, sans lien avec l'implantation réelle de l'entreprise : **disproportionné**.
- **Emploi** : « tout poste informatique » ignore les fonctions de Tom : **trop large**.
- **Contrepartie financière** : **absente**, ce qui rend la clause **nulle**.

La clause n'est donc **pas valable** : Atelier Pixel ne peut pas empêcher Tom de travailler chez le concurrent sur ce fondement. (Une clause correctement rédigée aurait pu être valable.)
</details>

**6.** Tom a **emporté le fichier clients**. Quels sont les **recours** d'Atelier Pixel ?

<details markdown="1">
<summary>Voir la réponse attendue</summary>

Même sans clause valable, l'emport du fichier est une **faute** : manquement à la confidentialité, **concurrence déloyale** si le fichier sert à démarcher. Atelier Pixel peut **mettre en demeure** Tom et son nouvel employeur, **réunir les preuves** (journaux d'accès, copies), et saisir le juge pour obtenir la **cessation** et des **dommages et intérêts**. Le fichier clients contient des **données personnelles** : cette fuite est aussi à examiner au regard du RGPD (notification éventuelle).
</details>

**7.** **Rédigez une recommandation** de huit lignes au gérant.

<details markdown="1">
<summary>Voir la réponse attendue</summary>

Réponse type : (1) **régulariser Karim** par un contrat de cession ; (2) renforcer le **secret** (journaux d'accès, procédure de départ, mention « confidentiel ») ; (3) **réviser** les clauses de non-concurrence des contrats, avec temps, espace, emploi et **contrepartie financière** ; (4) ne pas compter sur le **brevet** ; (5) agir contre Tom sur le fondement de la **faute** et de la concurrence déloyale ; (6) examiner le volet **RGPD**. La réponse doit **trancher** et **hiérarchiser**.
</details>

## Je sais faire

Coche honnêtement ; ce que tu ne coches pas se reprend avant la séance suivante.

- [ ] Dire à qui appartient un logiciel (salarié, prestataire)
- [ ] Citer le contenu d'une cession de droits
- [ ] Vérifier les trois conditions du secret des affaires
- [ ] Vérifier la validité d'une clause de non-concurrence
- [ ] Expliquer pourquoi le logiciel n'est pas brevetable « en tant que tel »

**Ce que je dois reprendre :** ______________________

**Ma question à poser à l'enseignant :** ______________________
