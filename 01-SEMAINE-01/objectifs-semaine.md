# Objectifs — Semaine 1
# Semaine 1 — Fondations :Linkedin, Git, GitHub & Statistique descriptive

**De la donnée à la décision : comprendre le métier, travailler avec Git/GitHub et réaliser une première analyse descriptive.**
## 🎯 Objectifs de la semaine

À la fin de la semaine, l'apprenant doit être capable de :

- Mettre en place un profil professionnel (LinkedIn, GitHub) et l'utiliser comme outil de collaboration
- Installer, configurer et pratiquer Git en ligne de commande 
- Maîtriser le vocabulaire de base de la statistique descriptive : variable, type de variable, population, échantillon, moyenne, médiane, mode
- expliquer le rôle d'un Data Analyst ;
- distinguer donnée, information, insight et décision ;
- formuler une question métier simple ;
- identifier les variables utiles à une analyse ;
- utiliser les commandes Git essentielles ;
- créer et synchroniser un dépôt GitHub ;
- comprendre un workflow de travail collaboratif ;
- calculer et interpréter des statistiques descriptives simples ;
- communiquer des résultats avec une lecture métier ;
- produire un premier livrable propre et structuré.

---

## ✅ Séance 1
- Création des profils LinkedIn et GitHub
- Installation et configuration de Git (`git config --global user.name`, `user.email`)
- Introduction à la statistique descriptive : variables, types de variables (qualitatives/quantitatives), population, échantillon, moyenne, médiane, mode

## 📅 Séance 2 — Programme

### Objectif de la séance

1. Passer de la théorie Git à la pratique en conditions réelles avec ce dépôt
2. Découvrir le flux de travail GitHub (dépôt distant, clone, pull, fork, issues)
3. Approfondir la statistique descriptive : étendue, variance, écart-type, quartiles
4. Appliquer ces notions sur de vrais jeux de données

## 1. Comprendre le métier de Data Analyst

L'apprenant doit pouvoir expliquer :

- ce qu'est une donnée ;
- ce qu'est une information ;
- ce qu'est une analyse ;
- ce qu'est un insight ;
- ce qu'est une recommandation ;
- comment l'analyse contribue à la décision.

## 2. Comprendre la chaîne de valeur de la donnée

```text
Question métier
      ↓
Collecte des données
      ↓
Nettoyage / préparation
      ↓
Analyse
      ↓
KPI / indicateurs
      ↓
Visualisation
      ↓
Insight
      ↓
Recommandation
      ↓
Décision
```

## 3. Acquérir les bases de Git et GitHub

L'apprenant doit savoir :

- installer Git ;
- configurer son identité ;
- créer un repository ;
- cloner un repository ;
- vérifier l'état d'un repository ;
- ajouter des fichiers ;
- créer un commit ;
- envoyer des modifications sur GitHub ;
- récupérer les modifications distantes ;
- consulter l'historique.

## 4. Acquérir les bases de l'analyse descriptive

L'apprenant doit savoir calculer ou identifier :

- effectif ;
- fréquence ;
- pourcentage ;
- moyenne ;
- médiane ;
- minimum ;
- maximum ;
- étendue ;
- comparaison entre groupes.

## 5. Développer une lecture métier

L'apprenant doit apprendre à passer de :

**« La moyenne est de X »**

à :

**« Ce résultat signifie que..., ce qui peut avoir pour conséquence..., et l'entreprise pourrait donc... »**

## 6. Livrables

À la fin de la semaine :

- exercices réalisés ;
- TP Git/GitHub terminé ;
- analyse descriptive du dataset ;
- mini-projet de semaine ;
- repository organisé proprement.

Chaque apprenant doit produire une première analyse du dataset `clients_satisfaction.csv` et présenter :

1. la problématique ;
2. les variables utilisées ;
3. les statistiques principales ;
4. au moins 3 constats ;
5. au moins 2 recommandations argumentées ;
6. une conclusion courte.


   ```

### Contenu de ce dossier

| Fichier | Description |
|---|---|
| `support-git-github.md` | Mini-syllabus des commandes Git essentielles et prise en main de GitHub |
| `DATASETS/notes_etudiants.csv` | Jeu de données pour les exercices de statistique (30 étudiants) |
| `DATASETS/ventes_kinshasa.csv` | Jeu de données pour les exercices de statistique et une première exploration de données tabulaires |
| `questions.md` | Exercices Git (pratique) + exercices de statistique sur les deux datasets |

### Comment rendre le travail

Après avoir répondu aux questions dans `questions.md` (ou dans un notebook si vous préférez), sur votre branche personnelle :

```bash
git add .
git commit -m "Semaine 1 - reponses exercices"
git push origin <votre-prenom>
```

Le formateur relira et commentera directement sur GitHub (voir `syllabus-github.md`, section Pull Request).

## 📚 Ressources

- objectifs et compétences ;
- `01-SEANCE-1/` : cours, exercices et correction ;
- `02-SEANCE-2/` : Git, GitHub et TP ;
- `03-SEANCE-3/` : analyse descriptive et cas métier ;
- `DATASETS/` : données et dictionnaire ;
- `PROJET-SEMAINE-1/` : projet fil rouge ;
- `TRAVAUX-APPRENANTS/` : espace de production ;
- `SOLUTIONS-FORMATEUR/` : éléments réservés au formateur.

## 🔄 Méthode de travail

Pour chaque activité :

**Comprendre → Manipuler → Analyser → Interpréter → Communiquer**

L'objectif est de ne pas produire uniquement des calculs, mais de toujours relier les résultats à une question métier.


## ⚠️ Important

Le dossier `SOLUTIONS-FORMATEUR/` est réservé au formateur. Les apprenants doivent d'abord réaliser les exercices sans consulter les corrections.
