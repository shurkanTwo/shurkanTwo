# ToDos

Legend: `status` = ⚪ open, 🟡 in progress, 🟢 done; `severity` = 🔴 high, 🟠 medium, 🟢 low, ⚪ not set.

## Open

| status | severity | deprecated code | topic | todo |
|---|---|---|---|---|
| ⚪ | 🟢 | Vercel project `github-readme-stats-omega-three-60`, fork `shurkanTwo/github-readme-stats` | Unused self-hosted stats instance | The profile README now uses the public GitHub Stats Extended instance, so the self-hosted Vercel deployment of the unmaintained `anuraghazra/github-readme-stats` fork is unused. Its stats endpoint was failing with `Resource not accessible by personal access token`. Delete the Vercel project, revoke the GitHub PAT stored in its `PAT_1` env var, and archive or delete the fork. |
