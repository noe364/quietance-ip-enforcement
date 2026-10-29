# Quietance IP Enforcement

Dépôt de travail pour la mission de recherche, comparaison et préparation de dossiers de propriété intellectuelle de Quietance.

## État initial

La mission originale est conservée dans [MISSION.md](MISSION.md). [AGENTS.md](AGENTS.md) fournit les consignes applicables à Codex. Aucun résultat d’investigation ni logiciel n’est présent à ce stade.

## Démarrer dans Codex Cloud

Sélectionner le dépôt `noe364/quietance-ip-enforcement`, branche `main`, puis soumettre :

> Lis AGENTS.md et MISSION.md, puis exécute la mission avec les outils disponibles, en priorité sur YU Monaco, Vitalyne et Oragel Paris. Vérifie les antériorités et les droits. Conserve les sources vérifiables, documente les accès manquants et prépare les dossiers sans transmettre de signalement.

Aucun script d’installation ni aucune dépendance ne sont nécessaires pour ce dépôt documentaire. Les connecteurs disponibles sur le poste local doivent être vérifiés séparément dans la session Cloud. Un accès réseau aux sources publiques est nécessaire à la recherche.

## Utilisation locale et vérification

```sh
git clone https://github.com/noe364/quietance-ip-enforcement.git
cd quietance-ip-enforcement
cat AGENTS.md MISSION.md
git diff --check
```

Il n’existe pas de serveur à lancer, de compilation ou de suite de tests applicatifs. La mission s’exécute par une tâche Codex suivant les instructions ci-dessus.

## Livrables attendus

La mission définit `competitors.csv`, `evidence/`, `comparisons/`, `ready-to-file/`, `needs-review/`, `submissions.csv` et `final-report.md`. Ils seront produits à partir d’observations réelles. Les éléments privés sont exclus de Git et les signalements exigent une approbation explicite avant transmission.
