# ₹ Banking Pulse

AI-powered banking & finance news for Indian bankers.

**Live:** [bankingpulse.app](https://bankingpulse.app)

## Architecture

- **GitHub Pages** — hosts static files (landing + PWA)
- **GitHub Actions** — fetches news 4x/day via Claude API
- **Supabase** — stores news data (free tier)
- **PWA** — reads directly from Supabase REST API

## Cost

| Item | Cost |
|------|------|
| Hosting (GitHub Pages) | Free |
| Database (Supabase) | Free |
| News fetch (Claude API) | ~₹600/month |
| Domain | ~₹1,400/year |
| **Total** | **~₹700/month** |
