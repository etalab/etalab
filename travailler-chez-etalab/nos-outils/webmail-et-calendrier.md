# Webmail et calendrier

## Configurer les e-mails, les calendriers et les contacts <a href="#configurer-les-e-mails-les-calendriers-et-les-contacts" id="configurer-les-e-mails-les-calendriers-et-les-contacts"></a>

Cette page explique comment accéder à et utiliser la messagerie d’Etalab pour envoyer et recevoir des e-mails depuis un ordinateur et un mobile.

### Accéder aux e-mails par des protocoles ouverts

#### Accéder aux e-mails sur le web (SOGO)

Le webmail est un site internet accessible par tous les utilisateurs authentifiés, pour consulter ses e-mails à distance. Le protocole utilisé est en https, donc sécurisé.

Muni de vos identifiants, vous pouvez accéder au webmail par l’intermédiaire de l’adresse : [https://webmail.data.gouv.fr](https://webmail.data.gouv.fr).

**S’abonner au calendrier d’un collaborateur**

Ce paragraphe décrit comment afficher le calendrier d’un collaborateur, ou de l’agenda d’équipe, sur votre profil Sogo.

En premier lieu, il faut l’accord de votre collaborateur et que celui-ci vous autorise l’accès à son calendrier.

**Définir les droits aux calendriers**

Actions à réaliser par votre collaborateur sur son compte Sogo :

1. Se rendre sur le webmail : [https://webmail.data.gouv.fr](https://webmail.data.gouv.fr) ;
2. Aller dans l’onglet `Agenda` ;
3. Dans la section agenda, faite un clique droit sur votre `agenda personnel` puis `Partage..` ;
4. Une fenêtre s’ouvre, puis on clique sur `Ajouter` ;
5. Une deuxième fenêtre s’ouvre pour sélectionner le collaborateur voulu ;
6. On sélectionne le nom du collaborateur, puis on clique sur `Ajouter` ;
7. La fenêtre se ferme, et sur la fenêtre précédente on double clique sur le nom du collaborateur ;
8. Une troisième fenêtre s’ouvre, et on défini les droits que l’on souhaite définir ;
9. On valide en cliquant sur `Mettre à jour`.

En second temps, vous devez ajouter son calendrier à votre compte.

**Ajout du calendrier d’un collaborateur**

Action à réaliser par vous même sur votre compte Sogo :

1. Se rendre sur le webmail : [https://webmail.data.gouv.fr](https://webmail.data.gouv.fr)
2. Aller dans l’onglet `Agenda`
3. Dans la section agenda, cliquez sur la 3ème icone (S’inscrire à un agenda.. )
4. Une fenêtre s’ouvre et on renseigne dans le champs, le nom ou l’email du collaborateur.
5. On clique sur le `+` en face du nom du collaborateur et on sélectionne `Personnal Calendar`
6. On clique sur `Ajouter`, c’est terminé.

#### S’abonner à l’agenda d’équipe

Action à réaliser par vous même sur votre compte Sogo :

1. Se rendre sur le webmail : [https://webmail.data.gouv.fr](https://webmail.data.gouv.fr) ;
2. Aller dans l’onglet `Agenda` ;
3. Dans la section agenda, cliquez sur la 3ème icône (S’inscrire à un agenda…) ;
4. Une fenêtre s’ouvre et on renseigne dans le champs, `équipe` ;
5. On clique sur le `+` en face du nom et on sélectionne `Personnal Calendar` ;
6. On clique sur `Ajouter`, c’est terminé.

Si vous souhaitez utiliser un client lourd type Thunderbird, vous pouvez suivre les instructions ci-après.

### Accéder aux e-mails par un client de messagerie

#### Configurer l’accès avec Thunderbird sur ordinateur

Pour les clients de messagerie de type Thunderbird, la configuration des paramètres de comptes est automatique.

Les champs qu’il faut renseigner sont les suivants:

* la description du compte ;
* l’adresse e-mail ainsi que ;
* le mot de passe.

#### Configurer l’accès avec un mobile Android

Concernant les autres clients de messagerie comme les téléphones par exemple, les champs à renseigner doivent être similaire à ce qui suit:

Accédez aux paramètres des comptes dans `Paramètre` > Section Compte, `Ajouter un compte` > `IMAP`

**Service IMAP (réception)**

Renseignez les champs suivants :

```
Utilisateur       : felix.defrance@data.gouv.fr (Ajustez à votre mail)
Password          : *****************
Serveur IMAP      : imap.data.gouv.fr
Type de sécurité  : SSL/TLS si disponible
Port              : 993
```

**Server SMTP (envoi)**

Renseignez les champs suivants :

```
Serveur                   : smtp.data.gouv.fr
Type de sécurité          : STARTTLS
Port                      : 587
Type d’authentification   : LOGIN ou PLAIN ou AUTOMATIC
Utilisateur / Password    : Idem que pour le service IMAP
```

#### Configurer l’accès avec un iPhone

Pour les téléphones d’Apple procédez comme suit :

1. Appuyez sur `Réglages` > `Mails, Contacts, Calendrier` > `Ajouter un compte` > `Autre` ;
2. Appuyez sur `Ajouter un compte mail`.

Puis renseignez les champs suivants :

```
Nom         : Felix Defrance (Ajustez à votre nom)
Adresse     : felix.defrance@data.gouv.fr (Ajustez à votre mail)
Mot de passe: **************
Description : Félix Defrance Etalab
```

Appuyez sur `Suivant`.

Ensuite, appuyez sur `IMAP` :

1. Entrez `webmail.data.gouv.fr` aux différents endroits appelés `Nom d’hôte` ;
2. Entrez votre adresse email complète aux différents endroits appelés `Nom d’utilisateur` ;
3. Entrez le `Mot de passe` de votre adresse email aux différents endroits demandés ;
4. Appuyez sur `Suivant` puis enregistrez ces paramètres.

Ensuite on s’assure que le protocole SSL est activé :

1. Appuyez sur `Réglages` > `Mails, Contacts, Calendrier` ;
2. Aller dans le compte que vous venez de configurer, puis dans la section `Réglage de la réception` assurez vous que SSL est activé.

### Accéder aux calendriers avec CalDAV et CardDAV

Cette section de la page explique comment configurer l’accès aux calendriers et aux contacts.

#### Configurer l’accès avec Thunderbird

Pour activer les fonctionnalités de calendrier et de contacts avecThunderbird, il faut installer le plugin SOGO conntector disponible ici[http://www.sogo.nu/downloads/frontends.html](http://www.sogo.nu/downloads/frontends.html).

Une fois le plugin installé et Thunderbird relancé, on configure le carnet d’adresse :

1. Allez dans `Outils` > `Carnet d’adresse` ;
2. Allez dans `Fichier` > `Nouveau` > `Carnet d’adresse distant` ;
3. Renseignez votre nom ainsi que l’URL : https://webmail.data.gouv.fr/SOGo/dav/felix.defrance/Contacts/personal/ (Ajustez à votre nom et prénom) ;
4. Cochez la synchronisation périodique et définissez la fréquence à laquelle vos contacts doivent être synchronisés.

De la même manière, on procède pour le calendrier :

1. Allez dans `Fichier` > `Nouveau` > `Agenda` ;
2. Cochez `Sur le réseau` ;
3. Cochez Format : `CalDAV` ;
4. Emplacement : https://webmail.data.gouv.fr/SOGo/dav/felix.defrance/Calendar/personal/ (Ajustez à votre nom et prénom) ;
5. Cliquez sur suivant, puis renseigner votre Nom, une couleur. Sélectionnez le compte de messagerie auquel le calendrier est attaché.

**Ajout de l’agenda d’équipe**

Pour ajouter le calendrier partagé de l’équipe Etalab, on procède comme il suit :

1. Allez dans `Agenda` > `Fichier` > `Nouveau` > `Agenda…` ;
2. Cochez `Sur le réseau` ;
3. Cochez Format : `CalDAV` ;
4. Emplacement : https://webmail.data.gouv.fr/SOGo/dav/agenda.etalab/Calendar/personal/ ;
5. Cliquez sur suivant, puis renseigner votre Nom, une couleur ;
6. Sélectionnez le compte de messagerie auquel le calendrier est attaché. (le votre).

#### Configurer l’accès avec un mobile Android

L’application DAVdroid, permet de synchroniser les contacts ainsi que les calendriers.

**Configuration de DAVdroid**

L’outil est téléchargeable depuis googleplay ou F-droid :

* [https://f-droid.org/repository/browse?fdfilter=davdroid\&fdid=at.bitfire.davdroid](https://f-droid.org/repository/browse?fdfilter=davdroid\&fdid=at.bitfire.davdroid)
* [https://play.google.com/store/apps/details?id=at.bitfire.davdroid\&hl=fr](https://play.google.com/store/apps/details?id=at.bitfire.davdroid\&hl=fr)

On lance Davdroid puis on clique sur l’icone de la clé avec un `+`, on selectionne DAVdroid et on renseigne comme il suit : [webmail.data.gouv.fr/SOGo/dav](https://%20webmail.data.gouv.fr/SOGo/dav)

```
Utilisateur : felix.defrance@data.gouv.fr (Ajustez à votre mail)
Mot de passe  : **********
```

Et on décoche l’authentification par `Digest`.

#### Configurer l’accès avec un iPhone

**Apple Calendrier**

Pour ajouter un calendrier, procédez comme suit :

Appuyez sur `Réglages` > `Mails, Contacts, Calendrier` > `Ajouter un compte` > `Autre`

Dans la section Calendrier, appuyez sur `Ajouter un compte CalDAV` :

```
Server  : https://webmail.data.gouv.fr/SOGo/dav/felix.defrance/ (Ajustez à votre nom et prenom)
Nom     : felix.defrance@data.gouv.fr (Ajustez à votre mail)
Password: **********************
Description: Félix Defrance Etalab
```

#### Configurer l’accès iCal/Calendar.app

Pour ajouter un calendrier, procédez comme suit :

Appuyez sur `Calendar` > `Preferences...` > `+`

```
Account information

Username: votre email complet
Password: votre mot de passe mail

Server Settings

Server Address: webmail.data.gouv.fr
Server Path: /SOGo/dav/tamkien.duong/
Port: 443
Use SSL: ✅
```

**Apple Contacts**

Pour ajouter un carnet d’adresse, procédez comme suit :

Appuyez sur `Réglages` > `Mails, Contacts, Calendrier` > > `Ajouter un compte` > `Autre`

Dans la section Contacts, appuyez sur `Ajouter un compte CardDAV` :

```
Server : https://webmail.data.gouv.fr/SOGo/dav/felix.defrance/ (Ajustez à votre nom et prenom)
Nom : felix.defrance@data.gouv.fr (Ajustez à votre mail)
Password: **********\*\***********
Description: Félix Defrance Etalab
```

### Configurer un message d’absence prolongée

Pour configurer un message d’absence prolongée sur sa boîte mail @data.gouv.fr, voici la procédure :

* Se rendre sur le [webmail](https://webmail.data.gouv.fr)
* Aller dans l’onglet “Préférences” du menu principal
* Aller dans l’onglet “Absence prolongée” dans le menu des préférences

\
