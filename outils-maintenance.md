
# Accès aux outils et maintenance

Cette page expose les règles de maintenance des outils de travail
déployés par Etalab.  Il s'agit bien des *outils de travail* et non de
l'ensemble des *services* proposés par Etalab (data.gouv.fr, etc.).


# Qui peut se servir de ces outils ?

Le tableau ci-dessous indique, pour chaque service maintenu par
Etalab, qui peut s'en servir comme outil :

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Service</th>
<th scope="col" class="org-left">EIG</th>
<th scope="col" class="org-left">Etalab</th>
<th scope="col" class="org-left">DINSIC</th>
<th scope="col" class="org-left">Administration</th>
<th scope="col" class="org-left">Public</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">www.etalab.gouv.fr</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">status.etalab.studio</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">lists.eig-forever.org</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">eig.etalab.gouv.fr</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">eig3.ma-semaine.eig-forever.org</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">lists.eig-forever.org</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">nextcloud.data.gouv.fr</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">webmail.data.gouv.fr</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">pfa.data.gouv.fr</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">pad.etalab.studio</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">stats.data.gouv.fr</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">sentry.data.gouv.fr</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">mastodon.etalab.gouv.fr</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">forum.etalab.gouv.fr</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
<td class="org-left">✓</td>
</tr>
</tbody>
</table>


# Règles de maintenance de ces outils

-   Les services en `eig-forever.org` sont soit dédiés au programme EIG
    soit expérimentaux.  Il n'y a pas de contrainte de disponibilité, de
    sauvegarde ou de supervision sur ces services.

-   Les services en `etalab.studio` sont expérimentaux.  Il n'y a pas de
    contrainte de disponibilité, de sauvegarde ou de supervision sur ces
    services.

-   Les services mis à disposition du reste de l'administration le sont
    sans contrainte de disponibilité, de sauvegarde ou de supervision.

-   Lorsqu'un outil d'Etalab est mis à disposition de la DINSIC, toutes
    les fonctionnalités implémentées doivent aussi servir à Etalab.  Par
    exemple, si beta.gouv.fr a besoin d'un module sur stats.data.gouv.fr
    ce module n'est installé et maintenu que s'il est aussi utilisé par
    un service d'Etalab.

