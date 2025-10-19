# Joshua David Smith — Portfolio (Starter)

This is a lightweight, static portfolio you can deploy **free** with **GitHub Pages**. It links out to your project demos hosted on Netlify/Vercel/Render.

## 🚀 Quick Deploy — GitHub Pages

1. Create a new GitHub repo called `joshua-smith222.github.io` (use your actual username).
2. Upload these files (`index.html`, `style.css`, `assets/`).
3. Push to the `main` branch.
4. In the repo, go to **Settings → Pages**. If needed, set **Branch: main / root**.
5. Your site will be live at `https://<your-username>.github.io/`.

### Custom Domain (optional)
- Buy a domain (e.g., Namecheap).
- In GitHub → **Settings → Pages → Custom domain**, enter `yourdomain.com`.
- Add DNS `CNAME` to point to `<your-username>.github.io`.

## 🔗 Add Your Project Links
Edit `index.html` and replace the placeholder links for:
- Mechanic Shop API (Render URL + GitHub)
- E‑Commerce Frontend (Netlify URL + GitHub)
- Trivia App (Vercel URL + GitHub)

## 🧩 Hosting Your Project Demos

### Netlify (React frontends)
- Connect repo → set build: `npm run build` and publish dir: `dist` (Vite) or `build` (CRA).

### Vercel (Next.js/React)
- Import repo → Vercel auto-detects and deploys. Add a custom domain if you want.

### Render (Flask API)
- Create new **Web Service** → connect your GitHub repo.
- Environment: `Python` → `gunicorn app:app` (update to your module/app).
- Add env vars, then deploy. Render gives you a public URL.

## 📝 Customize
- Update your **name, email, GitHub, LinkedIn** in `index.html`.
- Tweak styles in `style.css`. Keep it minimal for fast loads.

## 🧪 Tips
- Use 1280×720 screenshots in `/assets` for crisp previews.
- Run your HTML through a validator (optional) before committing.
