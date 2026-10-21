# SCIE Sustainable Campus Digital Twin — Premium interactive concept

A static, self-contained browser demonstration based on the user’s existing campus Digital Twin simulation and their current Blender screenshot. It contains **no real sensor or meter feeds** and **does not control school facilities**.

## Quick preview
Open `index.html` directly in a browser, or use `python -m http.server 8000` in this folder then visit http://localhost:8000.

## Deploy to Vercel
Import this folder as a static **Other** project in Vercel. No build command, no environment variables and no framework are required. The ZIP can be unzipped into a repository root before import.

## Files
- `index.html` — entry page
- `style.css` / `premium.css` — original working interface plus premium theme
- `scene.js` — interactive procedural 3D approximation based on the project’s Blender screenshot
- `app.js` — all functioning demonstration screens, modular decision engine and leadership content
- `assets/scie-blender-progress.webp` — optimised screenshot supplied by the project team

## Project facts and limits
- The real Blender source model **is not included**. The interactive massing is approximate, not accurate architectural geometry.
- Main modelling target: end of 2026, as provided by the team.
- All energy, environmental, timetable, elevator and maintenance records in the app are fictional illustrative data.
- Module recommendations are provisional and can be changed in-browser and exported as CSV.
- Real integrations would require school approvals and an appropriate authenticated backend.
