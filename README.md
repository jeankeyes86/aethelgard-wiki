# The Light of Aethelgard: Field Guide

A player's wiki for The Light of Aethelgard: how to play, character creation, attributes,
skills, equipment, magic, combat and war mode, crafting, food, fishing and camping, the world,
reputation, and the
people of the town.

## Publishing on GitHub Pages

1. Create a repository (for example `aethelgard-wiki`) and upload everything in this folder,
   with the images sitting next to the HTML files (no folders needed).
   On a phone, use **Add file → Upload files** and select every file in this zip at once.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and the
   `/ (root)` folder, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

`index.html` is the home page. Every page links to the others with relative links, so the
site also works if you put it in a `docs/` folder and publish from there instead.
The empty `.nojekyll` file tells GitHub to serve the files exactly as they are.
