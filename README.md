# MKDocs Site with PyScript
A generic example of how to use PyScript in your [mkdocs](https://www.mkdocs.org/) documentation. The post-build version of the site can be viewed on the [`gh-pages` branch]().

## Live Site
This site is [viewable live on GitHub Pages](https://lilabidi.github.io/mkdocs-pyscript-demo-Jeff/), if you want to play with it online.

## Usage/Deployment
  * Create a virtual environment of your choice
  * install `mkdocs` and `mkdocs-pyscript`
  * Add `mkdocs-pyscript` to your list of plugins in `mkdocs.yml`
  * Write your documentation - all codeblocks will (by default) be converted to runnable code blocks in the browser.
  * Publish!

  # Conseil pour reprendre ce repertoire

  [Video pour comprendre le fonctionnement de Pipefile](https://youtu.be/74pSNpgHFGo?feature=shared)

  * Verfier la version de votre python3 `python3 --version`
  * mise a jour de ubunto `sudo apt update && sudo apt upgrade -y`
  * Création de repertoire pour installer Python3.12 `sudo add-apt-repository ppa:deadsnakes/ppa`
  * puis `sudo apt update`
  * Vérifier Python3.12 `apt list | grep python3.12`
  * Installer avec `sudo apt install python3.12`

  * Vérifier où se trouve le python3.12 avec `which python3.12`

  * Création du virtualenv avec `pipenv --python env/bin/python3.12`
  * supprimer le virtualenv `pipenv --rm`

  ## Installer les dépendances en mode trady
  * Créer un fichier avec toutes les dépendances avec `pip freeze > requirements.txt`
  * Pour installer les dépendances `pip install -r requirements.txt`
  
  ## Installer les dependances + efficace
  * Vérifier au préalable que pipenv est installer avec `pip install pipenv`
  * Création d'un fichier `Pipfile` (P majuscule) selon le modèle de ce repo
  * `pipenv install`
  * `pipenv shell`