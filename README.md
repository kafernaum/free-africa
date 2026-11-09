# Free Africa

**Free Africa** est une compétence (*skill*) pour Claude conçue comme un assistant d’investigation documentaire au service du développement des pays africains.

Elle aide à identifier les obstacles, les opportunités et les solutions documentées ; à confronter les explications ; à comparer les interventions possibles ; et à transformer les conclusions en plans d’action évaluables.

Elle ne prétend pas produire une réponse unique sur « tout ce qui développe l’Afrique ». Elle impose au contraire un cadrage précis, une recherche traçable et une distinction rigoureuse entre faits établis, hypothèses, propositions et recommandations.

## Mission

Free Africa vise à soutenir la réflexion et l’action sur les leviers du développement humain, économique, institutionnel et écologique des territoires africains.

Elle peut aider à :

- Comprendre un problème de développement dans un pays, une région ou un secteur.
- Identifier les données disponibles, leurs limites et les informations manquantes.
- Rechercher des politiques, réformes, projets, financements et expériences pertinentes.
- Comparer plusieurs solutions et leurs conditions de réussite.
- Examiner les effets sur l’emploi, les revenus, les services essentiels, l’équité et l’environnement.
- Préparer des notes de synthèse, des diagnostics, des notes d’orientation ou des plans d’action.
- Vérifier les conditions d’accès à des financements, appels à projets ou instruments de financement.

## Principe de méthode

Free Africa ne traite pas l’Afrique comme un bloc homogène. Chaque enquête doit préciser le pays ou le territoire, le secteur, la population concernée, la période et la décision à éclairer.

La compétence privilégie :

- Des questions délimitées plutôt que des généralités.
- Des sources primaires lorsque disponibles.
- Le recoupement des affirmations importantes.
- La distinction entre constat, association, causalité, hypothèse et jugement.
- La prise en compte des contraintes institutionnelles, budgétaires, sociales et environnementales.
- La recherche des réussites, des échecs, des contre-exemples et des effets indésirables.
- La transparence sur les incertitudes et les limites des preuves.

## Cas d’usage

| Besoin | Exemple de demande |
|---|---|
| Diagnostic sectoriel | « Analyse les obstacles à l’accès des PME mauritaniennes à une électricité fiable. » |
| Politique publique | « Compare deux options de financement de la formation professionnelle dans ce pays. » |
| Financement | « Vérifie les conditions et les dates limites de cet appel à projets. » |
| Évaluation | « Examine les preuves disponibles sur l’effet de ce programme d’emploi des jeunes. » |
| Souveraineté économique | « Identifie les leviers de transformation locale des produits agricoles dans cette région. » |
| Plan d’action | « Propose un pilote de 12 mois avec responsables pressentis, coûts, risques et indicateurs. » |

## Méthode d’investigation

Pour chaque enquête, Free Africa est conçue pour suivre une démarche en plusieurs étapes :

1. **Cadrer la question** : préciser le territoire, le secteur, la population, la période et la décision à éclairer.
2. **Formuler les hypothèses concurrentes** : ne pas rechercher uniquement ce qui confirme une idée préétablie.
3. **Construire un plan de recherche** : identifier les sous-questions, les sources et les lacunes.
4. **Rechercher les preuves** : consulter les données primaires, les études indépendantes et les sources locales lorsque disponibles.
5. **Établir un registre des preuves** : documenter chaque affirmation importante, sa source, sa date, sa période de données et ses limites.
6. **Recouper les conclusions** : distinguer les sources indépendantes des simples reprises d’un même communiqué.
7. **Analyser les mécanismes** : examiner les institutions, les incitations, les capacités, les infrastructures et les contraintes d’exécution.
8. **Comparer les options** : évaluer le statu quo, les interventions possibles et les alternatives crédibles.
9. **Proposer une action** : préciser les acteurs pressentis, les étapes, les coûts, les financements à vérifier, les risques et les indicateurs.
10. **Contrôler le résultat** : signaler les incertitudes, les contradictions et les informations qui restent à vérifier.

## Règles de qualité

Free Africa est conçue pour respecter les règles suivantes :

- Ne pas inventer de source, de citation, de chiffre, de référence juridique ou de financement.
- Ne pas présenter un extrait de moteur de recherche comme la preuve du contenu complet d’un document.
- Distinguer la date de publication d’un document de la période couverte par ses données.
- Préciser les unités, monnaies, définitions, périmètres et méthodes de calcul lorsque nécessaire.
- Ne pas remplacer une donnée manquante par zéro.
- Ne pas déduire une causalité à partir d’une simple corrélation.
- Ne pas transformer une expérience étrangère en recette universelle.
- Ne pas présenter un acteur pressent comme un partenaire déjà engagé.
- Ne pas présenter un bailleur potentiel comme un financement obtenu.
- Ne pas confondre une allégation, une enquête, une décision de justice et un fait établi.

## Installation dans Claude

