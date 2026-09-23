# TP Git & GitHub

## Objectif

Créer un premier espace de travail versionné et apprendre le workflow de base.

## Partie 1 — Configuration

1. Vérifier que Git est installé :

```bash
git --version
```

2. Configurer son nom.
3. Configurer son email.
4. Vérifier la configuration.

## Partie 2 — Repository local

1. Créer un dossier nommé :

```text
sda-data-analyst-semaine-01
```

2. Initialiser Git.
3. Créer :

```text
README.md
notes.md
```

4. Ajouter du contenu dans les deux fichiers.
5. Vérifier l'état.
6. Ajouter les fichiers.
7. Faire un premier commit.

## Partie 3 — Historique

Afficher l'historique avec :

```bash
git log --oneline
```

## Partie 4 — GitHub

Créer un repository GitHub correspondant.

Connecter le repository local au repository distant.

Effectuer un `push`.

## Partie 5 — Modification

Modifier `notes.md`.

Puis effectuer le workflow :

```bash
git status
git add .
git commit -m "Mise à jour des notes"
git push
```

## Livrable

Le repository GitHub doit contenir :

```text
README.md
notes.md
```

et au moins deux commits compréhensibles.

## Questions

1. Quelle différence entre Git et GitHub ?
2. Que montre `git status` ?
3. À quoi sert `git add` ?
4. À quoi sert `git commit` ?
5. À quoi sert `git push` ?
6. À quoi sert `git pull` ?
