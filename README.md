# Basel Pharma PackHub – Test Landing Page

Diese statische Seite zeigt das erste "First View" für das Basel Pharma PackHub-Portal: Newswall, Seller Directory (Tamper Evidence & Inline Printing) und RFQ-Board.

## Jetzt live stellen (GitHub Pages)
1. Repository initialisieren:
   ```bash
   git init
   git add .
   git commit -m "first view"
   ```
2. Remote anlegen (`git remote add origin https://github.com/<dein-user>/basel-pharma-packhub.git`).
3. Nach GitHub pushen (`git push -u origin main`).
4. In GitHub: Repository → Settings → Pages → Branch: `main` → Root → Save.
5. Die Seite ist dann unter `https://<dein-user>.github.io/basel-pharma-packhub` erreichbar.

## Optional: Netlify Preview
- Netlifykonto erstellen, Repo verbinden, das automatische Build-Target ist `index.html` (static).

## Weiteres
- Die `index.html` kann mit weiteren Newscards/Ad-CTAs erweitert werden.
- Nutze `assets/` für Bilder oder `scripts/` für automatische News-Refreshes.
