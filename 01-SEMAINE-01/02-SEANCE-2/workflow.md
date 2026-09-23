# Workflow Git & GitHub — SDA Academy

## Workflow standard

```text
1. git pull
       ↓
2. Travailler
       ↓
3. git status
       ↓
4. git add .
       ↓
5. git commit -m "..."
       ↓
6. git push
```

## Étape 1 — Récupérer les modifications

```bash
git pull
```

Toujours effectuer cette étape avant de commencer une session de travail sur un repository partagé.

## Étape 2 — Travailler

Créer ou modifier les fichiers nécessaires.

## Étape 3 — Vérifier

```bash
git status
```

Lire le résultat avant de continuer.

## Étape 4 — Préparer

```bash
git add .
```

## Étape 5 — Enregistrer

```bash
git commit -m "Ajout analyse satisfaction"
```

## Étape 6 — Publier

```bash
git push
```

## En cas de conflit

Ne pas supprimer ou écraser le travail d'un autre apprenant.

1. Lire le message Git.
2. Identifier les fichiers concernés.
3. Comprendre les différences.
4. Résoudre manuellement si nécessaire.
5. Ajouter le fichier corrigé.
6. Créer le commit approprié.
7. Push.

Si le conflit n'est pas compris, demander au formateur avant toute suppression.

## Structure recommandée du travail apprenant

```text
TRAVAUX-APPRENANTS/
└── NOM-PRENOM/
    ├── README.md
    ├── exercices/
    ├── analyses/
    └── projet/
```
