# Alias Git et quelques Commandes Utiles

## Configuration des Alias Git

- `git config --global alias.st 'status -sb'`
  - Affiche le statut du dépôt de manière concise.

- `git config --global alias.ll 'log --oneline'`
  - Affiche l'historique des commits sous forme de liste simplifiée.

- `git config --global alias.last 'log -1 HEAD --stat'`
  - Affiche le dernier commit avec ses statistiques.

- `git config --global alias.cm 'commit -m'`
  - Crée un commit avec un message spécifié.

- `git config --global alias.rv 'remote -v'`
  - Affiche les URL des dépôts distants configurés.

- `git config --global alias.d 'diff'`
  - Affiche les différences entre les modifications non indexées et l'index.

- `git config --global alias.dv 'difftool -t vimdiff -y'`
  - Utilise Vimdiff pour afficher les différences de manière interactive.

- `git config --global alias.gl 'config --global -l'`
  - Affiche la liste des configurations globales de Git.

- `git config --global alias.se '!git rev-list --all | xargs git grep -F'`
  - Recherche une chaîne de caractères dans tout l'historique du dépôt.

- `git config --global alias.co checkout`
  - Alias pour la commande `checkout` de Git.

- `git config --global alias.br branch`
  - Alias pour la commande `branch` de Git.

- `git config --global alias.ci commit`
  - Alias pour la commande `commit` de Git.

- `git config --global alias.todo-list "! git grep --extended-regexp -I --line-number --count 'TODO|FIXME'"`
  - Recherche les annotations `TODO` ou `FIXME` dans le projet.

## Commande pour Voir les Commits du Mois

- `git log --author="Andriantomanga NABIL" --since="$(date +%Y-%m-01)" --format="%h %s"`
  - Affiche les commits de l'auteur spécifié depuis le début du mois.

 ## git got
- git config --global alias.got "log --oneline --graph --decorate --all"

