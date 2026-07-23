# Agentic Marketers Vault — Installer

Serves the one-line installer/updater at `/update`.

Client command:
```
curl -fsSL https://agentic-marketers.vercel.app/update | bash
```

The script (`public/update`) connects the client to GitHub, then clones the
private `agentic-marketers/vault-template` (first run) or pulls the latest
(every run after). Holds no secrets. Deployed on Vercel as a static site.
