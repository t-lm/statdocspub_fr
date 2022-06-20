# Charger des indicateurs


## Créer une collection

Sur Statit, les indicateurs font partie de collections.

Les collections sont des ensembles d'indicateurs qui se ressemblent. Ce sont un petit peu comme des étagères avec des livres de même nature ou comme des répertoires sur un ordinateur.

Si vous ne travaillez pas dans une collection déjà créée, vous allez d'abord devoir en créer une. Suivez les étapes ci-dessous. Si la collection est déjà créée, passez à l'étape suivante.

Rendez-vous sur la page d'accueil de votre organisation.

![](/img/publisher-fr_gs_metrics_0.png){: style="width:700px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}

Si vous ne voyez pas s'afficher le menu avec les onglets 'Collections' et 'Membres', cela signifie que vous n'avez pas la vue 'Utilisateur'. Rendez-vous dans 'Mon Compte' en haut à droite et dans la partie 'Configuration', changez la vue pour 'Organisation'.

Cliquez ensuite sur l'onglet 'Collections' et cherchez le bouton 'Créer une collection' en bas. Appuyez dessus.

![](/img/publisher-fr_gs_metrics_1.png){: style="width:700px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}

Vous êtes prêt à créer une collection. Choisissez d'abord un identifiant pour la collection. C'est un nom avec uniquement des lettres, des chiffres, les tirets '-_' et le '.'. Prenez par exemple 'test'.

Ajoutez ensuite un nom pour la collection 'Une collection test'.

Définissez l'accès. Choisissez 'Public'. Cela signifie que tous les membres de l'organisation auront accès à la collection.

Enfin, ajouter une description brève, par exemple 'Ma première collection'.

Cliquez sur 'Enregistrer'. C'est parti

![](/img/publisher-fr_gs_metrics_2.png){: style="width:700px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}


## Ajouter des indicateurs

Vous êtes de nouveau à l'accueil de l'organisation.

Cliquez sur l'onglet 'Collections' et cliquez sur la collection 'test' que vous venez de créer.

![](/img/publisher-fr_gs_metrics_3.png){: style="width:700px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}

La collection est vide. Nous allons maintenant ajouter des indicateurs.

Cliquez sur l'onglet 'Indicateurs' et puis sur le bouton 'Ajouter des indicateurs'

![](/img/publisher-fr_gs_metrics_4.png){: style="width:700px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}


## Utiliser les fichiers 'exemple'

Pour commencer simplement, nous allons charger un fichier 'exemple'.

Allez en bas de la page et cliquez sur 'Indicateurs simples'. Si vous travaillez avec Microsoft Excel, sélectionnez Excel. Sinon, choisissez Csv.

En cliquant sur le choix, un fichier exemple va être téléchargé. Nous utilisons de notre côté Excel.

![](/img/publisher-fr_gs_metrics_5.png){: style="width:700px;margin:30px;padding:20px;border:1px solid #ddd;border-radius:5px"}

Ouvrons le fichier et observons les lignes:

- La première ligne contient les identifiants des indicateurs. Nous y reviendrons
- La seconde ligne a le nom des indicateurs
- La troisième ligne la description des indicateurs s'il y en a une
- La quatrième l'unité
- La cinquième la fréquence: D est pour Jour (Day), W pour Semaine (Week), M pour Mois (Month), Q pour Trimestre (Quarter) et enfin Y pour Année (Year)
- A partir de la sixième ligne, nous retrouvons les valeurs de l'indicateur et la date de l'observation

Ce fichier est un exemple de format qui peut être utilisé pour charger des indicateurs.

## Comprendre les identifiants

Comme cela a été présenté dans le guide 'utilisateur', les indicateurs sur Statit ont un identifiant unique qui les réprésente et qui ressemble à un lien Internet.

Par exemple, [clim/copernicus-r/daily/dk01/temp/real](https://www.gostatit.com/clim/copernicus-r/daily/dk01/temp/real) est l'identifiant unique d'un indicateur qui représente la température au Danemark.

Les indicateurs sont aussi toujours représentés par leur fréquence (jour, semaine, mois) et leur unité (kilo, mètre, US Dollar...).

Vous allez donc devoir renseigner ces éléments pour vos indicateurs.
