# Espidrm

## Deploy to Vercel
1. Push this folder to a GitHub repo, then import it in Vercel.
2. In Vercel → Project → Settings → Environment Variables, add:
   ANTHROPIC_API_KEY = your key
3. Deploy. `index.html` calls `/api/chat`, which holds the key server-side.
