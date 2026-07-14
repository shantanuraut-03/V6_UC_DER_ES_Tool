# Deployment checklist

## Before uploading

- [ ] Confirm the file is named `index.html`.
- [ ] Confirm `.nojekyll`, `favicon.svg` and `robots.txt` are present.
- [ ] Keep all files in the repository root.
- [ ] Remove or archive the previous `index.html` before replacing it.

## GitHub Pages settings

- [ ] Repository → **Settings** → **Pages**.
- [ ] Source: **Deploy from a branch**.
- [ ] Branch: **main**.
- [ ] Folder: **/(root)**.
- [ ] Save.
- [ ] Enable **Enforce HTTPS** after the first successful deployment.

## Functional checks after publishing

- [ ] All three logos load.
- [ ] The title stays within three lines on desktop.
- [ ] Step navigation works.
- [ ] Budget bands and exact budget input work.
- [ ] Measure-category filters support multiple selections.
- [ ] Measure selections remain selected when filters change.
- [ ] PV appears under Renewables and produces a solar result when selected.
- [ ] The four pathways reorder when inputs change.
- [ ] Contact and C-NEWTRAL links open correctly.
- [ ] Mobile layout is readable.

## Expected URL

For a project repository:

`https://<username>.github.io/<repository-name>/`

For a user site repository named `<username>.github.io`:

`https://<username>.github.io/`
