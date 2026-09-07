# Portfolio — how to use

Everything lives in `index.html`. You only ever edit the block at the top.

## Add a project
1. Make a folder: `media/<project-name>/` and put photos (jpg/png) and videos (mp4) in it.
2. Open `index.html`, find `const PROJECTS = [`, copy the example block, paste it below, edit the text.
3. Point each media entry at your files, e.g. `media/robot-arm/front.jpg`.
4. Open `index.html` in a browser. Missing files show a striped "add image at…" box so you can see what's wrong.

Delete the example project once you have a real one.

## Put your CV on it
Save your CV as `cv.pdf` in this folder. The "CV (PDF)" link already points to it.

## Publish (free, ~5 min)
1. Create a GitHub repo called `<your-username>.github.io`.
2. Upload this whole folder (index.html, README.md, media/, cv.pdf).
3. Repo → Settings → Pages → Source: Deploy from branch `main`, folder `/ (root)`. Save.
4. Site is live at `https://<your-username>.github.io` within a minute or two. Put that on your CV.

To update later: edit index.html, upload the new files, done.

## Tips
- Keep videos under ~30 MB each or use YouTube (unlisted) and the `youtube` media type.
- Resize photos to ~1600 px wide before uploading so the page loads fast.
- First image in each project should be the finished thing, not the breadboard.
