# Registre des patchs Zone A

Un patch = une modification d'un fichier amont. Chaque patch doit pouvoir répondre à la
question : **« comment le supprimer un jour ? »**

Revue trimestrielle obligatoire. Indicateur de santé : le nombre de patchs supprimés par
trimestre doit être ≥ au nombre de patchs ajoutés.

| ID | Motif | Fichiers amont touchés | Remplaçable par un point d'extension ? | Proposable en PR amont ? | Ajouté le |
|----|-------|------------------------|----------------------------------------|--------------------------|-----------|
| P-001 | Index d'inclusions de nos changesets Liquibase (ADR-0002) : le serveur exécute ce fichier, qui inclut l'index amont puis nos changelogs | *aucun* — fichier ajouté, `schema/changelog-gps1fo-master.xml` | Non : l'amont n'offre aucun point d'extension pour le changelog | Non : spécifique à notre fork | 2026-09-20 |
