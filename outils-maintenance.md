# Accès aux outils et maintenance

Cette page expose les règles de maintenance des outils de travail
déployés par Etalab.  

Il s'agit bien des *outils de travail* et non de l'ensemble des
*services* proposés par Etalab (data.gouv.fr, etc.).

# Qui peut se servir de ces outils ?

Le tableau ci-dessous indique, pour chaque service maintenu par
Etalab, qui peut s'en servir comme outil :

| Service                         | EIG | Etalab | DINSIC | Administration | Public | Référent |
|---------------------------------|-----|--------|--------|----------------|--------|----------|
| www.etalab.gouv.fr              |     | ✓      |        |                |        | AB / SD  |
| status.etalab.studio            |     | ✓      |        |                |        | AB / SD  |
| lists.eig-forever.org           |     | ✓      |        |                |        | BG       |
| infolettres.etalab.gouv.fr      |     | ✓      |        |                |        | BG       |
| eig.etalab.gouv.fr              | ✓   | ✓      |        |                |        | BG / AA  |
| eig3.ma-semaine.eig-forever.org | ✓   |        |        |                |        | AA       |
| nextcloud.data.gouv.fr          |     | ✓      | ✓      |                |        | ?        |
| webmail.data.gouv.fr            |     | ✓      | ✓      |                |        | ?        |
| pfa.data.gouv.fr                |     | ✓      | ✓      |                |        | ?        |
| pad.etalab.studio               |     | ✓      | ✓      |                |        | AB       |
| stats.data.gouv.fr              |     | ✓      | ✓      |                |        | AB       |
| sentry.data.gouv.fr             |     | ✓      | ✓      |                |        | AB       |
| mastodon.etalab.gouv.fr         | ✓   | ✓      | ✓      | ✓              |        | BG       |
| forum.etalab.gouv.fr            |     | ✓      | ✓      | ✓              | ✓      | ?        |
| yunohost.etalab.studio/date     | ✓   | ✓      |        |                |        | BG       |
| listes.etalab.gouv.fr           |     | ✓      |        |                |        | BG       |

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

# Règles de maintenance de ces outils

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
