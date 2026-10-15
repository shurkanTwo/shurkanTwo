# ToDos

Legend: `status` = ⚪ open, 🟡 in progress, 🟢 done; `severity` = 🔴 high, 🟠 medium, 🟢 low, ⚪ not set.

## Open

| status | severity | deprecated code | topic | todo |
|---|---|---|---|---|
| ⚪ | 🟢 | Fork `shurkanTwo/github-readme-stats`, its GitHub PAT | Leftovers of the old self-hosted stats instance | The Vercel project serving the unmaintained `anuraghazra/github-readme-stats` fork is deleted; the profile cards now come from a GitHub Action. Still open: revoke the GitHub PAT that was stored in its `PAT_1` env var (most likely a fine-grained token, judging by the `Resource not accessible by personal access token` error; check https://github.com/settings/personal-access-tokens and https://github.com/settings/tokens), and archive or delete the fork. |
