# NEOVERSE — GitHub Pages Ready

The public website is intentionally flat at the repository root:

```text
index.html
style.css
app.js
assets/
backend/
ARCHITECTURE.md
README.md
```

## GitHub Pages
1. Create a repository.
2. Upload the **contents of this folder** (so `index.html` is at the root).
3. Commit to `main`.
4. Open **Settings → Pages**.
5. Choose **Deploy from a branch → main → / (root)**.
6. Save and open the generated Pages URL.

## Included
- 3D Three.js experience
- 4D-style illusion effects
- AI command area
- Study / Library / Games / Media / Chat / Workspace / Discover modules
- Responsive UI
- Backend folder for future real AI, accounts, memory, messaging and other services

## Important
GitHub Pages can host the frontend, but it cannot run the Node backend. For real persistent AI memory, authentication, private chat, cloud storage, live feeds and other server features, deploy `backend/` separately and connect the frontend to its API.
