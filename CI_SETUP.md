# Landing CI Setup

The GitHub Actions workflow (`.github/workflows/deploy.yml`) auto-deploys to Vercel on push to `main`.

## Prerequisites

1. Go to https://vercel.com/account/tokens → create a token → add as `VERCEL_TOKEN` in repo secrets
2. Get `VERCEL_ORG_ID` and `VERCEL_PROJECT_ID` from `.vercel/repo.json` (already present):
   - `VERCEL_ORG_ID` = `team_SGagBr0AMIIWm3vbNDZm0eeS`
   - `VERCEL_PROJECT_ID` = `prj_Sg3GWULMFQxzoaHKs2MPrSlHsEdw`

## Add Secrets to GitHub

In your repo `Aqui001/amakio-landing` → Settings → Secrets and variables → Actions:

| Secret | Value |
|--------|-------|
| `VERCEL_TOKEN` | Your Vercel token |
| `VERCEL_ORG_ID` | `team_SGagBr0AMIIWm3vbNDZm0eeS` |
| `VERCEL_PROJECT_ID` | `prj_Sg3GWULMFQxzoaHKs2MPrSlHsEdw` |

## Custom Domain

Purchase `amakiohq.com` from a domain registrar (e.g., Namecheap, GoDaddy, Porkbun).

In Vercel dashboard → amakio-landing project → Domains → add `amakiohq.com` and follow DNS instructions.
