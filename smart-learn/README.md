# SMART LEARN – Communication Skills & Computer Networks

Beginner-friendly e-learning site: 30 topics, quizzes, flashcards, timed final exam, dashboard, bookmarks, search, daily challenge, AI tutor (built-in), dark/light mode.

## Structure
- `index.html` – page shell
- `css/style.css` – styles, themes, animations
- `js/app.js` – lessons, quizzes, exam, dashboard, accounts, tutor
- `assets/favicon.svg` – icon
- `.nojekyll` – tells GitHub Pages to serve files as-is
- `.github/workflows/pages.yml` – automatic deployment

## Deploy on GitHub Pages
1. Create a new GitHub repository and upload everything in this folder (keep the folder structure and the hidden `.nojekyll` and `.github` items).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions** (the included workflow deploys on every push to `main`). Alternatively choose **Deploy from a branch**, pick `main` and `/ (root)`.
4. Your site appears at `https://<username>.github.io/<repository>/`.

## Notes
- Plain HTML/CSS/JavaScript, no build step and no React.
- Accounts, progress, bookmarks and feedback are stored in the visitor's browser (localStorage), not on a server.
- All paths are relative, so it works under a repository sub-path.
