# Semaine 1 — Exercices

Ces exercices se font en deux temps : d'abord une mise en pratique de Git/GitHub, puis des exercices de statistique descriptive sur les deux jeux de données du dossier `DATASETS/`.

---

## Partie A — Pratique Git & GitHub

À faire directement dans votre terminal, sur votre branche personnelle.

1. Clonez le dépôt  s'il ne l'est pas déjà.
2. Créez une branche personnelle nommée avec votre prénom (ex. `git checkout -b patrick`).
3. Dans cette branche, créez un fichier `reponses.md` à la racine de `semaine-01/` et copiez-y les énoncés de la Partie B ci-dessous.
4. Faites un premier commit avec un message clair (ex. `"Semaine 1 - creation fichier reponses"`).
5. Répondez aux questions de statistique directement dans `reponses.md`, au fur et à mesure. Faites **au moins 3 commits distincts** au cours de l'exercice (pas un seul commit final) pour vous entraîner au versionnement progressif.
6. Poussez votre branche vers GitHub avec `git push origin <votre-prenom>`.
7. Sur GitHub, ouvrez une Pull Request de votre branche vers `main` intitulée `"Semaine 1 - <votre-prenom>"`.
8. Bonus : ouvrez une issue sur le dépôt pour poser une question que vous vous êtes posée pendant l'exercice (même une question simple — c'est l'usage de l'outil qui compte).
9. Avant la prochaine séance, faites un `git checkout main` puis `git pull origin main` pour récupérer le contenu de la semaine 2.

---

## Partie B — Statistique descriptive

### Sur `datasets/notes_etudiants.csv`

1. Combien d'étudiants composent cette population ?
2. Quelle est la moyenne de la colonne `note_statistique` ?
3. Quelle est la médiane de `note_statistique` ? Comparez-la à la moyenne : que remarquez-vous ?
4. Identifiez le mode de la colonne `sexe`.
5. Calculez l'étendue (valeur max − valeur min) de `note_maths`.
6. Un étudiant est-il qualifié de "population" ou d'"échantillon" dans ce jeu de données ? Justifiez.
7. Si l'on ne travaillait que sur les 10 premières lignes du fichier pour estimer la moyenne générale, s'agirait-il d'une étude sur la population ou sur un échantillon ?
8. Calculez la variance et l'écart-type de `note_francais` (à la main ou avec une calculatrice — la formule sera revue en séance).
9. Classez les trois matières (maths, français, statistique) de la moins bien réussie à la mieux réussie, en vous basant sur la moyenne de chaque colonne.

### Sur `datasets/ventes_kinshasa.csv`

10. Combien de ventes ont été enregistrées au total sur les 14 jours ?
11. Quelle est la catégorie de produit (`categorie`) la plus fréquente ? (mode)
12. Quelle commune a enregistré le plus de ventes ?
13. Quel est le prix unitaire moyen tous produits confondus ?
14. Quelle est la médiane de la colonne `quantite` ?
15. Le prix unitaire (`prix_unitaire_cdf`) est-il une variable qualitative ou quantitative ? Discrète ou continue ?
16. La `commune` est-elle une variable qualitative ou quantitative ?
17. **Question ouverte :** en comparant les deux datasets, quelles différences voyez-vous entre une donnée collectée pour un usage académique (`notes_etudiants.csv`) et une donnée collectée pour un usage commercial/opérationnel (`ventes_kinshasa.csv`) ? (structure, granularité, usage prévu)

---

## Barème indicatif

| Partie | Points |
|---|---|
| A — Pratique Git/GitHub (branche, commits multiples, PR) | 8 |
| B — Exercices sur `notes_etudiants.csv` (Q1–9) | 9 |
| B — Exercices sur `ventes_kinshasa.csv` (Q10–17) | 8 |
| **Total** | **25** |
