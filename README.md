# The Light of Aethelgard: Field Guide

A player's handbook for the game, written as a small website. It needs no build step. Its fonts load from Google Fonts when online, with built-in fallbacks.

## Put it online from an Android phone (GitHub Pages)

1. In the GitHub app or in your phone's browser (use "Desktop site" if the upload button is missing), create a new repository, for example `aethelgard-guide`. Make it **Public**.
2. Open the repository, tap **Add file → Upload files**.
3. Unzip the downloaded zip first (Files by Google can do this), then select **all** the files inside: the `.html` pages, `style.css`, `README.md` and `.nojekyll`. Everything sits in one folder level, so there is nothing to arrange.
4. Tap **Commit changes**.
5. Go to **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, and Save.
6. After a minute the guide is live at `https://YOUR-NAME.github.io/aethelgard-guide/`. Start page: `index.html`.

If your file picker hides `.nojekyll` because it starts with a dot, that is fine. The guide works without it.

## Files

- `index.html`: the home page. The other `.html` files are the chapters.
- `style.css`: the look. It follows the phone's light or dark setting.

To edit text, open a page on GitHub, tap the pencil icon, and change it.
