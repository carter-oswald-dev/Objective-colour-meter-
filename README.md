# Chromameter

A single-file, static, client-side colour identification tool. Crop, downsample,
and sample a colour from a photo — with flash-distance and shooting-condition
tips built in. No build step, no dependencies, no server. Everything runs in
the browser; no image data leaves the device.

## Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g. `chromameter`).
2. Add `index.html` (from this zip) to the root of the repository.
3. In the repo, go to **Settings → Pages**.
4. Under **Source**, choose the branch (usually `main`) and root folder (`/`).
5. Save. GitHub will publish the site at:
   `https://<your-username>.github.io/<repo-name>/`

## Deploying from iOS

You don't need a computer — this can be done entirely from an iPhone/iPad:

- **GitHub app**: create the repo, then use "Add file" → "Upload files" to
  upload `index.html` directly from the Files app.
- **Working Copy** (a Git client for iOS): clone or create the repo, copy
  `index.html` into it, then commit and push.
- Either way, once the file is pushed, enable GitHub Pages as above (this step
  currently requires the GitHub website, which works fine in Safari).

## Notes

- `index.html` is the entire app — one file, no other assets required.
- Nothing is uploaded anywhere; all image processing (crop, downscale, colour
  sampling) happens locally in the browser via Canvas.
