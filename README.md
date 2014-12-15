# Contribution GitHub

Nous allons voir comment contribuer à des projets sur GitHub.

Les étapes sont les suivantes :
* Création d'un compte sur GitHub
* Copie de ce projet sur votre compte
* Téléchargement sur votre poste
* Modification du projet
* Sauvegarde
* Upload du projet
* Création de la PR - Pull Request (on propose les changements au projet)

Pour notre exemple, on va contribuer au dépôt de [test](https://github.com/Picta-it/test).
Mais vous pourriez très bien contribuer au noyau de [Linux}(https://github.com/torvalds/linux).

Mais pour apprendre, on va travailler sur le projet de test.

## Création d'un compte GitHub

Vous pouvez passer par [ici](https://github.com/join).

Pour l'explication, GitHub correspond à site Internet qui fonctionnne autour de [Git](http://git-scm.com/) et permet d'héberger des projets. Dans le même style, mais plus pour des dépôt privés, il y a [BitBucket](https://bitbucket.org/).

## Fork d'un projet
Il s'agit de la copie d'un projet vers votre espace personnel.

Allez [ici](https://github.com/Picta-it/test) et cliquez sur **Fork** en haut à droite.
Sinon, si vous êtes déjà connecté, cliquez [là](https://github.com/Picta-it/test/fork).

Vous pouvez vérifier sur votre espace. Vous disposez maintenant de du projet **test**.

## Pull du projet
Maintenant, que vous avez une copie du projet sur GitHub, vous allez le récupérer pour le modifier.

Donc, sur votre Pc ou Mac. vous installez [Git](http://git-scm.com/download).

Une fois installé, ouvrez un terminal, allez dans votre espace de travail et faites.
```sh
# Remplacer <Votre compte> par votre nom de compte
git clone https://github.com/<Votre compte>/test
```

Par exemple, pour l'utilisateur Toto
```sh
git clone https://github.com/toto/test
```

## Modification du projet
Ouvrez README.md et ajoutez votre nom à la suite du fichier et sauvegardez.

## Commit de nos modifications
Pour sauvegarder, on va ajouter nos modifications au commit.
Un commit peut être vu comme un regroupement de modifications apportées à un projet.

Donc, depuis le répertoire, on fait
```sh
git add README.md
git commit -m "Contribution au projet de test"
```

## Push du projet
On pousse toutes nos modifications sur votre compte GitHub.

```sh
git push origin master
```

## On soumet une Pull Request
Maintenant que l'on a fait toutes nos modifications, on va les soumettre au projet.

Allez sur la page du [projet](https://github.com/Picta-it/test) et cliquez sur [Pull Request](https://github.com/Picta-it/test/pulls).

Ensuite,
* cliquez **New Pull Request**
* *compare across forks*
* choisissez votre projet dans la liste de gauche

Puis créez la Pull Request en précisant dans le message les modifications que vous avez apportés.

## Et voilà
Les modifications sont proposés au projet. Maintenant, il faut attendre qu'un des administrateurs du projet les intègre.

Pas si compliqué que ça non ?!
