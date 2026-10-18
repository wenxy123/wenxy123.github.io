# Xiaoyi Wen — Academic Website

Static website for https://wenxy123.github.io/.

## Publish

Keep the existing source branch as a backup. Place the files in this package at the root of a dedicated `gh-pages` branch in `wenxy123/wenxy123.github.io`. The `index.html` file must be directly at the root, alongside `styles.css`, `script.js`, `.nojekyll`, and `assets/`.

On GitHub, open the repository's Settings → Pages. Under Build and deployment, choose Deploy from a branch. Choose `gh-pages` and `/(root)`, then Save. Wait for the Pages deployment to complete. The public address is https://wenxy123.github.io/.

The `.nojekyll` file is included and should be committed. This site has no build or installation step.

## Update the website later

1. Open the repository and select the `gh-pages` branch.
2. Open `index.html` and click the pencil icon to edit the biography, education, work experience, research, publications, or links.
3. Commit the change to `gh-pages` (or merge your pull request into that branch if branch protection requires it).
4. GitHub Pages republishes the configured branch automatically. Check the repository's Actions tab if the update does not appear.

Use `styles.css` for colors, fonts, spacing, and portrait sizing. `script.js` controls publication filters and the mobile navigation menu.

## Update the CV or portrait

Replace `assets/Xiaoyi_Wen_CV.pdf` or `assets/xiaoyi-wen.png` with a new file using the same filename, then commit. If you use a different filename, update the matching references in `index.html`.

## Preview locally

Run `python3 -m http.server 4173` in this folder, then open http://localhost:4173/.

The GitHub Pages deployment and the private chatgpt.site deployment are separate copies. Updates to one are not automatically copied to the other.
