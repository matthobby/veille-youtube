# Veille YouTube Marketplace

Marketplace Claude contenant des skills pour créateurs YouTube.

## Plugin : veille-youtube

Newsletter hebdomadaire de veille concurrentielle pour créateurs YouTube.

- **Onboarding intelligent** : niche, segment de prix, concurrents, objectifs, ambitions de format
- **Classification par segment** : concurrents directs, veille stratégique, collaborateurs, wild cards
- **Newsletter hebdo** : activité concurrents, tendances, idées de contenu, voix de l'audience
- **Multi-format** : review, divertissement, challenge, storytelling, documentaire, interview
- **Feedback loop** : s'améliore au fil du temps grâce à tes retours

## Installation

Dans Claude Desktop :
1. **Paramètres > Personnaliser > Plugins**
2. Ajouter l'URL : `https://github.com/matthobby/veille-youtube`
3. Le plugin "veille-youtube" apparaît dans tes skills

## Structure

```
├── .claude-plugin/
│   └── marketplace.json
├── plugins/
│   └── veille-youtube/
│       ├── .claude-plugin/
│       │   └── plugin.json
│       └── skills/
│           └── veille-youtube/
│               ├── SKILL.md
│               └── evals/
│                   └── evals.json
└── README.md
```

## Licence

MIT
