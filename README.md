# Hydro Web Demo on GitHub Pages

This repository is a clean GitHub Pages package for the hydrology front-end demo.

## Publish mode

- Branch: `main`
- Folder: `/docs`

## Local structure

- `docs/index.html`
- `docs/dem_assets/huaihe_wjb_dem_90_preview.png`
- `docs/.nojekyll`

## Recommended workflow

1. Create a new GitHub repository.
2. Push this folder as the repository root.
3. In GitHub:
   - `Settings`
   - `Pages`
   - `Build and deployment`
   - `Source = Deploy from a branch`
   - `Branch = main`
   - `Folder = /docs`
4. Wait for the first Pages deployment.

## Notes

- This is front-end only.
- No real SWAT, VIC, forcing data, or API services are connected yet.
- The public website should only expose the `docs/` folder contents.
