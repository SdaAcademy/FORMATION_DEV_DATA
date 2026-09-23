# Dictionnaire des données — clients_satisfaction.csv

| Variable | Type | Description | Modalités / unité |
|---|---|---|---|
| `client_id` | Texte | Identifiant unique du client | C001, C002... |
| `date_enquete` | Date | Date de collecte de l'observation | AAAA-MM-JJ |
| `ville` | Catégorielle | Ville du client | Kinshasa, Lubumbashi, Goma |
| `agence` | Catégorielle | Agence de rattachement | A, B, C |
| `anciennete` | Catégorielle | Niveau d'ancienneté | Nouveau, Intermediaire, Ancien |
| `segment` | Catégorielle | Segment client | Particulier, Entreprise |
| `age` | Numérique | Âge du client | années |
| `satisfaction_5` | Numérique | Note de satisfaction | 1 à 5 |
| `reclamation` | Catégorielle | Client ayant effectué une réclamation | Oui / Non |
| `delai_traitement_min` | Numérique | Délai de traitement observé | minutes |
| `depenses_mensuelles_usd` | Numérique | Dépenses mensuelles estimées | USD |

## Notes

- Le dataset est **pédagogique et fictif**.
- `client_id` sert à identifier les lignes et ne doit pas être utilisé comme indicateur.
- `satisfaction_5` est une échelle de 1 à 5.
- `delai_traitement_min` permet d'explorer une éventuelle différence descriptive entre expérience client et satisfaction.
- L'observation d'une association ne permet pas, à elle seule, de conclure à une causalité.
