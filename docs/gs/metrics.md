# Charger des indicateurs


## Créer une collection

Sur Statit, les indicateurs font partie de collections.

Les collections contiennent des indicateurs qui se ressemblent. Ce sont un petit peu comme des étagères avec des livres de même nature ou des répertoires sur un ordinateur.

Si la collection avec laquelle vous souhaitez travailler existe déjà, passez à l'étape suivante. Sinon, vous allez d'abord devoir en créer une.

Rendez-vous d'abord sur la page d'accueil du compte 'Organisation' - soit en vous connectant avec les identifiants de votre compte 'Organisation', soit en cliquant sur l'organisation dans 'Mes organisations' dans le menu en haut à droite.

![](/img/publisher-fr_gs_metrics_0.png){: style="width:700px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}

Si tout va bien, vous devez voir s'afficher les onglets 'Accueil', 'Collections' et 'Membres'

*Un problème?*

> Si vous ne voyez pas s'afficher ces onglets, rendez-vous dans 'Mon Compte' en haut à droite et dans la partie 'Configuration' et changez la vue pour 'Organisation'.

> Si la vue 'Organisation' n'est pas proposée, cela signifie que le compte n'est pas un compte 'Organisation', suivez les instructions de la [section précédente](index.md))


Cliquez ensuite sur l'onglet 'Collections' et cherchez le bouton 'Créer une collection' en bas. Cliquez dessus.

![](/img/publisher-fr_gs_metrics_1.png){: style="width:700px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}

Vous êtes prêt à créer une collection.

- Choisissez d'abord un identifiant pour la collection. C'est un nom sans espace avec uniquement des lettres, des chiffres, les tirets '-_' et le '.'. Prenez par exemple 'test'.

- Ajoutez ensuite un nom pour la collection 'Une collection test'.

- Définissez l'accès. Choisissez 'Public'. Cela signifie que tous les membres de l'organisation auront accès à la collection.

- Enfin, ajouter une description brève, par exemple 'Ma première collection'.

Cliquez sur 'Enregistrer'. C'est parti

![](/img/publisher-fr_gs_metrics_2.png){: style="width:700px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}


## Ajouter des indicateurs

Vous êtes de nouveau à l'accueil de l'organisation.

Cliquez sur l'onglet 'Collections' et cliquez sur la collection 'test' que vous venez de créer.

![](/img/publisher-fr_gs_metrics_3.png){: style="width:700px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}

La collection est vide. Nous allons maintenant ajouter des indicateurs.

Cliquez sur l'onglet 'Indicateurs' et puis sur le bouton 'Ajouter des indicateurs'

![](/img/publisher-fr_gs_metrics_4.png){: style="width:700px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}


## Télécharger un fichier 'exemple'

Pour commencer simplement, nous allons charger un fichier 'exemple'.

Allez en bas de la page et cliquez sur 'Indicateurs simples'. Si vous travaillez avec Microsoft Excel, sélectionnez Excel. Sinon, choisissez Csv.

![](/img/publisher-fr_gs_metrics_5.png){: style="width:400px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}

En cliquant sur le choix, un fichier exemple va être téléchargé. L'image ci-dessous montre le fichier Excel.

![](/img/publisher-fr_gs_metrics_6.png){: style="width:700px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}

Ouvrez le fichier et observez les lignes:

- La première ligne contient les identifiants des indicateurs
- La seconde ligne le nom des indicateurs
- La troisième ligne la description des indicateurs s'il y en a une
- La quatrième l'unité
- La cinquième la fréquence: D est pour Jour (Day), W pour Semaine (Week), M pour Mois (Month), Q pour Trimestre (Quarter) et enfin Y pour Année (Year)
- A partir de la sixième ligne, nous retrouvons les valeurs de l'indicateur et la date de l'observation

Ce fichier est un exemple qui peut être utilisé pour charger des indicateurs.


## Charger les indicateurs

Dans notre exemple, les identifiants commencent par 'industrieco/test'. C'est l'identifiant de la collection.

Dans votre cas, les identifiants du fichier téléchargé commenceront par le nom d'utilisateur du compte, suivi de l'identifiant de la collection ('test' si vous avez choisi cela).

Prenez maintenant le fichier avec la souris et déposez le dans la zone grise de la page. Automatiquement, le fichier va être lu et analysé.

![](/img/publisher-fr_gs_metrics_7.png){: style="width:400px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}

*Un problème ?*
> Si vous n'êtes pas familier cette technique, vous pouvez cliquer sur le lien 'cliquez là' pour sélectionner manuellement le fichier exemple à chargé

Une fenêtre apparait avec le résultat de la lecture du fichier: le nombre d'indicateurs valides, invalides et les identifiants des indicateurs qui vont être chargés.

![](/img/publisher-fr_gs_metrics_8.png){: style="width:400px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}

Cliquez sur 'Chargez les indicateurs'

Au bout de quelques secondes, vous êtes de nouveau sur la page d'accueil. Cliquez sur l'onglet 'Indicateurs'. Les indicateurs sont bien là.

## Prochaines étapes

Vous avez maintenant charger vos premiers indicateurs. Vous pouvez essayer de charger les autres fichiers 'exemple' ou de charger vos propres indicateurs.

Si vous souhaitez comprendre comment inviter des collaborateurs, continuez [ici](members.md), si vous souhaitez voir comment publier des graphiques, c'est [là](charts.md)
