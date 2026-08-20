# Shiqi Su — Portfolio Website

This is a simple static website for `shiqisu.com`. It can be published for free with GitHub Pages, Cloudflare Pages, or Netlify.

## Edit your information

- Open `index.html` in any code editor.
- Search for `Shiqi`, `hello@shiqisu.com`, and the placeholder project titles to replace the sample content.
- To add a photo, put an image in `assets/` and replace the `<div class="portrait-placeholder">…</div>` block with an `<img>` tag.
- Place a PDF resume at `assets/Shiqi-Su-Resume.pdf`, or change its linked filename.

## Add a playable HTML game

1. Create a folder such as `games/my-game/`.
2. Put your playable game entry file inside it as `index.html` (and include all of its assets).
3. In the relevant project card in `index.html`, change its `href` to `games/my-game/`.

The visitor clicks the card and the game opens in a new tab.

## Publish at shiqisu.com with GitHub Pages

1. Create a GitHub repository named `<your-github-username>.github.io` and upload these files.
2. In the repository, open **Settings → Pages**, select **Deploy from a branch**, then choose `main` and `/(root)`.
3. In **Settings → Pages → Custom domain**, enter `shiqisu.com`.
4. At the company where you bought `shiqisu.com`, add the DNS records GitHub shows. Turn on **Enforce HTTPS** after DNS has propagated.

GitHub Pages hosting is free for public repositories. Domain registration is separate and needs renewal.
