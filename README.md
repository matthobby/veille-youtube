# Veille Concurrentielle YouTube

Plugin Claude pour produire une **newsletter hebdomadaire de veille concurrentielle** destinée aux créateurs YouTube.

## Ce que fait ce plugin

- **Onboarding intelligent** : identifie ta niche, ton segment de prix, tes concurrents, tes objectifs et tes ambitions de format
- **Classification par segment** : concurrents directs, veille stratégique, collaborateurs, wild cards
- **Newsletter hebdomadaire** : activité concurrents, tendances marché, idées de contenu, voix de l'audience, découvertes
- **Multi-format** : idées adaptées selon tes ambitions (review, divertissement, challenge, storytelling, documentaire, interview, etc.)
- **Stratégie cross-segment** : angles de différenciation pour entrer sur un nouveau segment de prix
- **Feedback loop** : s'améliore au fil du temps grâce à tes retours

## Installation

### Via le marketplace Jean-Claude

1. Dans Claude Desktop, va dans **Paramètres > Plugins > Marketplace**
2. Cherche "veille-youtube"
3. Clique sur **Installer**

### Manuel

Clone ce repo dans ton répertoire de plugins Claude :

```bash
git clone https://github.com/matthobby/veille-youtube.git
```

## Structure du plugin

```
veille-youtube/
├── .claude-plugin/
│   └── plugin.json            # Manifeste du plugin
├── skills/
│   └── veille-youtube/
│       ├── SKILL.md           # Instructions complètes de la skill
│       └── evals/
│           └── evals.json     # Tests de validation (6 scénarios)
├── LICENSE
└── README.md
```

## Utilisation

Lance avec n'importe quelle formulation :

- "Fais ma veille concurrentielle YouTube"
- "Qu'est-ce que mes concurrents ont publié cette semaine ?"
- "Donne-moi des idées de vidéos basées sur la concurrence"
- "Surveille les tendances de ma niche YouTube"

## Fonctionnement

1. **Onboarding** — Questions sur ta chaîne, niche, segment, concurrents, objectifs, ambitions de format
2. **Configuration** — Classification automatique des acteurs
3. **Newsletter** — Recherche + rédaction avec 6 sections structurées
4. **Feedback** — Collecte tes retours, ajustements automatiques, revue trimestrielle

Fonctionne pour **toutes les niches YouTube** (tech, cuisine, fitness, gaming, etc.).

## Licence

MIT — utilise, modifie, partage librement.
