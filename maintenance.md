# Maintenance des plateformes publiques

Le tableau ci-dessous indique qui maintient les plateformes opérées
par Etalab.  La colonne « Administration » indique si des agents
publics peuvent créer des comptes sur la plateforme.

| Service                 | Etalab | Administration | Public | Référent          |
|-------------------------|--------|----------------|--------|-------------------|
| www.data.gouv.fr        | ✓      | ✓              | ✓      | Équipe datagouv   |
| transport.data.gouv.fr  |        |                |        | Équipe Transport  |
| entreprise.data.gouv.fr |        |                |        | Équipe Entreprise |
| adresse.data.gouv.fr    |        |                |        | Équipe Géo        |
| cadastre.data.gouv.fr   |        |                |        | Équipe Géo        |
| geo.data.gouv.fr        |        |                |        | Équipe Géo        |
| geo.api.gouv.fr         |        |                |        | Équipe Géo        |
| app.dvf.etalab.gouv.fr  |        |                | ✓      | Équipe Géo / MP   |
| www.etalab.gouv.fr      | ✓      |                |        | AB / SD / BG      |
| code.etalab.gouv.fr     |        |                | ✓      | BG                |
|-------------------------|--------|----------------|--------|-------------------|
| mastodon.etalab.gouv.fr | ✓      |                | ✓      | BG                |
| forum.etalab.gouv.fr    | ✓      |                | ✓      | BG                |
|-------------------------|--------|----------------|--------|-------------------|
| piaf.etalab.studio      |        |                | ✓      | AB / GL           |

# Maintenance des outils d'Etalab

La tableau ci-dessous indique, pour chaque outil opéré par Etalab, qui
peut s'en servir et qui est responsable de sa maintenance.

| Service                         | EIG | Etalab | DINSIC | Référent |
|---------------------------------|-----|--------|--------|----------|
| nextcloud.data.gouv.fr          |     | ✓      | ✓      | ?        |
| webmail.data.gouv.fr            |     | ✓      | ✓      | ?        |
| mail.data.gouv.fr               |     | ✓      | ✓      | ?        |
| pfa.data.gouv.fr                |     | ✓      | ✓      | ?        |
| eig.etalab.gouv.fr              | ✓   | ✓      |        | BG / AA  |
| stats.data.gouv.fr              |     | ✓      | ✓      | AB       |
| sentry.data.gouv.fr             |     | ✓      | ✓      | AB       |
| infolettres.etalab.gouv.fr      |     | ✓      |        | BG       |
| listes.etalab.gouv.fr           |     | ✓      |        | BG       |
|---------------------------------|-----|--------|--------|----------|
| status.etalab.studio            |     | ✓      |        | AB / SD  |
| eig3.ma-semaine.eig-forever.org | ✓   |        |        | AA       |
| pad.etalab.studio               |     | ✓      | ✓      | AB       |
| yunohost.etalab.studio/date     | ✓   | ✓      |        | BG       |

# Règles de maintenance des plateformes et outils

- Les services en `eig-forever.org` sont soit dédiés au programme EIG
  soit expérimentaux.  Il n'y a pas de contrainte de disponibilité, de
  sauvegarde ou de supervision sur ces services.

- Les services en `etalab.studio` sont expérimentaux.  Il n'y a pas de
  contrainte de disponibilité, de sauvegarde ou de supervision sur ces
  services.

- Les services mis à disposition du reste de l'administration le sont
  sans contrainte de disponibilité, de sauvegarde ou de supervision.

- Lorsqu'un outil d'Etalab est mis à disposition de la DINSIC, toutes
  les fonctionnalités implémentées doivent aussi servir à Etalab.  Par
  exemple, si beta.gouv.fr a besoin d'un module sur stats.data.gouv.fr
  ce module n'est installé et maintenu que s'il est aussi utilisé par
  un service d'Etalab.

# Quel « liste » utiliser pour les mails ?

Il y a trois types de _listes_:

- **Les listes de destinataires** : il s'agit de la fonction "groupe"
  de certains clients de messagerie.  Si vous avez souvent besoin
  d'écrire à un même groupe de desinataires sans qu'il soit nécessaire
  que chacun puisse répondre à tous, le mieux est d'ouvrir un _alias_
  @data.gouv.fr.
  
- **Les listes de diffusion** : il s'agit de _newsletters_ envoyées à
  un grand nombre de personnes, sans que les messages envoyés soient
  archivés.  Les infolettres d'Etalab sont sur
  [infolettres.etalab.gouv.fr](https://infolettres.etalab.gouv.fr/). Si
  vous avez besoin d'une newsletter, envoyez un mail à
  Bastien.  

- **Les listes de discussion** : il s'agit de groupes de discussion
  par emails, dont les messages sont archivés et lisible soit en
  public soit pour les seuls abonnés de la liste.  Vous avez besoin
  d'une liste de discussion pour un nombre limité de personnes (en
  général moins de 100) et lorsque vous souhaitez que les personnes
  puissent se répondre entre elles.  Les listes de discussion d'Etalab
  sont sur
  [listes.etalab.gouv.fr](https://listes.etalab.gouv.fr/listinfo).  Si
  vous avez besoin d'une nouvelle liste, envoyez un mail à Bastien.

