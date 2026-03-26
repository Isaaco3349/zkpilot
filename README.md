# ⚡ ZKPilot — Midnight Network dApp Copilot

> Idea → Privacy dApp in minutes. Powered by Claude AI + Midnight Network.

## Stack
- **Frontend**: Vanilla HTML/CSS/JS
- **Backend**: Vercel Serverless Function (Node.js)
- **AI**: Anthropic Claude
- **Hosting**: Vercel

## Project Structure
```
zkpilot/
├── public/index.html     # Frontend UI
├── api/generate.js       # Serverless proxy → Anthropic API
├── vercel.json           # Routing config
├── package.json
└── .env.local            # API key (never committed)
```

## Local Development
1. Clone the repo
2. Add your key to `.env.local`: `ANTHROPIC_API_KEY=your_key`
3. Run: `npm run dev`

## Deploy to Vercel
1. Push to GitHub
2. Import repo on vercel.com
3. Add `ANTHROPIC_API_KEY` in environment variables
4. Deploy ✅

## Midnight Network
- Docs: https://docs.midnight.network
- Faucet: https://faucet.preprod.midnight.network
- Explorer: https://explorer.preprod.midnight.network