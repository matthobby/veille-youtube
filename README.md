# Veille Concurrentielle YouTube

Skill Claude pour produire une **newsletter hebdomadaire de veille concurrentielle** destinée aux créateurs YouTube.

## Ce que fait cette skill

- **Onboarding intelligent** : identifie ta niche, ton segment de prix, tes concurrents (directs et veille), tes objectifs et tes ambitions de format
- **Classification par segment** : distingue concurrents directs, veille stratégique, collaborateurs et wild cards — pas juste "gros" vs "petit"
- **Newsletter hebdomadaire** avec 6 sections : activité concurrents, tendances marché, idées de contenu, voix de l'audience, découvertes
- **Idées de contenu adaptées** selon tes ambitions : review, divertissement, challenge, storytelling, documentaire, interview, etc.
- **Stratégie cross-segment** : angles de différenciation pour entrer sur un nouveau segment de prix
- **Boucle de feedback** : après chaque newsletter, collecte ton retour et s'améliore au fil du temps
- **Livraison** : fichier Markdown + email formaté

## Installation

### Claude Desktop (Cowork)

1. Télécharge le fichier `.skill`
2. Dans Claude Desktop, va dans Paramètres > Skills
3. Importe le fichier

### Manuel

Copie le dossier dans ton répertoire de skills Claude :

```
~/.claude/skills/veille-youtube/
├── SKILL.md
└── evals/
    └── evals.json
```

## Utilisation

Lance la skill avec n'importe quelle formulation :

- "Fais ma veille concurrentielle YouTube"
- "Qu'est-ce que mes concurrents ont publié cette semaine ?"
- "Donne-moi des idées de vidéos basées sur la concurrence"
- "Surveille les tendances de ma niche YouTube"

Au premier lancement, la skill te posera des questions pour comprendre ton profil. Ensuite, elle produit la newsletter directement.

## Structure de la skill

```
veille-youtube/
├── SKILL.md          # Instructions complètes de la skill
└── evals/
    └── evals.json    # Tests de validation (6 scénarios)
```

## Fonctionnement

### Phase 1 — Onboarding
Questions sur ta chaîne, ta niche, ton segment de prix, tes concurrents, tes objectifs, et vers quels formats tu veux aller.

### Phase 2 — Configuration
Classification automatique des acteurs : concurrent direct, veille stratégique, collaborateur, wild card.

### Phase 3 — Newsletter
Recherche + rédaction de la newsletter avec 6 sections structurées. Idées de contenu adaptées à tes ambitions de format.

### Phase 4 — Feedback
Après chaque livraison : collecte du feedback, stockage dans `feedback-log.md`, ajustements automatiques pour la prochaine newsletter. Revue trimestrielle tous les 3 mois.

## Personnalisation

La skill est **générique** : elle fonctionne pour n'importe quelle niche YouTube (tech, cuisine, fitness, gaming, etc.). L'onboarding adapte tout au profil du créateur.

## Licence

MIT — utilise, modifie, partage librement.
