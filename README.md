# Annales — kit de démarrage

Contenu de ce dossier et où le placer dans ton dépôt Quartz :

| Ici | Dans ton dépôt |
|---|---|
| `content/` | remplace le dossier `content/` |
| `quartz.config.yaml` | remplace le fichier du même nom (pense à changer `baseUrl`) |
| `.github/workflows/deploy.yml` | à la racine du dépôt, tel quel |

Prévisualiser en local :

```bash
npm ci
npx quartz plugin install
npx quartz build --serve
```

Puis ouvre http://localhost:8080. Le dossier `content/` est aussi un coffre Obsidian valide : ouvre-le directement dans Obsidian pour éditer.
