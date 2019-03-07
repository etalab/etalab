# Guide des algorithmes publics

La mission Etalab accompagne les administrations dans l'application du nouveau cadre juridique sur les algorithmes publics.
Ce guide est composé de trois parties qui peuvent se lire de manière indépendante.
- La première partie donne des **éléments de contexte**: qu'est-ce qu'un algorithme ? à quoi servent les algorithmes dans le secteur public ? 
- La seconde partie détaille les **enjeux en termes d'éthique et de responsabilité**, 
- La troisième partie présente le **cadre juridique applicable** suite à l'adoption de la loi pour une République numérique.

## A qui est-il destiné ?

Ce guide est destiné à l'ensemble des administrations et organisations chargées d'une mission de service public qui concoivent, développent et opèrent des traitements algorithmiques.

## Comment contribuer ?

Vous pouvez contribuer à améliorer ce guide en proposant une modification dans cette page, ou en contactant directement Simon Chignard (Mission Etalab - Direction interministérielle du numérique): simon@data.gouv.fr

# 1- A quoi servent les algorithmes publics ?

Commencons tout d'abord par une définition: **qu'est qu'un algorithme** ? 
> Selon la CNIL, un algorithme est une "*suite finie et non ambigüe d’étapes ou d’instructions permettant d’obtenir un résultat à partir d’éléments fournis en entrée"*.

Retenons que, selon cette définition, un algorithme peut donc exister indépendament d'un traitement informatique. Une grille de notation "papier" utilisée par une administration peut donc être considérée comme un algorithme.

Nous avons recensé plusieurs types d'usages des algorithmes dans les administrations, avec une série d'exemples associés.

| Usages      | Exemples |
| ----------- | ----------- |
| Attribuer des droits, calculer des montants selon des règles prédéfinies| Calcul des taxes et des impôts, attribution de prestations sociales, ... |
| Réaliser un appariement entre une "offre" et une "demande"   | Gestion de la mobilité des agents (RH), accès à l'enseignement supérieur (Parcoursup), attribution de places en crèches, ... |
| Prédire une situation ou un risque en analysant des données  | Prédire un risque de défaillance d'une entreprise (Signaux Faibles), cibler les contrôles de lutte contre la fraude fiscale, ...        |
| Aider à la décision des usagers | Aider les demandeurs d'emploi à cibler leurs candidatures spontanées (La Bonne Boîte), simuler le coût d'une embauche, ...        |

## Décision automatisée ou aide à la décision ?

Certains algorithmes peuvent être utilisés pour prendre des décisions envers des individus, personnes physiques (agents, usagers du service public, ...) ou morales (entreprises, autres acteurs publics, ...).
On les distingue selon le **degré d'intervention humaine dans la prise de décision**: 
- Certains fonctionnent sans intervention humaine (par exemple le calcul de l'impôt des 37 millions de foyers fiscaux). On parle alors de **traitement automatisé**.

- D'autres sont des outils d'**aide à la décision**: ils aident l'humain à prendre une décision, par exemple en classant des dossiers selon des critères de priorité pour qu'ils soient ensuite étudiés par une commission qui prendra formellement la décision.

# 2 - Les enjeux des algorithmes publics

## Algorithmes du secteur public vs. algorithmes du secteur privé

Tout le monde a entendu parler des algorithmes utilisés par les grandes entreprises du numérique. Citons quelques exemples: 
- le **PageRank** du moteur de recherche Google qui détermine les pages de résultats pour une requête,
- le **Newsfeed** qui détermine le contenu d'un fil d'actualités Facebook,
- l'**algorithme de tarification dynamique** d'Uber qui fait varier les prix des courses en fonction de la demande, 
- ...

Par rapport aux algorithmes mis en oeuvre par le secteur privé, les algorithmes publics ont des caractéristiques particulières: 
1. Ils sont censés **opérer au service de l'intérêt général**
2. Ils servent souvent à **exécuter le droit**, à (faire) appliquer la loi
3. Ils sont bien souvent **incontournables**, c'est à dire qu'il n'existe pas d'alternatives pour les usagers.

En ce sens, les algorithmes publics sont des formes de l'action publique et sont à ce titre soumis à la même forme d'exigence de redevabilité. Ils doivent "rendre des comptes".

## Comment les algorithmes publics peuvent-ils "rendre des comptes" ?

Ce ne sont pas tant les algorithmes eux-mêmes que les administrations qui les mettent en oeuvre qui doivent rendre des comptes. On parle de **principe de redevabilité**. Concrètement cela signifie: 
- **signaler**, en indiquant quand un algorithme est utilisé,
- **décrire**, en précisant le fonctionnement général de l'algorithme,
- **justifier**, en expliquant les objectifs poursuivis et les raisons du recours à cet algorithme,
- **expliquer ses effets**, en expliquant un résultat individuel mais aussi en précisant les impacts généraux et particuliers,
- **rendre accessible**, en publiant le code source et la documentation associée,
- **permettre la contestation**, en indiquant les voies de recours possibles.

Il faut noter que plusieurs manières de rendre des comptes (se signaler, décrire, justifier, expliquer, ...) correspondent à des **obligations légales** introduites par la loi pour une République numérique ou plus récemment le Réglement général sur la protection des données (RGPD). La troisième partie de ce document présente le cadre juridique applicable.

## Comment rendre des décisions "justes" à l'aide des algorithmes ? ##

La prise de décision (automatisée ou non) constitue l'un des principaux usages des algorithmes dans le secteur public. Par exemple pour déterminer le droit à une aide sociale ou encore gérer la mobilité des enseignants. 
Nous nous intéressons ici au **principe de justice**: quelles sont les conditions requises pour qu'un individu concerné par la décision la juge "juste" ? 

Nous avons identifié **quatre critères** à respecter pour qu'une décision prise à l'aide d'un algorithme soit considéré comme juste: 
- la **transparence**: il faut que la procédure soit décrite,
- l'**intelligibilité**: il faut que la procédure soit comprise par les intéressés,
- la **loyauté**: il faut que la procédure décrite soit effectivement utilisée de manière complète et fidèle,
- l'**égalité de traitement**: il faut qu'aucun individu n'ait fait l'objet d'un traitement plus favorable (ou défavorable) que les autres individus concernés.

On notera qu'un individu peut tout à fait considérer comme juste une décision qui ne lui est pas favorable (si par exemple la décision consiste à lui refuser une indemnité car il n'est pas éligible selon les critères fixés par la loi).