1. Téléchargez ou clonez ce dépôt.
2. Créez un dossier nommé `free-africa` contenant `SKILL.md`, `references/` et `assets/`.
3. Compressez ce dossier en archive ZIP, en conservant le dossier racine `free-africa/`.
4. Dans Claude, ouvrez **Customize > Skills > + > Create skill > Upload a skill**, selon les options disponibles dans votre interface.
5. Importez l’archive, activez la compétence et testez-la avec une question délimitée.

La compétence ne crée pas elle-même un accès web, un connecteur, un abonnement, une mémoire permanente ou une veille programmée. Elle utilise uniquement les capacités réellement disponibles dans l’environnement Claude utilisé.

## Exemple de demande

> Utilise Free Africa pour étudier les leviers d’emploi productif des jeunes en Mauritanie.
>
> Délimite la question, sélectionne deux secteurs à approfondir sur la base des preuves disponibles, et précise la période des données. Recherche les sources publiques pertinentes, recoupe les faits importants et distingue les faits établis, les hypothèses et les propositions.
>
> Compare les interventions possibles, leurs conditions de réussite et les risques de transfert d’expériences étrangères. Termine par un plan pilote comprenant les responsables pressentis, les coûts documentés ou restant à chiffrer, les financements à vérifier, les risques, les indicateurs et les principales incertitudes.
>
> N’invente aucun chiffre, aucune référence et aucun financement. Si l’accès web n’est pas disponible, annonce-le avant de commencer.

## Structure du dépôt

```text
free-africa/
├── README.md
├── SKILL.md
├── GUIDE.md
├── LICENSE
├── references/
│   ├── protocole-enquete.md
│   ├── domaines-sources.md
│   └── evaluation.md
├── assets/
│   └── modele-rapport.md
└── tests/
    └── tests-reception.md
```

| Fichier | Rôle |
|---|---|
| `SKILL.md` | Instructions principales de la compétence. |
| `GUIDE.md` | Utilisation, validation et maintenance. |
| `references/protocole-enquete.md` | Méthode de recherche, registre des preuves et examen contradictoire. |
| `references/domaines-sources.md` | Domaines d’investigation et pistes de sources. |
| `references/evaluation.md` | Comparaison des options et fiche d’action. |
| `assets/modele-rapport.md` | Structure des dossiers d’investigation. |
| `tests/tests-reception.md` | Scénarios de test et critères de qualité. |

## Domaines couverts

Free Africa peut être utilisée pour explorer les domaines suivants, selon la question posée :

- Institutions, paix, justice, redevabilité et capacités administratives.
- Fiscalité, budget, dette, commande publique et flux financiers.
- Agriculture, eau, systèmes alimentaires et transformation locale.
- Énergie, transports, logistique, logement et aménagement territorial.
- Industrie, chaînes de valeur, commerce régional et entreprises.
- Éducation, recherche, santé, compétences et protection sociale.
- Emploi, travail informel, entrepreneuriat, jeunesse et égalité.
- Numérique, intelligence artificielle, données, cybersécurité et souveraineté technologique.
- Ressources naturelles, climat, biodiversité et résilience.
- Diasporas, financements, intégration régionale et partenariats internationaux.
- Culture, langues, savoirs locaux et participation citoyenne.

## Cadre vitaliste facultatif

Free Africa peut intégrer, sur demande explicite, une lecture inspirée du cadre vitaliste : dignité, capacités de vie, services essentiels, emploi décent, résilience et équité territoriale.

Cette dimension ne remplace pas l’exigence de preuve. Elle doit être distinguée des résultats empiriques et ne doit pas être présentée comme un consensus scientifique. Si la formule du Score de Restitution Vitaliste (SRV) ou son corpus de référence n’est pas fourni, la compétence doit le demander plutôt que l’inventer.

## Limites

Free Africa est un outil d’aide à l’investigation, non une source de vérité définitive.

Elle ne garantit ni l’exhaustivité, ni l’exactitude de chaque information, ni l’absence d’erreur. Les conclusions importantes, les décisions publiques et les financements doivent être vérifiés auprès des sources primaires et validés par les personnes compétentes.

La compétence ne doit pas être utilisée pour produire des accusations non fondées, contourner des restrictions d’accès, collecter des données personnelles sans base légitime ou exécuter des actions externes sans autorisation explicite.

## Contribution

Les contributions sont bienvenues, notamment pour :

- Améliorer les instructions de recherche et de vérification.
- Ajouter des sources africaines fiables et des méthodes d’évaluation.
- Développer des modèles de rapports adaptés à des secteurs précis.
- Ajouter des tests de réception et des cas d’usage.
- Traduire ou adapter la compétence à d’autres langues et contextes.

Avant toute contribution, veillez à ne pas inclure de données personnelles, de documents confidentiels ou de contenus dont vous ne détenez pas les droits nécessaires.

## Statut

Il s’agit d’une version initiale proposée, destinée à être testée dans Claude.

Les tests de réception sont fournis, mais leur réussite n’est pas revendiquée. La grille de comparaison proposée est un outil méthodologique de discussion, non un indicateur scientifiquement validé.

Aucune affiliation officielle avec Anthropic n’est revendiquée.

## Licence

Ce projet est distribué sous licence MIT. Voir le fichier [`LICENSE`](./LICENSE).
