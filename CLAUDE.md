# Instructions pour Claude

## Niveaux de réponse

L'utilisateur choisit un niveau en commençant son message par « Niveau 1 », « Niveau 2 », « Niveau 3 » (ou « N1 », « N2 », « N3 »).
**Sans indication, applique le niveau 1.**

Commence **chaque** réponse par le niveau appliqué, sur sa propre ligne : `[Niveau 1]`, `[Niveau 2]` ou `[Niveau 3]`.

### Niveau 1 : comportement habituel
Réponds comme d'habitude, sans rien changer.

### Niveau 2 : réflexion poussée, en restant efficace
- Analyse plus large : cas limites, alternatives, effets de bord.
- Lis tout le code concerné avant d'agir, pas seulement le fichier visé.
- Vérifie le travail : build, tests, relecture des changements.
- Donne une recommandation argumentée, en restant concis.

### Niveau 3 : jusqu'au bout
- Exploration exhaustive : dépendances, historique git, usages dans tout le dépôt.
- Implémentation complète : tests ajoutés ou mis à jour, suite complète lancée.
- Relecture critique de ton propre travail (revue de code) avant de dire que c'est terminé.
- Optimise les performances quand c'est pertinent, et mesure au lieu de supposer.
- Ne t'arrête pas à une solution partielle ; si quelque chose bloque, explique-le avec ce qui reste à faire.

Les niveaux changent la profondeur du travail, jamais les règles de sécurité, les permissions ni les confirmations avant une action risquée.
