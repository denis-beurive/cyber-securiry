# Firefox configuration

Ce document a été rédigé en se basant sur la version `105.0` (64 bits) de Firefox:

![](images/firefox/firefox-version.png)

## Sécurisation des mots de passe enregistrés

Firefox permet de sécuriser l'accès à sa base de mots de passe sauvegardés, ainsi que l'utilisation de cette dernière, par un mot de passe, appelé "mot de passe principal" (exigé au démarrage du navigateur).

Procédure à suivre pour définir un "mot de passe principal" : https://support.mozilla.org/fr/kb/utiliser-mot-passe-principal-proteger-identifiants

Veuillez noter que la documentation en ligne publiée par Mozilla peut être imprécise ou présenter quelques petites erreurs. Sur mon installation de Firefox (à jour à l'heure où ces lignes ont été écrites), la procédure pour définir le mot de passe principal est légèrement différente de celle présentée sur la documentation officielle. Ci-dessous, vous trouverez la procédure à suivre pour la version `105.0` (64 bits) de Firefox (en français).

Dans le bandeau de commande de Firefox, cliquez sur l'icône ci-dessous (en haut, à droite):

![](images/firefox/firefox-menu-start.png)

Puis, sur:

`Paramètres` => `Vie privée et sécurité` => `Utiliser un mot de passe principal`

## Suppression de toutes les traces de navigation

Firefox peut être configuré de façon à ce qu'il supprime toutes les traces de navigation lorsque vous mettez fin à son exécution. On parle de "navigation privée".

Procédure à suivre pour activer la "navigation privée": https://support.mozilla.org/fr/kb/navigation-privee-naviguer-avec-firefox-sans-enregistrer-historique

Veuillez chercher la section intitulée "_Paramétrer Firefox pour utiliser automatiquement la navigation privée_". Cette section présente la procédure à suivre pour définir le mode de navigation privé comme mode par défaut.

Veuillez noter que vous pouvez:
* Démarrer une fenêtre (ou un onglet) de navigation privée "à usage unique". Lorsque cette fenêtre (ou cet onglet) est fermé, toutes les traces de navigation sont supprimées.
* Configurer Firefox de telle façon que le mode de navigation privé soit le mode par défaut, activé automatiquement au démarrage de l'application. Cette configuration est recommandée. Le texte qui suit résume la procédure à suivre pour définir le mode de navigation privé en tant que mode par défaut.

Dans le bandeau de commande de Firefox, cliquez sur l'icône ci-dessous (en haut, à droite):

![](images/firefox/firefox-menu-start.png)

Puis, sur:

`Paramètres` => `Vie privée et sécurité` => `Historique`... (Règles de conservation), puis sélectionner "Ne jamais conserver l'historique".

