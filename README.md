# jevstore-explainer

Static explainer for **JevStore**: the feed that reads your mind (Jev system-one personalization). Deploys on Vercel as-is (no build).

Live demo repo: https://github.com/juanri7/jev-store

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Video slot

Drop the final `/brag` export at `assets/jevstore-demo.mp4` + poster at `assets/poster.svg`.

Workflow (keeps artifacts out of the demo repo):
1. From `jev-store/`, run `/brag` with output to `%TEMP%/opencode`
2. Copy only the finished `.mp4` here
3. Never commit `brag-output/`
