# The Light of Aethelguard: Field Guide

A player's wiki for The Light of Aethelguard: how to play, character creation, attributes,
skills, equipment, magic, combat and war mode, crafting, the world, reputation, and the
people of the town.

## Publishing on GitHub Pages

1. Create a repository (for example `aethelguard-wiki`) and upload everything in this folder,
   with the images sitting next to the HTML files (no folders needed).
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and the
   `/ (root)` folder, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

`index.html` is the home page. Every page links to the others with relative links, so the
site also works if you put it in a `docs/` folder and publish from there instead.
The empty `.nojekyll` file tells GitHub to serve the files exactly as they are.
