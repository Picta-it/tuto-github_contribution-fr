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

Pour notre exemple, on va contribuer à ce [dépôt](https://github.com/Picta-it/tuto-github_contribution-fr).
Mais vous pourriez très bien contribuer au noyau de [Linux}(https://github.com/torvalds/linux).

Mais pour apprendre, on va rester sur ce dépôt.

## Pré-requis
Pour effectuer ce tutoriel, vous devez installer [Git](http://git-scm.com/download).

Pour plus d'information sur le fonctionnement de Git, vous pouvez aller vous [ici](https://github.com/Picta-it/tuto-git-fr).

## Création d'un compte GitHub

Vous pouvez passer par [ici](https://github.com/join).

Pour l'explication, GitHub correspond à site Internet qui fonctionnne autour de [Git](http://git-scm.com/) et permet d'héberger des projets. Dans le même style, mais plus pour des dépôt privés, il y a [BitBucket](https://bitbucket.org/).

## Fork d'un projet
Il s'agit de la copie d'un projet vers votre espace personnel.

Allez [ici](https://github.com/Picta-it/tuto-github_contribution-fr) et cliquez sur **Fork** en haut à droite.
Sinon, si vous êtes déjà connecté, cliquez [là](https://github.com/Picta-it/tuto-github_contribution-fr/fork).

Vous pouvez vérifier sur votre espace. Vous disposez maintenant du projet **tuto-github_contribution-fr**.

## Pull du projet
Ouvrez un terminal, allez dans votre espace de travail et faites.
```sh
# Remplacer <Votre compte> par votre nom de compte
git clone https://github.com/<Votre compte>/tuto-github_contribution-fr
```

Par exemple, pour l'utilisateur Toto
```sh
git clone https://github.com/toto/tuto-github_contribution-fr
```

## Modification du projet
Créez un fichier **<votre nom>**.md avec le contenu que vous souhaitez dans le répertoire /contribs.

## Commit de nos modifications
Pour sauvegarder, on va ajouter nos modifications au commit.
Un commit peut être vu comme un regroupement de modifications apportées à un projet.

Donc, depuis le répertoire, on fait
```sh
git add <votre nom>.md
git commit -m "Contribution au projet de test"
```

## Push du projet
On pousse toutes nos modifications sur votre compte GitHub.

```sh
git push origin master
```

## On soumet une Pull Request
Maintenant que l'on a fait toutes nos modifications, on va les soumettre au projet.

Allez sur la page du [projet](https://github.com/Picta-it/tuto-github_contribution-fr) et cliquez sur [Pull Request](https://github.com/Picta-it/tuto-github_contribution-fr/pulls).

Ensuite,
* cliquez **New Pull Request**
* *compare across forks*
* choisissez votre projet dans la liste de gauche

Puis créez la Pull Request en précisant dans le message les modifications que vous avez apportés.

## Et voilà
Les modifications sont proposés au projet. Maintenant, il faut attendre qu'un des administrateurs du projet les intègre.

Pas si compliqué que ça non ?!
