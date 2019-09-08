# Accès aux outils et maintenance

Cette page expose les règles de maintenance des outils de travail
déployés par Etalab.  Il s'agit bien des *outils de travail* et non de
l'ensemble des *services* proposés par Etalab (data.gouv.fr, etc.).

# Qui peut se servir de ces outils ?

Le tableau ci-dessous indique, pour chaque service maintenu par
Etalab, qui peut s'en servir comme outil :

| Service                         | EIG | Etalab | DINSIC | Administration | Public |
|---------------------------------|-----|--------|--------|----------------|--------|
| www.etalab.gouv.fr              |     | ✓      |        |                |        |
| status.etalab.studio            |     | ✓      |        |                |        |
| lists.eig-forever.org           |     | ✓      |        |                |        |
| eig.etalab.gouv.fr              | ✓   | ✓      |        |                |        |
| eig3.ma-semaine.eig-forever.org | ✓   |        |        |                |        |
| lists.eig-forever.org           | ✓   | ✓      |        |                |        |
| nextcloud.data.gouv.fr          |     | ✓      | ✓      |                |        |
| webmail.data.gouv.fr            |     | ✓      | ✓      |                |        |
| pfa.data.gouv.fr                |     | ✓      | ✓      |                |        |
| pad.etalab.studio               |     | ✓      | ✓      |                |        |
| stats.data.gouv.fr              |     | ✓      | ✓      |                |        |
| sentry.data.gouv.fr             |     | ✓      | ✓      |                |        |
| mastodon.etalab.gouv.fr         | ✓   | ✓      | ✓      | ✓              |        |
| forum.etalab.gouv.fr            |     | ✓      | ✓      | ✓              | ✓      |

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
