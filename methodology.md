# Méthode et limites

Collecte du 30 octobre 2026, heure de Paris ; les horodatages techniques des archives sont en UTC (29 octobre au soir).

1. Lecture de MISSION.md, AGENTS.md et des deux références locales de septembre, sans modifier `sources/`.
2. Vérification du dépôt public GitHub et des connecteurs. Pas d’exécuteur Cloud accessible ni d’outil environment_status ; aucune instance présumée disponible.
3. Recherche TrendTrack par marque puis domaine. Pagination complète, 20 lignes maximum, statut all, tri createdAt asc pour Quietance, YU, Vitalyne, Oragel et Sereolys : 478 entrées, sans doublon d’identifiant dans chaque corpus. Le tri createdAt et le champ firstSeenAt sont distincts ; l’analyse des dates utilise ce dernier en le qualifiant de signal d’indexation.
4. Recherches ciblées Microvia, SecuraDent, Dentigrip ; découverte France avec pays ciblés FR et recherches par marques historiques. Faux positifs non dentaires écartés. Les compteurs de résultats ne comptent pas des violations.
5. Textes normalisés pour rechercher les ressemblances : minuscules, URL retirées, noms des marques remplacés par un jeton commun, tokenisation en mots. Comparaison de groupes de huit mots et aide SequenceMatcher. Ces scores sont des outils de repérage sans valeur de seuil juridique. Textes complets conservés en privé.
6. Captures des pages réellement visitées : URL de départ et finale, statut HTTP, HTML, texte et images de page. Les captures sont celles de la session et ne sont pas des archives historiques.
7. Images des landing pages : SHA-256 des fichiers, pHash 64 bits pour classer les ressemblances, puis inspection visuelle. Variantes de résolution et faux positifs présents. Les médias TrendTrack ont renvoyé 403 : aucun binaire d’annonce conservé, aucune analyse des plans ou sons annoncée.
8. Contrôle des pièces de droits : références locales, recherches Drive et Gmail ciblées, boutique connectée. Aucune cession/licence probante retrouvée pour les œuvres revendiquées. L’absence dans ces résultats est une limite de recherche, pas une preuve générale d’inexistence.
9. Consultation des procédures officielles Shopify, Meta et Cloudflare. Aucun dépôt sans droits établis et sans pouvoir de réaliser exactement les déclarations exigées.
10. Rapport et registres publics ; originaux, copies intégrales, captures et données privées exclus de Git. Validation documentaire avec git diff --check.

Les listes d’URL et empreintes sont reproductibles à partir des archives locales. Les captures sauvegardées, les dates de fichiers et les paramètres CDN ne constituent pas des constats judiciaires. Une page 404, un changement de domaine ou un statut publicitaire inactif ne prouvent jamais un retrait causé par un signalement.