# 3 - Le cadre juridique applicable

La loi pour une République numérique, et plus récemment le Réglement sur la protection des données à caractère personnel (RGPD) ont introduit de nouvelles dispositions concernant les algorithmes publics. Ces dispositions visent à introduire une plus grande transparence et une plus grande redevabilité de ces systèmes, en particulier quand ils sont utilisés pour prendre des décisions.

## Qui est concerné par la transparence des algorithmes ?

Le code des relations entre le public et l'administration (CRPA) précise le périmètre des administrations et des traitements concernés. 
Si: **une administration d’Etat, une collectivité, un organisme de droit public ou de droit privé intervenants dans le cadre d’une mission de service public**,
- vous utilisez un **traitement algorithmique**,
- à l’aide de ce traitement, vous prenez des **décisions administratives individuelles envers des personnes physiques ou morales, de droit public ou privé nommément désignées**,
- et que ce traitement n’est **pas couvert par l’un des secrets définis par la loi**, et en particulier: délibérations du Gouvernement, défense nationale, conduite de la politique extérieure, sûreté de l’Etat, sécurité publique, sécurité des personnes ou des systèmes d’information, recherche et prévention d’infractions, etc. 

Alors vous devez remplir les nouvelles obligations liées à la **transparence des algorithmes**.

## Quelles sont ces obligations ?

La loi définit 3 obligations: fournir une **information générale** (article L.312-1-13 du Code des relations entre le public et l'administration), faire figurer une **mention explicite** (article L.311-3-1) et **fournir une information individuelle à la demande** (article L.311-3-1-2).

A noter que l'obligation d'information générale ne s'applique uniquement qu'aux administrations comptant plus de 50 équivalents temps plein (agents et/ou salariés) et aux collectivités de moins de 3500 habitants. 

Concrètement, si vous remplissez les conditions, alors vous devrez:
- au titre de l'information générale: **publier en ligne** les règles définissant les principaux traitements utilisés dans l’accomplissement de vos missions lorsqu’ils fondent des décisions individuelles,
- au titre de la mention explicite: **faire figurer en ligne et sur les documents** (avis, notifications) une mention précisant les finalités du traitement, le rappel du droit de communication, les modalités d’exercice de ce droit,
- au titre de l'information individuelle: **fournir à la demande de l’intéressé** : le degré et le mode de contribution du traitement algorithmique à la prise de décision, les données traitées et leurs sources, les paramètres de traitement et leur pondération, appliqués à la situation de l'intéressé, les opérations effectuées par le traitement.

On notera que ces obligations s'appliquent à l'ensemble des traitements qui fondent des décisions administratives individuelles, quel que soit le degré d'intervention humaine. Elles concernent donc aussi bien les traitements automatisés que les outils d'aide à la décision.

Cependant, le législateur a introduit en 2018 dans la loi dite "Informatique et libertés" une contrainte supplémentaire concernant les traitements automatisés (sans intervention humaine): à compter du 1er juillet 2020, tout traitement automatisé devra comporter, **à peine de nullité**, l'obligation de mention explicite [article 10 (https://www.legifrance.gouv.fr/affichTexteArticle.do;jsessionid=244F9CD5D2EFCDA76E8894D66088713F.tplgfr28s_1?idArticle=LEGIARTI000037090394&cidTexte=LEGITEXT000006068624&dateTexte=20190307) de la loi du 6 janvier 1978).

## Un outil pour tester vos connaissances






