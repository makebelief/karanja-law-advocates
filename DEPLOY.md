# Publish from an Ubuntu terminal

1. Download and unzip `karanja-law-advocates-production.zip` to `~/Downloads`.
2. Authenticate with GitHub CLI (`gh auth login`) and Vercel CLI if necessary (`npx vercel login`).
3. Create **new** repo and deploy:

```bash
cd ~/Downloads && unzip -oq karanja-law-advocates-production.zip && cd karanja-law-advocates && git init && git branch -M main && git add -A && git commit -m "Launch Karanja Law and Co Advocates website" && gh repo create karanja-law-advocates --public --source=. --remote=origin --push && npx vercel --prod
```

Vercel prompts: create new project, framework `Other`, no build command, output root (`.`). For existing repository, do not re-run git init/gh repo create: `git add -A && git commit -m "Update website" && git push origin main && npx vercel --prod`.

After deployment, change all `https://karanja-law-advocates.vercel.app` references if deployed to a different domain, and then submit your production `sitemap.xml` to Google Search Console.
